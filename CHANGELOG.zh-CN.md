---
order: 6
title: 更新日志
toc: false
timeline: true
---

`antd` 严格遵循 [Semantic Versioning 2.0.0](http://semver.org/lang/zh-CN/) 语义化版本规范。

#### 发布周期

* 修订版本号：每周末会进行日常 bugfix 更新。（如果有紧急的 bugfix，则任何时候都可发布）
* 次版本号：每月发布一个带有新特性的向下兼容的版本。
* 主版本号：含有破坏性更新和新特性，不在发布周期内。

如果需要查看 `2.0.0` 之前的更新日志，请移步 [GitHub](https://github.com/ant-design/ant-design/blob/1.x-stable/CHANGELOG.md)。

---

## 2.13.14

`2018-04-28`

- 🐞 修复对 less 3 的兼容性问题。[#7850](https://github.com/ant-design/ant-design/issues/7850)


## 2.13.13

`2018-03-09`

- 🐞 修复 `Upload` 组件当 `beforeUpload` 返回 `false` 时文件列表的更新逻辑。 [626ebf2](https://github.com/ant-design/ant-design/commit/ef6d7a5d9070c0b82deed837a7ebce7de9bc18aa)


## 2.13.12

`2018-02-26`

- 🐞 修复 Menu 的 `defaultOpenKeys` 包含不存在的 key 时，子菜单不能正确显示的问题。 [#8475](https://github.com/ant-design/ant-design/issues/8475)
- 🐞 修复 DatePicker 的值不能正确受控的问题。[#8885](https://github.com/ant-design/ant-design/issues/8885)

## 2.13.11

`2017-12-01`

- 📝 完善组件对 TypeScript 的支持。[#8394](https://github.com/ant-design/ant-design/pull/8394) [#8395](https://github.com/ant-design/ant-design/pull/8395) [@burdell](https://github.com/burdell) [@khayalan-mathew](https://github.com/khayalan-mathew)
- 🐞 修复了 Tooltip 不支持 `defaultVisible` 属性的问题。[#8257](https://github.com/ant-design/ant-design/issues/8257)
- 🐞 修复了 Modal 组件在传入自定义 `footer` 的时候默认 `footer` 被覆盖的问题。[#8379](https://github.com/ant-design/ant-design/issues/8379)
- 🐞 修复了 Upload 组件在 `beforeUpload` 中返回 `false` 时，修改 `fileList` 导致上传列表展示不正常的问题。[#8036](https://github.com/ant-design/ant-design/issues/8036)
- 🐞 修复了 Form 表单的信息回显在当 Input 组件 `size` 属性为 `default\small` 时没有对齐的问题。[#8243](https://github.com/ant-design/ant-design/issues/8243)
- 🐞 修复了 Form.Item 在互相嵌套时样式异常的问题。[#8320](https://github.com/ant-design/ant-design/issues/8320)
- 🐞 修复了 Form.Item 在 Chrome 和 Safari 下高度不一致的问题。 [#8220](https://github.com/ant-design/ant-design/issues/8220)
- 🐞 修复了 Form.Item 在部分情况下 label 内链接无法点击的问题。 [bf70d30](https://github.com/ant-design/ant-design/commit/bf70d30a60595916a38671f384ed17cbd0c4ba5d)
- 🐞 修复了 Progress 对于折行的场景兼容性问题。[#8239](https://github.com/ant-design/ant-design/issues/8239)

## 2.13.10

`2017-11-12`

- 📝 添加 [招聘](http://ant.design/docs/resource/work-with-us-cn) 页面。
- 📝 重构了可编辑表格的演示代码。[#8026](https://github.com/ant-design/ant-design/issues/8026)
- 🌟 优化了 Layout.Sider 的探测方式，现在支持 Sider 随意内嵌和组合（不再需要指定 `__ANT_LAYOUT_SIDER` 属性）。[#8077](https://github.com/ant-design/ant-design/pull/8077/) [@yasinuslu](https://github.com/yasinuslu)
- 🐞 修复 Chrome 62 下 Input.Group 内 Select 和 Input 的对齐问题。[ant-design/ant-design-pro#139](https://github.com/ant-design/ant-design-pro/issues/139)
- 🐞 修复 Cascader 搜索在 options 内 children 为空数组时工作不正常的问题。[#8130](https://github.com/ant-design/ant-design/issues/8130) [@jdz321](https://github.com/jdz321)
- 🐞 修复一个 AutoComponent 和 Input 样式优先级导致错位的问题。[#8081](https://github.com/ant-design/ant-design/issues/8081)
- 🐞 修复 IE9 下 Upload 初始化时报错的问题。[#7706](https://github.com/ant-design/ant-design/issues/7706)
- 🐞 修复 Select 的 filterOption 参数的 TypeScript 定义。[#8128](https://github.com/ant-design/ant-design/issues/8128)

## 2.13.9

`2017-11-06`

- 🌟 发布 [Ant Design Pro](https://pro.ant.design/)。
- 🐞 修复 `Cascader[popupVisible]` 失效问题。[#8088](https://github.com/ant-design/ant-design/issues/8088)
- 🐞 修复原生 `input[type=checkbox|radio]` 看不到的问题。[7c3a483](https://github.com/ant-design/ant-design/commit/7c3a48319074a800c89935e728904933d503ee86)
- 🐞 修复 `Input.Search[suffix]` 失效的问题。[#7970](https://github.com/ant-design/ant-design/issues/7970)
- 🐞 修复 Slider TypeScript 定义问题。[#8102](https://github.com/ant-design/ant-design/pull/8102) [@davschne](https://github.com/davschne)

## 2.13.8

`2017-10-27`

- 🌟 新增国内镜像文档站点：[http://ant-design.gitee.io](http://ant-design.gitee.io)
- 🐞 修复了 Menu 在 React 16 下 `ref warning` 的问题。[#8037](https://github.com/ant-design/ant-design/pull/8037) [@vgeyi](https://github.com/vgeyi)
- 🐞 修复了 Card 在比较宽的时候 `loading` 样式的问题。[ad9809ec](https://github.com/ant-design/ant-design/commit/ad9809ec2e29275c9348537b04584dcfdc96659a)
- 📝 引入了 API 展示排序规则，增强文档易读性。[#7896](https://github.com/ant-design/ant-design/pull/7896)[@monkindey](https://github.com/monkindey)
- 📝 优化了 Modal 设置样式的文档。[#7840](https://github.com/ant-design/ant-design/issues/7840) [@kossel](https://github.com/kossel)
- 🐞 修复了 IOS 下 Input 有内阴影的样式问题。[#7974](https://github.com/ant-design/ant-design/pull/7974) [@cnahliu](https://github.com/cnahliu)

## 2.13.7

`2017-10-22`

- 🐞 修复了 AutoComplete 的 input 高度。 [#7918](https://github.com/ant-design/ant-design/issues/7918)
- 🐞 修复了 Cascader `inputPrefixCls` 不能完全生效的问题。[#7945](https://github.com/ant-design/ant-design/pull/7945) [@vgeyi](https://github.com/vgeyi)
- 🐞 修复了有侧边栏的 Layout 存在多余外边距的问题。[#7967](https://github.com/ant-design/ant-design/issues/7967)
- 🐞 修复了 RangePicker 在选中预设范围时间时不能关闭选择面板的问题。[#7747](https://github.com/ant-design/ant-design/issues/7747)
- Table
  - 🐞 修复了 Table 列中 Radio 选择框无法居中的问题。[#7969](https://github.com/ant-design/ant-design/issues/7969)
  - 🐞 修复了去掉 `fixed` 属性设置后 Table 列无法进行筛选的问题。[#7909](https://github.com/ant-design/ant-design/issues/7909)
- 🌟 Badge 新增 `scrollNumberPrefixCls` 属性。[#7882](https://github.com/ant-design/ant-design/pull/7882) [@vgeyi](https://github.com/vgeyi)
- 🌟 补充了一些 less 变量。[#7886](https://github.com/ant-design/ant-design/issues/7886) [@syssam](https://github.com/syssam)

## 2.13.6

`2017-10-12`

- 🐞 修复 `beforeUpload` 未指定返回值时会阻止上传的问题。[#7870](https://github.com/ant-design/ant-design/issues/7870)

## 2.13.5

`2017-10-11`

- 🐞 修复 FormItem 不能跟 reac-hot-loader 一起使用的问题。[#7775](https://github.com/ant-design/ant-design/issues/7775)
- 🐞 修复 less 变量 `@link-hover-decoration` 没按预期工作的问题。[#7821](https://github.com/ant-design/ant-design/issues/7821)
- 🐞 修复 Uploade 的 `beforeUpload` 没返回 promise 的问题。[#7833](https://github.com/ant-design/ant-design/issues/7833)
- 🐞 修复 Input.Search 的搜索图标会被 Form 的验证图标遮住的问题。[#7854](https://github.com/ant-design/ant-design/issues/7854)
- AutoComplete
  - 🐞 修复循环引用问题。[#7742](https://github.com/ant-design/ant-design/pull/7742) [@menberg](https://github.com/ant-design/ant-design/pull/7742)
  - 🐞 修复使用 TextArea 并拖动输入框大小时的样式错乱问题。[#7801](https://github.com/ant-design/ant-design/issues/7800)
- 🌟 改进一些 TypeScript 定义。[cf788d7](https://github.com/ant-design/ant-design/commit/cf788d7b4dda58f61da91086ccfe0c67872fc709) [d4c75d43](https://github.com/ant-design/ant-design/commit/d4c75d43a1824d36583d9d8f9b209a4b9526a3af)
- 🌟 新增 less 变量 [2e2acb5](https://github.com/ant-design/ant-design/commit/2e2acb5be9a171f217f2a1a143b34b2624b49b06)

## 2.13.4

`2017-09-29`

- 🐞 修复 Pagination 小号样式失效的问题。
- 🐞 修复 Anchor 的样式错位。[#7712](https://github.com/ant-design/ant-design/issues/7712)
- 🐞 修复 TreeSelect 搜索框下多余文字的问题。[#7703](https://github.com/ant-design/ant-design/issues/7703)
- 🐞 修复 Form 校验文字跳动的问题。[#7730](https://github.com/ant-design/ant-design/issues/7730)
- 🐞 修复各类型 Button Group 的 loading 样式。 [#7709](https://github.com/ant-design/ant-design/issues/7709)
- 🐞 修复 placeholder 文本在某些情况下无法看清的问题。[#7365](https://github.com/ant-design/ant-design/issues/7365)
- 🐞 修复一个 Mention 的 `suggestion.toLowerCase is not a function` 报错问题。 [#7696](https://github.com/ant-design/ant-design/issues/7696) [@kappa-gooner](https://github.com/kappa-gooner)
- 🐞 修复一个 Layout.Sider 子元素的高度问题。[#7716](https://github.com/ant-design/ant-design/pull/7716) [@zheeeng](https://github.com/zheeeng)
- 🐞 修复 Dropdown 菜单分组的样式。
- 🐞 修复 Table 筛选图标和菜单样式错位。
- 🐞 修复一个 AutoComplete 在 Inferno 下循环引用的问题。[#7742](https://github.com/ant-design/ant-design/pull/7742) [@menberg](https://github.com/menberg)
- 🐞 修复 Upload 使用 `beforeUpload` 验证文件类型失败后无法再次上传的问题。[#7762](https://github.com/ant-design/ant-design/issues/7762) [#6983](https://github.com/ant-design/ant-design/issues/6983)
- TypeScript
  - 🐞 修复 Input 的 `maxLength` 定义。[#7744](https://github.com/ant-design/ant-design/pull/7744) [@delesseps](https://github.com/delesseps)
  - 🐞 修复 DatePicker 等组件的 `disabledTime` 的返回值定义。[#7740](https://github.com/ant-design/ant-design/pull/7740) [@778758944](https://github.com/778758944)

## 2.13.3

`2017-09-22`

- 🐞 修复 Affix 在内容与视口高度差小于 children 高度时触发的滚动抖动问题。[#2349](https://github.com/ant-design/ant-design/issues/2349)
- 🐞 修复 `Card[title]` 为空且设置 `Card[extra]` 时样式错乱的问题。[f46112d#commitcomment-24480417](https://github.com/ant-design/ant-design/commit/f46112d38561c89780eb44ecbba82347d2b912da#commitcomment-24480417)
- 🐞 修复 `Checkbox[children]` TypeScript definition。[#7650](https://github.com/ant-design/ant-design/issues/7650) [@liaokaien](https://github.com/liaokaien)
- 🐞 修复 `getFieldDecorator` 内使用嵌套 id 后点击 `Form.Item` label 报错的问题。[#7693](https://github.com/ant-design/ant-design/issues/7693)
- Input
  - 🐞 修复 `Input.Group[compat]` 内嵌 `Select` 等控件时的样式问题。[#7662](https://github.com/ant-design/ant-design/issues/7662)
  - 🐞 优化 `Input[autoComplete]` TypeScript 定义。[#7699](https://github.com/ant-design/ant-design/pull/7699) [@delesseps](https://github.com/delesseps)
- LocaleProvider
  - 🇵🇹 新增葡萄牙语。[#7449](https://github.com/ant-design/ant-design/pull/7449) [@taviroquai](https://github.com/taviroquai)
  - 🐞 修复荷兰语 locale 缺少文案的问题。[#7694](https://github.com/ant-design/ant-design/pull/7694) [@kstiopin](https://github.com/kstiopin)
- Table
  - 🐞 修复 `rowSelection` 导致的表头高度问题。[#7663](https://github.com/ant-design/ant-design/issues/7663)
  - 🐞 修复使用 `rowSelection.hideDefaultselections` 时导致自定义选项点击没反应的问题。[#7626](https://github.com/ant-design/ant-design/issues/7626) [@infeng](https://github.com/infeng)
  - 🐞 优化 `Table[scroll]` TypeScript definition。[#7640](https://github.com/ant-design/ant-design/pull/7640) [@BlackGanglion](https://github.com/BlackGanglion)

## 2.13.2

`2017-09-15`

- 🐞 修复了 Card Extra 内容过多样式错乱的问题。[#7604](https://github.com/ant-design/ant-design/issues/7604)
- 🐞 修复了分组 Menu 收缩时的错位问题。[#7109](https://github.com/ant-design/ant-design/issues/7109)
- 🐞 回滚 [#7142](https://github.com/ant-design/ant-design/issues/7142) 里对固定列表格空数据的样式优化，修复带来的一系列样式问题。
- 🐞 修复了 Form `getFieldDecoratorOptions` 缺失 `normalize` 以及 `validateFirst` 属性定义的问题。[#7552](https://github.com/ant-design/ant-design/issues/7552) [@meteor91](https://github.com/meteor91) [@mitchelldemler](https://github.com/mitchelldemler)
- 🐞 修复了 Modal 的 `zIndex` 属性定义。[#7624](https://github.com/ant-design/ant-design/issues/7624)
- 🌟 优化了 Tree 加载中图标的显示位置。[#7584](https://github.com/ant-design/ant-design/issues/7584)
- 🌟 优化了大量组件的英文文档。[@khalibloo](https://github.com/khalibloo)

## 2.13.1

`2017-09-10`

- 🐞 修复了 Card.Grid 的样式问题。[commit/c7d6ce](https://github.com/ant-design/ant-design/commit/c7d6ce5d3f7bfae1f2252d702fb1bdf04fdc80cb)
- 🐞 修复了 Cascader 指针图标与文字重叠的问题。[#7475](https://github.com/ant-design/ant-design/issues/7475)
- 🐞 修复了 Pagination 在简洁模式下前后按钮未展示的问题。[#7500](https://github.com/ant-design/ant-design/issues/7500)
- 🐞 修复了 Slider 的 type 定义。[#7532](https://github.com/ant-design/ant-design/issues/7532)
- Table
  - 🐞 修复了在空数据情况下包含固定列时的一些样式问题。[#7457](https://github.com/ant-design/ant-design/issues/7457) [#7468](https://github.com/ant-design/ant-design/issues/7468) [#7470](https://github.com/ant-design/ant-design/issues/7470) [#7509](https://github.com/ant-design/ant-design/issues/7509)
  - 🌟 补充了 API 文档。[#7525](https://github.com/ant-design/ant-design/pull/7525) [@hansnow](https://github.com/hansnow)
- 🐞 修复了 Upload 的 type 定义。 [#7507](https://github.com/ant-design/ant-design/pull/7507) [@WingGao](https://github.com/WingGao)
- 🐞 修复了 Submenu 展开时 inlineCollapsed Menu 的样式问题。[#7514](https://github.com/ant-design/ant-design/issues/7514)
- 🐞 修复了一些表单控件的校验样式问题。[#7498](https://github.com/ant-design/ant-design/issues/7498)
- 🐞 修复了 @link-hover-decoration 无效的问题。[#7531](https://github.com/ant-design/ant-design/issues/7531)
- 🌟 优化了部分组件的英文文档。[@khalibloo](https://github.com/khalibloo)

## 2.13.0

`2017-09-01`

- 🌟 Popconfirm 和 Modal 及其相关方法新增 `okType` 和 `cancelType` 用以指定按钮类型。[#6848](https://github.com/ant-design/ant-design/pull/6848) [@yociduo](https://github.com/yociduo)
- 🌟 Modal 及其相关方法新增 `zIndex`。[#6880](https://github.com/ant-design/ant-design/pull/6880) [@Alex1990](https://github.com/Alex1990)
- 🌟 RadioGroup 新增 `name` 属性。[#7009](https://github.com/ant-design/ant-design/pull/7009) [@djyde](https://github.com/djyde)
- 🌟 Table 新增 `hideDefaultSelections` 属性。[#7295](https://github.com/ant-design/ant-design/issues/7295)
- Dropdown
  - 🌟 新增 `disabled` 属性。[#7102](https://github.com/ant-design/ant-design/pull/7102) [@yociduo](https://github.com/yociduo)
  - 🌟 Menu 默认调整为不能选中。
- 🌟 Pagination 的 `itemRender` 新增第三个参数 `originalElement`。
- 🌟 AutoComplete 新增 `backfill` 属性，键盘选择时能回填选中项到输入框中。[#5764](https://github.com/ant-design/ant-design/issues/5764)
- 🌟 Select 新增 `firstActiveValue` 属性，允许指定首次打开时默认选中的项。[#6318](https://github.com/ant-design/ant-design/issues/6318) [@L-x-C](https://github.com/ant-design/ant-design/issues/6318)
- LocaleProvider
  - 🌟 新增波斯语。[#6878](https://github.com/ant-design/ant-design/pull/6878) [@mkermani144](https://github.com/mkermani144)
  - 🌟 新增希腊语。[#6928](https://github.com/ant-design/ant-design/pull/6928) [@michmach](https://github.com/michmach)
  - 🌟 新增挪威语。[#7122](https://github.com/ant-design/ant-design/pull/7122) [@santi](https://github.com/santi)
  - 🌟 新增塞尔维亚语。[#7201](https://github.com/ant-design/ant-design/pull/7201) [@paunovic-stefan](https://github.com/paunovic-stefan)
- 🐞 修复 Sider 隐藏时 Menu 的标题不会隐藏的问题。[#7409](https://github.com/ant-design/ant-design/issues/7409)
- 🐞 修复 TypeScript 定义 [#7355](https://github.com/ant-design/ant-design/pull/7355) [#7378](https://github.com/ant-design/ant-design/pull/7378) [#7384](https://github.com/ant-design/ant-design/pull/7384)
- 🐞 修复一些组件不能使用条件渲染的问题。[#6530](https://github.com/ant-design/ant-design/issues/6530)
- 网站
  - 🌟 新增快捷键 `s` 聚焦搜索框。
  - 🌟 页脚新增主色修改预览功能。

## 2.12.8

`2017-08-27`

- 📖 重写了 [《在 create-react-app 中使用》](/docs/react/use-with-create-react-app) 文档，现在不再需要 eject。[#7276](https://github.com/ant-design/ant-design/pull/7276)
- 🌟 优化了固定列的空表格样式。[#7298](https://github.com/ant-design/ant-design/issues/7298)
- 🐞 修复了 CheckboxGroup 和 Checkbox 的 `disabled` 属性逻辑。[#7266](https://github.com/ant-design/ant-design/issues/7266) [@dilidili](https://github.com/dilidili)
- 🐞 修复在 react-snapshot 或 jsdom 环境下测试 Spin 和 Carousel 时报错的问题。[#3308](https://github.com/ant-design/ant-design/issues/3308) [#7318](https://github.com/ant-design/ant-design/issues/7318)
- 🐞 修复 Select、Tooltip、Menu 的一些细节样式问题。

## 2.12.7

`2017-08-21`

- Angular@4.0 版 antd [ng-zorro-antd](https://ng.ant.design) 开源。
- 优化 Affix 支持的场景。[01d4acb](https://github.com/ant-design/ant-design/commit/01d4acb7a9b030be3552b4ca19b4e899dc2bb7c7)
- 修复 AutoComplete children ref 失效的问题。[#6814](https://github.com/ant-design/ant-design/issues/6814)
- Button
  - 优化自动在中文字符中间插入空格的逻辑。[59b11f3](https://github.com/ant-design/ant-design/commit/59b11f3b480d43cb32fb24e351cb4c4dd569243c)
  - 修复点击事件的 `event.target` 不是 button 的问题。[#7034](https://github.com/ant-design/ant-design/issues/7034)
- 修复 Carousel 的 `innerSlider` 引用问题。[#7191](https://github.com/ant-design/ant-design/issues/7191)
- 修复 DatePicker 中的按钮样式。[ad6dbcb](https://github.com/ant-design/ant-design/commit/ad6dbcb9c6dac407a38f2391d3e5fa1d8ae1cfab)
- 修复 Form TypeScript definition。[#7245](https://github.com/ant-design/ant-design/pull/7245)
- 修复 InputNumber 的 TypeScript definition。[#7257](https://github.com/ant-design/ant-design/issues/7257)
- 修复 `Layout.Sider` 在 IE11 下没有折叠动画的问题。[#6349](https://github.com/ant-design/ant-design/issues/6349)
- 修复 LocaleProvider 西班牙语的拼写问题。[#7234](https://github.com/ant-design/ant-design/pull/7234) [@ramsesmoreno](https://github.com/ramsesmoreno)
- 修复 notification 默认 placement 会被覆盖的问题。[#5895](https://github.com/ant-design/ant-design/issues/5895)
- 修复 Pagination 按钮的 disabled 样式。[cf3c0aa](https://github.com/ant-design/ant-design/commit/cf3c0aac43e2825bfd85ca3b8abbf4742e504260)
- 修复 Select exports 导致的 webpack 构建错误的问题。[#7222](https://github.com/ant-design/ant-design/issues/7222)
- 修复 Tabs 在父容器宽度动态变化时切换按钮没有出现的问题。[#7231](https://github.com/ant-design/ant-design/issues/7231) [#7210](https://github.com/ant-design/ant-design/issues/7210)
- 修复 Timeline 在只有一个 `Timeline.Item` 时的样式问题。[#7214](https://github.com/ant-design/ant-design/issues/7214)
- 修复 Upload 在 uid 为 0 时的错误行为。[#7269](https://github.com/ant-design/ant-design/issues/7269)

## 2.12.6

`2017-08-11`

- 修复了在 IE9/10/11 下 Collapse 的箭头位置不正确的问题。[af9dc73](https://github.com/ant-design/ant-design/commit/af9dc73eef2aac3e68fdfc99f9231153437f5068)
- 修复了 Table 为空表格时滚动条展示位置不正确的问题。[#7142](https://github.com/ant-design/ant-design/issues/7142)
- 修复了 RangePicker Input 的高度。[47c5de2](https://github.com/ant-design/ant-design/commit/47c5de29f370a77fc19a6a8eda8ac57476f312a6)
- Card
  - 优化了 Card.Grid 边框覆盖的样式。[807b573](https://github.com/ant-design/ant-design/commit/807b573bff43bc71115afeb086f565561807a32d)
  - 修复了对应 `no-animation` 类型的 className。[#7185](https://github.com/ant-design/ant-design/issues/7185)
- 修复了 Input Safari 下文本对齐的问题。[#7135](https://github.com/ant-design/ant-design/issues/7135)
- Layout
  - 修复了组件的拉伸展示问题。[500b222](https://github.com/ant-design/ant-design/commit/500b2225567f03397d9faec5f4e60a8f35fc4d28)
  - 修复了折叠箭头的位置。[f689ede](https://github.com/ant-design/ant-design/commit/f689ede0fa836dd0d99f4e4d96e0c43d0ff19742)
- 修复了 Upload 的 response 不是 string 的情况下没有处理错误提示信息的问题。[#6818](https://github.com/ant-design/ant-design/issues/6818)
- Form
  - 补充了文档中缺少的 `validateFirst` 属性描述。[#6959](https://github.com/ant-design/ant-design/issues/6959)
  - 修复了 `wrappedComponentRef`。[#6545](https://github.com/ant-design/ant-design/issues/6545)
  - 补充了 FormCreateOption 的 `generic type`。[#7119](https://github.com/ant-design/ant-design/pull/7119) [@djyde](https://github.com/djyde)
  - 修改了 `square` 的字体大小为 `@form-feedback-icon-size`。[9bcde59](https://github.com/ant-design/ant-design/commit/9bcde590015855a12fdee851cf4e4836d0195cd7)

## 2.12.5

`2017-08-07`

- 修复 ES 模式下报 `SelectPropTypes not found` 的问题。[#7123](https://github.com/ant-design/ant-design/issues/7123)
- 修复 Row 在 flex 模式下元素不换行的问题。[4f73a23](https://github.com/ant-design/ant-design/commit/4f73a23a103733a3c148bb04013493a042f90a8f)
- 修复 InputNumber 和 RangePicker 的样式问题。[#7117](https://github.com/ant-design/ant-design/issues/7117) [#7126](https://github.com/ant-design/ant-design/issues/7126)

## 2.12.4

`2017-08-06`

- 修复了 Affix 在 IE 下调用对象无效的报错。[#7060](https://github.com/ant-design/ant-design/issues/7060)
- 对 Badge 默认 title 的出现条件进行了优化。[#7024](https://github.com/ant-design/ant-design/issues/7024)
- Card
  - 修改了文档中 `onHovering` 属性的错误描述。[#7078](https://github.com/ant-design/ant-design/issues/7078)
  - 修复了 `children` 的类型定义。[pull/7030](https://github.com/ant-design/ant-design/pull/7030) [@djyde](https://github.com/djyde)
- 修复了 Collapse `onChange` 属性参数的类型定义。[pull/7084](https://github.com/ant-design/ant-design/pull/7084) [@davidctj](https://github.com/davidctj)
- Dropdown
  - 修复了 Dropdown.Button 的对齐问题。[#7070](https://github.com/ant-design/ant-design/issues/7070)
  - 补充了文档中缺失的 `size` 属性。[pull/7071](https://github.com/ant-design/ant-design/pull/7071) [@hansnow](https://github.com/hansnow)
- Input
  - 修复了 outline 被 addon 遮盖的问题。[commit/0f63c7](https://github.com/ant-design/ant-design/commit/0f63c7186ef3a5db36c01df9d9ebde9d5b3871ef)
  - 修复了 InputGroup 的示例问题。[pull/7089](https://github.com/ant-design/ant-design/pull/7089) [@jdz321](https://github.com/jdz321)
- 修复了 InputNumber 格式化示例的报错问题。[pull/7098](https://github.com/ant-design/ant-design/pull/7098) [@tim-soft](https://github.com/tim-soft)
- Menu
  - 修复了 Menu 折叠并缩起时的不正常表现。[#7048](https://github.com/ant-design/ant-design/issues/7048) [#7063](https://github.com/ant-design/ant-design/issues/7063)
  - 修复了子菜单被选中时 SubMenu 没有高亮的问题。[pull/7042](https://github.com/ant-design/ant-design/pull/7042) [@atomgao](https://github.com/atomgao)
- 修复了 notification `type` 的类型定义。[#7073](https://github.com/ant-design/ant-design/issues/7073) [@marswong](https://github.com/marswong)
- 修复了 Pagination `showTotal` 的类型定义。[#7054](https://github.com/ant-design/ant-design/issues/7054)
- 修复了 RangePicker 在清空后的报错问题。[#7077](https://github.com/ant-design/ant-design/issues/7077)
- 补充了 Select 缺失的 `onFocus` `onBlur` 类型定义。[pull/7082](https://github.com/ant-design/ant-design/pull/7082) [@troynt](https://github.com/troynt)
- 修复了 Tabs 垂直模式下 `tabBarExtraContent` 样式错乱的问题。rc-tabs 升级到 9.0.2，对 TabBar 的 `extraContent` 的结构进行了重构。[#6578](https://github.com/ant-design/ant-design/issues/6578)
- 修复了 TreeSelect 图标不能正常展示的问题。[#7020](https://github.com/ant-design/ant-design/issues/7020)
- 修复了 `error TS7016: Could not find a declaration file for module 'rc-util/lib/Dom/addEventListener'` 的报错。[#7033](https://github.com/ant-design/ant-design/issues/7033) [@djyde](https://github.com/djyde)
- 完成了『模式-列表』的文档翻译。[list](https://ant.design/docs/pattern/list) [@zachguo](https://github.com/zachguo)

## 2.12.3

`2017-07-30`

- 修复 Checkbox 半选状态禁用时的样式。
- 修复 Card 会出现 `this.container` 不存在的问题。[#6976](https://github.com/ant-design/ant-design/pull/6976) [@neekey](https://github.com/neekey)
- 修复基础字体改为 `14px` 时 Button 的对齐问题。[#7001](https://github.com/ant-design/ant-design/issues/7001)
- 修复 Grid Card 的内边距。
- Dropdown
  - 修复菜单可能被多次点击的问题。[#6314](https://github.com/ant-design/ant-design/issues/6314)
  - 修复在菜单显示前 hover 会导致菜单消失的问题。[#6949](https://github.com/ant-design/ant-design/issues/6949)
  - 修复菜单的错位问题。
- 改进了 Menu 的动画效果。[#6955](https://github.com/ant-design/ant-design/pull/6955)
- 调整了 DatePicker 中图标的位置。
- 新增 less 变量。[e1a46cc](https://github.com/ant-design/ant-design/commit/e1a46cc419fb4975ae1782ba793b378c8e584057)
- 修复了一些 TypeScript 定义问题。

## 2.12.2

`2017-07-22`

- 将 message 默认出现的时长从 1.5s 调整为 3s。
- 重构了 Anchor，修复未滚动时链接没有高亮的问题。[#6473](https://github.com/ant-design/ant-design/issues/6473)
- 修复 Input.TextArea 的失效样式。[#6858](https://github.com/ant-design/ant-design/pull/6858) [@lyz810](https://github.com/lyz810)
- 修复 TimePicker 的失效样式。[#6918](https://github.com/ant-design/ant-design/issues/6918)
- 修复 2.12.1 里再次出现的表单反馈图标和下拉图标重叠的问题。[#4431](https://github.com/ant-design/ant-design/issues/4431)
- 修复垂直 Tabs 的切换箭头样式。[255eac9](https://github.com/ant-design/ant-design/commit/255eac907949ded5b79f216a29831dcf4afa9362)
- 调整波兰语的文案。[#6869](https://github.com/ant-design/ant-design/pull/6869) [#6870](https://github.com/ant-design/ant-design/pull/6870) [#6871](https://github.com/ant-design/ant-design/pull/6871) [@imosapatryk](https://github.com/imosapatryk)
- 修复源码中含有 http 的链接而被集团安全扫描工具报错的问题。[#6893](https://github.com/ant-design/ant-design/issues/6893)
- 调整 Menu 的图标和文字对齐问题。
- 修复一个 Tooltip 的 `overlay is marked as required` 的警告问题。[#6897](https://github.com/ant-design/ant-design/issues/6897)
- 修复 Slider 在有色背景下的失效样式。[#6665](https://github.com/ant-design/ant-design/issues/6665)
- 调整了 TreeSelect 选项的点击范围。
- 修复了一些 TypeScript 定义问题。

## 2.12.1

`2017-07-17`

- 修复保加利亚语中的拼写错误。[#6788](https://github.com/ant-design/ant-design/pull/6788) [@NoHomey](https://github.com/NoHomey)
- 修复 `<Avatar src="..." />` 无法加载图片时的样式问题。[#6804](https://github.com/ant-design/ant-design/issues/6804)
- 修复 `Button.Group` 内使用 loading 状态的图标按钮时的样式问题。[#6822](https://github.com/ant-design/ant-design/issues/6822)
- 修复 Checkbox TypeScript 定义问题。[#6768](https://github.com/ant-design/ant-design/issues/6768)
- 修复 `Collapse.Panel[header]` 内容过长时的样式问题。[#6832](https://github.com/ant-design/ant-design/issues/6832)
- Input
  - 修复 `className` 没有添加到 wrapper 上的问题。[#6809](https://github.com/ant-design/ant-design/issues/6809)
  - 修复 `Input.Search` 的 TypeScript 定义。[#6837](https://github.com/ant-design/ant-design/pull/6837) [@newraina](https://github.com/newraina)
  - 修复 `Input.TextArea` 的 value 无法被重置的问题。[#6776](https://github.com/ant-design/ant-design/issues/6776)
  - 修复 `Input.Group` 内使用 Select 组件时的 error 样式问题。

    <img src="https://user-images.githubusercontent.com/507615/27983847-551ffe0a-63f9-11e7-81ba-8c3336ddafd0.png" />

- 修复 Layout 实现影响 Anchor、BackTop 的功能的问题。[#6817](https://github.com/ant-design/ant-design/issues/6817)
- Menu
  - 修复折叠动画失效问题。
  - 修复 `Menu.Item` 边框样式问题。[46ffda9](https://github.com/ant-design/ant-design/commit/46ffda9c9385ec54e0c78594ed6c280d40ef035d)
- 修复 RangePicker 设置了 `value|defaultValue` 后，浮层中的月份展示不对的问题。[#6764 point 3](https://github.com/ant-design/ant-design/issues/6764)
- 修复 Tooltip 对齐问题。[#6830](https://github.com/ant-design/ant-design/issues/6830)

## 2.12.0

`2017-07-08`

- 新增 Card `noHovering` 属性以及 Card.Grid 组件。[pull/6748](https://github.com/ant-design/ant-design/pull/6748)
- DatePicker、MonthPicker、RangePicker 支持 `className` 属性。[pull/6584](https://github.com/ant-design/ant-design/pull/6584) [@EnrikoLabriko](https://github.com/EnrikoLabriko)
- 新增 Input.TextArea，原 Input[type='textArea'] 将被废弃。[pull/6138](https://github.com/ant-design/ant-design/pull/6138)
- LocaleProvider 新增泰语支持。[pull/6721](https://github.com/ant-design/ant-design/pull/6721) [@koobitor](https://github.com/koobitor)
- Mention 支持 `focus` 方法。[#6135](https://github.com/ant-design/ant-design/issues/6135)
- Menu `inline` 模式下支持用 `inlineCollapsed` 属性缩起/展开，同时 Layout.Sider 使用 `context` 向 Menu 传递 `collapsed` 属性，无需再自己定制样式。[pull/6686](https://github.com/ant-design/ant-design/pull/6686)
- 新增 Pagination `itemRender` 属性，用于自定义页码的结构。[25a603](https://github.com/ant-design/ant-design/commit/25a60322e5c6649522fb9f0d34919eba0ccb1f65)
- 新增 Tooltip `autoAdjustOverflow` 属性，支持关闭自动调整位置的功能。[pull/6661](https://github.com/ant-design/ant-design/pull/6661) [@jdz321](https://github.com/jdz321)
- 修复了 Avatar 错误的文档。[pull/6711](https://github.com/ant-design/ant-design/pull/6711) [@llaski](https://github.com/llaski)
- DatePicker
  - 修复 `onOk` 类型定义。[pull/6619](https://github.com/ant-design/ant-design/pull/6619) [@newraina](https://github.com/newraina)
  - 优化了图标样式。[pull/6655](https://github.com/ant-design/ant-design/pull/6655) [@megawac](https://github.com/megawac)
- Form
  - 修复 FormItem `extra` 文案的行高问题。[#6618](https://github.com/ant-design/ant-design/issues/6618)
  - 修复 FormItem `labelCol` `wrapperCol` 类型定义。[pull/6611](https://github.com/ant-design/ant-design/pull/6611) [@newraina](https://github.com/newraina)
- 修复自适应高度的 Input 文本域出现滚动条的问题。[#6609](https://github.com/ant-design/ant-design/issues/6609)
- 补充了 InputNumber 中缺失的 `precision` 类型定义。[#6715](https://github.com/ant-design/ant-design/issues/6715)
- 修复 Select 样式溢出的问题。[#6621](https://github.com/ant-design/ant-design/issues/6621)
- Slider
  - 优化了样式。[#6665](https://github.com/ant-design/ant-design/issues/6665)
  - rc-slider 升级至 8.2.0，新增 `dotStyle`，`activeDotStyle` 属性。[rc-slider/pull/292](https://github.com/react-component/slider/pull/292)
- 修复 Spin 遮罩层被穿透的样式问题。[#6759](https://github.com/ant-design/ant-design/issues/6759)
- 修复嵌套 Steps 的样式问题。[#6754](https://github.com/ant-design/ant-design/issues/6754)
- Table
  - 修复了固定头部 Table 中展开区域的背景色样式问题。[#6657](https://github.com/ant-design/ant-design/issues/6657)
  - 补充了 Table 文档中缺失的 `onRowDoubleClick` 属性。[pull/6667](https://github.com/ant-design/ant-design/pull/6667) [@yurtaev](https://github.com/yurtaev)
  - 补充了 Table 文档中 `loading` 属性的说明。[pull/6763](https://github.com/ant-design/ant-design/pull/6763) [@hansnow](https://github.com/hansnow)
  - rc-table 升级至 5.4.0，新增对 `onRowMouseEnter`，`onRowMouseLeave` 的支持。[rc-table/0db582](https://github.com/react-component/table/commit/0db582a75dfa119715eb4db8a59eacfca744c5a0)
- 优化了 TimePicker 的格式支持。[950c32](https://github.com/ant-design/ant-design/commit/950c321b25091ef31b130b83674478974590d7f3)
- 对大量组件的样式进行了优化或微调，包括 [Checkbox](https://ant.design/components/checkbox/)，[Radio](https://ant.design/components/radio/)，[Tabs](https://ant.design/components/tabs/)，[Card](https://ant.design/components/card/) 等等。
- Demo 现在可以在 codepen 中打开。[#5140](https://github.com/ant-design/ant-design/issues/5140)

## 2.11.2

`2017-06-25`

- 修复 Dropdown.Button 不支持 `getPopupContainer` 方法的问题。[#6527](https://github.com/ant-design/ant-design/pull/6527)
- 修复 Dropdown 子菜单 disabled 时的样式错误问题。[#6548](https://github.com/ant-design/ant-design/issues/6548)
- 修复 Calendar 的背景颜色问题。 [aaf2a50](https://github.com/ant-design/ant-design/commit/aaf2a508bef96f81faf556036649b2a2fe5b635b)
- Calender 的下拉菜单现在在 header 中显示。[#6479](https://github.com/ant-design/ant-design/pull/6479)
- 修复 Input 和 Textarea 横向滚动的问题。[#6577](https://github.com/ant-design/ant-design/issues/6577)
- 补充了 Checkbox 和 Radio 的 `disabled` 属性文档。[#6597](https://github.com/ant-design/ant-design/pull/6597)
- 增大了 Table 的排序和过滤图标的可点击区域。[#6528](https://github.com/ant-design/ant-design/pull/6528)
- 为 Table.props.onRowClick 函数增加了 event: Event 参数。[e2a99f5](https://github.com/ant-design/ant-design/commit/e2a99f53f7a27bd7de4adf99d0e1ee755b537c72)

## 2.11.1

`2017-06-18`

- 修复 Table 的分页设置 `className` 无效的问题。[#6416](https://github.com/ant-design/ant-design/issues/6416)
- 修复 Tabs 嵌套使用时的样式问题。[#6431](https://github.com/ant-design/ant-design/issues/6431) [@sadmark](https://github.com/sadmark)
- 修复 RadioButton 在小屏幕下会没有左侧边框的问题。[#6492](https://github.com/ant-design/ant-design/issues/6492) [@pierreneter](https://github.com/pierreneter)
- 修复 RangePicker 底部会多一条边框的问题。
- 完善 Dropdown.Button 类型定义。[#6482](https://github.com/ant-design/ant-design/pull/6482) [@newraina](https://github.com/newraina)

## 2.11.0

`2017-06-07`

- 新增头像组件 [Avatar](https://ant.design/components/avatar/)。🌝
- LocaleProvider
  - 新增保加利亚语支持。[#6297](https://github.com/ant-design/ant-design/pull/6297) [@dimitrov-adrian](https://github.com/dimitrov-adrian)
  - 新增波兰语支持。[#6326](https://github.com/ant-design/ant-design/pull/6326) [@longersson](https://github.com/longersson)
  - 新增英式英语支持。[#6344](https://github.com/ant-design/ant-design/pull/6344) [@damiangreen](https://github.com/damiangreen)
  - 新增意大利语支持。[#6344](https://github.com/ant-design/ant-design/pull/6344) [@damiangreen](https://github.com/damiangreen)
  - 新增法语支持。[#6344](https://github.com/ant-design/ant-design/pull/6344) [@damiangreen](https://github.com/damiangreen)
  - 新增比利时语支持。[#6344](https://github.com/ant-design/ant-design/pull/6344) [@damiangreen](https://github.com/damiangreen)
- Collapse.Panel 现在可以被禁用，禁用时无法通过用户交互改变面板打开/关闭状态。[#6119](https://github.com/ant-design/ant-design/issues/6119) [demo](https://ant.design/components/collapse/#components-collapse-demo-basic)
- DatePicker 与 RangePicker 现在支持在弹层中渲染自定义 footer。[#6122](https://github.com/ant-design/ant-design/issues/6122) [#5188](https://github.com/ant-design/ant-design/issues/5188) [demo](https://ant.design/components/date-picker/#components-date-picker-demo-extra-footer)
- InputNumber 现在可以通过 `precision` 单独设置精度，即精度与 `step` 可以不再绑定。[#5998](https://github.com/ant-design/ant-design/issues/5998)
- TreeSelect 多选模式支持 `allowClear` 展示清除按钮。

- 优化 Pagination 对键盘操作的支持。[rc-pagination#83](https://github.com/react-component/pagination/pull/83) [@geramirez](https://github.com/geramirez)
- 优化 Progress 样式。[#6354](https://github.com/ant-design/ant-design/issues/6354)
- 优化 Slider 的可访问性支持。[#6301](https://github.com/ant-design/ant-design/pull/6301)

- 修复正在执行动画的元素可点击的问题。[#6314](https://github.com/ant-design/ant-design/issues/6314)
- 修复时间类组件的 `Cannot read property '0' of undefined` 报错问题。[#6334](https://github.com/ant-design/ant-design/issues/6334)
- DatePicker
  - 修复弹层错位的问题。[#6347](https://github.com/ant-design/ant-design/issues/6347)
  - 修复日期单元格 tooltip 的内容格式问题。[#5724](https://github.com/ant-design/ant-design/issues/5724) [@zefj](https://github.com/zefj)
  - 修复能通过键盘操作选择 disabled 日期的问题。[#6345](https://github.com/ant-design/ant-design/issues/6345)
- 修复 Form `validateFieldsAndScroll` 不支持 nested fields 的问题。[#5410](https://github.com/ant-design/ant-design/issues/5410)
- Input[addon]
  - 修复 style 属性失效的问题。[#6379](https://github.com/ant-design/ant-design/issues/6379)
  - 修复垂直对齐的问题。[#6403](https://github.com/ant-design/ant-design/issues/6403)
- 修复 Modal.confirm onOk 返回的 Promise rejected 后用户无法重试的问题。[#6183](https://github.com/ant-design/ant-design/issues/6183)
- 修复 Pagination 简单模式下输入框过小的问题。[#6339](https://github.com/ant-design/ant-design/issues/6339)
- 修复 Select 在搜索模式下用户输入的内容被截断的问题。[#6382](https://github.com/ant-design/ant-design/issues/6382)
- 修复 Spin 定时器没有被正确移除的问题。[#6383](https://github.com/ant-design/ant-design/issues/6383)
- 修复 Switch 对 onClick 的支持。[#6373](https://github.com/ant-design/ant-design/issues/6373)
- 修复 Table.Column TypeScript definition 导致 `error TS2304: Cannot find name 'T'` 的问题。[#6313](https://github.com/ant-design/ant-design/issues/6313)
- 修复 Timeline.Item 和 Dropdown.Button 在 TypeScript 报 `does not have any construct or call signatures` 错中的问题。[#6356](https://github.com/ant-design/ant-design/issues/6356)
- 修复 Tree、TreeSelect disabled 样式问题。[#6320](https://github.com/ant-design/ant-design/issues/6320)

## 2.10.4

`2017-06-01`

- 修正 `rc-util`  依赖。[#6310](https://github.com/ant-design/ant-design/pull/6311) [@bkniffler](https://github.com/bkniffler)
- 修正 `es` 版本的语法错误。[#6310](https://github.com/ant-design/ant-design/issues/6310#issuecomment-305176273)

## 2.10.3

`2017-05-31`

- **Calendar**
  - 修复了样式问题以支持 disabledDate，补充了 Type 定义及文档。[#6074](https://github.com/ant-design/ant-design/issues/6074)
  - rc-calendar 依赖升级至 8.4.0，支持保加利亚语，支持首先选择结束日期。[commit/a4a6db](https://github.com/ant-design/ant-design/commit/a4a6db76de57ac2559a2be80208121ab5e168fbf)
- **Alert** 去掉了默认的下边距。[commit/5ef482](https://github.com/ant-design/ant-design/commit/5ef48289747409b6d962f75627ddb11e2765f965)
- **Tabs** 修复了隐藏标签下内容的表现问题。[#6237](https://github.com/ant-design/ant-design/issues/6237)
- **Layout** 修复了折叠侧边栏中的内容不能自动隐藏的问题。[#6131](https://github.com/ant-design/ant-design/issues/6131)
- **Table** 修复了 filter 被 Table 截断的问题。[#6245](https://github.com/ant-design/ant-design/issues/6245)
- **InputNumber** 修复了配置 hasFeedback 时校验结果图标位置有误的问题。[#6289](https://github.com/ant-design/ant-design/issues/6289)
- **Typescript**
  - typescript 升级至 2.3.x。[#6263](https://github.com/ant-design/ant-design/issues/6263)
  - 补充了 Table 的 type 定义. [commit/acdc56](https://github.com/ant-design/ant-design/commit/acdc563a547c49960521b2b48cd5c707ac1e4cf2) [pull/6291](https://github.com/ant-design/ant-design/pull/6291) [@jch254](https://github.com/jch254)
  - 修复了 Mention、Form 组件中错误的 type 定义. [pull/6268](https://github.com/ant-design/ant-design/pull/6268) [@jch254](https://github.com/jch254)
  - 修复了 Badge 组件中错误的 type 定义. [pull/6291](https://github.com/ant-design/ant-design/pull/6291) [@jch254](https://github.com/jch254)
  - 补充了 Input 相关组件的 type 定义。[pull/6276](https://github.com/ant-design/ant-design/pull/6276/commits/94901de2e8c0a2ed6f62f5aa50c98994aad71844) [@panjiesw](https://github.com/panjiesw)  [commit/220264](https://github.com/ant-design/ant-design/commit/2202648d6e1c53409ade2141955232922b0040d6#diff-26cb6da96d10397e18e7dbd6c5d8f7a1L265) [@clinyong](https://github.com/clinyong)

## 2.10.2

`2017-05-23`

- 修复了 React 升级引起的 `prop-types` 相关的 warning 问题。[#5678](https://github.com/ant-design/ant-design/issues/5678)
- 修复 DatePicker 和 RangePicker showTime 模式下 defaultValue 的问题。[#6160](https://github.com/ant-design/ant-design/pull/6160)
- 修复 TreeSelect 的样式问题。[#6137](https://github.com/ant-design/ant-design/issues/6137)
- 修复 包含 prefix 和 addon 的 Input 的样式问题。[#6144](https://github.com/ant-design/ant-design/issues/6144)
- 修复 `notification.destroy` 的 Bug。[#6161](https://github.com/ant-design/ant-design/issues/6161)
- 修复了 Upload 和 Table 组件中缺失的翻译。
- 修复了在 Input.Group 中的 Cascader 的样式问题。[#6208](https://github.com/ant-design/ant-design/issues/6208)
- 增大了 Tree 图标的可点击区域面积。

## 2.10.1

`2017-05-14`

- 升级 normalize.css 到 7.0.0。
- 修复 AutoComplete 在 Input.Group 里的样式问题。[#6058](https://github.com/ant-design/ant-design/issues/6058)
- 修复 Tabs 在 `card` 和 `editable-card` 模式下不能设置动画的问题。[#6070](https://github.com/ant-design/ant-design/issues/6070)
- 修复 Form 在屏幕缩放时的样式问题。[#6097](https://github.com/ant-design/ant-design/issues/6097)
- 修复 RangePicker 在 Safari 和 360 浏览器下的 placeholder 显示错位的问题。[#6061](https://github.com/ant-design/ant-design/issues/6061)
- Notification
  - 修复设置 `getContainer` 无效的问题。[#6099](https://github.com/ant-design/ant-design/pull/6099) [@hardfist](https://github.com/hardfist)
  - 修复会出现重叠的问题。[#5895](https://github.com/ant-design/ant-design/issues/5895) [@ystarlongzi](https://github.com/ystarlongzi)
- 新增 `fork` 图标。
- 新增 less 变量 [#6039](https://github.com/ant-design/ant-design/pull/6039) [#6038](https://github.com/ant-design/ant-design/pull/6038) [#6105](https://github.com/ant-design/ant-design/issues/6105) [#6040](https://github.com/ant-design/ant-design/pull/6040)

## 2.10.0

`2017-05-02`

- LocaleProvider
  - 新增繁体中文。[#5665](https://github.com/ant-design/ant-design/pull/5665) [@GeorgioWan](https://github.com/GeorgioWan)
  - 新增芬兰语。[#5699](https://github.com/ant-design/ant-design/pull/5699) [@kirbo](https://github.com/kirbo)
  - 新增越南语。[#5927](https://github.com/ant-design/ant-design/pull/5927) [@pnghai](https://github.com/pnghai)
  - 更新西班牙语。[#5932](https://github.com/ant-design/ant-design/pull/5932) [@ginodeise](https://github.com/ginodeis)
- AutoComplete 新增 `onSearch` 以监听搜索事件。
- Checkbox.Group 可以内嵌 Checkbox，以支持更灵活的布局。[demo](http://ant.design/components/checkbox-cn/#components-checkbox-demo-layout)
- Notification 现在可以自定义弹出框的样式和 className。[#5893](https://github.com/ant-design/ant-design/issues/5893) [@lixiaoyang1992](https://github.com/lixiaoyang1992)
- TimePicker 的展开状态可以通过受控属性 `open` 控制。[#5913](https://github.com/ant-design/ant-design/pull/5913)
- Upload `onRemove` 方法可以返回一个 Promise 用于异步控制移除逻辑。[#5973](https://github.com/ant-design/ant-design/issues/5973) [@shlice](https://github.com/shlice)
- 调整 Dropdown 弹出层的边距。[#5088](https://github.com/ant-design/ant-design/issues/5088)
- AutoComplete
  - 修复 dataSource 为 `Object[]` 时行为与 `String[]` 不一致的问题。[#5860](https://github.com/ant-design/ant-design/issues/5860)
  - 修复在 Form 内使用时，错误样式显示错误的问题。[#5834](https://github.com/ant-design/ant-design/issues/5834) [@kossel](https://github.com/kossel)
- 修复 Button 内嵌 Icon 后，两个汉字之间会插入空格的问题。[#5977](https://github.com/ant-design/ant-design/issues/5977)
- 修复 Card[title] 内使用 Cascader 导致样式错乱的问题。[#5952](https://github.com/ant-design/ant-design/issues/5952)
- 修复 Checkbox Radio 禁用后的 cursor 样式问题。[#5935](https://github.com/ant-design/ant-design/issues/5935)
- 修复 DatePicker 内嵌的 TimePicker 使用 `use12Hours` 后样式错误的问题。[#5959](https://github.com/ant-design/ant-design/issues/5959)
- 修复 Input.Group 内嵌 AutoComplete Cascader Mention TimePicker 时的样式问题。[#5832](https://github.com/ant-design/ant-design/issues/5832)
- 修复 Menu 的 TypeScript 定义缺少 `inlineIndent` 的问题。[#5903](https://github.com/ant-design/ant-design/pull/5903) [@brookshi](https://github.com/brooksh)
- Mention
  - 修复不支持 readOnly 和 disabled 的问题。[#5175](https://github.com/ant-design/ant-design/issues/5175)
  - 修复受控模式。[#5788](https://github.com/ant-design/ant-design/issues/5788)
- 修复 RangePicker 与 Form 一起使用时会报错的问题。[#5872](https://github.com/ant-design/ant-design/issues/5872)
- 修复 loading 状态 Table 的分页能点击的问题。[#5937](https://github.com/ant-design/ant-design/issues/5937)
- Tabs
  - 修复内嵌 Table 或者表单控件时布局错乱的问题。[#5953](https://github.com/ant-design/ant-design/issues/5953)
  - 修复 `2.9.2` 引入的垂直布局样式错乱的问题。[#5877](https://github.com/ant-design/ant-design/issues/5877)
- Transfer
  - 修复搜索结果无法正常显示的问题。[#5631](https://github.com/ant-design/ant-design/issues/5631)
  - 修复搜索模式下全选和反选的逻辑。[#5993](https://github.com/ant-design/ant-design/issues/5993)

## 2.9.3

`2017-04-24`

- **notification** 修复了不能在默认的 4.5s 后关闭的问题。[#5869](https://github.com/ant-design/ant-design/issues/5869)
- **Tabs** 增加了 `ink-bar` 宽度渐变动效。[#5858](https://github.com/ant-design/ant-design/pull/5858) [@hlehmann](https://github.com/hlehmann)

## 2.9.2

`2017-04-22`

- **Alert** 修复 banner 型属性无法覆盖的问题。[#5800](https://github.com/ant-design/ant-design/issues/5800)
- **AutoComplete** 修复自定义输入组件无法监听 `onKeyDown` 事件的问题。[#5487](https://github.com/ant-design/ant-design/issues/5487)
- **Button** 危险按钮使用新的样式。[#5815](https://github.com/ant-design/ant-design/pull/5815)
- **DatePicker**
  - 优化了 RangePicker 的体验，rc-calendar 升级至 `~8.0.0`。[#4985](https://github.com/ant-design/ant-design/issues/4985)
  - 修复了 RangePicker 自定义高度后文字不能上下居中的问题。[pull/5718](https://github.com/ant-design/ant-design/pull/5718) [@leadream](https://github.com/leadream)
- **Form** 增加样式变量来控制表单项标题冒号的展示。[pull/5855](https://github.com/ant-design/ant-design/pull/5855) [@megawac](https://github.com/megawac)
- **Input**
  - 修复了 Input.Search 在 Input.Group 下的样式问题。[#5743](https://github.com/ant-design/ant-design/issues/5743)
  - 修复了 AutoComplete 在 Input.Group 下的样式问题。[#5832](https://github.com/ant-design/ant-design/issues/5832)
  - 修复了 Select 在 Input.Group 下的 size 问题。[#5754](https://github.com/ant-design/ant-design/issues/5754)
  - 调整了 suffix 的颜色。[pull/5820](https://github.com/ant-design/ant-design/pull/5820) [@megawac](https://github.com/megawac)
- **InputNumber** 更新了 `parser` 和 `formatter` 配合使用的文档及示例。[#5683](https://github.com/ant-design/ant-design/issues/5683)
- **Layout**
  - 增加了[固定侧边栏](https://ant.design/components/layout/#components-layout-demo-fixed-sider)示例。
  - 修复 firefox 下响应式侧边栏的样式问题。[#5613](https://github.com/ant-design/ant-design/issues/5613)
- **LocaleProvider** 自动引入样式变量以便自定义。[#5712](https://github.com/ant-design/ant-design/issues/5712) [@lionkeng](https://github.com/lionkeng)
- **Menu** 去掉 Menu 组件中 a 标签默认的 focus 下划线样式。[#5707](https://github.com/ant-design/ant-design/issues/5707)
- **Notification** 样式自适应单行文案。[#5846](https://github.com/ant-design/ant-design/issues/5846)
- **Radio** 新增 Radio.Button 颜色及背景色样式变量。[pull/5791](https://github.com/ant-design/ant-design/pull/5791) [@megawac](https://github.com/megawac)
- **Table**
  - 增加了头部背景及行 hover 背景样式变量。[#5706](https://github.com/ant-design/ant-design/issues/5706) [@kappa-gooner](https://github.com/kappa-gooner)
  - 修复了表头分组示例的展示问题。[#5697](https://github.com/ant-design/ant-design/issues/5697)
- **Tabs** 修复了垂直模式下滚动按钮的位置问题。[#5765](https://github.com/ant-design/ant-design/issues/5765) [@dicklwm](https://github.com/dicklwm)
- **TreeSelect** 修复了下拉箭头方向不能改变的问题。[#5693](https://github.com/ant-design/ant-design/issues/5693)
- **TypeScript**
  - 补充了 InputNumber 的部分定义。[#5717](https://github.com/ant-design/ant-design/issues/5717)  [@whtang906](https://github.com/whtang906)
- **全局性优化**
  - 修复了组件中因升级 React@15.5.0 带来的 `React.PropTypes` 警告。[pull/5723](https://github.com/ant-design/ant-design/pull/5723)  [@manjitkumar](https://github.com/manjitkumar)
- **网站**
  - 『指引』中增加了英文版的[图标说明](https://ant.design/docs/spec/icon)。[@kenaniah](https://github.com/kenaniah)
  - 增加了[英文版在线讨论](https://gitter.im/ant-design/ant-design-english)。

## 2.9.1

`2017-04-09`

- Step
  - 增加 less 变量。[#5624](https://github.com/ant-design/ant-design/pull/5624) [@megawac](https://github.com/megawac)
  - 修复样式问题。[#5623](https://github.com/ant-design/ant-design/issues/5623)
- Button 点击后不会再失去焦点。[#5597](https://github.com/ant-design/ant-design/pull/5597) [@kenaniah](https://github.com/kenaniah)
- 链接获取焦点的时候增加下划线。[#5587](https://github.com/ant-design/ant-design/pull/5597) [@kenaniah](https://github.com/kenaniah)
- 修复 Dropdown.Button 不能使用 `placement` 的问题。[#5594](https://github.com/ant-design/ant-design/issues/5594)
- 修复 Pagination 不对齐的问题。[#5632](https://github.com/ant-design/ant-design/issues/5632)
- 修复 AutoComplete 使用 `allowClear` 时的样式问题。[#5634](https://github.com/ant-design/ant-design/issues/5634)
- 修复 DatePicker 设置 `showToday` 为 `false` 时的样式问题。[#5620](https://github.com/ant-design/ant-design/issues/5620)
- 修复 Select 搜索无结果时默认显示英文的问题。[#5661](https://github.com/ant-design/ant-design/pull/5661) [@LeeHarlan](https://github.com/LeeHarlan)

## 2.9.0

`2017-04-01` 👻

- 默认字体中数字设为等宽，方便进行纵向比较。[b526083](https://github.com/ant-design/ant-design/commit/b526083fa6a619113a3d26c4f4f092a8648f3bd4)
- Select
  - 新增 `mode` 参数，废弃 `tags|combobox|multiple` 属性，使用 `mode={tags|combobox|multiple}` 来代替。
  - `tags|multiple` 模式现在支持配置 `allowClear` 清除按钮。[#4843](https://github.com/ant-design/ant-design/issues/4843)
- Progress 新增 `dashboard` 仪表盘类型。[#5225](https://github.com/ant-design/ant-design/issues/5225) [@qiaolb](https://github.com/qiaolb)
- Tree 新增 `showLine` 属性，支持纵向连接线展示。[#3854](https://github.com/ant-design/ant-design/issues/3854)
- TimePicker 支持 12 小时制：`use12Hours`。[#4063](https://github.com/ant-design/ant-design/issues/4063)
- Table 支持 `column.filterIcon`，支持使用自定义筛选菜单时自定义图标。[#5293](https://github.com/ant-design/ant-design/pull/5293)
- Spin 新增 `wrapperClassName`，方便给包裹形态的加载条增加类名。[#5425](https://github.com/ant-design/ant-design/pull/5425) [@aaronplanell](https://github.com/aaronplanell)
- Tabs 新增点击左右切换箭头的回调 `onPrevClick` `onNextClick`。[#4395](https://github.com/ant-design/ant-design/issues/4395)
- InputNumber 新增 `parser` 属性，用于有时指定了 `formatter` 时需要解析出数字。[#5178](https://github.com/ant-design/ant-design/pull/5178#issuecomment-284557933)
- 国际化
  - 新增日语。[#5529](https://github.com/ant-design/ant-design/pull/5529)  [@novi](https://github.com/novi)
  - 新增斯洛伐克语。[#5304](https://github.com/ant-design/ant-design/pull/5304) [@Kamahl19](https://github.com/Kamahl19)
  - 新增爱沙尼亚语。[#5266](https://github.com/ant-design/ant-design/pull/5266) [@madisvain](https://github.com/madisvain)
  - 新增土耳其语。[#5536](https://github.com/ant-design/ant-design/pull/5536) [@c0b41](https://github.com/c0b41)
- TypeScript
  - 参照 react-slick 补充 Carousel 的定义。
  - 修复 Form 的部分定义。
  - 修正 `getPopupContainer` 定义。
- 允许分开禁用 Tabs 的高亮条和面板的切换动画。[#5089](https://github.com/ant-design/ant-design/issues/5089) [@xieguanglei](https://github.com/xieguanglei)
- Button 的 `loading` 属性支持 `{ delay: 1000 }` 的形式，默认不再延迟切换状态 。[#5365](https://github.com/ant-design/ant-design/issues/5365)
- 增加 Card 头部的 less 变量。[#5354](https://github.com/ant-design/ant-design/pull/5354) [@kossel](https://github.com/kossel)
- 修复 Breadcrumb 没有设置 `breadcrumbName` 时分隔符多余的问题。
- 修复 Dropdown.Button 的 `Unknown prop placement` 警告信息。[#5594](https://github.com/ant-design/ant-design/issues/5594)
- 修复 RangePicker 和 InputNumber 的占位文字颜色。
- 修复 Cascasder 搜索模式下无法使用退格键的问题。[#5340](https://github.com/ant-design/ant-design/issues/5340)
- 修复 LocaleProvider 有时对 `Modal.confirm` 失效的问题。[#5493](https://github.com/ant-design/ant-design/issues/5493) [@hargasinski](https://github.com/hargasinski)
- 修复 BackTop 设置了 `target` 时滚动动效消失的问题。[#5564](https://github.com/ant-design/ant-design/issues/5564)
- 优化 Pagination 的样式实现。[#5557](https://github.com/ant-design/ant-design/issues/5557)

## 2.8.3

`2017-03-27`

- TypeScript
  - 修复 `AutoComplete[filterOption]` 定义缺失的问题。[#5393](https://github.com/ant-design/ant-design/pull/5393) [@mitchelldemler](https://github.com/mitchelldemler)
  - 修复 `getPopupContainer` `getCalendarContainer` `getTooltipContainer` `getSuggestionContainer` 等的定义问题。[322e9ef](https://github.com/ant-design/ant-design/commit/322e9efdc9db28bd92230fc690f1fdf5a72cf7cd)
  - 优化 `Form.create` 的定义。[#5420](https://github.com/ant-design/ant-design/pull/5420) [@infeng](https://github.com/infeng)
- 修复 Badge 在 Maxthon 内的兼容性问题。[#5477](https://github.com/ant-design/ant-design/issues/5477)
- 修复 Button 内无法使用 `null` `undefined` 的问题。[#5472](https://github.com/ant-design/ant-design/issues/5472) [@blade254353074](https://github.com/blade254353074)
- Breadcrumb 不再强依赖于 `route.breadcrumbName` [ac1c7f3](https://github.com/ant-design/ant-design/commit/ac1c7f312bc46ba6ef7aacace43e4ac99b87dd54)
- 修复 `Form.Item[hasFeedback]` 与 `Input[prefix]` 混用时的样式问题。[#5456](https://github.com/ant-design/ant-design/issues/5456) [@william-yz](https://github.com/william-yz)
- 修复 Layout.Content 与 Carousel 一起使用时的样式问题。[#5415](https://github.com/ant-design/ant-design/issues/5415)
- LocaleProvider
  - 修复对德语支持不完善的问题。[#5387](https://github.com/ant-design/ant-design/pull/5387) [@Knacktus](https://github.com/Knacktus)
  - 修复对俄语支持不完善的问题。[#5406](https://github.com/ant-design/ant-design/pull/5406) [@plandem](https://github.com/plandem)
  - 修复不支持 Upload 的问题。[#5388](https://github.com/ant-design/ant-design/pull/5388) [@natergj](https://github.com/natergj)
- 修复 Menu 内 Icon 动画效果与文字不一致的问题。[#5495](https://github.com/ant-design/ant-design/issues/5495)
- 修复 `Modal[footer]` 无法置空的问题。[#5462](https://github.com/ant-design/ant-design/issues/5462)
- 修复 `2.8.2` 引入的 Pagination 在 `IE<=10` 下样式丢失的问题。[#5484](https://github.com/ant-design/ant-design/issues/5484)
- 修复 Popover 内使用 Table 时会意外关闭的问题。[#5407](https://github.com/ant-design/ant-design/issues/5407)
- 去掉 Radio 只能作为 Radio.Group 的直接后代的限制。[#5443](https://github.com/ant-design/ant-design/issues/5443)
- 修复 Switch 在 Form.Item 内使用时的 warning。[#5368](https://github.com/ant-design/ant-design/issues/5368)
- Table 的选择全部菜单现在默认隐藏，`selections` 设置为 true 时展现。[#5246](https://github.com/ant-design/ant-design/issues/5246) [@infeng](https://github.com/infeng)
- 新增 `@info-color` 主题变量。[#5442](https://github.com/ant-design/ant-design/issues/5442)
- 现在可以通过 `NODE_ENV=test` 来禁用测试时 antd 全量加载的 warning。[#5345](https://github.com/ant-design/ant-design/issues/5345)
- 升级 moment 到 `2.18.0`。

## 2.8.2

`2017-03-19`

- 发布了新的 [设计基础文档](https://ant.design/docs/spec/colors-cn)。
- 修复使用 Modal.confirm 时报错的问题。[#5269](https://github.com/ant-design/ant-design/issues/5269)
- 修复 Upload 的蒙层样式。[#5275](https://github.com/ant-design/ant-design/issues/5275)
- 修复 Upload 上传进度条不显示的问题。[#5323](https://github.com/ant-design/ant-design/issues/5323)
- 修复 Table 的分页的 showTotal 数据错误的问题。[#5259](https://github.com/ant-design/ant-design/issues/5259)
- 修复了 Popconfirm 与 Button 同时使用时的样式问题。[#5301](https://github.com/ant-design/ant-design/issues/5301)
- 修复 Radio 的一个样式问题。[#5336](https://github.com/ant-design/ant-design/pull/5336)
- 修复 Message 的 getContainer 无法使用的问题。[#5380](https://github.com/ant-design/ant-design/issues/5380)
- 修复 Checkbox 和 Radio 标签的文字对齐。 [696a3c0](https://github.com/ant-design/ant-design/commit/696a3c0e34156d78e87d629a3f0f8703af1f03ec)
- 调整了 Spin 的动画。[fa1e031](https://github.com/ant-design/ant-design/commit/fa1e031a7396c61fa9709a0c46fe63200c35d232)
- 调整了 Mention 的一些样式。[240a93c](https://github.com/ant-design/ant-design/commit/240a93cee25bc8c6ad4520cd907a14a7b22ed773)

## 2.8.1

`2017-03-11`

- **DatePicker** 优化了带时间的 DatePicker 的选择行为，并修复父组件 state 变化导致无法选中的问题。[#5189](https://github.com/ant-design/ant-design/issues/5189) [@megawac](https://github.com/megawac)
- **Form**
  - 补充了校验规则相关文档。[#5201](https://github.com/ant-design/ant-design/issues/5201)
  - 修复了一些样式问题。[#5196](https://github.com/ant-design/ant-design/issues/5196) [#5236](https://github.com/ant-design/ant-design/issues/5236) [#5222](https://github.com/ant-design/ant-design/issues/5222)
- **Icon** 增加 `shake` 和 `android-o` 图标。[commit/941782](https://github.com/ant-design/ant-design/commit/941782f7ec000a9054c3bc945ab887f93ab46749)
- **Input** 修复有 `addonBefore` 时 `hasFeedback` 失效的问题。[#5228](https://github.com/ant-design/ant-design/issues/5228)
- **InputNumber** 补充缺失的 type 定义。[#5240](https://github.com/ant-design/ant-design/issues/5240) [@hlehmann](https://github.com/hlehmann)
- **Modal** 支持点击 esc 调用 `onCancle`。[#5203](https://github.com/ant-design/ant-design/issues/5203) [@elios264](https://github.com/elios264)
- **Table**
  - 补充缺失的 type 定义。[#5206](https://github.com/ant-design/ant-design/issues/5206) [@kvey](https://github.com/kvey)
  - 修复小号表格无数据时右边线缺失的问题。[#5237](https://github.com/ant-design/ant-design/issues/5237)
  - 修复表头分组时排序失效的问题。[#5158](https://github.com/ant-design/ant-design/issues/5158)
- **Tooltip** 修复 Trigger 为绝对定位且禁用的按钮时失效的问题。[#5254](https://github.com/ant-design/ant-design/issues/5254)
- **Upload**
  - 修复上传文件名字过长时的样式问题。[commit/0a3519](https://github.com/ant-design/ant-design/commit/0a35197a35513ca45308bb7163c8243b75dd6f8d)
  - 修复并优化了动画。[pull/5210](https://github.com/ant-design/ant-design/pull/5210)
  - 支持覆盖 `onProgress`。[pull/5260](https://github.com/ant-design/ant-design/pull/5260) [@minwe](https://github.com/minwe)
- **全局性优化**
  - 修复 `lodash.debounce` 依赖缺失问题。[#5230](https://github.com/ant-design/ant-design/issues/5230)
- **网站**
  - 修复 safari 语言检测失效的问题。[pull/5245](https://github.com/ant-design/ant-design/pull/5245)
  - 色板支持点击复制色号。[pull/5247](https://github.com/ant-design/ant-design/pull/5247) [@bsheikh](https://github.com/bsheikh)
  - 增加脚手架示例。[commit/f2f786](https://github.com/ant-design/ant-design/commit/f2f786d66d75eebef8406a72db8a15e1640cea1f)

## 2.8.0

`2017-03-06`

- Tabs
  - 新增 `tabBarStyle` 用于自定义 tabBar 的样式。[#4966](https://github.com/ant-design/ant-design/issues/4966)
  - 新增 `TabPane[closable]` 用于设置是否显示删除按钮。[#4807](https://github.com/ant-design/ant-design/pull/4807) [@lixiaoyang1992](https://github.com/lixiaoyang1992)
- Anchor
  - 新增 `showInkInFixed` 用于设置在 fixed 状态下是否圆形图标。[#4960](https://github.com/ant-design/ant-design/pull/4960)
  - 修复 `children` 不是 AnchorLink 时会报错的问题。[#5129](https://github.com/ant-design/ant-design/issues/5129)
- Table
  - 新增反选功能并允许自定义全选选项。[#4962](https://github.com/ant-design/ant-design/pull/4962)
  - `spin` 属性支持所有 Spin 的属性。[#4824](https://github.com/ant-design/ant-design/pull/4824) [@lixiaoyang1992](https://github.com/lixiaoyang1992)
  - 修正 `size` 是 `small` 的时候表头没有底边框的问题。[#5182](https://github.com/ant-design/ant-design/issues/5182)
- Mention 新增自定义触发字符的支持。[demo](https://ant.design/components/mention-cn/#components-mention-demo-multiple-trigger)
  - ![Mention animation](https://zos.alipayobjects.com/rmsportal/QDYwAbwKrqOUOykRaNai.gif)
- Rate
  - 支持自定义字符。[demo](https://ant.design/components/rate-cn/#components-rate-demo-character)
  - 新增 `className` 属性。
- Layout
  - 新增 `顶部-侧边布局-通栏` 的例子。[demo](http://ant.design/components/layout-cn/#components-layout-demo-top-side-2)
  - 新增 `固定头部` 的例子。[demo](https://ant.design/components/layout-cn/#components-layout-demo-fixed)
  - Sider 新增 `breakpoint` 用于设置响应式展示。[#4931](https://github.com/ant-design/ant-design/pull/4931)
- Form
  - 新增 `layout` 属性用于取代原有的 `horizontal`、`vertical`、`inline`。[#5056](https://github.com/ant-design/ant-design/issues/5056)
- Calendar
  - 新增 `dateFullCellRender` 和 `monthFullCellRender` 用于覆盖单元格的内容。[#5138](https://github.com/ant-design/ant-design/pull/5138) [@wonyun](https://github.com/wonyun)
  - 新增 `onSelect` 用于日期选择功能。[demo](https://ant.design/components/calendar-cn/#components-calendar-demo-select)
- AutoComplete
  - 修复在 Form.Item 里不对齐的问题。[#5139](https://github.com/ant-design/ant-design/issues/5139)
  - 新增 `查询模式 - 确定类目` 的例子。[demo](https://ant.design/components/auto-complete-cn/#components-auto-complete-demo-uncertain-category)
- Col 新增 `xl` 属性，支持 1600px 的响应布局断点。[#4796](https://github.com/ant-design/ant-design/pull/4796) [@hjin-me](https://github.com/hjin-me)
- Upload 新增 `locale` 支持国际化文案定义。[#4697](https://github.com/ant-design/ant-design/issues/4697)
- Transfer 新增 `onScroll` 支持动态加载数据。[#4188](https://github.com/ant-design/ant-design/issues/4188)
- message 和 notification 新增 `getContainer` 参数支持自定义消息渲染的容器。[#5019](https://github.com/ant-design/ant-design/issues/5019)
- Badge 新增 `showZero` 支持设置是否显示 `0`。[#4251](https://github.com/ant-design/ant-design/issues/4251)
- InputNumber
  - 新增 `formatter` 用于格式化展示的值。
  - 新增组合键的支持。[详细](https://github.com/react-component/input-number#keyboard-navigation)
- 新增大量图标。[#5107](https://github.com/ant-design/ant-design/pull/5107)
- 新增语言支持：
  - 荷兰语 [#4785](https://github.com/ant-design/ant-design/pull/4785) [@corneyl](https://github.com/corneyl)
  - 加泰罗尼亚语 [#4929](https://github.com/ant-design/ant-design/pull/4929) [@aaronplanell](https://github.com/aaronplanell)
  - 捷克语 [#5169](https://github.com/ant-design/ant-design/pull/5169) [@martinnov92](https://github.com/ant-design/ant-design/pull/5169)
  - 韩语/朝鲜语 [#5141](https://github.com/ant-design/ant-design/pull/5141) [@minsungryu](https://github.com/ant-design/ant-design/pull/5141)
- 优化 Spin 显示位置。[#4722](https://github.com/ant-design/ant-design/issues/4722)
- 优化 Checkbox 以兼容 `browser-sync`。[#2744](https://github.com/ant-design/ant-design/issues/2744)
- 修复 Steps 在窗口变化时的宽度问题。[#5083](https://github.com/ant-design/ant-design/issues/5083)
- 修复 Upload.Dragger unmount 时会报错的问题。[#5162](https://github.com/ant-design/ant-design/issues/5162)
- 修复 Button 里的文字在 IE 下点击时会移动的问题。
- 修复 Input 的前缀跟后缀的垂直居中对齐问题。

## 2.7.4

`2017-02-28`

- 修复 TreeSelect 多选框无法展现的问题。[#5092](https://github.com/ant-design/ant-design/issues/5092)
- 修复 Anchor 的 `e.stopPreventDefault is not a function` 的报错。[#5080](https://github.com/ant-design/ant-design/issues/5080)
- 修复 Input、Cascader、Upload 的一些样式细节。

## 2.7.3

`2017-02-25`

- 演示代码统一为 ES6 class 的写法。[#4878](https://github.com/ant-design/ant-design/issues/4878)
- TypeScript
  - 修复 `Cannot find module '../../package.json'` 的问题。[#4935](https://github.com/ant-design/ant-design/issues/4935)
  - 补充了 Table、RangePicker 和 Upload 的部分属性定义。
- 修复了 Modal `onOk` `afterClose` 和 Popconfirm `onConfirm` `onCancel` 缺少点击 event 参数的问题。 [#4787](https://github.com/ant-design/ant-design/issues/4787)
- 优化 Menu inline 模式和 Collapse 的折叠动画效果。
- 优化了 Checkbox 和 Radio 的垂直对齐样式。
- Table
  - 修复固定列时列头样式错位的问题。[#4936](https://github.com/ant-design/ant-design/issues/4936)
  - 修复未清除浮动导致排版错位的问题。[#4945](https://github.com/ant-design/ant-design/issues/4945)
  - 修复筛选子菜单无法显示的问题。[#4975](https://github.com/ant-design/ant-design/issues/4975)
  - 修复固定列上的自定义筛选菜单无法交互的问题。[#5010](https://github.com/ant-design/ant-design/issues/5010)
  - 修正 `pagination.onChange` 和 Pagination 的 `onChange` 参数不一致的问题。
  - 修复加载状态切换不柔和的问题。[#4934](https://github.com/ant-design/ant-design/issues/4934)
- 优化多个 message 展示重叠的问题。[#3543](https://github.com/ant-design/ant-design/issues/3543)
- 修复 Carousel 在改变浏览器窗口大小后 autoplay 会失效的问题。[#2550](https://github.com/ant-design/ant-design/issues/2550)
- 修复了 InputNumber 在受控模式（Form 表单内）无法输入 `1.01` `1.001` 等数字的问题。[#5012](https://github.com/ant-design/ant-design/issues/5012)
- 优化 Button 加载状态切换时的宽度抖动问题。[#4913](https://github.com/ant-design/ant-design/issues/4913)
- 修复 Dropdown 的菜单选中样式和 `Menu[theme="dark"]` 样式无效的问题。[#5013](https://github.com/ant-design/ant-design/issues/5013) [#4903](https://github.com/ant-design/ant-design/issues/4903)
- 修复 Menu 的弹出菜单的 `z-index` 问题。[#4937](https://github.com/ant-design/ant-design/issues/4937)
- 修复 DatePicker 和 RangePicker 无法设置小于 300px 的宽度的问题。[#4920](https://github.com/ant-design/ant-design/issues/4920)
- 修复 Spin 内嵌 Spin 的样式问题。[#4971](https://github.com/ant-design/ant-design/issues/4971)
- 修复了使用 babel-plugin-import 引入 Popconfirm 时，未引入 Button 样式的问题。
- 修复了样式变量在 Progress `type="circle"` 上未生效的问题。[#5002](https://github.com/ant-design/ant-design/issues/5002)
- 修复了 Breadcrumb 的 chilren 为 `null` 或 `undefined` 时报错的问题。[#5015](https://github.com/ant-design/ant-design/issues/5015)
- 修复 Slider 的 tooltip 闪烁的问题。[#5003](https://github.com/ant-design/ant-design/issues/5003)
- 修复了 Transfer 中 disabled 选项仍然可以被移动的问题。[#4981](https://github.com/ant-design/ant-design/pull/4981) [@tianlizhao](https://github.com/tianlizhao)
- 文档
  - 修复和优化了移动端的展现。
  - 优化了 1.x 升级到 2.x 的不兼容改动文档。

## 2.7.2

`2017-02-17`

- 修复 `antd.version` 无法正常使用的问题。 [#4844](https://github.com/ant-design/ant-design/issues/4844)
- 修复 dist 文件没有 locales 的问题。 [#4910](https://github.com/ant-design/ant-design/pull/4910)
- 修复 Cascader 搜索模式下可以选择已禁用选项的问题。 [#4699](https://github.com/ant-design/ant-design/issues/4699)
- **Button**
  - 修复 `Button[type=danger]` 的点击动画。
  - 修复设置 `loading` 时的样式问题。 [#4875](https://github.com/ant-design/ant-design/issues/4875)
- **Menu**
  - 修复 `vertical` 模式下 `openKeys` 为受控属性。 [#4876](https://github.com/ant-design/ant-design/issues/4876)
  - 修复 Menu.Item 选中时的动画问题。
  - 修复 Menu.SubMenu 的样式问题。 [#4906](https://github.com/ant-design/ant-design/issues/4906)
- **Table**
  - 修复在混合使用固定表头和小尺寸时的样式问题。 [#4850](https://github.com/ant-design/ant-design/issues/4850)
  - 修复无数据时的占位符样式问题。 [#4851](https://github.com/ant-design/ant-design/pull/4851)
  - 精简了 DOM 结构。 [#4868](https://github.com/ant-design/ant-design/issues/4868)
- 修复 Radio 组件 children 无法为数字 `0` 的问题。 [#4874](https://github.com/ant-design/ant-design/issues/4874) [@HQidea](https://github.com/HQidea)
- 修复 RangePicker `style.width` 无法小于 300 的问题。 [#4920](https://github.com/ant-design/ant-design/issues/4920)
- 修复 Spin 样式在打包时会导致编译错误的问题。 [#4915](https://github.com/ant-design/ant-design/issues/4915)
- 修复 Chrome 下 Tooltip 无法在 disabled 的按钮上使用的问题。 [#4865](https://github.com/ant-design/ant-design/pull/4865)
- 修复 Tree 节点在拖动时会导致整棵树抖动的问题。 [#4858](https://github.com/ant-design/ant-design/issues/4858)
- 修复 Upload 上传失败的样式问题。 [#4810](https://github.com/ant-design/ant-design/issues/4810)
- 修复 `Menu[vertical]` 和 Layout.Sider 配合使用时二级菜单无法弹出的问题。 [#4890](https://github.com/ant-design/ant-design/issues/4890)
- 优化 Button、`Badge[status=processing]` 的动画。

![Badge animation](https://camo.githubusercontent.com/6874b2333f2fac3fac346404c6e70684e4dafc1a/68747470733a2f2f7a6f732e616c697061796f626a656374732e636f6d2f726d73706f7274616c2f73516b72756c716346734b4e54785158615971512e676966)
![Button animation](https://camo.githubusercontent.com/3963d12b45de4f522c2799361dbc3177e7bd93d1/68747470733a2f2f7a6f732e616c697061796f626a656374732e636f6d2f726d73706f7274616c2f46624b776d636f766d795364666c557468494e522e676966)

## 2.7.1

`2017-02-10`

- **Affix**
  - 修复 hover 时元素被隐藏的问题。[#4800](https://github.com/ant-design/ant-design/issues/4800)
  - 修复 event listener 未被正确移除的问题。[#4755](https://github.com/ant-design/ant-design/issues/4755)
  - 修复快速滚动时不能正确复位的问题。[#4760](https://github.com/ant-design/ant-design/issues/4760)
- **Anchor** 修复了有 offsetTop 时的定位问题。[#4706](https://github.com/ant-design/ant-design/issues/4706)
- **AutoComplete**
  - 修复了 size 问题。[#4766](https://github.com/ant-design/ant-design/issues/4766)
  - 修复了自动加入其他字符的问题。[#4778](https://github.com/ant-design/ant-design/issues/4778)
- **Dropdown** 补充了之前缺失的弹出框位置设定相关的文档及示例。[#4811](https://github.com/ant-design/ant-design/issues/4811)
- **Layout** 修复了侧边布局动效不平滑的问题。[#4752](https://github.com/ant-design/ant-design/issues/4752)
- **LocaleProvider** 修复了瑞典语相关问题。[pull-4762](https://github.com/ant-design/ant-design/pull/4762) [@JesperWe](https://github.com/JesperWe)
- **RangePicker** 修复了图标与表单校验反馈图标重叠的问题。[#4783](https://github.com/ant-design/ant-design/issues/4783) [@zhenzong](https://github.com/zhenzong)
- **Table**
  - 修复了 size 定义里没有 'middle' 的问题。[#4819](https://github.com/ant-design/ant-design/pull/4819) [@warrenseymour](https://github.com/warrenseymour)
  - 修复过滤功能在 JSX 模式下不生效的问题。[#4759](https://github.com/ant-design/ant-design/issues/4759)
  - 修复分页跳转问题。[#4779](https://github.com/ant-design/ant-design/issues/4779)
- **Tabs** 修复了在 IE9 中从第二个标签页起都显示空白的问题。[#4795](https://github.com/ant-design/ant-design/issues/4795)
- **rc-pagination** 升级至 ~1.7.0，onChange 增加 pageSize 参数。
- **全局性优化**
  - 修复或优化了一些了文档，链接，样式细节。
  - 接入 stylelint 以替代 lesslint，修复一些 lint 问题。[#2179](https://github.com/ant-design/ant-design/issues/2179)
  - border-radius 统一为 4px。[#4772](https://github.com/ant-design/ant-design/issues/4772)
  - 支持 `import { version } from 'antd'`。[#4751](https://github.com/ant-design/ant-design/pull/4751)
- **网站**
  - 首页自动选择语言。[#4552](https://github.com/ant-design/ant-design/issues/4552)
  - 接入 Google 作为文档的全文本搜索。[#4814](https://github.com/ant-design/ant-design/issues/4814)
  - 改变版本切换 Select 的位置。[pull-4799](https://github.com/ant-design/ant-design/pull/4799)

## 2.7.0

`2017-02-03`

* Button 新增 `danger` 和 `ghost` 属性。[#4679](https://github.com/ant-design/ant-design/pull/4679)
* AutoComplete 支持自定义输入框的用法。 [#4483](https://github.com/ant-design/ant-design/pull/4483)
* 升级了 rc-cascader 到 0.11.0，支持键盘操作。[#4411](https://github.com/ant-design/ant-design/pull/4411)
* notification 支持更多弹出方向。[#4732](https://github.com/ant-design/ant-design/pull/4700)
* 升级了 rc-steps 到 2.3.0，Steps 新增 `progressDot` 属性，支持自定义点状步骤条的样式。[#4659](https://github.com/ant-design/ant-design/pull/4659)
* 升级了 rc-input-number 到 3.0.0
  * 现在输入时也会触发 `onChange`。[#4265](https://github.com/ant-design/ant-design/pull/4265)
  * 修复了 `onKeyUp` 事件。[#4717](https://github.com/ant-design/ant-design/issues/4717)
* Slider 增加 `veritical` 模式。[#4473](https://github.com/ant-design/ant-design/pull/4473)
* Tag
  - 增加了预设颜色。[#4571](https://github.com/ant-design/ant-design/pull/4571)
  - 调整了垂直对齐和默认间距。
* 添加了对德语的支持。[#4686](https://github.com/ant-design/ant-design/pull/4686)
* 添加了对瑞典语的支持。[#4455](https://github.com/ant-design/ant-design/pull/4455)
* 添加了对法语的支持。[#4538](https://github.com/ant-design/ant-design/pull/4538)
* Transfer 添加了 `onSearchChange` 回调。 [#4464](https://github.com/ant-design/ant-design/pull/4464)
* Modal.confirm 添加了 maskClosable 配置项。[#4488](https://github.com/ant-design/ant-design/pull/4488), [#4488](https://github.com/ant-design/ant-design/pull/4490)
* Form
  * 增加 `options.onValuesChange` 参数，可用于代替会触发多次 `options.onFieldsChange`。[#2934](https://github.com/ant-design/ant-design/pull/2934)
  * 增加 `props.form.getFieldsError` `props.form.isFieldTouched` `props.form.isFieldsTouched` 三个方法，可用于提交表单按钮的禁用展示。 [#4374](https://github.com/ant-design/ant-design/issues/4374)
  * 增加 `hideRequiredMark` 属性。[#4732](https://github.com/ant-design/ant-design/pull/4732)
* 改进了 Upload 的列表图片预览。 [#4516](https://github.com/ant-design/ant-design/pull/4516)
* 升级了 rc-select 到 6.7.1。
  * 修复了 Select 的 `onChange` 回调重复触发的问题。[#156@rc-select](https://github.com/react-component/select/pull/156)
  * 修复了 Select 显示初始化值的问题。[#152@rc-select](https://github.com/react-component/select/pull/152)
* 升级 rc-tree-select 到 `1.9.0`。
  * 新增 `treeDefaultExpandedKeys` 属性。[#43@rc-tree-select](https://github.com/react-component/tree-select/pull/43)
  * 修复了文字溢出换行问题。[#42@rc-tree-select](https://github.com/react-component/tree-select/pull/42)
* 新增 less 变量: `@border-style-base` `@border-width-base` `@btn-danger-color` `@btn-danger-bg` 等。
* 修复了 Badge 在页面放大时错位的问题。[#4747](https://github.com/ant-design/ant-design/issues/4747) [#4290](https://github.com/ant-design/ant-design/issues/4290)
* 修复一个固定表头的表格错位问题。[#4750](https://github.com/ant-design/ant-design/issues/4750)
* 修复一个 IE 下表格滚动时卡顿的问题。[#4522](https://github.com/ant-design/ant-design/issues/4522)
* 添加别名以修正图标命名风格：`addfile` => `file-add`，`addfolder` => `folder-open`，原有的命名依然有效。[#4758](https://github.com/ant-design/ant-design/issues/4758)

## 2.6.4

`2017-01-20`

* 优化 RangePicker 选择预设时间时的界面显示。[#4561](https://github.com/ant-design/ant-design/issues/4561)
* 修复 DatePicker 选择时间界面的滚动问题。[#4412](https://github.com/ant-design/ant-design/issues/4412)
* 修复 Menu 在 `vertical` 的受控模式下，子菜单不会弹出的问题。[#3783](https://github.com/ant-design/ant-design/issues/3783)
* 修复 Cascader 禁用时的值显示样式问题。[#4648](https://github.com/ant-design/ant-design/issues/4648)
* Table
  * 优化固定表头的滚动条显示。[#4637](https://github.com/ant-design/ant-design/issues/4637)
  * 修复在 Safari 下显示 loading 效果时表头会闪烁的问题。[#4622](https://github.com/ant-design/ant-design/issues/4622)
  * 修复多处边框问题。[#4647](https://github.com/ant-design/ant-design/issues/4647)、[#4635](https://github.com/ant-design/ant-design/issues/4635)
  * 修复 showHeader 的默认值不为 `false` 的问题。[#4658](https://github.com/ant-design/ant-design/issues/4658)
  * 修复找不到 `TableColumnConfig` 的类型定义的问题。[#4660](https://github.com/ant-design/ant-design/issues/4660)

## 2.6.3

`2017-01-15`

* 修复 `2.6.2` 中 Popconfirm 不可用的问题。[#4606](https://github.com/ant-design/ant-design/issues/4606)

## 2.6.2

`2017-01-14`

* 新增社区精选组件页面。[链接](/docs/react/recommendation)
* 修复一个内容过长导致 Layout 侧边布局错位的问题。[#4459](https://github.com/ant-design/ant-design/issues/4459)
* 修复 Input.Search 输入框和图标错位的问题。[#4540](https://github.com/ant-design/ant-design/issues/4540)
* 补充了一个自定义灰底样式的 Collapse 折叠面板的例子。[链接](/components/collapse/#components-collapse-demo-custom)
* Table
  * 调大了 Table 选择框和展开按钮的列宽度。
  * 修复 `pagination` 属性切换后分页不可用的问题。[#4532](https://github.com/ant-design/ant-design/issues/4532)
  * 修复不支持三级筛选菜单的问题。[#4541](https://github.com/ant-design/ant-design/issues/4541)
  * 修复 `column.filteredValue` 无法设置为 `null` 的问题。
* 调整 Carousel 为默认不可拖拽和文字可选择。
* 增加了 Breadcrumb 内嵌非 Breadcrumb.Item 元素时的警告提示。[#4403](https://github.com/ant-design/ant-design/issues/4403)
* 修复 Tooltip 在 `onVisibleChange(visible)` 返回 `true` 时不展示的问题。[#4579](https://github.com/ant-design/ant-design/issues/4579)
* 优化 TreeSelect 内容过长时的面板高度。[#4537](https://github.com/ant-design/ant-design/pull/4537)
* 补充了 TimePicker 和 Spin 的组件样式变量。
* 用年份代替了 DatePicker 年份选择面板上的箭头。[#4415](https://github.com/ant-design/ant-design/issues/4415)
* 修复 AutoComplete 和 Form `[options.validateTrigger]` 的 TypeScript 定义。
* 优化 Spin、Progress 的动画细节效果。

## 2.6.1

`2017-1-6`

* 修复 Menu dark theme 样式问题。[#4440](https://github.com/ant-design/ant-design/issues/4440)
* 修复 `Select[tokenSeparators]` `Modal[afterClose]` `Input[name]` 等的 TypeScript interface 定义。[#4441](https://github.com/ant-design/ant-design/pull/4441) [@eddhannay](https://github.com/eddhannay)
* 修复 `TimePicker[placeholder]` 无法置空的问题。[#4446](https://github.com/ant-design/ant-design/pull/4446) [@jialeicui](https://github.com/jialeicui)
* 修复 DatePicker 等年份选择面板折行问题。[#4415](https://github.com/ant-design/ant-design/issues/4415)
* 修复 Table loading 状态分页器可操作的问题。[#4461](https://github.com/ant-design/ant-design/issues/4461)
* 修复 `Input[prefix|suffix]` 垂直对齐问题。[commit](https://github.com/ant-design/ant-design/commit/c4ac4d1eca53ae2f6f4a1e15210b43745f283534)
* 修复 Cascader 对齐问题。[commit](https://github.com/ant-design/ant-design/commit/1fbebd4ecfff432e1b2261c9dfee4b9f471e7b1f)

## 2.6.0

`2017-1-2`

- 采用全新的色彩系统。[pull/4426](https://github.com/ant-design/ant-design/pull/4426)
  - 使用新的算法函数代替 `tint/shade`。
  - 利用算法生成的新版色板。[色板演示](http://ant.design/docs/spec/colors)
  - 调整默认文字颜色。
- 增加 Layout 布局组件。[#3534](https://github.com/ant-design/ant-design/issues/3534)
- 增加 Grid 栅格配置器示例。[commit/ee17ab](https://github.com/ant-design/ant-design/commit/ee17abfa9d0362c6f9baab4a9a09e57574583246)
- Input
  - 增加 prefix 和 suffix 属性，支持前后缀配置。[#4226](https://github.com/ant-design/ant-design/issues/4226) [@ystarlongzi](https://github.com/ystarlongzi)
  - InputGroup 增加 compact 属性，支持紧凑型展示。[pull/4309](https://github.com/ant-design/ant-design/pull/4309)
- Spin 增加延迟显示属性 delay。[#4306](https://github.com/ant-design/ant-design/issues/4306)
- 修复 Pagination 在低分辨率下的错位问题。[#4349](https://github.com/ant-design/ant-design/issues/4349)
- 修复 Dropdown.Button 换行的问题。[pull/4355](https://github.com/ant-design/ant-design/pull/4355) [@Morhaus](https://github.com/Morhaus)
- 修复 Cascader disabled 状态底色的问题。[#4434](https://github.com/ant-design/ant-design/issues/4434)
- 修复 MonthPicker monthCellContentRender 属性无效的问题，并修正了错误的文档。[#4394](https://github.com/ant-design/ant-design/issues/4394)
- 修复 ButtonGroup 存在多余蓝色边框的问题。[#4382](https://github.com/ant-design/ant-design/pull/4382) [@ystarlongzi](https://github.com/ystarlongzi)
- 修复 Menu horizontal 模式子菜单选择项背景色错误的问题。[#4414](https://github.com/ant-design/ant-design/issues/4414)
- 修复配置了 hasFeedback 的 Select/Cascader 下拉箭头被遮盖的问题。[#4431](https://github.com/ant-design/ant-design/issues/4431) [@JesperWe](https://github.com/JesperWe)
- Table 没有 header 时，第一行改为非圆角。[#4373](https://github.com/ant-design/ant-design/issues/4373)
- 优化 Tree 的拖拽效果。[#4371](https://github.com/ant-design/ant-design/issues/4371)
- 进行了一些文档或示例优化、文档错误修正以及网站样式问题修复。
- 升级 rc-form 底层依赖，getFieldDecorator 的 id 支持嵌套式写法。

## 2.5.3

`2016-12-24` 🎄🎄🎄

* 支持 TypeScript@2.1。[#4208](https://github.com/ant-design/ant-design/issues/4208)
* 修正了 Tabs 嵌套时的样式问题。 [#4317](https://github.com/ant-design/ant-design/issues/4317)
* 修正了 Radio 在当前项选中时，再次点击仍会触发 onChange 的问题。 [#4242](https://github.com/ant-design/ant-design/issues/4242) [@ystarlongzi](https://github.com/ystarlongzi)
* 修正了 Form 多列栅格式的表单排列方式布局异常。 [#4271](https://github.com/ant-design/ant-design/issues/4271)
* 修正了 Menu 竖直方向的当前选择项的背景问题。[#4253](https://github.com/ant-design/ant-design/issues/4253)
* 优化了 Dropdown 的 `onVisibleChange` 回调参数 Type 类型。[#4236](https://github.com/ant-design/ant-design/issues/4236)
* 优化了 Cascader 的 `onChange` 回调参数的 Type 类型。[#4231](https://github.com/ant-design/ant-design/issues/4231)
* 优化了 Datepicker[showTime] 的默认宽度 [b912f1c](https://github.com/ant-design/ant-design/commit/b912f1cea6f470c16b8dd90554883460161cef47)

## 2.5.2

`2016-12-10`

* 优化 Menu 已选择项的样式。
* 修复 Mention 不能响应 `onFocus` 和 `onBlur` 的问题。[#4163](https://github.com/ant-design/ant-design/issues/4163)
* 修复 `disabled` 和 `checked` 的 Radio 之间会多一条阴影的问题。[#4114](https://github.com/ant-design/ant-design/pull/4114) @jdz321
* 修复 RangePicker、TimePicker、Calendar 设置 Moment 的 `defaultValue` 和 `value` 时也会报错的问题。[#4147](https://github.com/ant-design/ant-design/issues/4147)
* 修复 Affix 在开启动画的 Tabs 里使用时会消失的问题。[#3943](https://github.com/ant-design/ant-design/issues/3943)
* 修复 Cascader 手动选择和搜索选择时 `onChange` 接收到的 `selectedOptions` 不同的问题。[#4096](https://github.com/ant-design/ant-design/issues/4096)
* 修复 Tabs 页增加到一定数量时会产生偏移的问题。[#3637](https://github.com/ant-design/ant-design/issues/3637)
* Table
  * 居中对齐表头分组的父表头。
  * 修正设置 filterDropdownVisible 时不生效的问题。[#4162](https://github.com/ant-design/ant-design/issues/4162)

## 2.5.1

`2016-12-03`

* 提升网站首页在移动端访问的体验。
* 补充从 `1.x` 升级到 `2.x` 时的组件改动警告提示。[#4028](https://github.com/ant-design/ant-design/pull/4028)
* 现在 ToolTip、Popover、Popconfirm 支持直接包裹文本节点和多个节点。[#3924](https://github.com/ant-design/ant-design/issues/3924)
* Anchor
  * 修复快速滚动时的定位问题。[#4053](https://github.com/ant-design/ant-design/issues/4053)
  * 修复 target 指定父元素 ref 时无效的问题。[#4037](https://github.com/ant-design/ant-design/issues/4037)
* Table
  * 修复设置 defaultChecked 时的一个选中问题。[#4020](https://github.com/ant-design/ant-design/issues/4020)
  * 修复分组表头中筛选功能无法使用的问题。[#4099](https://github.com/ant-design/ant-design/issues/4099)
* 修复在 `Input[type="textarea"]` 上使用 Popover 定位错误问题。[#4092](https://github.com/ant-design/ant-design/issues/4092)
* 修复 Popconfirm 的 `visible` 属性失效的问题。[#4068](https://github.com/ant-design/ant-design/issues/4068)
* 修复 TimePicker 无法设置 `style.width` 的问题。
* 修复 Steps 自定义图标和默认图标大小不一致的问题。[#3817](https://github.com/ant-design/ant-design/issues/3817)
* 修复 Form、Button、Slider、Table 等组件的一些样式细节。

## 2.5.0

`2016-11-25`

* 默认主题风格修改为支付宝钱包风格，及大量样式优化。
* 支持服务端渲染。（Mention 会因为 [draft-js](https://github.com/facebook/draft-js/issues/385) 的问题有 warning）
* 引入 [Jest Snapshot](https://facebook.github.io/jest/docs/tutorial-react.html#snapshot-testing) 测试组件结构及服务端渲染问题。
* 官网及文档优化。
* 新增自定义主题的 [文档](https://ant.design/docs/react/customize-theme)。
* 新增 [Sketch 资源文件](https://ant.design/docs/resource/download)。
* LocaleProvider 新增巴西语支持。[#4004](https://github.com/ant-design/ant-design/pull/4004) [@nathantn](https://github.com/nathantn)
* DatePicker
  * DatePicker 现在可以决定是否展示 “今天” 按钮。[commit](https://github.com/ant-design/ant-design/commit/bbef274aae169d142e3e7e3ea0af922d48e6dd64)
  * RangePicker 现在可以自定义快捷选择。[demo](https://ant.design/components/date-picker/#components-date-picker-demo-presetted-ranges)
  * 修复 DatePicker 设置 `showTime` 后 “此刻” 按钮失效的问题。[#3748](https://github.com/ant-design/ant-design/issues/3748)
  * 修复 `RangePicker[format]` 失效的问题。[#3808](https://github.com/ant-design/ant-design/issues/3808)
  * 修复 RangePicker `placeholder=['xx', 'xx']` 失效的问题。
* 新增并优化部分 Icon。[#3977](https://github.com/ant-design/ant-design/pull/3977)
* 新增 Input.Search 控件。[demo](https://ant.design/components/input/#components-input-demo-search-input)
* Mention onSelect 事件现在可以获取完整的数据。[#3867](https://github.com/ant-design/ant-design/issues/3867)
* Pagination 现在支持展示当前页的索引范围。[demo](https://ant.design/components/pagination/#components-pagination-demo-total)
* Table
  * 自定义筛选的显示隐藏现在可以通过代码控制。[demo](https://ant.design/components/table/#components-table-demo-custom-filter-panel)
  * 支持 JSX 风格的方式设置 columns。[demo](https://ant.design/components/table/#components-table-demo-jsx)
  * 现在可以监听单元格的点击事件 `onCellClick`。[#3774](https://github.com/ant-design/ant-design/issues/3774)
  * 修复无边框 Table 头部的圆角样式问题。
  * 修复 title 和 footer 高度不随 `Table[size]` 变化的问题。[commit](https://github.com/ant-design/ant-design/commit/9e6439b06cd099ab384a4a2f026f0def6e12bf23)
  * 修复选中状态出错的问题。[#3900](https://github.com/ant-design/ant-design/issues/3900)
* Upload
  * 修复 children 不能为 `null` 的问题。
  * 修复预览逻辑的问题。[commit](https://github.com/ant-design/ant-design/commit/e552880c32aaa3f5b0fb09a5e1fb7454c24d5378)
* 修复 Badge 会覆盖其他组件的问题。[#3898](https://github.com/ant-design/ant-design/issues/3898)
* 修复多行 Checkbox 样式不对齐的问题。[#3971](https://github.com/ant-design/ant-design/issues/3971) [@flashback313](https://github.com/flashback313)
* 修复 InputNumber 与其它表单控件不对齐的问题。[#3866(comment)](https://github.com/ant-design/ant-design/issues/3866#issuecomment-261148256)
* 修复 `Menu.Divider` 样式问题。[#3813](https://github.com/ant-design/ant-design/issues/3813)
* 修复 Popover 直接内嵌 Checkbox 和 Radio 无效的问题。[#3455](https://github.com/ant-design/ant-design/issues/3455)
* 修复 Select combobox 高度异常问题。[#3855](https://github.com/ant-design/ant-design/issues/3855)
* 修复 Switch actived 后的样式问题。[#3838](https://github.com/ant-design/ant-design/issues/3838)
* 修复 Transfer 搜索无结果时不展示 “Not Found” 提示的问题。[#3996](https://github.com/ant-design/ant-design/issues/3996)
* 修复 TreeSelect 占位符的样式问题。[#3841](https://github.com/ant-design/ant-design/issues/3841)
* 修复 TypeScript 编译报错的问题。[#3969](https://github.com/ant-design/ant-design/pull/3969) [@AlbertZheng](https://github.com/AlbertZheng)
* 修复表单反馈图标影响用户操作的问题。[#3891](https://github.com/ant-design/ant-design/issues/3891)

## 2.4.3

`2016-11-17`

* 修复 `Anchor` 内部 querySelector 报错，并做了一些体验优化 。[#3832](https://github.com/ant-design/ant-design/issues/3832) [#3844](https://github.com/ant-design/ant-design/issues/3844)

## 2.4.2

`2016-11-13`

* 修复 `Dropdown.Button` 不弹出的问题。[#3815](https://github.com/ant-design/ant-design/issues/3815)

## 2.4.1

`2016-11-11`

* 修复 `2.4.0` 组件 index 文件丢失的问题。

## 2.4.0

`2016-11-11`

* 调整了组件的导航结构。
* 新增 [Anchor](https://ant.design/components/anchor) 锚点组件。
* 整理了样式变量，修复 `@font-size-base` 和 `@text-color` 在部分组件无效的问题，新增 `@font-size-lg` `@text-color-secondary`，并移除了部分无用的变量。
* `Transfer` 组件新增了受控属性 `selectedKeys`。[#3729](https://github.com/ant-design/ant-design/issues/3729)
* `Tag` 新增选中状态。
* 修复 `Dropdown.Button` 不支持 `visible` 和 `onVisibleChange` 的问题。[#3779](https://github.com/ant-design/ant-design/issues/3779)
* 修复 `DatePicker[showTime]`` 的 `此刻` 按钮。[#3748](https://github.com/ant-design/ant-design/issues/3748)
* 修复 `Steps` 竖直方向的样式。[#3760](https://github.com/ant-design/ant-design/issues/3760)
* 修复 `Spin` 组件在 IE10+ 的样式问题。[#3755](https://github.com/ant-design/ant-design/issues/3755)
* 修复 `Mention` 组件的 focus 逻辑. [#3801](https://github.com/ant-design/ant-design/issues/3801)
* 修复 `Progress` 组件的动画问题。[#3784](https://github.com/ant-design/ant-design/issues/3784)
* 修复 `Select` 搜索时的丢失焦点问题。[#3778](https://github.com/ant-design/ant-design/issues/3778)
* 修复 `TimePicker` 不支持 `format="HH"` 等格式的问题。[#3793](https://github.com/ant-design/ant-design/issues/3793)
* 修复 `Input` 的 `suffix` 部分区域中鼠标事件无法响应的问题。[#3714](https://github.com/ant-design/ant-design/issues/3714)
* 优化了 `Table` 选择的性能。[#3757](https://github.com/ant-design/ant-design/pull/3757)
* 优化 `Carousel` 的默认样式。
* 优化 `Checkbox` 和 `Radio` 的样式。[#3590](https://github.com/ant-design/ant-design/issues/3590)
* 修复 `DatePicker`、`Form`、`Table` 等组件的样式细节。

## 2.3.2

`2016-11-09`

* 修复使用 `getFieldProps` 会导致死循环的问题。

## 2.3.1

`2016-11-07`

* 修正上个版本缺少 `dist/antd.css` 的问题。

## 2.3.0

`2016-11-04`

* 升级 normalize.css 到 5.0。
* package.json 的 main 换成了 `lib/index.js`。[#3397](https://github.com/ant-design/ant-design/pull/3397)
* 全新的 `Spin` 设计。
* `TimePicker` 新增了 `addon` 以支持自定义的附加内容。
* `Tree` 新增了 `onDragEnd`。
* `Collapse` 新增了 `bordered`。
* 优化 `Tabs` 切换时的动画效果。
* 优化 `Radio` 和 `Checkbox` 在禁用和鼠标停留时的样式。[#3590](https://github.com/ant-design/ant-design/issues/3590)
* 优化 `Transfer` 的性能。[#2860](https://github.com/ant-design/ant-design/issues/2860)
* 修复 `Popover` 嵌套时的样式问题。[#3448](https://github.com/ant-design/ant-design/issues/3448)
* 修复 `Transfer` 服务端渲染报错的问题。[#3686](https://github.com/ant-design/ant-design/issues/3686)
* 修复 `Upload` `picture-card` 模式下新上传的图片不显示预览的问题。[#3706](https://github.com/ant-design/ant-design/pull/3706) [@denzw](https://github.com/denzw)
* DatePicker
  * 在 `showTime` 模式下现在失去焦点也会触发 `onChange`。
  * `MonthPicker` 增加了 `monthCellContentRender`。
  * `RangePicker` 现在可以手动输入时间了。[#3718](https://github.com/ant-design/ant-design/issues/3718)
  * 新增了捷克语的翻译。
* Badge
  * 优化鼠标停留时超过 99 的数字显示。[#3645](https://github.com/ant-design/ant-design/issues/3645)
  * 修复单独使用时会有移动动画的问题。[#3709](https://github.com/ant-design/ant-design/issues/3709)
* Mention
  * 修复会被 `Table` 遮住的问题。[#3588](https://github.com/ant-design/ant-design/issues/3588)
  * 新增 `getSuggestionContainer` 来指定容器。[#3658](https://github.com/ant-design/ant-design/pull/3658)
* Tag
  * 废弃 `color` 属性。[#3560](https://github.com/ant-design/ant-design/issues/3560)
  * 新增 `type`。[#3560](https://github.com/ant-design/ant-design/issues/3560)
  * 新增 `checkable`。[#3560](https://github.com/ant-design/ant-design/issues/3560)
* Radio.Group
  * 新增 `className`。
  * `children` 为 `null` 或 `undefined` 时现在会被忽略。
* Select
  * 新增 `tokenSeparators` 支持粘贴时自动分词。[#2071](https://github.com/ant-design/ant-design/issues/2071)
  * 新增 `onFocus` 回调。[#3587](https://github.com/ant-design/ant-design/issues/3587)
  * 修复 `combobox` 模式下选中项不能正确显示的问题。[#3401](https://github.com/ant-design/ant-design/issues/3401)

## 2.2.1

`2016-11-02`

* 修复 Form 中 DatePicker[showTime]（受控）无法使用的问题。[#3665](https://github.com/ant-design/ant-design/issues/3665)

## 2.2.0

`2016-10-28`

* 支持 TypeScript@2.0。[@AlbertZheng](https://github.com/AlbertZheng) [#3358](https://github.com/ant-design/ant-design/issues/3358)
* 不再强依赖于 React 特定版本。[#3627](https://github.com/ant-design/ant-design/pull/3627)
* Alert 支持 `className` `style` 属性。
* DatePicker MonthPicker RangePicker 现在允许设置是否显示清除按钮。[#3618](https://github.com/ant-design/ant-design/issues/3618)
* Form.Item 现在可以感知深层嵌套的表单域，以自动为其生成错误信息和状态。[#3212](https://github.com/ant-design/ant-design/issues/3212)
* RangePicker 现在可以设置不可选的时间。[#](https://ant.design/components/date-picker/#components-date-picker-demo-disabled-date)
* Switch
  * 宽度现在会随着 `checkedChildren/unCheckedChildren` 自动调整。[#3380](https://github.com/ant-design/ant-design/issues/3380)
  * 优化切换动画。
* Upload 现在可以 [自定义上传方式](https://github.com/react-component/upload#customrequest)。[@edgji](https://github.com/edgji)
* Icon
  * 新增 `bulb` `select` `like-o` `dislike-o`。
  * 调整 `loading` `like` `dislike`。
* 优化 Card DatePicker Icon Table 的 TypeScript 定义。[@infeng](https://github.com/infeng) [3468](https://github.com/ant-design/ant-design/pull/3468) [#3603](https://github.com/ant-design/ant-design/pull/3603) [#3531](https://github.com/ant-design/ant-design/pull/3531)
* 修复 Cascader `defaultValue` 失效的问题。[#3470](https://github.com/ant-design/ant-design/issues/3470)
* 修复在一行内同时使用 Button Input DatePicker Select 时对齐的问题。[#3481](https://github.com/ant-design/ant-design/issues/3481)
* DatePicker
  * 修复设置 `DatePicker[showTime]` 后 `onChange` 事件触发时机问题。[#3523](https://github.com/ant-design/ant-design/issues/3523)
* 修复 Dropdown.Button disabled 后仍然响应操作的问题。[#3535](https://github.com/ant-design/ant-design/issues/3535)
* Menu
  * 修复服务端渲染问题，感谢 [@xpcode](https://github.com/xpcode) 定位问题。[#2061](https://github.com/ant-design/ant-design/issues/2061) [#2406](https://github.com/ant-design/ant-design/issues/2406) [#3293](https://github.com/ant-design/ant-design/issues/3293)
  * 修复 children 不能为 `null` 的问题。[#3599](https://github.com/ant-design/ant-design/issues/3599)
* 修复 message 加载状态无动画的问题。[#3536](https://github.com/ant-design/ant-design/issues/3536)
* Form
  * 修复 `Form[inline]` 与 `Input[addonBefore|addonAfter]` 一起使用时的样式问题。[#3524](https://github.com/ant-design/ant-design/issues/3524)
  * 修复 Form.Item 内 Radio.Button 样式问题。
  * 修复 Form.Item 内搜索按钮的样式问题。[#3630](https://github.com/ant-design/ant-design/issues/3630)
  * 修复用户无输入时 Form.Item 识别为校验成功的问题。[#3613](https://github.com/ant-design/ant-design/issues/3613)
* 当 `Popover[title]` 没有设置时，不再限制 Popover 的最小宽度。
* Table
  * 修复固定表头在没有数据情况下的样式问题。[#3567](https://github.com/ant-design/ant-design/issues/3567)
  * 修复无数据时会覆盖 SubMenu 的问题。[#3521](https://github.com/ant-design/ant-design/issues/3521)
* Tabs
  * 修复卡片叶签头部高度与设计稿不一致的问题。
  * 修复 TabPane 的高度会被同级 TabPane 撑高的问题。[#3304](https://github.com/ant-design/ant-design/issues/3304)
* 修复 `TreeSelect[showSearch]` 样式问题。[#3520](https://github.com/ant-design/ant-design/issues/3520)

## 2.1.0

`2016-10-16`

- Icon 现在支持旋转动画。
- Tabs 现在可以禁用切换动画。[#3324](https://github.com/ant-design/ant-design/issues/3324)
- 新增西班牙语的 localization 支持。@Danjavia
- 更新俄语的 localization 文案。@plandem
- 新增 AutoComplete[onSelect] 回调。
- 优化 Modal 样式细节。
- 优化 Tooltip 动画。
- 优化 Transfer 按钮的样式。
- 优化 Tree 的样式细节。
- 整理和修复了部分 less 变量。
- 修复服务端渲染时全量引入 antd 报错的问题。
- 修复 Affix 与 BackTop 的服务端渲染问题。[#3283](https://github.com/ant-design/ant-design/issues/3283) [#3343](https://github.com/ant-design/ant-design/issues/3343)
- 修复 Card[title] 内无法使用 `h3` 之类的标签的问题。[#3388](https://github.com/ant-design/ant-design/issues/3388)
- 修复 Cascader 搜索模式与浏览器自动完成有冲突的问题。[#3350](https://github.com/ant-design/ant-design/issues/3350)
- DatePicker
  - 修复设置 `showTime` 后，`onChange` 重复触发的问题。[#3376](https://github.com/ant-design/ant-design/issues/3376)
  - 修复浮层与 Trigger 日期格式不一致的问题。[#3405](https://github.com/ant-design/ant-design/issues/3405) [#3298](https://github.com/ant-design/ant-design/issues/3298)
  - 修复与 TimePicker 样式冲突问题。[#3312](https://github.com/ant-design/ant-design/issues/3312) [#3307](https://github.com/ant-design/ant-design/issues/3307)
- 修复 Form.Item 标签文案过长溢出的问题。
- 修复 Icon 在 Safari 下会出现边框的问题。
- 修复 InputNubmer 键盘事件死循环问题。[#3239](https://github.com/ant-design/ant-design/issues/3239)
- 修复 Popover 箭头样式问题。
- 修复 Popover 和 Popconfirm 的 `arrowPointAtCenter` 无效的问题。
- Select
  - 修复样式重复引入的问题。[#3376](https://github.com/ant-design/ant-design/issues/3376)
  - 修复 `notFoundContent` 无法置空的问题。[#3345](https://github.com/ant-design/ant-design/issues/3345)
  - 修复 Table 内使用 Select[showSearch] 后宽度会跳动的问题。[#3413](https://github.com/ant-design/ant-design/issues/3413)
- 修复 Table 边框线与页头页脚冲突的问题。[#3301](https://github.com/ant-design/ant-design/issues/3301)
- 修复 TabPane 高度不随内容变化的问题。[#3377](https://github.com/ant-design/ant-design/issues/3377)
- 修复 Transfer[titles] 不受 LocaleProvider 控制的问题。[#3264](https://github.com/ant-design/ant-design/pull/3264)
- Upload
  - 修复用户自定义 `onRemove` 事件会覆盖默认行为的问题。[#3317](https://github.com/ant-design/ant-design/issues/3317)
  - 修复图片卡片样式问题。[#3316](https://github.com/ant-design/ant-design/issues/3316)
- 修复项目构建时 moment locales 找不到的问题。[#3204](https://github.com/ant-design/ant-design/issues/3204) [#3411](https://github.com/ant-design/ant-design/issues/3411)

## 2.0.1

`2016-10-01`

- 修复无法调用 react-slick 方法的问题。[#3164](https://github.com/ant-design/ant-design/issues/3164)
- 修复 Steps.Step[icon] 不支持 React.ReactNode 的问题。[#3159](https://github.com/ant-design/ant-design/issues/3159)
- 修复 Affix 不支持服务端渲染的问题。[#3216](https://github.com/ant-design/ant-design/issues/3216)
- 修复 Mention 不支持 `onSelect` `placeholder` 的问题。[#3236](https://github.com/ant-design/ant-design/issues/3236) [#3226](https://github.com/ant-design/ant-design/issues/3226)
- 修复 Transfer 与 `getFieldDecorator` 一起使用时的报错问题。
- 修复 LocaleProvider 对时间组件无效的问题。
- 修复 Cascader 搜索模式搜索文字显示不了的问题。
- 修复 Spin 动画与文案整体不垂直居中的问题。
- 修复 RangePicker Modal Tag Progress 等组件样式问题。

## 2.0.0

`2016-09-28`

很高兴的通知各位，经过四个月时间的紧密开发，`antd@2.0.0` 终于发布了。这个版本我们重构了底层代码，持续完善现有组件功能和优化细节，并提供了英文版的文档，其中很多都来自社区的贡献，无法一一感谢，欢迎各位持续关注和鞭策。在升级过程中遇到任何问题，请及时 [反馈给我们](https://github.com/ant-design/ant-design/issues)。

### 2.x 主要变化

* 开发语言改为 TypeScript，提供 **官方支持的 `.d.ts` 文件**，感谢 [#1846](https://github.com/ant-design/ant-design/issues/1846) 中所有参与到这次重构的人以及后期 @infeng 对其的完善。
* **新增英文文档**， 以后将同时提供中英双语文档，感谢 [#1471](https://github.com/ant-design/ant-design/issues/1471) 里所有参与到翻译和审阅工作中的人。
* 时间类组件 DatePicker、TimePicker、Calendar 等的底层 **使用 [moment](http://momentjs.com/) 替换 [gregorian-calendar](github.com/yiminghe/gregorian-calendar)**。
* 全新设计的 [图标](http://ant.design/components/icon/)。
* 新增提及组件 [Mention](http://ant.design/components/mention/)。
* 新增自动完成组件 [AutoComplete](http://ant.design/components/auto-complete/)。
* Form 新增 `getFieldDecorator` 作为 `getFieldProps` 的替代，对于不正确的使用方式 `getFieldDecorator` 会给出提示，可以降低踩坑的概率。相关讨论见 [#1533](https://github.com/ant-design/ant-design/issues/1533)。
* Table 支持 [表头分组](http://ant.design/components/table/#components-table-demo-grouping-columns)。@yesmeck
* 完全移除 `antd@1.x` 中已经废弃的 QueueAnim、Validation、Form.ValueMixin、Progress.Line、Progress.Circle、Popover[overlay] 及 Slider[marks] 对数组的支持。

### 2.x 不兼容改动

> 建议从 `1.x` 升级时，直接升级到 `2.x` 的最新版本。

> 建议在升级 antd 的过程中，每做完一次合理的修改并 review 和测试之后，就 git commit 一次，这样在误操作时能随时回滚到之前的版本

此版本有部分不兼容的改动，升级时确保修改相应的使用代码。另外由于人肉查找代码中的废弃用法过于低效，所以我们提供了 [antd-migration-helper](https://github.com/ant-design/antd-migration-helper) 用于扫描代码中的废弃用法。

* 时间类组件的 `value` 和 `defaultValue` 不再支持 `String/Date` 类型，请使用 [moment](http://momentjs.com/)。需要对代码进行如下修改，可人手修改也可用我们提供的 [codemod](https://github.com/ant-design/antd-codemod#time-related-value-to-moment) 脚本自动修改类似用法，但注意脚本不能覆盖所有情况，所以在运行脚本后仍然需要 review 和测试。
  ```diff
  - <TimePicker defaultValue="12:08:23" />
  + <TimePicker defaultValue={moment('12:08:23', 'HH:mm:ss')} />

  - <DatePicker defaultValue="2015/01/01" />
  + <DatePicker defaultValue={moment('2015/01/01', 'YYYY/MM/DD')} />

  - <Calendar defaultValue={new Date('2010-10-10')} />
  + <Calendar defaultValue={moment('2010-10-10', 'YYYY-MM-DD')} />
  ```
* 时间类组件的 `onChange` 和 `onPanelChange` 及其他回调函数中为 `Date/GregorianCalendar` 类型的参数，均修改为 moment 类型，两者 API 有所不同，但功能基本一致，请对照 [moment 的 API 文档](http://momentjs.com/docs/) 和 [gregorian-calendar 的文档](https://github.com/yiminghe/gregorian-calendar) 进行修改。
  1. 也可以参考这个 [commit](https://github.com/ant-design/ant-design/commit/4026221d451b246956983bb42140142d4a48b7d7) 来进行修改。
  1. 也可用我们提供的 [codemod](https://github.com/ant-design/antd-codemod#gergoriancalendar-to-moment) 脚本自动修改类似用法，但注意脚本不能覆盖所有情况，所以在运行脚本后仍然需要 review 和测试。
  ```diff
  function disabledDate(date) {
  - console.log(date.getTime());
  + console.log(date.valueOf());
  }
  ```
* 由于 `JSON.stringify(date: moment)` 返回的值会丢失时区设置，所以在提交前要先使用 `.format` 把日期转成字符串，相关 issue 见 [#3082](https://github.com/ant-design/ant-design/issues/3082)：
  ```js
  handleSubmit() {
    const values = this.props.form.getFieldsValue();
    values.date = values.date.format('YYYY-MM-DD HH:mm:ss'); // 或其它格式
    const data = JSON.stringify(values);
    // 发送 data 到服务器
  }
  ```
* 时间类组件与表单校验一起使用时，`type: 'date'` 改为 `type: 'object'`。
  ```diff
  getFieldDecorator('time', {
    rules: [{
      required: true,
  -   type: 'date',
  +   type: 'object',
    }],
  })(...)
  ```
* 时间类组件的 `format` 属性也发生了变化，从 [gregorian-calendar-format 的格式](https://github.com/yiminghe/gregorian-calendar-format#api) 变化为与 [moment 的格式](http://momentjs.com/docs/#/parsing/string-format/)，例如原来的 `yyyy-MM-dd` 将变为 `YYYY-MM-DD`。可人手修改也可用我们提供的 [codemod](https://github.com/ant-design/antd-codemod#time-related-value-to-moment) 脚本自动修改类似用法，但注意脚本不能覆盖所有情况，所以在运行脚本后仍然需要 review 和测试。
* Breadcrumb 移除 `linkRender` 和 `nameRender`，请使用 `itemRender`。
* Menu 移除 `onClose` `onOpen`，请使用 `onOpenChange`。API 差异较大，请先研究 [demo](http://beta.ant.design/components/menu/#components-menu-demo-sider-current)。
* Table 移除列分页功能，请使用 [固定列](http://ant.design/components/table/#components-table-demo-fixed-columns)。
* Popover 移除 `overlay` ，请使用 `content`。

以下变化升级后旧代码仍然能正常运行，但是控制台会出现警告提示，建议按提示进行修改。

* Form 废弃 `getFieldProps`，请使用 `getFieldDecorator`。可人手修改也可用我们提供的 [codemod](https://github.com/ant-design/antd-codemod#getfieldprops-to-getfielddecorator) 脚本自动修改类似用法，但注意脚本不能覆盖所有情况，所以在运行脚本后仍然需要 review 和测试。

  ```diff
  -  <Input placeholder="text" {...getFieldProps('userName', { ... })} />
  +  {getFieldDecorator('userName', { ... })(
  +    <Input placeholder="text" />
  +  )}
  ```

  相关讨论可以看 [#1533](https://github.com/ant-design/ant-design/issues/1533)。

* DatePicker 废弃 `toggleOpen`，请使用 `onOpenChange`：

  ```diff
  - handleToggleOpen({ open }) {
  + handleOpenChange(open) {
    ...
  }
  ```

最后，由于时间类组件修改比较复杂，可能还需要深入业务逻辑，所以在项目比较赶的情况下，可以考虑使用 [antd-adapter](https://github.com/ant-design/antd-adapter) 适配为 `antd@1.x` 里面的用法，但不建议。

### 2.x Bug 修复

* 修复 Dropdown.Button `disabled` 属性无效的问题。[#3070](https://github.com/ant-design/ant-design/issues/3070)
* 修复 Form.create `withRef` 选项失效的问题。[#2843](https://github.com/ant-design/ant-design/issues/2843)
* 修复 Menu inline 模式下子菜单展开的问题。[#2701](https://github.com/ant-design/ant-design/issues/2701)
* 修复 Modal.confirm 之类的弹窗在异步调用时按钮仍可点击的问题。[#2684](https://github.com/ant-design/ant-design/issues/2684)
* 修复 DatePicker[showTime] 参数中的 `format` 失效的问题。[#3123](https://github.com/ant-design/ant-design/issues/3123)
* 修复 Table[dataSource] 中的项的 key 为 `0` 时识别错误的问题。[#3166](https://github.com/ant-design/ant-design/pull/3166) @noonnightstorm
* 修复 Tree.Node 无子节点时仍然显示箭头的问题。[#2616](https://github.com/ant-design/ant-design/issues/2616)
* 修复 Tree.Node 箭头隐藏后鼠标 hover 上去光标仍会发生变化的问题。[#2748](https://github.com/ant-design/ant-design/issues/2748)

### 2.x 其他改进

* Alert 新增 [`banner` 模式](http://ant.design/components/alert/#components-alert-demo-banner)。
* BackTop 增加回到顶部的动画效果。
* Badge 新增 [状态点模式](http://ant.design/components/badge/#components-badge-demo-status)。
* Cascader 新增 [搜索功能](http://ant.design/components/cascader/#components-cascader-demo-search)。
* Checkbox 新增 [indeterminate 状态](http://ant.design/components/checkbox/#components-checkbox-demo-check-all)。
* Form 新增 [垂直布局](http://ant.design/components/form/#components-form-demo-validate-customized)。
* InputNumber 现在支持长按。[#](http://ant.design/components/input-number/#components-input-number-demo-basic)
* notification 支持 [自定义 icon](http://ant.design/components/notification/#components-notification-demo-custom-icon)。
* Spin 现在允许 [自定义文案与动画共存](http://ant.design/components/spin/#components-spin-demo-tip)。@jerrybendy
* Transfer 现在可以监听用户选择了哪些选项。[#](http://ant.design/components/transfer/#components-transfer-demo-basic)
* Transfer 现在可以定义哪些选项是 [不可选择的](http://ant.design/components/transfer/#components-transfer-demo-basic)。
* 优化 Alert 和 notification 的样式。
* 优化 Modal.confirm 之类的弹窗的键盘交互。@Dafrok
* 优化 [DatePicker 的时间选择](http://ant.design/components/date-picker/#components-date-picker-demo-time) 交互。
* 优化 [Spin 状态切换](http://ant.design/components/spin/#components-spin-demo-nested ) 时的效果。
* 更新 [font-family](https://github.com/ant-design/ant-design/commit/2f308b0f995cfcb2a3c8feb1e35ffd3f0bf93cfc)。

### 2.x 相关工具发布

* 新增配套网站 [AntD Library](http://library.ant.design/)，提供遵循 Ant Design 设计规范的组件、模式等的 Axure 资源。
* `babel-plugin-antd` 更名为 [babel-plugin-import](https://github.com/ant-design/babel-plugin-import)，标志着该插件将作为一个通用的按需加载方案存在，而不再是 `antd` 专有。

  请更新 `package.json`：

  ```diff
  {
    "devDependencies": {
  -   "babel-plugin-antd": "^0.x.x",
  +   "babel-plugin-import": "^1.0.0",
    }
  }
  ```

  同时更新 `.babelrc` 或你在其它地方对其的配置：

  ```diff
  {
  -  "plugins": [["antd", { "style": "css" }]]
  +  "plugins": [["import", { "libraryName": "antd", "style": "css" }]]
  }
  ```

* [dva@1.0.0](https://github.com/dvajs/dva) 也已经发布，并推荐 [在实战项目中使用](http://ant.design/docs/react/practical-projects)。
* 脚手架工具推荐使用 [dva-cli](https://github.com/dvajs/dva-cli)，原来的 `antd-init` 以后仅会用于学习以及 demo。

## 1.11.4

去 [GitHub](https://github.com/ant-design/ant-design/blob/1.x-stable/CHANGELOG.md) 查看 `0.x` 到 `1.x` 的 Change Log。
