# Jar4Halo
`Halo博客`的Java构建, 为有使用jar部署的用户提供最新的jar构建
同步halo的release日志

每日从([halo]([https://github.com/halo-dev/halo/tree/main](https://github.com/halo-dev/halo)))的最新release中构建, 包含Prerelease. 

使用H2数据库更新至2.11.0-rc1版本时, 由于H2依赖更新, 需要导出数据然后再重新导入.

## 构建方式
使用Github Actions 自动构建jar包, 并上传release
