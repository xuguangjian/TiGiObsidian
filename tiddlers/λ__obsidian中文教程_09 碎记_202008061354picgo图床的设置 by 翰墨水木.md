根据[[202008061350阿里云oss搭建图床 by 落山鸡|λ:/obsidian中文教程/09 碎记/202008061350阿里云oss搭建图床 by 落山鸡]]的建议，[[picgo|λ:/obsidian中文教程/01 2021新教程/picgo]]可以支持阿里云。by[[翰墨水木|λ:/obsidian中文教程/07 信息源与贡献者/翰墨水木]]
[img [202008271231.png]]
[img [202008271232.png]]
```
{
  "picBed": {
    "uploader": "aliyun",
    "aliyun": {
    "accessKeyId": "你的配置",
    "accessKeySecret": "你的配置",
    "bucket": "你的配置", // 存储空间名
    "area": "你的阿里云区域", // 存储区域代号
    "path": "img/", // 自定义存储路径
     "customUrl": "", // 自定义域名，注意要加 http://或者 https://
     "options": "" // 针对图片的一些后缀处理参数 PicGo 2.2.0+ PicGo-Core 1.4.0+
    }
  },
  "picgoPlugins": {}
}
```
具体可以再参考https://picgo.github.io/PicGo-Doc/zh/guide/config.html#%E9%98%BF%E9%87%8C%E4%BA%91oss

[[如何插入代码块|λ:/obsidian中文教程/03 教程/如何插入代码块]]