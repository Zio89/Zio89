Skip to content
Navigation Menu
WusThanhDieu
/
Template-Profile-Card

Type / to search
Code
Issues
Pull requests
Actions
Projects
Security
Insights
Commit
first commit
 main
ThanhDieuTV committed on Nov 8, 2022 
0 parents
commit c4875c9
 
Showing 5 changed files with 409 additions and 0 deletions.
Filter changed files
 Binary file addedBIN +543 KB 
Css-Javascript/ThanhDieu-Template.png
Loading
 344 changes: 344 additions & 0 deletions344  
Css-Javascript/home.css
Copied!
Original file line number	Diff line number	Diff line change
@@ -0,0 +1,344 @@
body {
    margin: 0;
    padding: 0;
    background-color: #292929;
}
#particles-js canvas {
    display: block;
    vertical-align: bottom;
    -webkit-transform: scale(1);
    -ms-transform: scale(1);
    transform: scale(1);
    opacity: 1;
    -webkit-transition: opacity .8s ease, -webkit-transform 1.4s ease;
    transition: opacity .8s ease, transform 1.4s ease
}

#particles-js {
    width: 100%;
    height: 100%;
    position: fixed;
    z-index: 0;
    top: 0;
    left: 0
}

.flex {
    display: flex;
}

.flex-both-center {
    display: flex;
    justify-content: center;
    align-items: center;
}

.flex-wrap {
    flex-wrap: wrap;
}

.flex-h-center {
    display: flex;
    justify-content: center;
}

.flex-dir-c {
    flex-direction: column;
}

.mt-8 {
    margin-top: 12px;
}

.mt-16 {
    margin-top: 16px;
}

.mt-24 {
    margin-top: 24px;
}

.mt-32 {
    margin-top: 32px;
}

.mt-36 {
    margin-top: 48px;
}

.m-auto {
    margin: auto;
}

.ml-6 {
    margin-left: 6px;
}

.ln-h-22 {
    line-height: 22px;
}

.text-fs-16 {
    font-size: 16px;
}
.Blob { 



}
.page-overlay {
    background: rgba(0, 0, 0, 0.1);
    -webkit-backdrop-filter: blur(45px);
    backdrop-filter: blur(45px);
    z-index: 100;
}

.page-image, .page-overlay {
    position: fixed;
    left: 0;
    top: 0;
    width: 100vw;
    height: 100vh;
}

.display-image, .page-image {
    -o-object-fit: cover;
    object-fit: cover;
}

.display-image {
    width: 96px;
    height: 96px;
    display: block;
    border-radius: 50%;
}

.text-center {
    text-align: center;
}

.page-title {
    margin-bottom: 0;
}

.page-bioline {
    font-weight: 500;
}

.page-full-wrap {
    width: 680px;
    z-index: 10;
}

.page-item-wrap {
    transition: transform 0.15s cubic-bezier(0.17, 0.67, 0.29, 2.71) 0s;
}

.page-item-wrap:hover {
    transform: translateZ(0) scale(1.015);
}

.page-item {
    box-sizing: border-box;
}

.page-social {
    display: block;
    margin: 0 12px 12px;
}

.page-social svg {
    width: 28px;
    height: 28px;
}

.relative {
    position: relative;
}

.link-each-image {
    width: 43px;
    height: 43px;
    position: absolute;
    left: 9px;
    -o-object-fit: cover;
    object-fit: cover;
}

.page-logo {
    position: absolute;
    bottom: 32px;
    left: calc(50% - 15px);
}

.rounded-md {
    border-radius: 8px;
}

.close-embed {
    width: 25px;
    height: 25px;
    border-radius: 50%;
    background: #fff;
    opacity: 0.7;
}

.embed-wrap {
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
}

.close-embed:hover {
    opacity: 1;
}

.cursor-pointer {
    cursor: pointer;
}

.page-item-each {
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    text-decoration: none;
    overflow: hidden;
    z-index: 10;
}

.social-icon-fill:hover {
    transition: all 0.1s ease-in-out;
    transform: scale(1.1);
}

.page-item-title {
    font-weight: 700;
    margin-bottom: 16px;
}

@media (max-width: 768px) {
    .page-full-wrap {
        width: 80%;
    }
}

.page-bg {
    background: #292929;
}

.page-title {
    font-size: 18px;
    font-weight: 700;
}

.page-bioline {
    font-size: 16px;
    font-weight: 500;
}

.page-item-title {
    font-size: 16px;
    font-weight: 700;
}

.page-item-each {
    color: #ffffff;
    font-family: "Inter", sans-serif;
    font-size: 16px;
    font-weight: 400;
    border-radius: 8px;
}

.page-item {
    border: 0px solid transparent;
    background: #3a3a3d;
    border-radius: 8px;
    box-shadow: 0px 6px 14px -6px rgba(24, 39, 75, 0.12), 0px 10px 32px -4px rgba(24, 39, 75, 0.1), inset 0px 0px 2px 1px rgba(255, 255, 255, 0.05);
    height: 60px;
    margin-top: 16px;
}

.link-each-image, .embed-wrap iframe, .page-item-wrap {
    border-radius: 8px;
}

.page-text-font {
    font-family: "Inter", sans-serif;
}

.page-text-color {
    color: #ffffff;
}

