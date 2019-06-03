# awesome-tools

> 从 [Blog][1] 迁移到 GitHub 仓库维护，可以有历史记录。

## 翻墙

主 [**google cloud**][2]，备 [**rixcloud**][3]、**阿里云香港**和**公司翻墙**。

- google cloud 免费，一年到期后可无限续，支持 netflix
- rixcloud 到期后可能不续了，有点贵，不过老牌服务商，比较稳定，支持 surge 客户端，当时买这个主要是为了看 netflix，后来 google cloud 支持 netflix 后就没必要再买他了
- 软件方面，Mac 下用 [**ShadowsocksX-NG-R**][4]，iPhone 下用 [**ShadowRocket**][5]（需切美区下载）
- 通过 [**Proxifier**][6] 实现命令行应用或其他应用翻墙，比如 iTerm2 下执行 npm publish 偶尔会被墙，并且实测下来比 `export http_proxy` 快
- 家里的路由器翻墙是用 [**RT-AC88U**][7] + **梅林小宝版固件**
- 电视上看 youtube 和 netflix 可以用 [**Nvidia Shield TV**][8]，我买的美版，据说国版也可刷原生系统

## Mac 软件

用了 [SetApp][9]，包含以下的不少应用，能省不少。

### 编辑器和 Terminal

主 [**Intellij Idea**][10]，辅 [**VSCode**][11] 和 **Vim**。选 Intellij Idea 的原因是无需安装插件就很好用，另外也是没有时间去折腾插件。

- 字体主 [**Dank Mono**][12]，辅 [**Operator Mono**][13]，看厌了一个换另一个
- Intellij Idea 使用 [**material-theme-jetbrains**][14]，Theme 选 Material One Dark，字号 16 号，行距 1.2，[效果图][15]
- Intellij Idea 插件额外装了 **File Watchers**、**GitLink**、**Import Cost**、**Prettier** 和 **Rainbow Brackets**
- Terminal 用 [**iTerm2**][16] + [**zsh**][17] + [**oh-my-zsh**][18] 的组合，主题是 [robbyrussell][19]
- zsh 的插件开了 git、autojump、brew、git、git-extra、git-flow、git-prompt、git-remote-branch、github、gitignore、history、history-substring-search、iterm2、node、npm、npx、nvm、tig、vscode、yarn、[zsh-autosuggestions][20]
- iTerm2 里配 `Run command...` 为 `/usr/local/bin/idea \1` ([图][21])，这样 Command + 点击文件路径，就会在 Intellij Idea 里打开

### 开发辅助

- [**SourceTree**][22]，git 辅助，由于 git 高级操作命令记不住，就只用借助 UI 了
- [**Paw**][23]，请求模拟，前后端联调时我会用这个先走一遍
- [**Github Desktop**][24]，管理 github 仓库的变更和 PR，代替了 SourceTree 的部分工作，可以方便地把别人的 PR checkout 到本地验证
- [**Gas Mask**][25] ，Hosts 管理
- [**ColorSnapper2**][26]，取色工具
- [**Charles**][27]，抓包用，支持 https
- [**Google Chrome**][28] + [**Google Chrome Canary**][29] + [**Firefox**][30] + **Safari**，浏览器，调试用，IE 的测试会借助内网的云测平台

### 输出

- [**Notion**][31]，笔记工具，准备逐渐从 Bear 迁到 Notion
- [**Bear**][32]，笔记工具，颜值高，订阅了 Pro，和手机同步
- [**Typora**][33]，可以基于目录编辑 Markdown，所以 github 仓库的文档都会用他编辑
- [**MultiMarkdown Composer**][34]，单文件的 markdown 编辑
- [**OmniGraffle**][35] + [**iThoughtsX**][36]，分别用于画架构图和和脑图
- [**LICEcap**][37] ，GIF 录屏工具

### 输入

- [**Reeder**][38]，RSS 阅读软件，我的主要信息来源，没有提供 rss 源的我会先在 [**rsshub.app**][39] 上找，再没有就自己写一个 serverless 服务部署在 now@2 上
- [**Kiwi for Gmail**][40]，Gmail 客户端

### 效率

