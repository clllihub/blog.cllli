![](https://cllli.oss-cn-beijing.aliyuncs.com/banner-blog.cllli.webp)
# 站点设置
```
site:
  name: # 左上角显示内容
    class:  text #i_class/text/img
    custom: Cllli #自定义内容 例如：scoicon sco-logo / 王卓Sco / https://p.sondy.top/logo.png
  siteIcon: https://ossoososssn.oss-cn-beijing.aliyuncs.com/files/about-logo.png # 网页icon
  icon: https://ossoososssn.oss-cn-beijing.aliyuncs.com/files/loading.gif # 页脚的icon、加载动画默认的icon
  icp:  # ICP 例如：湘ICP备2023015327号
```

# 导航栏

```
nav:
  #导航栏左侧
  left:
    enable: false
    menu:
        项目:
          cllli:
            icon: https://avatars.githubusercontent.com/u/94744879?v=4
            url: https://github.com/DuoSco/Hexo-Theme-solitude

```
  # 导航栏内容
  ```
  menu:
      文库:
        url: false
        child:
          文章列表:
            url: /archives/
            icon: scoicon sco-folder-fill
          全部分类:
            url: /categories/
            icon: scoicon sco-checkbox-multiple-blank-fill
          全部标签:
            url: /tags/
            icon: scoicon sco-price-tag-fill

            
      友链:
        url: false
        child:
          鱼塘:
            url: /moments/
            icon: scoicon sco-wifi-fill
          友情链接:
            url: /links/
            icon: scoicon sco-group-fill
          宝藏博主:
            url: javascript:travelling()
            icon: scoicon sco-gift-fill
      我的:
        url: false
        child:
          装备:
            url: /equipment/
            icon: scoicon sco-laptop-line
          工具箱:
            url: /tlink/
            icon: scoicon sco-tools-fill
      关于:
        url: false
        child:
          关于本站:
            url: /about/
            icon: scoicon sco-contacts-fill
```

  # 导航栏右侧快捷菜单 (true,false)
```
  right: # @todo 允许用户自定义
    travellings: false      #开往
    random: true           # 随机文章跳转
    console: true          #控制台
```

# 自定义icon
```
icon:
  customicon: //at.alicdn.com/t/c/font_4279509_pff2t0cmwos.css
```

# 首页顶部样式
```
hometop:
  bbtime: false # 即刻顶部是否开启
  banner:
    enable: true   # 是否打开顶部banner
    title: 宁静致远<br>热爱生活 # 左上角显示文字
    url: Happy every day # title下方小字
    # 轮播icon
    icon:
      HTML:
        img: https://ossoososssn.oss-cn-beijing.aliyuncs.com/images/software/icon/vs.png
        color: '#ffffff'
      JS:
        img: https://ossoososssn.oss-cn-beijing.aliyuncs.com/images/software/icon/png/pr.png
        color: '#3c2144'
      Kotlin:
        img: https://ossoososssn.oss-cn-beijing.aliyuncs.com/images/software/icon/png/ps.png
        color: '#0d0e23'
      Docker:
        img: https://npm.elemecdn.com/wleelw-blog-abs@1.0.0/img/icon/docker.png
        color: '#57b6e6'
      Flutter:
        img: https://npm.elemecdn.com/wleelw-blog-abs@1.0.0/img/icon/flutter.png
        color: '#ffffff'
      WebPack:
        img: https://ossoososssn.oss-cn-beijing.aliyuncs.com/images/software/icon/oc.png
        color: '#9d2f2f'
      Git:
        img: https://npm.elemecdn.com/wleelw-blog-abs@1.0.0/img/icon/git.png
        color: '#df5b40'
      VS:
        img: https://npm.elemecdn.com/wleelw-blog-abs@1.0.0/img/icon/vs-logo.svg
        color: '#ffffff'
```
  # 顶部三大分类
```  
  categoryGroup:
    G1:
      name: chatgpt
      icon: iconfont icon-aislogo
      url: https://www.cllli.online/
    G2:
      name: 岁月静好
      icon: iconfont icon-ruanjian
      url: /Gallery/
    G3:
      name: 实用教程
      icon: scoicon sco-book-mark-fill
      url: /tags/教程/
```
  # 右侧置顶列表（在文章的front matter中添加“recommend: true”）
```
  recommendList:
    sup: 置顶 # 左上角显示文字
    title: 实用工具 # 左下角大字
    url: https://blog.cllli.com/tlink/ # 点击跳转链接
    img: https://ossoososssn.oss-cn-beijing.aliyuncs.com/images/software/GettyImages-1136829806-e1667836169987.webp # 显示背景
    color: '#ff0000' # 背景颜色
```
# 侧边栏
```
aside:
  # 值：about（关于我）、power（爱发电）、newestPost（最新文章）、allInfo（网站信息）、flip（公众号二维码）、welcome（个性定位）、history（那年今日）
  home: # 在主页显示的侧边栏信息
    noSticky: "about"
    Sticky: "allInfo"
  post: # 在文章页显示的侧边栏信息
    noSticky: "about"
    Sticky: "newestPost"
  page: # 在页面中显示的侧边栏信息
    noSticky: "about"
    Sticky: "newestPost,allInfo"
   爱发电
  power:
    link: https://afdian.net/a/wleelw0u0
    post: false
    page: false
   侧边栏个人信息卡片
  card:
    author:
      img: https://avatars.githubusercontent.com/u/94744879?v=4 # 头像
      js: https://cdn3.codesign.qq.com/icons/XgRxnjPG4VZLmqr/latest/iconfont.js # 自定义图标js（用于显示带颜色的状态表情）
      state: "#sco-smile" # 状态表情（使用symbol）
    content: 记录分享美好<b>瞬即</b>，对美好生活的<b>向往</b>，对知识海洋<b>探索历程</b>。 # 文案1
    content2: 相信你可以在这里找到对你有用的知识和教程。 # 文案2
    # 个人信息卡片底部的小图标，按照例子填写
    information:
      Github:
        icon: scoicon sco-github-line
        url: https://github.com/clllihub
      Bilibili:
        icon: scoicon sco-bilibili-line
        url: https://space.bilibili.com/295300559
    # 跳转按钮
    button:
      text: 了解更多
      url: /about/
  # 公众号二维码
  flip:
    favicon: # 右下角头像
    face: # 正面
    backface: # 鼠标悬停翻转图片
  # 个性定位
  welcome:
    enable: false
    title: #【选填】留空将默认显示为：来访者
    icon:
    key: # 腾讯key
    longitude: 112.8455033596802 # 经度
    Latitude: 26.430308353457896 # 纬度
  # 那年今日
  history:
    enable: false
    title: #【选填】留空将默认显示为：那年今日
    icon:
  # 页面目录
  toc:
    post: true # 在文章页显示
    page: false # 在任意页显示

  # 建站信息
  siteinfo:
    postcount: true # 文章数
    wordcount: true # 总字数
    pv: true # 访问量
    uv: true # 访客数
    updatetime: true # 最后更新日期
    runtimeenable: true # 建站时间
    runtime: '2020-04-20 00:00:00' # 格式：yyyy-MM-dd hh-mm-ss
```
# Footer Settings
# --------------------------------------
footer:
  # 底部上方一排图标
```  
  information:
    left: # 左侧显示图标
          Github:
            icon: scoicon sco-github-line
            url: https://github.com/clllihub
          Mail:
            icon: scoicon sco-mail-line
            url: 001@cllli.com
    right: # 右侧显示图标
        Bilibili:
          icon: scoicon sco-bilibili-line
          url: https://space.bilibili.com/295300559
        抖音:
          icon: iconfont icon-weibo
          url: https://weibo.com/u/6124296623
```          
  # 底部导航栏
```  
  group: # 从左至右
      导航:
        归档: /archives/
        分类: /categories/
        标签: /tags/
      服务:
        阿里云: https://aliyun.com/
        51la统计: https://v6.51.la/
        百度统计: https://tongji.baidu.com/
      支持:
        打赏记录: /about/
      协议:
        Cookies: /cookies/
        用户协议: /privacy/
        版权协议: /copyright/

  # 底部随机友链
  randomlink: false
  # rss
  rss:
    enable: false
    wechatOA: # 微信公众号链接
    emailOA:  # 邮箱链接
    rss:  # rss订阅链接
  # 版权
  license:
    url: /copyright/
```
# 页面页默认设置
```
page:
  error: true #
  tags: true # 标签
  categories: true # 分类
  default: # 默认值
    cover: /img/default.png # 默认图片
```
# 文章页默认设置
```
post:
  default: 
    cover: /img/default.png
    locate: 大连
    copyright: 原创
```
  # 顶部文章简介
```  
  meta:
    date: true # 发布日期
    updated: true # 更新日期
    locate: true # 位置
    wordcount: true # 字数
    readtime: true # 访问
    pv: true # 浏览量
    comment: true # 评论数
```    
  # 打赏
```  
  award:
    enable: false # 开启后文章底部显示打赏按钮
    wechat:  # 微信收款码
    alipay:  # 支付宝收款码
    url: /about # 打赏统计页面链接
```
  # 文章颜色获取
```
  covercolor: #文章cover取色
    enable: true
    local: true
```
# 关于界面
```
about: true
```
# 404 页面
```
errorpage:
  img: https://npm.elemecdn.com/wzheo-absolute@1.0.3/image/source/404.png
  text: =awa= 糟糕页面走丢了
  recommendList: true # 显示随机文章
```
# 懒加载
```
lazyload:
  enable: false
  placeholder: /img/loading.gif # 加载中显示图片
  errorimg: /img/error_load.png # 加载失败显示图片
```
# 图片灯箱
```
lightbox: true
```
#代码高亮增强
```
hightlight:
  enable: true
  hightlimit: 200
```
# 加载动画
```
loading:
  fullpage: true
  pace: true
```
# 第三方设置
```
thirdparty:
  wordcount: false # 字数统计
  busuanzi:
    enable: false
    usecomment: false #当评论系统开启时文章页面使用评论系统的统计数据
  search: # 搜索
    algolia_search:
      enable: false
      # hits:
      #   per_page: 6
    local_search:
      enable: false
      preload: false
      CDN:

  aplayer: # 播放器
    enable: true
    server: tencent # netease, tencent, kugou, xiami, baidu
    id: 8651639768 # 歌单ID
    api: "https://api.injahow.cn/meting/?server=:server&type=:type&id=:id&auth=:auth&r=:r" #自定义api
  #中控台拓展
  consolePlus: true

  ai: # 文章页面AI
    enable: false
    key: # 前往tianli-AI 购买
    rec_method: # 推荐文章方式（all:匹配数据库所有文章、web:仅当前博客文章）默认：web

  # 朋友圈配置
  circle:
    api: https://circle.sondy.top/  # api 地址
    error_img: /img/theme/avatar.png # 头像加载失败显示错误图片
    sort_rule: created # 排序规则
    expire_days: 1 # 文章缓存天数
    page_init_number: 12 # 默认加载文章数，默认10
    page_turning_number: 12 # 加载更多文章数，默认10
    angle: # 钓鱼
      enable: false
    appjs: '/lib/circle.min.js' # 主题appjs
    bundlejs: '/lib/bundle.min.js' # 主题bundejs

  # 文章统计
  echarts:
    js: https://cdn.bootcdn.net/ajax/libs/echarts/5.4.2/echarts.min.js

# 评论
comment:
  enable: true
  twikoo:
    envId: https://www.ossssnmessage.online/
    lang: 'zh-CN'
    accessToken:  # accessToken

# 插入代码到头部 </head> 之前 和 底部 </body> 之前
# 插入额外代码 如：统计，广告等
extends:
  head: # 在head中插入
  body: # 在body中插入

# 文章底部推荐文章
related_post:
  enable: false
  limit: 1 # 推荐文章数量
  date_type: updated # 根据创建日期（created）或是更新日期（updated）

# rightmenu(右键菜单)

# 站点验证
verify:
  # 百度
  baidu:

# PWA
# https://github.com/JLHwung/hexo-offline
pwa:
  enable: false
  startup_image_enable: false
  manifest: /manifest.json
  theme_color: '#ffffff'
```
# 非必要勿动
```
cdn:
  head:
    snackbarcss: /lib/snackbar.min.css
    scoicon: https://cdn3.codesign.qq.com/icons/7pOrz0WXB5ZWJPX/latest/iconfont.css
    aplayercss: https://cdn.bootcdn.net/ajax/libs/aplayer/1.10.1/APlayer.min.css
    swipercss: https://cdn.bootcdn.net/ajax/libs/Swiper/9.2.4/swiper-bundle.min.css
    twikoojs: https://cdn.bootcdn.net/ajax/libs/twikoo/1.6.20/twikoo.all.min.js
    instantsearch: https://cdn.bootcdn.net/ajax/libs/instantsearch.js/4.9.1/instantsearch.production.min.js
    algolia: https://cdn.bootcdn.net/ajax/libs/algoliasearch/4.9.3/algoliasearch-lite.umd.min.js
    pacejs: https://cdn.bootcdn.net/ajax/libs/pace/1.2.4/pace.min.js

  body:
    viewimagejs: /lib/view-image.min.js
    waterfalljs: /lib/waterfall.min.js
    lazyloadjs: /lib/lazyload.min.js
    snackbarjs: /lib/snackbar.min.js
    swiperjs: https://cdn.bootcdn.net/ajax/libs/Swiper/9.2.4/swiper-bundle.min.js
    busuanzijs: https://cdn.bootcdn.net/ajax/libs/busuanzi/2.3.0/bsz.pure.mini.min.js
    pjaxjs: https://cdn.bootcdn.net/ajax/libs/pjax/0.2.8/pjax.min.js
    aplayerjs: https://cdn.bootcdn.net/ajax/libs/aplayer/1.10.1/APlayer.min.js
    metingjs: https://cdn.bootcdn.net/ajax/libs/meting/2.0.1/Meting.min.js
    katexcss: https://cdn.bootcdn.net/ajax/libs/KaTeX/0.16.6/katex.min.css
    katexjs: https://cdn.bootcdn.net/ajax/libs/KaTeX/0.16.6/katex.min.js
```