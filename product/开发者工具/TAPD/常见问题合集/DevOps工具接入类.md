### 是否需要完成所有配置环节才能使用 TAPD DevOps 解决方案？
不是的，TAPD DevOps 解决方案支持主流工具集成，您可以根据需要，将业务正在使用的工具接入 TAPD。目前仅持续集成工具必须接入方可使用，其它工具可以根据业务需要灵活决定是否启用。

### TAPD 支持哪些 Jenkins 版本？
TAPD 目前支持集成 Jenkins 2.19 及以上版本。

### 支持哪些类型的 Jenkins 构建项目？
TAPD 支持自由风格、Pipeline 风格的 Jenkins 构建项目，后续将进一步扩展。如果您有相关需求或建议，欢迎与我们交流（support@tapd.cn）。

### 源码与 Jenkins 必须同时关联才能使用么？
源码与 Jenkins 关联可以独立使用，您可以根据业务需要及团队情况选择。如果您希望优化“需求-代码-构建-测试-交付”流程，实现代码提交、构建任务与业务对象的数据同步，建议同时使用。

### 每个 TAPD 项目仅能关联一个 Jenkins 服务么？
不是的，每个 TAPD 项目可以关联多个 Jenkins，每个 Jenkins Job 也可以关联多个 TAPD 项目，您可以根据团队持续集成需要进行添加。

### 如何获取项目 ID？
进入 TAPD 项目 > 持续集成，应用右上角直接复制即可。
