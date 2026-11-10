# mogu-plugins

mogu.cc.cd 插件库实际使用的修改版 Loon 插件。

- 原版（上游镜像）在 [Aswoth/QuGuangGao](https://github.com/Aswoth/QuGuangGao) 的 `lpx/` 目录，本仓库不改动那边任何文件。
- 本仓库 `lpx/` 里是站上改过的版本：已把广告平台拦截器 / HTTPDNS拦截器 / 可莉广告过滤器中对应家族的内容按 App 所属公司合并进各插件（独立 App 合并通用部分），同 App 的重复插件也已按功能去重合并。
- mogu.cc.cd 的 `/lpx/` 导入会优先取本仓库的文件，本仓库没有的回退到 QuGuangGao 原版。
- 另外收录上游不在 QuGuangGao 的新插件（如红果短剧广告拦截，源自 Tartarus2014/Loon-Script），原样收录、未改动。
