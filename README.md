# Jar4Halo

或许是经常在群里发jar构建, 使John Niang重新添加jar支持; Halo从 [2.12.0-alpha.1](https://github.com/halo-dev/halo/releases/tag/v2.12.0-alpha.1) 开始重新提供jar构建, 此项目已无必要.





`Halo博客`的Java构建, 为有使用jar部署的用户提供最新的jar构建
同步halo的release日志

每日从([halo]([https://github.com/halo-dev/halo/tree/main](https://github.com/halo-dev/halo)))的最新release中构建, 包含Prerelease. 

使用H2数据库更新至2.11.0-rc1版本时, 由于H2依赖更新, 需要导出数据然后再重新导入.

## 构建方式
使用Github Actions 自动构建jar包, 并上传release
