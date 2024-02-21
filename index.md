<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>App Introduction</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f2f2f2; /* 设置整个页面的背景颜色 */
    }
    .container {
        padding: 0 20px; /* 在左右两侧添加20像素的边距 */
    }
    .header {
        background-color: #f2f2f2;
        text-align: center;
        padding: 20px 0;
    }
    .screenshot { width: 300px; }
    .download-buttons {
        margin-top: 10px; /* 添加间距 */
    }
    .app-info {
        margin-bottom: 20px;
    }
/*    .app-info img {
        width: 100px;
        height: 100px;
        border-radius: 50%;
    }*/
    .screenshots {
        background-color: #f2f2f2;
        overflow-x: auto;
        white-space: nowrap;
        margin-bottom: 20px;
        width: 90%; /* 设置宽度为80% */
        margin: 0 auto; /* 水平居中 */
    }
    .screenshot {
        display: inline-block;
        margin-right: 10px;
    }
    .description {
        padding: 20px;
        background-color: #f2f2f2; /* 设置详细介绍区域的背景颜色 */
    }
    .footer {
        color: #000;
        text-align: left;
        padding: 20px 0;
    }
</style>
</head>
<body>

<!-- 上半部分：App信息 -->
<div class="header">
    <div class="app-info">
        <img src="https://pipyoutube.github.io/icon.webp" alt="App Icon" width="100" height="100">
        <h1>Float Tube</h1>
        <p>Floating Windows Play YoutTube Video & Music</p>
        <a href="https://apps.apple.com/us/app/id6474012067" target="_blank"><img src="https://pipyoutube.github.io/ios-download.webp" alt="iOS Download" width="120" height="38"></a>
        <a href="https://play.google.com/store/apps/details?id=com.k.video.tube" target="_blank"><img src="https://pipyoutube.github.io/android-download.webp" alt="Android Download" width="120" height="38"></a>
    </div>
</div>

<!-- 中部：截图滑动区域 -->
<div class="screenshots">
    <img class="screenshot" src="https://pipyoutube.github.io/3.webp" alt="Screenshot 1" >
    <img class="screenshot" src="https://pipyoutube.github.io/2.webp" alt="Screenshot 2" >
    <img class="screenshot" src="https://pipyoutube.github.io/1.webp" alt="Screenshot 3" >
    <img class="screenshot" src="https://pipyoutube.github.io/4.webp" alt="Screenshot 4" >
</div>

<!-- 下半部分：App详细介绍 -->
<div class="description">
    <h2>App Description</h2>
    <p>Float Tube is an app that can help you watch YouTube videos through Floating Window. With it, you can watch Tube videos while browsing the web and other things, completely free your phone.</p>
    <p>With a lot of features:</p>
    <!-- 添加更多详细介绍 -->
	<p>- Floating Play tube video and music</p>
	<p>- Free to used and you can limit ad playtimes</p>
	<p>- Move and resize the floating window player</p>
	<p>- Recommend your favorite videos based on playback history</p>
	<p>- Well design to optimize your viewing experience</p>
</div>

<footer class="footer">
    <div >
        <ul >
            <li><a href="https://pipyoutube.github.io/PrivacyPolicy.html" target="_blank">Privacy</a></li>
            <br>
            <li><a href="https://pipyoutube.github.io/EULA.html" target="_blank">EULA</a></li>
        </ul>
    </div>
</footer>
</body>
</html>
