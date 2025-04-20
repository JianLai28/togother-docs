# 导入视频源

"一起看"应用支持添加自定义CMS视频源，本文档提供了一些推荐的视频源配置，您可以直接复制添加到应用中。

## 什么是CMS视频源

CMS视频源是基于苹果CMS API格式的资源站点，可以通过API接口获取视频资源列表和播放地址。添加这些视频源可以丰富您的观影选择。

## 如何导入视频源

1. 打开"一起看"应用
2. 点击"资源"页面
4. 点击右上角按钮
5. 输入以下提供的视频源信息
6. 点击"保存"完成添加

## 推荐视频源列表

以下是一些经过测试可用的视频源列表，您可以根据需要选择导入：

```json
[
  {
    "name": "豆瓣",
    "url": "https://caiji.dbzy5.com/api.php/provide/vod/from/dbm3u8/at/josn/",
    "enabled": true,
 
    "use_proxy": true
  },
  {
    "name": "B",
    "url": "https://json02.heimuer.xyz/api.php/provide/vod/",
    "enabled": true,
 
    "use_proxy": true
  },
  {
    "name": "量子",
    "url": "https://cj.lziapi.com/api.php/provide/vod/from/lzm3u8/",
    "enabled": true,
 
    "use_proxy": true
  },
  {
    "name": "极速",
    "url": "https://jszyapi.com/api.php/provide/vod/from/jsm3u8/at/json",
    "enabled": true,
    "use_proxy": true
  },
  {
    "name": "暴风",
    "url": "https://bfzyapi.com/api.php/provide/vod/",
    "enabled": true,
    "use_proxy": true
  },
  {
    "name": "量子2",
    "url": "https://cj.lziapi.com/api.php/provide/vod/from/lzm3u8/at/json",
    "enabled": true,
    "use_proxy": true
  },
  {
    "name": "最大",
    "url": "https://api.zuidapi.com/api.php/provide/vod/from/zuidam3u8/",
    "enabled": true,
    "use_proxy": true
  },
  {
    "name": "非凡",
    "url": "http://cj.ffzyapi.com/api.php/provide/vod/at/json/",
    "enabled": true,
    "use_proxy": true
  },
  {
    "name": "360",
    "url": "https://360zy.com/api.php/provide/vod",
    "enabled": true,
    "use_proxy": true
  },
  {
    "name": "四圈",
    "url": "https://pg.fenwe078.cf/api.php/provide/vod/",
    "enabled": true,
    "use_proxy": true
  },
  {
    "name": "ikun",
    "url": "https://ikunzyapi.com/api.php/provide/vod/",
    "enabled": true,
    "use_proxy": false
  },
  {
    "name": "卧龙",
    "url": "https://collect.wolongzyw.com/api.php/provide/vod/at/json",
    "enabled": true,
    "use_proxy": true
  },
  {
    "name": "天空",
    "url": "http://api.tiankongapi.com/api.php/provide/vod/at/json",
    "enabled": true,
    "use_proxy": true
  },
  {
    "name": "无尽",
    "url": "https://api.wujinapi.me/api.php/provide/vod/from/wjm3u8/at/json/",
    "enabled": true,
    "use_proxy": true
  },
 
  {
    "name": "速播",
    "url": "https://subocaiji.com/api.php/provide/vod/at/json",
    "enabled": true,
    "use_proxy": true
  }
  
]
```

## 参数说明

视频源配置中的各参数含义如下：

| 参数 | 说明 |
|------|------|
| name | 视频源名称，用于在应用中显示 |
| url | 视频源API地址，必须是有效的苹果CMS API地址 |
| enabled | 是否启用该视频源，true表示启用，false表示禁用 |
| preview_count | 预览数量，搜索结果中预览显示的条目数 |
| use_proxy | 是否使用代理访问，部分资源站需要代理才能正常访问 |

## 注意事项

1. 视频源的可用性可能会随时变化，如遇到无法使用的情况，可以尝试更换其他视频源
2. 添加过多视频源可能会影响应用性能，建议只添加您常用的几个视频源
3. 使用视频源时请遵守相关法律法规，尊重知识产权
4. 本应用不存储任何视频内容，所有内容均来自第三方资源站

!!! warning "免责声明"
    以上列出的视频源仅作参考，其可用性和内容质量可能随时变化。我们不对这些第三方资源的内容负责，使用时请自行判断内容的合法性和安全性。


<div style="text-align: center; padding: 10px; margin: 10px 0; background-color: #f5f5f5; border-radius: 5px;">
  <script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>
  <span id="busuanzi_container_site_pv" style="font-size: 14px; color: #666;">
    本页总访问量 <span id="busuanzi_value_site_pv" style="font-weight: bold; color: #1976D2;"></span> 次
  </span>
</div>