- [**Alfred**][41] + [**Powerpack**][42]，应用启动、粘贴板管理、Workflow、Snippets 管理等
- [**Copied**][43]，粘贴板管理，之前一直用 Alfred 的粘贴板，试用后发现还是得用专业做粘贴板的工具
- [**Thor**][44]，一键直达应用
- [**TaskPaper**][45]，任务管理
- [**OmniFocus**][46] ，任务管理，通过 Omni Sync Server 和 iPhone 同步
- [**Karabiner Element**][47]，用于[把右 Command 和 Capslock 键利用起来][48]，避免快捷键冲突，[简单 note][49]，详见[《我的快捷键技巧》][50]

### vlog 相关

- [**ScreenFlow**][51]，视频录制和剪辑
- [**Final Cut Pro**][52]，视频剪辑
- [**RDM**][53]，分辨率切换，允许设置未支持的分辨率，比如我会在录屏时设置 720p(hd) 的分辨率
- [**KeyCastr**][54]，按键显示

### 其他

- [**CleanMyMac 3**][55]，系统清理
- [**1Password**][56]，密码管理
- [**Bartender 3**][57]，管理系统右上菜单项，隐藏或收起不常用的
- [**KeepingYouAwake**][58]，可保证系统不自动休眠
- [**Softorino YouTube Converter**][59]，YouTube 视频下载
- [**Downie 3**][60]，通用视频下载
- [**Folx 5**][61] + [**qBittorrent**][62] + [**Motrix**][63]，下载工具，Folx 下 http，qBittorrent 下 magnet，Motrix 是 aria2 的封装，可以[下百度云盘、115 等][64]
- [**f.lux**][65]，调节显示器色温，护眼，尤其是早上起来屏幕实在是刺眼
- [**IINA**][66]，视频播放
- [**Perculia**][67] - 蓝牙设备管理
- [**snipaste**][68]，截图工具，需要标注的时候用
- [**Get Plain Text**][69]，自动清除粘贴板内容的格式
- [**RunCat**][70] - 菜单栏显示奔跑的小猫，CPU 占用率越高跑地越快
- [**钉钉**][71] + [**QQ**][72] + [**微信**][73] + [**Telegram**][74] + [**Slack**][75]，通讯交流
- [**Tuxera NTFS**][76] - 支持 NTFS 格式
- [**Yoink**][77] - 临时文件存放处

### 命令行

#### 通过 [homebrew][78] 安装

- [**autojump**][79]，目录跳转
- [**the\_silver\_searcher**][80]，文件搜索，命令行是 ag
- [**hub**][81] - git 扩展
- [**tig**][82] - git 扩展
- [**bat**][83]，带行号的 cat，可以配 `alias cat="bat"`
- [**fd**][84]，比系统自带的 find 友好

#### 通过 `yarn global add` 安装

- [**projj**][85]，github/gitlab 项目管理
- [**serve**][86]，本地静态服务器
- [**fkill**][87]，比 kill 好用的进程 killer
- [**qrcode-terminal**][88]，二维码生成

### Chrome 插件

#### Github 相关

- [**OctoLinker**][89]，根据 require/import 或 package.json 中的 dependencies 进行快速跳转
- [**Refined Github**][90]，Github 改进
- [**npmhub**][91]，在 README 下方显示 npm 依赖信息
- [**Hide Files on GitHub**][92]，隐藏配置文件等非必要文件
- [**Github Hovercard**][93]，比如不用点进去就能看到 issue 详情
- [**Git History Browser Extension**][94]，可视化的方式显示文件修改历史
- [**File Icon for GitHub, GitLab and Bitbucket**][95]，更好看的文件 icon
- [**octotree**][96]，显示文件树形目录

#### 其他

- [**Workona**][97]，tab 管理，基于使用场景
- [**JSON Formatter**][98]，让 JSON 更易读
- [**Better History**][99]，搜索历史记录用
- [**Tampermonkey**][100]，油猴，通过脚本定制网页
- [**uBlock Origin**][101]，广告 Block
- [**Netflix Rating**][102]，在 netflix 上显示每个影片的 IMDB 的评分信息
- [**Select like a boss**][103]，可以选择链接里的内容
- [**Lingocloud Interpreter**][104]，全文翻译
- [**Video Speed Controller**][105]，在视频上显示按钮可控制播放速度

## iPhone 软件

