## 2023.9.19
1. 移除支持 UIA 的选项。
2. 移除对 QQ 的特殊支持。

## 2023.3.2
1. 兼容 NVDA2023.1。
2. 修复对搜狗旧版属性设置支持的一个小错误。

## 2022.9.21
1. 修复了不朗读搜狗拼音属性设置的问题。
2. 在插件更新器（NVDA中文站更新源）提供本插件的更新。

## 2022.9.10
1. 修复了微软拼音某些情况下上平后会朗读整个窗口内容的 Bug。
2. 完善了用户指南。

## 2022.8.26
- 更新了 win11 应用模块。

## 2022.8.13
1. 修复当存在未上屏的候选切换输入法会导致上下箭头失灵的情况；
2. 对“本地输入/字母数字输入”、“全/半角”、“中/英标点”的切换朗读进行了简化。

## 2022.7.9
1. Win11微软拼音支持；
2. 支持NVDA 本身列表键入定位后朗读已选项目；
3. 尝试改进标点朗读问题。

## 2022.6.9
- 提高稳定性，修复日志中出现的不必要警告信息

## 2022.6.5
- 提高标点朗读响应速度；
- 修复启用 UIA  支持后存在的重复朗读标点问题。


## 2022.6.4
- 修复标点朗读不准确的 Bug

## 2022.5.30
- 大幅提高响应速度

## 2022.5.26:
- 尝试修复候选朗读不完全或不准确的情况。

## 2022.4.18
- 增加了一个 UIA 支持的可选项，主要适配 QQ 等特殊场景，选中后，在中文输入过程中，回车后读实际上平的英文内容。

## 2022.4.16
 1. 兼容了输入法横排候选（左右箭头选字）；
2. 修复按 Escape 取消输入会导致退出焦点模式的问题；
3. 尝试解决某些情况下输入过快的意外打断朗读问题；
4. 增强稳定性。

## 2022.4.8
 1. 兼容 nvda2022.1；
2. 修复在 Word 中启用 UIA 接口支持的情况下无法朗读单词的问题；
3. 解决了在 Word 中按回车偶尔会读出其他行内容的问题。
4. 更新帮助文档。

##  2022.3.22更新：
1. 解决了 在qq输入框中键入英文不按单词朗读的问题；
2. 解决了微软拼音在 QQ 上键入中文个别候选会朗读为字母的问题。

##  2022.3.5 升级日志
1. 新增了插件专有设置面板并覆盖 NVDA 原有输入法设置；
2. 提供对解释方式和以词定字按键的个性化设置；
3. 修复上一版中文输入状态下按住 Shift +字母不朗读的问题；
4. 大幅优化代码并提升输入效率。

##  2022.2.24
1. 解决个别输入框大小写不提示问题；
2. 改进了输入法设置模块对 NVDA Alpha 版的兼容；
3. 对搜狗拼音（含智慧版、五笔）输入法卸载程序的朗读支持。
4. 细化朗读方式，在 NVDA 菜单 > 选项 > 设置内的“输入法”类别下调节，目前支持的朗读方式包括：
    - 只读解释；
    - 只读元字符；
    - 两个候选字以内读解释，否则先读解释后读元字符；
    - 两个候选字以内读解释，否则只读元字符。
    - p.s. 具体设置方式见插件帮助。


## 2022.15
 1. 飞中文语言下支持中文输入解释；
2. 搜狗无比“属性设置”支持；
3. 使用nvda输入法设置中的“朗读预上屏字串”控制是否读出候选字序号。


## 2022.2.14
第一版发布。