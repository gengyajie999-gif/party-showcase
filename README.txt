使用说明（加载优化版）：
1. 直接双击 index.html 可本地预览。
2. 第二模块“砺剑”新增了三类路径：
   - 本地图片路径：
     images/li/li_1_thumb.webp
     images/li/li_1_full.webp
     images/li/li_2_thumb.webp
     images/li/li_2_full.webp
     images/li/li_3_thumb.webp
     images/li/li_3_full.webp
   - 本地文字文件路径：
     data/li/li_1_intro.txt
   - 本地音乐路径：
     audio/li/mokuai2.mp3
   - 本地视频路径：
     videos/li/li_demo.mp4
3. 加载优化措施：
   - 首页使用纯渐变背景，避免首屏大图加载
   - 图片墙使用 webp 压缩图，并开启 loading="lazy"
   - 第二模块视频采用“点击后再加载”
   - 音频 preload="none"
如果想让第一、三、四、五模块也接入本地图片/音乐/文字，按同样路径结构扩展即可。