.social-icon-fill path, .social-icon-fill circle, .social-icon-fill rect {
    fill: white;
}

.glow-on-hover {
    width: 150px;
    height: 50px;
    border: none;
    outline: none;
    color: #fff;
    background: #111;
    cursor: pointer;
    position: relative;
    z-index: 0;
    border-radius: 10px;
text-shadow: 2px 2px blue;

}

.glow-on-hover:before {
    content: '';

    background: linear-gradient(45deg, #ff0000, #ff7300, #fffb00, #48ff00, #00ffd5, #002bff, #7a00ff, #ff00c8, #ff0000);
    position: absolute;
    top: -2px;
    left:-2px;
    background-size: 400%;
    z-index: -1;
    filter: blur(5px);
    width: calc(100% + 4px);
    height: calc(100% + 4px);
    animation: glowing 20s linear infinite;
    opacity: 0;
    transition: opacity .3s ease-in-out;
    border-radius: 10px;

}

.glow-on-hover:active {
    color: #000
}

.glow-on-hover:active:after {
    background: transparent;
}

.glow-on-hover:hover:before {
    opacity: 1;

}

.glow-on-hover:after {
    z-index: -1;
    content: '';
    position: absolute;
    width: 100%;
    height: 100%;
    background: #111;
    left: 0;
    top: 0;
    border-radius: 10px;

}

@keyframes glowing {
    0% { background-position: 0 0; }
    50% { background-position: 400% 0; }
    100% { background-position: 0 0; }
}
 3 changes: 3 additions & 0 deletions3  
Css-Javascript/p.js
Large diffs are not rendered by default.

 62 changes: 62 additions & 0 deletions62  
index.html
Original file line number	Diff line number	Diff line change
@@ -0,0 +1,62 @@
<!DOCTYPE html>
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>ThanhDieu-Template</title>
<link href="./Css-Javascript/css2" rel="stylesheet">
<link rel="shortcut icon" href="https://kenh14cdn.com/thumb_w/660/203336854389633024/2022/5/23/photo-1-1653312456997323551040.jpg" type="image/png">
<link rel="preconnect" href="https://fonts.gstatic.com/">
<link rel="stylesheet" href="./Css-Javascript/home.css">
<div id="particles-js"><canvas class="particles-js-canvas-el" width="1108" height="1586" style="width: 100%; height: 100%;"></canvas></div>
<div class="min-h-full flex-h-center page-bg" id="background_div">
<div class="background-overlay"></div>
<div class="mt-36 page-full-wrap relative">
<img class="display-image m-auto" src="./Css-Javascript/ThanhDieu-Template.png" >
<body>


<h2 class="page-title page-text-color page-text-font mt-16 text-center">ThanhDieuDev <img src="https://tanamedia.vn/wp-content/uploads/2021/09/unnamed-1.png"  width="17" height="17" alpha="_ThanhDieu_"></h2>
<div class="page-bioline text-fs-16 page-text-color page-text-font mt-8 ln-h-22 text-center">I'm a full stack web developer!</div>
<div class="flex-both-center flex-wrap mt-16">
	<audio id="myAudio">
  <source src="music.ogg" type="audio/ogg">
  <source src="music.mp3" type="audio/mpeg">
</audio>
<button class="glow-on-hover" onclick="playAudio()" type="button">Play Music </button>&nbsp;&nbsp;
<button class="glow-on-hover" onclick="pauseAudio()" type="button">Stop Music</button> 
</div>
<div class="mt-32">
<div class="page-item-wrap relative">
<div class="page-item flex-both-center relative"></div>
<a rel="noopener nofollow" class="page-item-each flex-both-center" href="https://github.com/WusThanhDieu" target="_blank">Github</a>
</div>
<div class="page-item-wrap relative">
<div class="page-item flex-both-center relative"></div>
<a rel="noopener nofollow" class="page-item-each flex-both-center" href="https://www.facebook.com/WusThanhDieu" target="_blank">Facebook</a>
</div>
<div class="page-item-wrap relative">
<div class="page-item flex-both-center relative"></div>
<a rel="noopener nofollow" class="page-item-each flex-both-center" href="https://t.me/WusThanhDieu" target="_blank">Telegram</a>
</div>
<div class="page-item-wrap relative">
<div class="page-item flex-both-center relative"></div>
<a rel="noopener nofollow" class="page-item-each flex-both-center" href="https://www.youtube.com/channel/UCl8jHh-5Nkmj__EYy4XUAgQ" target="_blank">Youtube</a>
</div>
<div class="text-center">
<br>
<p style="font-size: 14px; color: gray; font-family: Arial;">© 2022 Template Free</p>
</div>
</div>
</div>
</div>
<script>
var x = document.getElementById("myAudio"); 

function playAudio() { 
  x.play(); 
} 

function pauseAudio() { 
  x.pause(); 
} 
</script>
<script type="text/javascript" src="./Css-Javascript/p.js"></script>
</body><div class="troywell-avia"></div><div class="troywell-caa"></div></html>
 Binary file addedBIN +2.39 MB 
music.mp3
Binary file not shown.
0 comments on commit c4875c9
@ziodaubuoi
Comment
 
Leave a comment
 
Loading
Footer
© 2024 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact
Manage cookies
Do not share my personal information
Copied!
