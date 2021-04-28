1. 常用软件.md 文件里面包含了各个平台的翻墙软件，大部分是免费的，有些是付费的

2. proxy.md 文件里面以Windows平台V2rayN软件为例，展示了怎么配置环境

------

3. 订阅地址链接`https://jiang.netlify.com`,此订阅地址更新不要翻墙，建议每隔一段时间更新一次，订阅里面不是每一个节点都是可用的，可以自己尝试看哪个节点有效

***

**2021.4.10更新**

1. V2rayN软件演示的时候版本是3.xxx，目前已经更新到4.xxx，在4.xxx版本里面路由配置方面有了很大的改动，详细配置见[v2ray官方文档](https://www.v2fly.org/)，这个网址需要fq，也可以查看[V2rayN软件项目issues界面](https://github.com/2dust/v2rayN/issues)获取帮助

2. 在最近的使用过程中发现订阅地址链接`https://jiang.netlify.com`虽然可以更新，但是基本上所有节点都是不可用的，为此提供了新的订阅地址

   |           类型           |                            地址                            |
   | :----------------------: | :--------------------------------------------------------: |
   |       SSR节点订阅        | `https://raw.githubusercontent.com/freefq/free/master/ssr` |
   | v2ray(ss/trojan)节点订阅 | `https://raw.githubusercontent.com/freefq/free/master/v2`  |

   **新版订阅地址，上面订阅地址还是可用的，下面这两个订阅地址的信息和上面两个是一样的，只不过下面这两个订阅地址更新的时候不需要fq**

   |           类型           |                            地址                            |
   | :----------------------: | :--------------------------------------------------------: |
   |       SSR节点订阅        | `https://raw.githubusercontent.com/freefq/free/master/ssr` |
   | v2ray(ss/trojan)节点订阅 | `https://raw.githubusercontent.com/freefq/free/master/v2`  |

   **在此感谢[freefq项目](https://github.com/freefq/free)提供的订阅地址**，但是注意上面这两个订阅更新的时候都是需要fq的，因为国内墙住了`raw.githubusercontent.com`地址。这里的墙主要是通过DNS污染实现的，所以你可以通过一些[工具网站](https://www.ipaddress.com/)查询此域名的真正ip地址，然后在系统的`hosts文件`里面进行配置；还有一个简单的方法，就是设置系统代理为全局代理，更新完订阅之后再回到以前的代理模式。**在V2rayN软件里面即使你设置了`raw.githubusercontent.com`走代理，实际上在更新订阅的时候也没有走代理**，所以还是需要用到上面两种方法更新订阅。

3. 如果平时使用的要求不是太高，也可以使用**Sandbox**的方式，[链接地址](https://cdn.apkook.com/)