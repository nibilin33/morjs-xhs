# morjs-plugin-compiler-xhs
morjs compiler plugin for xiaohongshu miniprogram
morjs 插件, 用于支持编译小红书小程序

# 安装
```js
npm install morjs-plugin-compiler-xhs
```
# 使用方式
```js
import { setCompilerPlugins, getAllCompilerPlugins } from '@morjs/cli'
import * as PluginXHS from 'morjs-plugin-compiler-xhs'
const allCompilerTargets:any = getAllCompilerPlugins()
setCompilerPlugins([...allCompilerTargets,PluginXHS])
```

# vant 组件转换效果
![image](./assets/vant-xhs.png)