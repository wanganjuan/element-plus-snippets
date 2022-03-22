### Various basic code tips to make code writing take off

1. Basically all element plus tags are as follows. We trigger by keywords, e.g. `epb` for `<el-button>`,
   Actual code snippet: `<el-button type="primary">{$1}</el-button>`

- All code snippets, based on [element-plus](https://element-plus.org/)
  .

![image](https://cdn.wangxingyu.top/v.gif)

## Snippets List

#### 新增

```
note-->
/**
 * @description desc
 * @author jingwang36
 * @date 2022/02/16 20:14:36
 */
```
| No. | Trigger Key | Element Tag        |
| :-: | :---------: | :----------------- |
| 1.  |   `node`    | `标准的注释格式`   |
| 2.  |     `v`     | `vue3-ts-结构代码` |
| 3.  |   `temp`    | `<template>`       |
| 4.  |   `eptm`    | `<table> 多选`     |

#### Basic 基础组件

| No. | Trigger&nbsp;Key | Element Tag                                                                                                               |
| :-: | :--------------: | :------------------------------------------------------------------------------------------------------------------------ |
| 1.  |     `eprow`      | `<el-row>`                                                                                                                |
| 2.  |     `epcol`      | `<el-col>`                                                                                                                |
| 3.  |      `ephc`      | `hidden-xs-only,hidden-sm-only,etc`                                                                                       |
| 4.  |     `epcon`      | `<el-container>`                                                                                                          |
| 5.  |      `epas`      | `<el-aside>`                                                                                                              |
| 6.  |      `ephe`      | `<el-header>`                                                                                                             |
| 7.  |      `epma`      | `<el-main>`                                                                                                               |
| 8.  |      `epfo`      | `<el-footer>`                                                                                                             |
| 9.  |      `epcb`      | `#409EFF`                                                                                                                 |
| 10. |      `epcs`      | `#67C23A`                                                                                                                 |
| 11. |      `epcw`      | `#E6A23C`                                                                                                                 |
| 12. |      `epcd`      | `#F56C6C`                                                                                                                 |
| 13. |      `epci`      | `#909399`                                                                                                                 |
| 14. |     `epcpt`      | `#303133`                                                                                                                 |
| 15. |     `epcrt`      | `#606266`                                                                                                                 |
| 16. |     `epcst`      | `#909399`                                                                                                                 |
| 17. |     `epcht`      | `#C0C4CC`                                                                                                                 |
| 18. |     `epcbb`      | `#DCDFE6`                                                                                                                 |
| 19. |     `epclb`      | `#E4E7ED`                                                                                                                 |
| 20. |     `epclrb`     | `#EBEEF5`                                                                                                                 |
| 21. |     `epelb`      | `#DCDFE6`                                                                                                                 |
| 22. |     `eptypo`     | `font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;` |
| 23. |     `epbbs`      | `box-shadow: 0 2px 4px rgba(0, 0, 0, .12), 0 0 6px rgba(0, 0, 0, .04)`                                                    |
| 24. |     `epbls`      | `box-shadow: 0 2px 12px 0 rgba(0, 0, 0, 0.1)`                                                                             |
| 25. |      `epb`       | `ep-button`                                                                                                               |
| 26. |      `epbg`      | `ep-button-group`                                                                                                         |
| 27. |      `epl`       | `ep-link`                                                                                                                 |

#### Form 表单组件

| No. | Trigger&nbsp;Key | Element Tag                                     |
| :-: | :--------------: | :---------------------------------------------- |
| 1.  |      `epr`       | `<el-radio>`                                    |
| 2.  |      `eprg`      | `<el-radio-group>`                              |
| 3.  |     `eprbg`      | `<el-radio-group> with <el-radio-button>`       |
| 4.  |      `eprb`      | `<el-radio-button>`                             |
| 5.  |      `epc`       | `<el-checkbox>`                                 |
| 6.  |      `epcg`      | `<el-checkbox-group>`                           |
| 7.  |     `epcbg`      | `<el-checkbox-group> with <el-checkbox-button>` |
| 8.  |     `epcbt`      | `<el-checkbox-button>`                          |
| 9.  |      `epi`       | `<el-input>`                                    |
| 10. |      `epit`      | `<el-input type="textarea">`                    |
| 11. |      `epa`       | `<el-autocomplete>`                             |
| 12. |      `epis`      | `<template slot=''>`                            |
| 13. |      `epin`      | `<el-input-number>`                             |
| 14. |     `epsel`      | `<el-select>`                                   |
| 15. |     `epselr`     | `<el-select remote>`                            |
| 16. |      `epop`      | `<el-option>`                                   |
| 17. |     `epopg`      | `<el-option-group>`                             |
| 18. |      `epca`      | `<el-cascader>`                                 |
| 19. |     `epcap`      | `<el-cascader-panel>`                           |
| 20. |      `epsw`      | `<el-swtich>`                                   |
| 21. |      `epsl`      | `<el-slider>`                                   |
| 22. |      `eptp`      | `<el-time-picker>`                              |
| 23. |      `epts`      | `<el-time-select>`                              |
| 24. |     `eptsr`      | `<el-time-select> * 2`                          |
| 25. |     `eptpr`      | `<el-time-picker is-range>`                     |
| 26. |      `epdp`      | `<el-date-picker>`                              |
| 27. |     `epdpr`      | `<el-date-picker type="daterange,monthrange">`  |
| 28. |     `epdtp`      | `<el-date-picker type="datetime">`              |
| 29. |     `epdtpr`     | `<el-date-picker type="datetimerange">`         |
| 30. |      `epu`       | `<el-upload>`                                   |
| 31. |      `epra`      | `<el-rate>`                                     |
| 32. |      `epcp`      | `<el-color-picker>`                             |
| 33. |      `eptr`      | `<el-transfer>`                                 |
| 34. |      `epf`       | `<el-form>`                                     |
| 35. |      `epfi`      | `<el-form-item>`                                |

#### 数据展示

| No. | Trigger Key | Element Tag         |
| :-: | :---------: | :------------------ |
| 1.  |    `ept`    | `<el-table>`        |
| 2.  |   `eptc`    | `<el-table-column>` |
| 3.  |   `epta`    | `<el-tag>`          |
| 4.  |   `eppr`    | `<el-progress>`     |
| 5.  |  `eptree`   | `<el-tree>`         |
| 6.  |    `epp`    | `<el-pagination>`   |
| 7.  |   `epba`    | `<el-badge>`        |
| 8.  |   `epav`    | `<el-avatar>`       |

#### 反馈组件

| No. | Trigger Key | Element Tag             |
| :-: | :---------: | :---------------------- |
| 1.  |   `epal`    | `<el-alert>`            |
| 2.  |  `eploads`  | `epement-loading-*`     |
| 3.  |   `epme`    | `$app.$message({})`     |
| 4.  |  `epmeal`   | `$app.$alert({})`       |
| 5.  |  `epmecon`  | `$app.$confirm({})`     |
| 6.  |   `epno`    | `$app.$notify({})`      |
| 7.  |   `epnot`   | `$app.$notify.type({})` |
| 7.  |   `epmel`   | `$app.$loading({})`     |

#### 导航

| No. | Trigger Key | Element Tag            |
| :-: | :---------: | :--------------------- |
| 1.  |   `epmen`   | `<el-menu>`            |
| 2.  | `epsubmen`  | `<el-submenu>`         |
| 3.  |  `epmeni`   | `<el-menu-item>`       |
| 4.  |  `eptabs`   | `<el-tabs>`            |
| 5.  |  `eptabp`   | `<el-tab-pane>`        |
| 6.  |   `epbr`    | `<el-breadcrumb>`      |
| 7.  |   `epbri`   | `<el-breadcrumb-item>` |
| 8.  |   `eppa`    | `<el-page-header>`     |
| 9.  |   `epdr`    | `<el-dropdown>`        |
| 10. |   `epdri`   | `<el-dropdown-item>`   |
| 11. |   `epsts`   | `<el-steps>`           |
| 12. |   `epst`    | `<el-step>`            |

#### Others Part

| No. | Trigger Key | Element Tag          |
| :-: | :---------: | :------------------- |
| 1.  |   `epdi`    | `<el-dialog>`        |
| 2.  |   `epto`    | `<el-tooltip>`       |
| 3.  |   `eppo`    | `<el-popover>`       |
| 4.  |  `eppoco`   | `<el-popconfirm>`    |
| 5.  |  `epcard`   | `<el-card>`          |
| 6.  |  `epcaro`   | `<el-carousel>`      |
| 7.  |  `epcaroi`  | `<el-carousel-item>` |
| 8.  |  `epcolla`  | `<el-collapse>`      |
| 9.  | `epcollai`  | `<el-collapse-item>` |
| 10. |   `epti`    | `<el-timeline>`      |
| 11. |   `eptii`   | `<el-timeline-item>` |
| 12. |    `epd`    | `<el-divider>`       |
| 13. |   `epcal`   | `<el-calendar>`      |
| 14. |   `epim`    | `<el-image>`         |
| 15. |  `epback`   | `<el-backtop>`       |
| 16. |  `epinfi`   | `v-infinite-scroll`  |
| 17. |   `epdra`   | `<el-drawer>`        |