### 每天用

- **支付宝**
- **微信**
- **Chrome**，代替 Safari，好处是可以和电脑同步
- **Gmail**
- **Reeder**，我是 RSS 重度用户
- **钉钉**，工作交流
- **Shadowrocket**，你懂的，需切换美区安装
- **Twitter**，感觉官方客户端够用了
- **Workflow**，最常用的一个 workflow 是 clipboard to instapaper，用于把微信文章经由 instapaper 保存到 github issue
- **网易云音乐**
- **OmniFocus**，任务管理

更多 https://github.com/sorrycc/ama/issues/12

## 在线服务

#### 免费

- [**refiddle**][106] + [**regex101**][107]，调正则表达式
- [**30 seconds of code**][108]，代码片段
- [**astexplorer**][109]，调 ast
- [**globtester**][110]，调 glob
- [**ghub.io**][111]，redirect to an npm package's repository page
- [**unpkg**][112]，npm 包的 cdn 服务，可以查看 npm 包发布后的内容
- [**sketchboard**][113] + [**draw.io**][114] + [**MindMeister**][115]，在线画流程图
- [**HackMD**][116]，在线笔记，有 PPT 展示功能
- [**Slides**][117]，PPT 制作
- [**CodeSandbox**][118] + [**glitch**][119] + [**repl.it**][120]，在线代码编辑，前者支持 sandbox container，可以跑 npm scripts
- [**node.green**][121]，查询 NodeJS 的 ES2018 特性支持情况
- [**Can I use**][122]，查询浏览器的特性支持情况
- [**carbon**][123]，根据源码生成图片
- [**Tell me when it closes**][124]，github issue 关闭时发送邮件通知
- [**Package Diff**][125]，比较 npm 包两个版本直接的区别
- [**Firefox Send**][126] + [**ffsend**][127]，文件分享服务
- [**Cloud Convert**][128]，支持 218 种格式相互转换
- （beta）[**Webpack config tool**][129]，webpack 配置工具

#### 付费

- [**Oreilly Safari Books**][130]，Oreilly 图书、视频教程、newsletter 等，看地比较少，到期了不准备续费了
- [**Frontend Masters**][131]，视频教程
- [**Zeit Now**][132]，serverless 服务，域名等
- [**name.com**][133]，域名服务，之后会转到 Zeit Now 上
- [**少数派 Power+ 2.0**][134]，提效相关文章
- [**网易云音乐**][135]
- **百度云盘** + **115 网盘** + [**麦果网盘中转**][136]，资料下载
- **爱奇艺** + **腾讯视频** + **优酷**，会员去广告
- [**Netflix**][137]
- [**Youtube Premium**][138]，主要为了 iPhone 上切换应用或锁屏后能继续播放

## 硬件

#### 电脑

- **MacBook Pro 15-inch, Mid 2015**，公司配的，256 G 不太够用，自己买了个 [**SDCZ43 128G U 盘**][139] 一直插着做扩展
- [**神舟战神 Z7-KP7S1**][140]，可以玩一些要求不太高的 PC 游戏

#### 电脑配件

显示器、键盘、鼠标都 x2，保证公司和家里的体验一致。

- [**U28E590D**][141]x2，三星显示器，应该是 4K 中最便宜的了
- (**HHKB Pro 2 无刻** + [彩色键帽][142])x2
- [**Razer DeathAdder Chroma**][143]x2

#### 家庭网络

- J1900 软路由 + UBNT 交换机 + （UBNT AP & [**华硕 RT-AC88U**][144]）

#### 手机

- [**iPhoneX**][145]

#### 耳机

- [**Bose QC30**][146]，公司环境有点吵，降噪耳机必备

#### 相机

- [**FUJIFILM X100T**][147]
- [**GoPro Hero7 Black**][148]

## 相关

- [awesome-f2e-libs][149] - 我关注的前端库。
- [旧版本的装了啥][150]

