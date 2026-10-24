# 居家养老系统(Elderly Home Care System)

软件工程课程综合实践项目。面向居家养老场景,为老人提供一键紧急呼救、健康数据监测、上门服务预约等服务,为家属提供远程看护能力,为护工提供接单平台。

## 目录结构

```
docs/
└── 实验四-需求分析/
    ├── 01-软件利益相关方与初步需求分析表.md   # 利益相关方、需求清单、优先级
    ├── 02-软件需求UML模型集.md               # UML 模型说明与一致性检查
    ├── 03-软件需求规格说明书.md               # SRS(功能/非功能/外部接口)
    ├── 04-需求评审记录.md                     # 内部评审记录
    └── uml/                                   # PlantUML 源码(可渲染为图片)
        ├── 用例图.puml
        ├── 顺序图-紧急呼救.puml
        ├── 顺序图-服务预约.puml
        ├── 分析类图.puml
        └── 状态图-服务订单.puml
```

## UML 图渲染

1. 在线:打开 <https://www.plantuml.com/plantuml/uml/>,粘贴 `.puml` 文件内容即可生成图片;
2. IDEA:安装 *PlantUML Integration* 插件,直接打开 `.puml` 文件预览导出;
3. VSCode:安装 *PlantUML* 扩展,`Alt+D` 预览。

## 技术栈(规划)

- 后端:Java 17 + Spring Boot 3 + MySQL 8 + Redis
- 客户端:Android 9.0+ / iOS 13.0+
- 管理端:Web(Vue 3)
