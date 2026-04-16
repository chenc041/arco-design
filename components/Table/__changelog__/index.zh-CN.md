## 2.66.14

2026-04-16

### 🐛 问题修复

- 修复`Table` 在Table header 和Table body 分离模式下（设置Scroll y属性），调用原生横向 smooth scroll 时，滚动几乎不生效且出现轻微抖动问题([#3164](https://github.com/arco-design/arco-design/pull/3164))

## 2.66.10

2026-01-23

### 🐛 问题修复

- 修复 `Table` 组件在 data 数据异步拉取时，设置 defaultExpandAllRows 后失效的问题([#3110](https://github.com/arco-design/arco-design/pull/3110))
- 修复 `Table` 组件开启虚拟滚动后，在出现一次空数据的情况下，表头与表身不再同步横向滚动的问题([#3107](https://github.com/arco-design/arco-design/pull/3107))
- 修复 `Table` 组件开启虚拟滚动后，总结栏 summary 失效、未正常渲染的问题([#3106](https://github.com/arco-design/arco-design/pull/3106))
- 修复 `Table` 组件合并多行单元格后，鼠标悬停（hover）时仅第一行高亮的问题。([#3104](https://github.com/arco-design/arco-design/pull/3104))
- 修复 `Table` 组件第一列在合并单元格时，即便将borderCell设置为false，内部仍有部分边框外露的问题([#3102](https://github.com/arco-design/arco-design/pull/3102))
- 修复 `Table` 在定制展开/折叠图标后，展开/折叠点击事件失效的问题 。([#3101](https://github.com/arco-design/arco-design/pull/3101))
- 修复 `Table` 组件添加 fixed 定位后，若自定义 render 返回的 props 包含 style，则 fixed 定位失效的问题([#3099](https://github.com/arco-design/arco-design/pull/3099))
- 修复 `Table` 组件在开启行选择后，所有行都都不可选的情况下，表头CheckAll状态不对问题([#3094](https://github.com/arco-design/arco-design/pull/3094))

## 2.66.8

2025-11-11

### 🐛 问题修复

- 修复当 sortOrder 为 undefined 时的错误排序行为([#3076](https://github.com/arco-design/arco-design/pull/3076))

## 2.66.2

2025-07-15

### 🐛 问题修复

- 修复`ConfigProvider` 配置的 `size=mini` 对 `Table` 组件不生效的问题([#2981](https://github.com/arco-design/arco-design/pull/2981))

## 2.66.0

2025-04-03

### 🐛 问题修复

- 修复 `Table` 组件展开行内容重复渲染的 bug([#2959](https://github.com/arco-design/arco-design/pull/2959))

## 2.64.1

2024-10-28

### 🐛 问题修复

- `Table` 组件修复开启虚拟列表且数据量少时，固定列失效的问题([#2847](https://github.com/arco-design/arco-design/pull/2847))

## 2.61.1

2024-03-22

### 🐛 问题修复

- 修复rtl切换时fixedClassName错误的问题([#2602](https://github.com/arco-design/arco-design/pull/2602))
- 修复 `Table` 组件动态变化 scrollY 可能报错的问题([#2599](https://github.com/arco-design/arco-design/pull/2599))

## 2.61.0

2024-03-15

### 🐛 问题修复

- 修复 `Table` 由于 ReactKey 缺失导致的控制台警告。([#2592](https://github.com/arco-design/arco-design/pull/2592))

## 2.60.2

2024-03-01

### 💎 功能优化

- `Table` 组件虚拟滚动开启时支持展开行和树形数据。([#2553](https://github.com/arco-design/arco-design/pull/2553))

## 2.60.0

2024-02-23

### 🐛 问题修复

- 修复`Table`组件`scrollbar-color`属性导致宽度计算错误的问题。([#2533](https://github.com/arco-design/arco-design/pull/2533))

### 🆎 类型修正

- `Table` 组件 column 属性 TS 定义调整([#2531](https://github.com/arco-design/arco-design/pull/2531))

## 2.58.1

2024-01-05

### 🐛 问题修复

- 修复`Table`组件`loading`配置不生效的问题([#2474](https://github.com/arco-design/arco-design/pull/2474))

## 2.56.1

2023-11-24

### 🐛 问题修复

- 兼容`Table`组件在同一个生命周期内 `column` 中的 `sortOrder` 开始不受控，之后又受控的情况。([#2379](https://github.com/arco-design/arco-design/pull/2379))

## 2.56.0

2023-11-17

### 🐛 问题修复

- 优化 `Table` 组件 `data` 和 `columns` 空数据的定义方式，避免无限重绘。([#2370](https://github.com/arco-design/arco-design/pull/2370))

## 2.55.2

2023-11-10

### 🐛 问题修复

- 修复 `Table` 的 `columns` 中未指定 `dataIndex` 也未指定`key`时， `col key` 可能会重复的问题。([#2353](https://github.com/arco-design/arco-design/pull/2353))
- 修复`Table`开启虚拟滚动后，横向滚动样式问题 。([#2353](https://github.com/arco-design/arco-design/pull/2353))
- 修复`Table` 的 `scroll.x={max-content}`，`scroll.y={true}`且数据为空时，表头样式错乱的问题 。([#2353](https://github.com/arco-design/arco-design/pull/2353))

## 2.55.1

2023-11-03

### 🐛 问题修复

- 修复 `Table` 在动态更新 `scrollY`  时表头横向滚动失效的问题。([#2330](https://github.com/arco-design/arco-design/pull/2330))

## 2.55.0

2023-10-27

### 🐛 问题修复

- 修复 `Table` 组件 `data` 属性为二维数组时，`render` 参数可能为空的问题。([#2319](https://github.com/arco-design/arco-design/pull/2319))
- 修复 `Table` 组件在`columns`中同时存在`dataIndex`和`key`属性时，排序和筛选功能失效的问题。([#2311](https://github.com/arco-design/arco-design/pull/2311))

## 2.54.2

2023-10-20

### 🐛 问题修复

- 修复 `Table` 组件在 `scroll={x: 'max-content', y: true}` 时，表头和内容无法对齐的问题([#2303](https://github.com/arco-design/arco-design/pull/2303))

## 2.53.0

2023-09-08

### 🆕 功能升级

- `Table` 组件支持在虚拟列表的场景下通过 `ref.scrollIntoView` 滚动到指定区域。([#2226](https://github.com/arco-design/arco-design/pull/2226))
- `Table` 组件 `onChange` 回调增加参数 `extra.currentAllData`。([#2220](https://github.com/arco-design/arco-design/pull/2220))

## 2.52.1

2023-08-25

### 🐛 问题修复

- 修复 `Table` 组件的 render 属性第二个参数可能为 `undefined` 的 bug (该问题在 `2.50.2` 移除了对外回调参数附带了的内部属性 __ORIGIN_DATA__ 引入)([#2188](https://github.com/arco-design/arco-design/pull/2188) [@Ryuurock](https://github.com/Ryuurock))

### 💅 样式更新

- 修复 `Table` 组件设置 scrollX 时空白状态可能会出现滚动条样式的问题。([#2171](https://github.com/arco-design/arco-design/pull/2171) [@whyour](https://github.com/whyour))

## 2.51.0

2023-07-28

### 💎 功能优化

- 优化表格宽度在特定场景下出现不必要滚动条的问题。([#2066](https://github.com/arco-design/arco-design/pull/2066) [@hkhere](https://github.com/hkhere))

## 2.50.1

2023-07-14

### 🐛 问题修复

- 修复 `Table` 组件的 `sortOrder` 属性受控时，组件内部状态同步不正确问题([#2079](https://github.com/arco-design/arco-design/pull/2079))

## 2.50.0

2023-06-30

### 🐛 问题修复

- 修复 `Table` 开启虚拟滚动且数据量较小时可能出现的表头对齐问题。([#2056](https://github.com/arco-design/arco-design/pull/2056))

## 2.49.0

2023-06-02

### 🐛 问题修复

- 当 `Table` 组件没有数据但是 `pagination.total > 0` 时，应该显示分页。([#2005](https://github.com/arco-design/arco-design/pull/2005))

## 2.47.2

2023-05-06

### 🐛 问题修复

- 修复 `Table` 组件 `defaultExpandAllRows` 属性不生效的问题。([#1953](https://github.com/arco-design/arco-design/pull/1953))

## 2.47.1

2023-04-21

### 🐛 问题修复

- 修复 `Table` 组件分页隐藏逻辑。([#1937](https://github.com/arco-design/arco-design/pull/1937))

## 2.47.0

2023-04-14

### 🆕 功能升级

- Table组件新增多列排序功能([#1910](https://github.com/arco-design/arco-design/pull/1910))

### 🐛 问题修复

- 修复树形数据展示且内容为非文本时的缩进问题([#1913](https://github.com/arco-design/arco-design/pull/1913))

## 2.46.2

2023-03-31

### 💎 功能优化

- `Table` 在固定列时，`column.width` 可以设置为带像素的字符串。([#1883](https://github.com/arco-design/arco-design/pull/1883))

## 2.46.1

2023-03-24

### 🐛 问题修复

- 修复 `Table` 组件组合表头和 colSpan 一起使用时，colSpan 被覆盖的 bug。([#1865](https://github.com/arco-design/arco-design/pull/1865))

## 2.46.0

2023-03-17

### 🆕 功能升级

- `Table` 组件新增参数 `virtualListProps`。([#1848](https://github.com/arco-design/arco-design/pull/1848))

### 🐛 问题修复

- 修复 `Table` 组件在多表头多列 fixed 场景下滚动时出现表头和内容无法对齐的问题。([#1852](https://github.com/arco-design/arco-design/pull/1852))
- 修复Table 组件在多表头多列fixed场景下scroll 时出现表头和内容无法对齐的问题([#1840](https://github.com/arco-design/arco-design/pull/1840))

## 2.45.1

2023-03-01

### 💅 样式更新

- 修复 `Table` 组件在暗黑模式下固定列背景色存在透明度导致的样式问题([#1816](https://github.com/arco-design/arco-design/pull/1816))

## 2.45.0

2023-02-17

### 🐛 问题修复

- 修复 `Table` 组件 `data` 动态加载时固定列事件没触发的 bug。([#1787](https://github.com/arco-design/arco-design/pull/1787))

## 2.44.0

2023-01-13

### 💅 样式更新

- 修复 `Table` 组件总结行在 `fixed=top` 时有问题的 bug。([#1719](https://github.com/arco-design/arco-design/pull/1719))

## 2.42.0

2022-11-25

### 🐛 问题修复

- 修复 `Table` 组件 data 为 `number[]` 或 `string[]` 时，报错的问题。([#1611](https://github.com/arco-design/arco-design/pull/1611))
- 修复 `Table` 组件开启虚拟滚动时，动态改变 `scroll` 会导致固定列高亮丢失样式的 bug。([#1600](https://github.com/arco-design/arco-design/pull/1600))

## 2.41.2

2022-11-11

### 💎 功能优化

- 减少 `Table` 组件 `column.render` 不合预期的渲染次数。([#1562](https://github.com/arco-design/arco-design/pull/1562))

## 2.41.0

2022-10-28

### 💅 样式更新

- 修复 `Table` 组件当 `scroll.x` 过小时总结列高度塌陷的样式问题。([#1492](https://github.com/arco-design/arco-design/pull/1492))

## 2.40.2

2022-09-30

### 💅 样式更新

- 修复 `Table` 组件展开行嵌套子表格时，子表格开启固定列会出现单元格透明的问题。([#1433](https://github.com/arco-design/arco-design/pull/1433))

## 2.40.1

2022-09-23

### 🐛 问题修复

- 修复 Table 在关闭 `checkStrictly` 后，传入不存在的 `selectedKey` 导致页面报错的 bug([#1420](https://github.com/arco-design/arco-design/pull/1420))

## 2.39.2

2022-08-26

### 🐛 问题修复

- 修复 `Table` 组件更新 `data` 之后，下次选中 `selectedRows` 未及时更新的问题。([#1341](https://github.com/arco-design/arco-design/pull/1341))

## 2.39.0

2022-08-12

### 🐛 问题修复

- 修复 `Table` 组件在 data 格式为 `[['1']], ['2']]` 时不能正确渲染的问题。([#1270](https://github.com/arco-design/arco-design/pull/1270))

## 2.38.0

2022-07-29

### 🐛 问题修复

- 修复在 `Table` 单独传入 `pagination` 后，分页器的 `onChange` 回调不触发的 bug([#1217](https://github.com/arco-design/arco-design/pull/1217))

## 2.37.2

2022-07-22

### 🐛 问题修复

- 修复 `Table` 组件 `onChange` 回调参数更新不及时的bug([#1155](https://github.com/arco-design/arco-design/pull/1155))

## 2.37.0

2022-07-08

### 🐛 问题修复

- 修复 `Table` 组件同时开启 `column.sorter` 和 `column.ellipsis` 时，ellipsis 不生效的 bug。([#1108](https://github.com/arco-design/arco-design/pull/1108))
- 修复 `Table` 组件左边框在无数据时消失的样式问题。([#1106](https://github.com/arco-design/arco-design/pull/1106))
- 修复 `Table` 组件 data 为 null 时报错的 bug。([#1104](https://github.com/arco-design/arco-design/pull/1104))

## 2.36.0

2022-06-24

### 🐛 问题修复

- 修复 `Table` 组件对外输出的 data 和 record 包含内部数据的 bug。([#1047](https://github.com/arco-design/arco-design/pull/1047))

## 2.35.1

2022-06-17

### 🐛 问题修复

- 修复 `Table` 组件在树形数据时会改变原始 data 的 bug。([#990](https://github.com/arco-design/arco-design/pull/990))

## 2.35.0

2022-06-10

### 🆕 功能升级

- `Table` 组件开启 `virtualized` 后支持固定列。([#971](https://github.com/arco-design/arco-design/pull/971))

## 2.33.1

2022-05-20

### 🐛 问题修复

- 修复 `Table` 组件表头分组时，内部的表头单元格也有圆角的样式问题。([#872](https://github.com/arco-design/arco-design/pull/872))

## 2.33.0

2022-05-13

### 🆕 功能升级

- `Table` 组件新增 `rowSelection.checkStrictly` 支持父子选择关联。([#849](https://github.com/arco-design/arco-design/pull/849))

## 2.32.2

2022-04-29

### 🐛 问题修复

- 修复 `Table` 组件的外层 `ConfigProvider` 设置 `pagination` 后无法生效的bug。([#827](https://github.com/arco-design/arco-design/pull/827))

## 2.32.1

2022-04-22

### 🆎 类型修正

- 优化 `Table` 组件 `rowKey` 的 `TS` 定义为 `React.Key | ((record: T) => React.Key)` ([#799](https://github.com/arco-design/arco-design/pull/799))

## 2.31.1

2022-03-28

### 💅 样式更新

- 修复 `Table` 组件开启虚拟列表时复选框列宽度异常的问题。([#696](https://github.com/arco-design/arco-design/pull/696))

## 2.31.0

2022-03-25

### 🆕 功能升级

- `Table` 组件支持排序树形数据。([#678](https://github.com/arco-design/arco-design/pull/678))

## 2.30.2

2022-03-18

### 🐛 问题修复

- 修复 `Table` 组件开启 `virtualized` 之后 `column.align` 不生效的 bug。([#650](https://github.com/arco-design/arco-design/pull/650))

### 💅 样式更新

- 修复 `Table` 组件 `expandProps.width` 设置小于 40 不生效的问题。([#656](https://github.com/arco-design/arco-design/pull/656))

## 2.30.0

2022-03-04

### 🐛 问题修复

- `placeholder` 属性在`Table` 数据为空字符或者 null 生效([#609](https://github.com/arco-design/arco-design/pull/609))

## 2.29.0

2022-02-11

### 🐛 问题修复

- 修复 `Table` 组件 `onDropdownVisibleChange` 在点击确定按钮时不触发的 bug。([#521](https://github.com/arco-design/arco-design/pull/521))

## 2.28.2

2022-01-21

### 💎 优化

- 优化 `Table` 组件 `expandedRowRender` 会执行多次导致卡顿的问题。([#473](https://github.com/arco-design/arco-design/pull/473))
- 优化 `Table` 在开启 `virtualized` 之后，大于 10000 条数据时全选会卡的性能问题。([#472](https://github.com/arco-design/arco-design/pull/472))

### 🐛 问题修复

- 修复 `Table` 组件 `size` 没有作用到分页的 bug。([#475](https://github.com/arco-design/arco-design/pull/475))

## 2.28.1

2022-01-14

### 🐛 问题修复

- 如果表格没有数据，分页不应该展示 。([#435](https://github.com/arco-design/arco-design/pull/435))

### 💅 样式更新

- 修复 `Table` 组件在尺寸为 `mini` 时，在数据只有一条时的样式问题。([#449](https://github.com/arco-design/arco-design/pull/449))

## 2.28.0

2022-01-07

### 🐛 问题修复

- 修复 `Table` 组件在异步更新 `column.className` 时，类名有问题的 bug。([#398](https://github.com/arco-design/arco-design/pull/398))

## 2.27.2

2021-12-31

### 🐛 问题修复

- 修复 `Table` 组件筛选在受控模式下，`filteredValue` 设置为 `undefined` 不能重置的 bug。([#382](https://github.com/arco-design/arco-design/pull/382))

## 2.27.0

2021-12-17

### 🆕 功能升级

- `Table` 组件新增参数 `expandProps.strictTreeData`。([#334](https://github.com/arco-design/arco-design/pull/334))

### 🐛 问题修复

- 修复 `Table` 组件 `column.cellStyle` 生效位置不正确的 bug。([#332](https://github.com/arco-design/arco-design/pull/332))
- 修复 `Table` 当数据量变化时，当前页计算出错的 bug。([#329](https://github.com/arco-design/arco-design/pull/329))

## 2.26.2

2021-12-10

### 💅 样式更新

- 修复 `Table` 组件树形数据时，`column.render` 返回 `div` 会导致折行的问题。([#302](https://github.com/arco-design/arco-design/pull/302))

## 2.26.0

2021-12-03

### 💅 样式更新

- 修复 `Table` 组件复选框列在固定表头时没有对齐的样式问题。([#261](https://github.com/arco-design/arco-design/pull/261))

## 2.25.0

2021-11-19

### 💅 样式更新

- 修复 `Table` 组件在开启 `virtualized` 之后，当滚动条始终显示时表头出现错位的样式问题。([#182](https://github.com/arco-design/arco-design/pull/182))

## 2.24.1

2021-11-12

### 💅 样式更新

- 修复 `Table` 组件在列存在筛选时，单元格 align = 'right' 时会重叠的样式问题。([#140](https://github.com/arco-design/arco-design/pull/140))

## 2.24.0

2021-11-05

### 💅 样式更新

- 修复 `Table` 组件在表头分组时，`border={{ border: true, headerCell: true }}` 时，表头边框线断裂的问题。([#120](https://github.com/arco-design/arco-design/pull/120))

## 2.23.4

2021-10-26

### 🐛 问题修复

- `Table` 组件展开按钮的 `type` 设置为 `button`，避免点击触发 Form submit。([#23](https://github.com/arco-design/arco-design/pull/23))

## 2.23.2

2021-10-22

### 🐛 问题修复

- 修复 `Table` 组件使用树形数据时有唯一 key 警告的问题。

## 2.23.1

2021-10-15

### 🐛 问题修复

- 修复 `Table` 组件 `rowSelection.renderCell` 在单选时不生效的 bug。

## 2.23.0

2021-09-27

### 💎 优化

- `Table` 组件排序和筛选的列在没有设置 `dataIndex` 时也可以生效。

### 🆕 功能升级

- `Table` 组件新增参数 `placeholder`, 当单元格内容为空时，显示占位符，优先级低于 `column.placeholder`。

## 2.22.0

2021-09-10

### 🆕 功能升级

- `Table` 组件添加参数 `rowSelection.onSelect`。
- `Table` 组件支持设置 `column.placeholder`。
- `Table` 组件 `onChange` 回调的第 4 个参数增加 `currentData` 的返回。

### 🐛 问题修复

- 修复 `Table` 组件在筛选受控的时候，点击重置按钮，状态没有及时更新的问题。

## 2.21.2

2021-08-30

### 🐛 问题修复

- 修复 `Table` 组件在固定表头时，一些边界条件下动态修改 `columns` 会造成表头表身不同步滚动的问题。

## 2.21.1

2021-08-27

### 🐛 Bugfix

- 修复 `Table` 组件更新 `columns.fixed`，固定列表头没有更新事件的 bug。同时修复自定义表头设置为函数组件时，不能正确联动滚动的 bug。

## 2.21.0

2021-08-20

### 🐛 Bugfix

- 修复 `Table` 组件排序在受控下，视觉表现不对的 bug。

### 💅 样式更新

- 修复 Table 组件设置 `border={{ wrapper: true }}` 时也不显示表头下边框的问题。。

## 2.20.0

2021-07-30

### 🐛 Bugfix

- 修复 `Table` 组件 `preserveSelectedRowKeys` 在 `pagination` 为 `false` 时不生效的 bug。
- 修复 `Table` 组件在受控 `expandedRowKeys` 时 `onExpandedRowsChange` 返回值使用了内部未受控 `keys` 的 bug。
- 修复 `Table` 组件 `defaultFilters` 没有在 `filterDropdown` 中体现的 bug。

## 2.19.3

2021-07-23

### 💅 Style

- `Table` 组件可编辑单元格样式优化，修复跟树形数据结合时错行的问题。

## 2.19.0

2021-07-16

### 🆕 Feature

- `Table` 组件新增 `showSorterTooltip`，同时修复排序箭头被底色覆盖的样式问题。
- `Table` 组件新增 `expandProps.expandRowByClick`，支持点击行展开。
- `Table` 组件 `onChange` 参数新增第四个参数 `extra`，通过 `extra.action` 可以拿到当前触发动作。
- `Table` 组件新增 `rowSelection.renderCell`，支持定制复选框。
- `Table` 组件新增 `rowSelection.preserveSelectedRowKeys`，支持在数据项被删除之后保留 `selectedRowKeys` 中的 `key` 值。

## 2.18.2

2021-07-09

### 🐛 Bugfix

- 修复 `Table` 组件动态改变 `columns` 时，在树形数据判断是否时第一列时，存在多个第一列的 bug。



### 💅 Style

- 修复 `Table` 组件在表身存在滚动条时，数据变少滚动条消失，表头滚动条依然存在的样式问题。



## 2.18.1

2021-07-04

### 🐛 Bugfix

- 修复 `Table` 组件动态设置 `columns` 时，固定列逻辑没有处理的 bug。
- 修复 `Table` 组件开启虚拟滚动同时设置了 `scroll.x`，样式表现不对的问题。



## 2.18.0

2021-07-02

### 🐛 Bugfix

- 修复 `Table` 组件开启虚拟滚动之后，空数据显示有问题的 bug。
- 修复 `Table` 组件 `rowSelection` 切换为 `undefined` 之后导致报错的 bug。
- 修复 `Table` 组件在 `data` 改变之后，没有过滤 `selectedRowKeys` 中不存在的值的 bug。

## 2.17.3

2021-06-24

### 🐛 Bugfix

- 修复 `Table` 组件前置操作列用 `Tooltip` 包裹无法显示弹出的 bug。
- 修复 `Table` 组件 `column.width` 为 `string` 不生效的 bug。



### 🆎 TypeScript

- `Table` 组件 `column.children` 类型修正，修复表头分组时无法推导嵌套类型的问题。
- `Table` 组件 `column.filters` 类型修正，修复无法推导类型的问题。



## 2.17.1

2021-06-20

### 🐛 Bugfix

- 修复 `Table` 组件虚拟滚动同时设置 x 轴滚动不生效的问题。



## 2.17.0

2021-06-18

### 🆕 Feature

- `Table` 组件新增功能总结栏。
- `Table` 组件自定义前置操作列 `components.body.operations` 的 node 支持传入函数，该函数会接收 `record` 参数。

### 🐛 Bugfix

- 修复 `Table` 组件点击展开按钮，会冒泡到 `onRow.onClick` 的 bug。
- 修复 `Table` 组件 `pagination=false` 时，排序和筛选不生效的 bug。
- 修复 `Table` 组件 `rowSelection.selectedRowKeys` 中有 data 中不存在的值时选择报错的 bug。



## 2.16.0

2021-05-28

### 🆕 Feature

- `Table` 组件添加 `expandProps.rowExpandable` 参数，控制是否允许展开，优先级高于 `expandRowRender` 返回值。



## 2.15.3

2021-05-21

### 🐛 Bugfix

- `Table` 组件的 `propTypes` 中 `scroll` 添加 `string` 类型，避免 warning。
- 修复 `Table` 组件在翻页时，清空选中项但是没有触发 `rowSelection.onChange` 回调的 bug。

## 2.15.1

**注意：本次发版修复了 `2.15.0` 可能存在的隐患，如果你想升级 `2.15.0`，请直接升级到 `2.15.1`。**
**`2.15.0` 可能会在打包时出现 less 字体报错。**

### 💅 Style

- 修复 `Table` 组件 `size` 属性设置不生效的问题。



## 2.15.0

2021-04-30

### 💎 Optimization

- `Table` 组件优化选中逻辑，解决可能存在的keys、rows不同步的问题。

### 🆕 Feature

- `Table` 组件新增 `rowSelection.pureKeys` 参数，用于优化大数据选中体验。

### 🐛 Bugfix

- 修复 `Table` 组件 `pagination.defaultPageSize` 不生效的 bug。
- 修复 `Table` 组件 `onCell` 传自定义参数可能导致 Dom Warning 的 bug。

### 💅 Style

- 修复 `Table` 组件开启虚拟滚动和选中框之后，选中框宽度不对的问题。

### 🆎 TypeScript

- 修正 `Table` 组件 `expandedRowKeys` 的定义。



## 2.14.2

2021-04-23

### 💅 Style

- 修复 `Table` 组件表头自定义 `border-radius` 过大，内部元素会超出的样式问题。



## 2.14.1

2021-04-16

### 💎 Optimization

- `Table` 组件翻页时自动滚动至表格顶部。



## 2.14.0

2021-04-09

### 🐛 Bugfix

- 修复 `Table` 组件设置 `operations` 之后，空数据时总列数计算错误的 bug。

## 2.13.0

2021-03-26

### 💅 Style

- 修复 `Table` 组件在开启虚拟滚动时，复选框列没有居中的样式问题。

## 2.11.0

2021-03-12

### 🆕 Feature

- `Table` 组件支持 `renderPagination` 来自定义分页部分。

## 2.10.2

2021-03-09

### 🐛 Bugfix

- 修复 `Table` 组件 `bodyCellStyle` 会覆盖掉固定列样式的问题。



## 2.10.0 🏮

2020-02-26

### 💅 Style

- 修复 `Table` 组件在只有一页隐藏分页器时，依旧能看到分页器边距的样式问题。

## 2.9.0 🔥

2021-02-05

### 🆕 Feature

- 优化 `Table` 组件固定列类名计算逻辑，避免数据量大时滚动卡顿明显的问题。



### 🐛 Bugfix

- 修复 `Table` 组件 `expandedRowRender` 返回 `null` 时依旧会渲染空单元格的 bug。

## 2.8.1

2021-01-28

### 💅 Style

- 修复 `Table` 组件无数据时依旧有下边框的样式问题。



## 2.8.0

2021-01-22

### 🐛 Bugfix

- 修复 `Table` 组件 `expandedRowRender` 回调中 `index` 从 -1 开始而不是 0 的 bug。

### 💅 Style

- `Table` 筛选样式更新。

## 2.7.1

2021-01-18

### 🐛 Bugfix

- `Table` 组件圆角设置到 `header` 上，修复在某些场景下 chrome 引擎导致的滚动卡顿问题。
- 修复 `Table` 组件 `onChange` 回调在 `onSelectAll` 之前，导致 `onSelectAll` 受控被覆盖的 bug。



### 💅 Style

- 修复 `Table` 组件加载图标跟描述文案重叠的样式问题。

## 2.7.0

2021-01-15

### 🐛 Bugfix

- 修复 `Table` 组件 `onCell` 传入自定义参数，在自定义 `Cell` 组件内无法接受自定义参数的问题。

### 💅 Style

- 移除 `Table` 组件无数据时的下边框。

## 2.6.0

2021-01-08

### 🆕 Feature

- `Table` 组件新增 `rowSelection.onSelectAll` 属性，支持用户手动选择/取消选择所有行。

### 🐛 Bugfix

- 修复 `Table`传入`data`为`null`时，组件内部报错的问题。

## 2.5.0 🎅🏽

2020-12-25 🎄

### 🐛 Bugfix

- 修复 `Table` 定制前置操作列为空列的时候没有过滤掉引发空白的 bug。

## 2.4.1

2020-12-18

### 🆎 TypeScript

- 修正 `Table` 组件泛型定义及完善 `Ref` 类型。



## 2.4.0

2020-12-11

### 🆎 TypeScript

- `Table` 组件 `column.width` ts 类型添加 string 类型。

## 2.3.1

2020-12-04

### 🆎 TypeScript

- `Table` 组件的 `data` 和 `columns` 属性类型定义改为可选。

## 2.3.0

2020-11-27

### 🆕 Feature

- `Table` 组件 `filterDropdown` 的 `confirm` 参数添加参数 `filterKeys`，修复 `confirm` 不能立即拿到最新 `filterKeys` 的 bug。



### 💅 Style

- 修复 `Table` 组件空数据状态在固定列时暂无数据不居中的样式问题。



## 2.2.0

2020-11-20

### 💅 Style

- 修复 `Table` 组件在开启虚拟列表的时候，没有数据时 "暂无数据" 的提示未居中的问题。

## 2.1.0

2020-11-06

### 💅 Style

- 修复当 `Table` 组件高度过小时，选择分页条目的弹出框被遮盖的样式问题。
- 修复 `Table` 组件的 loading 遮罩没有盖住固定列的问题。
- 修复 `Table` 下边框被固定列覆盖的样式问题。

## 2.0.0

2020-10-30

### 🐛 Bugfix

- 修复 `Table` 组件 `pagination.sizeCanChange` 设置之后，点击切换分页无效的 bug。

