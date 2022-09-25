# 🫶 当前仓库的作用

主要存放一些自己编写的油猴脚本，用于解决一些使用场景上的问题。

# 👻 当前功能

**1.《掘金小册暗黑主题》**

脚本文件：juejin.js

> 主要解决掘金没有暗黑主题的功能，用于一些无光环境下看掘金小册
<br>

<img src="https://guitar-1305021979.cos.ap-guangzhou.myqcloud.com/uPic/Gynz9m.png" />

# 🥽 如何调试

1. 克隆当前仓库代码

2. 安装油猴谷歌插件

3. 打开油猴插件管理面板

4. 点击新增脚本

5. 进入谷歌插件管理点击油猴插件详情在设置里面打开允许访问本地文件

6. 回到油猴插件刚刚新增出来的脚本页面

7. 在头顶的注释里面写上以下的第一行代码

```js 
// @require file//这里填克隆项目下来的本地地址

// 例子： // @require file:///User/power/test_code/custom-tampermonkey/juejin.js
```

⚠️ 注意：头部的那些注释是油猴脚本的特殊的配置文件的地方，比如脚本如果有 GM_XXX 类似的方法使用那么你也要在你的新增的脚本这里添加 `// @grant   GM_addStyle` 这种代码。然后你要影响到的网站 `// @match  https://juejin.cn/book/*`。