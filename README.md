# dagbymurongqimiao

> a profile use to draw DAG

## Build Setup

npm i    ->     npm  run dev 

###  
基于SVG的DAG(单向无环图)前端实现.分享给有类似需求的前端研发同学.

本项目为公司内部PAI需求,
参考了国内外其他公司的DAG实现,

较粗糙,愿抛砖引玉.
更多内容欢迎+wechat讨论, murongqimiao

==================================================================

目录结构
    (文件内有详细注解)

    ------------
    |
    ---src
    |
    ------components
    |
    ----------STEP
    |
    ---------------STEP1
    |                   绘制节点
    ---------------STEP2
    |                   绘制节点的连线
    ---------------STEP3
    |                   绘制节点拖动的模拟框
    ---------------STEP4
    |                   绘制节点拖动连线的模拟框
    ---------------STEP5
    |                   组件抽离
    ---------------


==================================================================

需要实现的内容:
1. 图. 节点. 连线 的展示
2. 节点的增删, 位置变动 ( 开放右键功能
3. 连线的增删 ( 需开放右键功能
