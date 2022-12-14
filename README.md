<p align="center">
  <a href="https://v2.nonebot.dev/"><img src="https://v2.nonebot.dev/logo.png" width="200" height="200" alt="nonebot"></a>
</p>

<div align="center">
  
# Nonebot_Plugin_RePixivSearcher
  
_✨ 基于OneBot适配器的[NoneBot2](https://v2.nonebot.dev/)从Pixiv爬图的插件 ✨_
  
</div>

## 目前支持的功能

- 搜索标签
- 随机图

## 安装

- 源码
- 使用pip

```
pip install nonebot_plugin_RePixivSearcher
```

# 帮助  
(需要在命令前添加命令前缀)  
搜 + 任意tag ——> 搜索此tag下的所有图，有可能没有此图  
random ——> 随机一张图(压缩)  
画师 + ID(必须是纯数字) ——> 搜索画师信息  
(需要在群里@机器人才能使用的指令,依然需要命令前缀)  
login ——> 登录Pixivic(不登陆也行，但是图库量没这么大)  
## 注意
登陆之前请先修改account.json里的内容（开启机器人会自动生成在/data/PixivSearcher/内)

# 更新日志：  
2022/10/29 新增搜索画师功能，添加了一个新的接口用来构建转发信息，详见MessageSegment_.py，可以用于其他地方  
  
2022/10/6 新增Pixivic接口API，但是需要手动设置account.json登录