[1]:	https://github.com/sorrycc/blog/issues/83
[2]:	https://cloud.google.com/
[3]:	https://home.rixcloud.me/aff.php?aff=1432
[4]:	https://github.com/qinyuhang/ShadowsocksX-NG-R/releases
[5]:	https://itunes.apple.com/us/app/shadowrocket/id932747118?mt=8
[6]:	https://www.proxifier.com/
[7]:	https://www.asus.com/us/Networking/RT-AC88U/
[8]:	https://www.nvidia.com/en-us/shield/
[9]:	https://go.setapp.com/invite/sorrycc
[10]:	https://www.jetbrains.com/idea/
[11]:	https://code.visualstudio.com/
[12]:	https://dank.sh/
[13]:	http://www.typography.com/fonts/operator/overview/
[14]:	https://github.com/ChrisRM/material-theme-jetbrains
[15]:	https://gw.alipayobjects.com/zos/rmsportal/JKRPNvvHhPgFonHHXvPe.png
[16]:	https://www.iterm2.com/
[17]:	https://en.wikipedia.org/wiki/Z_shell
[18]:	https://github.com/robbyrussell/oh-my-zsh
[19]:	https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme
[20]:	https://github.com/zsh-users/zsh-autosuggestions
[21]:	https://zos.alipayobjects.com/rmsportal/RmWdxKRQUWFMoVDjerNQ.png
[22]:	https://www.sourcetreeapp.com/
[23]:	https://paw.cloud/
[24]:	https://github.com/desktop/desktop
[25]:	https://github.com/2ndalpha/gasmask
[26]:	https://colorsnapper.com/
[27]:	https://www.charlesproxy.com/
[28]:	https://www.google.com/chrome/
[29]:	https://www.google.com/chrome/canary/
[30]:	https://www.mozilla.org/en-US/firefox/new/
[31]:	https://www.notion.so/?r=159be429981b4725ad6f36c4f599bd98
[32]:	http://www.bear-writer.com/
[33]:	https://typora.io/
[34]:	https://multimarkdown.com/
[35]:	https://www.omnigroup.com/omnigraffle
[36]:	https://www.toketaware.com/ithoughts-osx
[37]:	http://www.cockos.com/licecap/
[38]:	http://reederapp.com/mac/
[39]:	https://docs.rsshub.app/
[40]:	http://kiwiforgmail.com/
[41]:	https://www.alfredapp.com/
[42]:	https://www.alfredapp.com/powerpack/
[43]:	https://copiedapp.com/
[44]:	https://github.com/gbammc/Thor
[45]:	https://www.taskpaper.com/
[46]:	https://www.omnigroup.com/omnifocus
[47]:	https://pqrs.org/osx/karabiner/
[48]:	http://lucifr.com/2013/02/16/caps-lock-to-hyper-key/
[49]:	https://hackmd.io/s/rk4u9i-pG
[50]:	https://www.bilibili.com/video/av44127555
[51]:	http://www.telestream.net/screenflow/overview.htm
[52]:	https://www.apple.com/final-cut-pro/
[53]:	https://github.com/avibrazil/RDM
[54]:	https://github.com/keycastr/keycastr
[55]:	https://macpaw.com/cleanmymac
[56]:	https://1password.com/
[57]:	https://www.macbartender.com/
[58]:	https://github.com/newmarcel/KeepingYouAwake
[59]:	https://softorino.com/youtube-converter
[60]:	http://software.charliemonroe.net/downie.php
[61]:	https://mac.eltima.com/download-manager.html
[62]:	https://www.qbittorrent.org/
[63]:	https://motrix.app/
[64]:	https://www.yuque.com/moapp/help/extensions
[65]:	https://justgetflux.com
[66]:	https://github.com/iina/iina
[67]:	https://itunes.apple.com/cn/app/perculia/id1462633284?mt=12
[68]:	https://www.snipaste.com/
[69]:	https://zipzapmac.com/GetPlainText
[70]:	https://itunes.apple.com/nz/app/runcat/id1429033973?mt=12&ref=appinn
[71]:	https://tms.dingtalk.com/markets/dingtalk/download
[72]:	https://im.qq.com/macqq/
[73]:	https://mac.weixin.qq.com/
[74]:	https://macos.telegram.org/
[75]:	https://slack.com/downloads/mac
[76]:	https://www.tuxera.com/products/tuxera-ntfs-for-mac/
[77]:	https://eternalstorms.at/yoink/
[78]:	https://brew.sh/
[79]:	https://github.com/wting/autojump
[80]:	https://github.com/ggreer/the_silver_searcher
[81]:	https://hub.github.com/
[82]:	https://github.com/jonas/tig
[83]:	https://github.com/sharkdp/bat
[84]:	https://github.com/sharkdp/fd
[85]:	https://github.com/popomore/projj
[86]:	https://github.com/zeit/serve
[87]:	https://github.com/sindresorhus/fkill
[88]:	https://github.com/gtanner/qrcode-terminal
[89]:	https://github.com/OctoLinker/browser-extension
[90]:	https://github.com/sindresorhus/refined-github
[91]:	https://github.com/npmhub/npmhub
[92]:	https://github.com/sindresorhus/hide-files-on-github
[93]:	https://github.com/Justineo/github-hovercard
[94]:	https://chrome.google.com/webstore/detail/git-history-browser-exten/laghnmifffncfonaoffcndocllegejnf
[95]:	https://chrome.google.com/webstore/detail/file-icon-for-github-gitl/ficfmibkjjnpogdcfhfokmihanoldbfe
[96]:	https://github.com/ovity/octotree
[97]:	https://workona.com/
[98]:	https://github.com/callumlocke/json-formatter
[99]:	https://chrome.google.com/webstore/detail/chrome-better-history/aadbaagbanfijdnflkhepgjmhlpppbad?hl=en
[100]:	https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo
[101]:	https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm
[102]:	https://chrome.google.com/webstore/detail/imdb-ratings-for-netflix/dnbpnlalaijjbogmjbpdkdcohoibjcmp/related?hl=en
[103]:	https://chrome.google.com/webstore/detail/select-like-a-boss/mnbiiidkialopoakajjpeghipbpljffi/related?hl=en
[104]:	https://chrome.google.com/webstore/detail/lingocloud-interpreter/jmpepeebcbihafjjadogphmbgiffiajh/related
[105]:	https://chrome.google.com/webstore/detail/video-speed-controller/nffaoalbilbmmfgbnbgppjihopabppdk/related?hl=en
[106]:	http://refiddle.com/
[107]:	https://regex101.com/
[108]:	https://30secondsofcode.org/
[109]:	https://astexplorer.net/
[110]:	http://www.globtester.com/
[111]:	http://ghub.io/
[112]:	https://unpkg.com/
[113]:	https://sketchboard.me/
[114]:	https://www.draw.io/
[115]:	https://www.mindmeister.com/
[116]:	https://hackmd.io/recent
[117]:	https://slides.com/
[118]:	https://codesandbox.io/
[119]:	https://glitch.com/
[120]:	https://repl.it/
[121]:	https://node.green/
[122]:	https://caniuse.com/
[123]:	https://carbon.now.sh/
[124]:	https://tellmewhenitcloses.com
[125]:	https://diff.intrinsic.com/
[126]:	https://send.firefox.com/
[127]:	https://github.com/timvisee/ffsend
[128]:	https://cloudconvert.com/
[129]:	https://webpack.jakoblind.no/
[130]:	https://www.safaribooksonline.com/
[131]:	https://frontendmasters.com/
[132]:	https://zeit.co/now
[133]:	https://www.name.com/
[134]:	https://sspai.com/series/70
[135]:	https://music.163.com/
[136]:	https://www.maiguopan.com/
[137]:	https://www.netflix.com
[138]:	https://www.youtube.com/
[139]:	https://www.sandisk.co.uk/home/usb-flash/ultra-fit-usb
[140]:	https://detail.tmall.com/item.htm?id=543437409299&skuId=3434337259021
[141]:	https://detail.tmall.com/item.htm?id=523282229383
[142]:	https://item.taobao.com/item.htm?id=522721338431&_u=41h6urte838
[143]:	http://www.razerzone.com/store/razer-deathadder-chroma
[144]:	https://item.jd.com/2104499.html
[145]:	https://www.apple.com/iphone-x/
[146]:	https://www.bose.com/en_us/products/headphones/earphones/quietcontrol-30.html
[147]:	https://www.fujifilmusa.com/products/digital_cameras/x/fujifilm_x100t/
[148]:	https://zh.shop.gopro.com/China/cameras/hero7-black/CHDHX-701-master.html
[149]:	https://github.com/sorrycc/awesome-f2e-libs
[150]:	https://github.com/sorrycc/blog/issues/16