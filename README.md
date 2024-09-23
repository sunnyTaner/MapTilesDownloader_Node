<!--
 * @Author: SunnyTaner
 * @Date: 2024-09-12 11:14:19
 * @LastEditors: SunnyTaner
 * @LastEditTime: 2024-09-23 17:56:03
 * @Description:
-->

# MapTilesDownloader_Node 地图瓦片下载器

#### 背景

MapTilesDownloader 的 node 版本, 页面借用 MapTilesDownloader 项目的，因为原项目下载文件不能控制 gizp 所以自己就写了 node 版本下载作为替代。

#### 介绍

在[node 版本](https://gitee.com/houlaidelu/map-tiles-downloader_node)基础上增加了输入西南角东北角范围，增加了边界数据导入

#### 免责声明

**注意：** 该项目只用于学习交流，由商业用途产生的纠纷概不负责！

**用于地图瓦片下载离线，支持 高德地图瓦片 谷歌地图 Mapbox bingMap OpenStreeMap 自定义瓦片地址 下载**

#### 使用教程 (请替换使用自己的 Mapbox Token！！！)

1.  npm install
2.  node index.js
3.  打开 http://localhost:9100/index.html
4.  请将 /UI/main.js 下的 MapBox 地图 token 全部替换成自己的 （防止滥用我将于近期关闭自己的 token, Mapbox token 为免费注册 请自行注册并替换 ！！！）
5.  保存路径默认在项目目录 out/当前时间戳/ 下

#### 后续计划

1. 导入 GeoJSON 文件下载
2. 全命令行下载（浏览器瓦片过大容易卡死）

#### 截图

![页面截图](https://foruda.gitee.com/images/1666339299101837814/2cf41a75_2258377.png "企业微信截图_16663392713916.png")

#### 原地址

[原始 python 版本](https://github.com/AliFlux/MapTilesDownloader)
[node 版本](https://gitee.com/houlaidelu/map-tiles-downloader_node)
