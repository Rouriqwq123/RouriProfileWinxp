========================================
  Rouri's Desktop - 使用说明
========================================

【文件夹结构】
Rouri_Desktop/
├── index.html          ← 主网页，双击打开
├── README.txt          ← 本说明文件
├── music/              ← 把你的音乐放这里
│   ├── 你的歌曲.mp3
│   ├── 你的歌曲.flac
│   └── ...（支持 mp3, flac, ogg, wav, m4a）
└── images/             ← 把封面图片放这里
    ├── bg.jpg          ← 桌面背景图（可替换）
    ├── 封面1.jpg
    └── ...（支持 jpg, png, webp, gif）

【如何添加歌曲】
1. 把音乐文件复制到 music/ 文件夹
2. 把封面图片复制到 images/ 文件夹
3. 打开 index.html，编辑其中的 TRACKS 列表（有注释指引）
4. 刷新浏览器即可

【图片与歌曲配对】
在 index.html 的 TRACKS 里，每首歌可以指定封面：
  { name: "歌名", src: "music/歌曲.mp3", art: "images/封面.jpg" }

【浏览器建议】
- Firefox：直接双击 index.html 打开即可 ✅
- Chrome/Edge：需要用本地服务器，或安装插件 "Web Server for Chrome"
  也可以用命令行：python3 -m http.server 8080
  然后访问 http://localhost:8080

========================================
