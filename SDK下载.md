<style>
    .card-container {
        width: 350px;
        display: block;
        float: left;
        padding-left: 15px;
        padding-right: 15px;
        box-sizing: border-box;
    }

    .card {
        border-radius: 10px;
        padding-top: 10px;
        padding-left: 10px;
        padding-right: 10px;
        padding-bottom: 10px;
        margin-top: 30px;
        border: 1px solid #ebeef5;
        background-color: #fff;
        overflow: hidden;
        box-shadow: 0 2px 12px 0 rgb(0 0 0 / 10%);
        text-align: center;
    }

    .markdown-text-box img {
        box-shadow: none;
    }


    .titlename {
                color:#191919;
        position: relative;
        top: -2px;
                font-weight: bolder;
                font-size: larger;
    }
        
        @media (max-width: 768px){
                .card-container,
                .scene-card-container{
                        width: 100%;
                }
                .scene-card > div{
                        width: 100%!important;
                        margin-left: 0!important;
                }
                img {
        box-shadow: none;
    }
        }
</style>

## 下载 SDK
实时音视频（TRTC） 是腾讯云提供的一套低延时、高质量的音视频通讯服务，致力于为腾讯云客户提供稳定、可靠和低成本的音视频传输能力。该服务由一套遍布全球的音视频传输网络和一组终端 SDK 组成，您可以在本页面下载到涵盖目前主流客户端平台和热门框架的 TRTC SDK（音视频通话 SDK）。

### Web SDK

<div style="position: relative; box-sizing: border-box;  padding-bottom: 10px; margin-bottom: 10px; overflow:hidden">
  <div class="card-container">
      <div class="card">
        <img src="https://main.qcloudimg.com/raw/7e2651085e3e3c6e32190e401a6dfd32.svg" data-nonescope="true">
        <p class="titlename">Web 播放器 SDK</p>
        <p style="color:#586376;">可用于直播播放和点播播放，适用于PC端浏览器和移动端浏览器。</p>
        <a onclick="reportEvent({name: 'download-click-web', ext1: 'zip'})" target="_blank" href="https://web.sdk.qcloud.com/player/tcplayer/release/v4.5.2/release.zip">ZIP 下载</a>
        <a style="margin-left: 10px;" onclick="reportEvent({name: 'download-click-web', ext1: 'github'})" target="_blank" href="https://cloud.tencent.com/document/product/881/30818">集成指引</a>
        <a style="margin-left: 10px;" onclick="reportEvent({name: 'download-click-web', ext1: 'doc-sdk'})" target="_blank" href="https://tcplayer.vcube.tencent.com">Demo示例</a>
      </div>
  </div>
</div>

### iOS & Android SDK

<div style="position: relative; box-sizing: border-box;  padding-bottom: 10px; margin-bottom: 10px; overflow:hidden">
        <div class="card-container">
            <div class="card">
                            <img src="https://main.qcloudimg.com/raw/b0211b0870806899009a17a4216ea65c.svg" data-nonescope="true">
                                <p class="titlename">精简版（TRTC）SDK</p>
                <p style="color:#586376;">包含 TRTC 和直播播放（TXLivePlayer）两项功能，SDK 体积小巧，功能稳定。</p>
                                <a href="https://liteav.sdk.qcloud.com/download/latest/TXLiteAVSDK_TRTC_Android_latest.zip">ZIP 下载</a>
                <a style="margin-left: 10px;" href="https://github.com/LiteAVSDK/TRTC_Android">GitHub</a>
                                <a style="margin-left: 10px;" href="https://cloud.tencent.com/document/product/647/32175">集成指引</a>
                                <a style="margin-left: 10px;" href="https://cloud.tencent.com/document/product/647/32166">运行 Demo</a>
            </div>
        </div>
			  <div class="card-container">
            <div class="card">
                                <img class="icon" src="https://main.qcloudimg.com/raw/613f2e15bed7c8297110676b52784b71.svg" data-nonescope="true">
                                <p class="titlename">精简版（TRTC）SDK</p>
                <p style="color:#586376;">包含 TRTC 和直播播放（TXLivePlayer）两项功能，SDK 体积小巧，功能稳定。</p>
                                <a href="https://liteav.sdk.qcloud.com/download/latest/TXLiteAVSDK_TRTC_iOS_latest.zip">ZIP 下载</a>
                <a style="margin-left: 10px;" href="https://github.com/LiteAVSDK/TRTC_iOS">GitHub</a>
                                <a style="margin-left: 10px;" href="https://cloud.tencent.com/document/product/647/32173">集成指引</a>
                                <a style="margin-left: 10px;" href="https://cloud.tencent.com/document/product/647/32396">运行 Demo</a>
            </div>
        </div>
</div>


### 跨平台 SDK

<div style="position: relative; box-sizing: border-box;  padding-bottom: 10px; margin-bottom: 10px; overflow:hidden">
        <div class="card-container">
            <div class="card">
									<img src="https://qcloudimg.tencent-cloud.cn/raw/3b6929f89ce1113bc2005873f2338de9.png" data-nonescope="true"/>
									<p class="titlename">Flutter SDK</p>
                <p style="color:#586376;">基于 Flutter 框架封装的 TRTC SDK，让您用一套代码快速构建出能够运行于各平台的 App。</p>
								<a href="https://pub.dev/packages/tencent_trtc_cloud/versions">ZIP 下载</a>
                <a style="margin-left: 10px;" href="https://github.com/c1avie/trtc_demo">GitHub</a>
								<a style="margin-left: 10px;" href="https://cloud.tencent.com/document/product/647/51602">集成指引</a>
								<a style="margin-left: 10px;" href="https://cloud.tencent.com/document/product/647/51601">运行 Demo</a>
            </div>
        </div>
</div>



## SDK 能力清单
