[返回](../README.md)

# Ch1 - 第一個 3D 網頁

# 下載

https://code.visualstudio.com

https://www.dropbox.com/s/vb99u8ynvik0mmu/assets.zip?dl=0




----------
# 什麼是 WebVR？

https://webvr.info
https://www.w3.org/TR/webxr/

WebVR是一項實驗性的JavaScript API，可以利用網頁瀏覽器提供虛擬實境體驗。從低進入門檻與開發成本、應用範圍廣泛、無安裝包、易於維護與擴充，到跨平台、隨連隨用等特性，大幅拓展了虛擬實境的應用與發展面向。但因WebVR體驗仰賴於網路瀏覽器與連線速度，目前WebGL在繪圖解析度上還無法勾勒出栩栩如生的視覺效果，對於愛好高解析度與擬真感的觀眾缺乏衝擊力。不過因為只要有可連網的行動裝置就能體驗，並可連接專業VR顯示器，在流通上比起傳統VR更有彈性與親和力。

https://www.youtube.com/watch?v=Jzrqrji_2xk&&feature=emb_logo


[https://youtu.be/Jzrqrji_2xk](https://youtu.be/Jzrqrji_2xk)



## 案例分享
- 音樂
https://look-at-the-sky.com/

https://www.youtube.com/watch?v=RIpob33uUEU&


[https://youtu.be/RIpob33uUEU](https://youtu.be/RIpob33uUEU)


- 展覽
https://artogo.tw/exhibition/freewill/space

https://shutdown.gallery/


https://shutdown.gallery


- 紀錄文件
https://bear71vr.nfb.ca/

https://accessmars.withgoogle.com/

- 創造、體驗
https://massmigrations.com/nocreg

https://portalis.goodboydigital.com/

- 真實場景模擬

https://showroom.littleworkshop.fr

https://showroom.littleworkshop.fr/

- 故事

https://negpoet.tw/esd01.html


- 搭配肢體
https://twitter.com/thirdaxis_xyz/status/1473679160006610955


[https://twitter.com/thirdaxis_xyz/status/1473679160006610955](https://twitter.com/thirdaxis_xyz/status/1473679160006610955)

https://twitter.com/concretescifi/status/1470413615077355520


[https://twitter.com/concretescifi/status/1470413615077355520](https://twitter.com/concretescifi/status/1470413615077355520)


- 其他

https://hubs.mozilla.com/


- 更多
https://experiments.withgoogle.com/collection/webvr

https://aframe.io/showcase/


https://aframe.io/showcase/
https://webxr.world/
https://twitter.com/aframevr


# 什麼是 A-Frame？

A-Frame是一個用於搭建虛擬實境（VR）體驗的開源網路框架，開發者可使用 HTML 來創建 3D 和 WebVR 場景。 HTML 環境為 Web 開發者和設計師提供了一個熟悉的創作工具，同時結合了 Unity 等引擎使用的流行遊戲開發模式。 A-Frame 以 Three.js 為基礎，最初是在 2015 年中後期 Mozilla VR 團隊內部開發的。創建 A-Frame 的目的是為了讓網絡開發者和設計師能夠在不了解 WebGL 的情況下，用 HTML 編寫 3D 和 VR 體驗。

https://aframe.io/

## Three.js

Three.js 是一個 webGL 函式庫，將很多功能包裝成一個物件，讓人能夠在網頁瀏覽器中建立和展示動畫的3D電腦圖形。

https://threejs.org/



## A-Frame 特色（官網）


- **在 HTML 標籤裡宣告：**基於 HTML 語言開發，簡單使用、易於閱讀。
- **跨裝置和各平台：**網頁提供桌機手機的使用，除此之外，還提供跨 Vive、Rift、Daydream、GearVR、Cardboard 設備使用。
- **組建式架構：**雖是以 HTML 標籤訪問，但仍可以使用 JavaScript、DOM APIs、Three.js、WebVR、WebGL 進行額外開發。
- **效能佳：**A-Frame 以 WebVR 為基礎進行優化，當 A-Frame 使用 HTML 時，並不會影響瀏覽器的顯示，所有的 3D 物件全都在記憶體做更新，以及用一個全域 requestAnimationFrame 呼叫下做非常小量的資源消耗。
- **非依賴式工具：**A-Frame 一樣可以跟普通的 JavaScript DOM APIs 和其他框架語言一起使用，不需轉換。
- **可視化的檢查方式：**A-Frame 提供內建的 3D 檢測器，類似瀏覽器開發工具，介面類似 Unity。
- **提供 Registry 資源：**有類似 Unity Asset Store 的蒐集資源庫，可以重用其他 A-Frame 開發人員創建和共享的強大組件。
- **方便的內建和擴充功能：**可以立即使用 A-Frame 內建的幾何體、材質、燈光、動畫、模型、射線、陰影、音頻和其他 Vive / Touch / Cardboard 的控制器，以及其他組建，例如粒子系統、物理學、海洋、山脈、多用戶、語音辨識、遠距操作。


(以上引用自http://test.domojyun.net/MEMO/3D/aframejs.html)


## A-Frame 支援什麼？
https://aframe.io/docs/1.2.0/introduction/vr-headsets-and-webvr-browsers.html


**支援的操作**

- VR on desktop with a headset
- VR on mobile with a headset
- VR on standalone headset
- Flat on desktop (i.e., mouse and keyboard)
- Flat mobile (i.e., magic window)

**支援的 VR 頭戴顯示**

- HTC Vive
- Oculus Rift
- Oculus Quest
- Oculus Go
- Google Daydream
- Samsung GearVR
- Vive Focus


# 編輯器

https://code.visualstudio.com

## 安裝 Extension
- A-Frame Completion

https://marketplace.visualstudio.com/items?itemName=mlueckert.a-frame-completion

- Live Server

https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer

- Path Autocomplete

https://marketplace.visualstudio.com/items?itemName=ionutvmi.path-autocomplete

# 網頁大概念
## What is HTML

HTML 是用來告訴瀏覽器該如何呈現網頁的**標記式語言(*****markup language*****)**。它由一系列的元素（element）組成，你將利用它們來圍住、包裹，或者說標記（*mark up）*網頁中的每個部分，使它們在外表或行為上呈現某種特定風貌。被標籤（tag）包住的內容會變成超連結，或者斜體字，以及諸如此類的功能

    <my-text size="20">Hi, How are you? </my-text>


- Element
- Tag
- Attributes


https://developer.mozilla.org/zh-TW/docs/Learn/HTML/Introduction_to_HTML



## What is Javascript？

JavaScript 是一種腳本，也能稱它為程式語言，可以讓你在網頁中實現出複雜的功能。讓網頁不只呈現靜態的內容，更多了：內容即時更新、地圖交動、繪製 2D/3D 圖形，影片播放控制⋯⋯等各種動作。


https://developer.mozilla.org/zh-TW/docs/Learn/JavaScript/First_steps



# A-Frame 基本介紹

 **👉 動手做**

    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        
        <!--  Todo: Change Title Here    -->
        <title></title>
        
        <!--  Todo: Change Discription Here    -->
        <meta name="description" content="">
        
        <!--  Todo: Add Aframe Src Script    -->
    
      </head>
      <body>
      </body>
    </html>


## 觀察 HTML


1. `<!DOCTYPE html>`: 文件類型(doctype)。 在很久很久以前，當 HTML 還年輕的時候(約莫在西元 1991 年左右)，文件類型是要作為一系列規範的連結，HTML 網頁必須要遵守這些規範才會被當作是好的 HTML，比如說具備自動錯誤檢查和其他有用的東西等。 不過，現在已經沒有人在乎它們了，它們只是個歷史痕跡，需要形式上地被引入，以確保一切正常。`<!DOCTYPE html>` 是字數最短的有效 doctype。你只需要知道這些就夠了。
2. 在那個時候，它們看起來像這樣：
3. `HTML <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">`
4. `<html></html>`: html 元素。該元素包裹住頁面的所有內容，有時也被稱作根元素(root element)。
5. `<head></head>`: head 元素。這個元素放著你想含括的所有重要資訊，這些資訊不會呈現在網頁瀏覽者眼前。這些東西包括，顯示於搜尋結果的關鍵字、頁面說明、CSS 等等。你將會在這個系列的下個章節中學到更多有關這部分的知識。
6. `<meta charset="utf-8">`: 這個元素指定你的文件使用 UTF-8 為字元編碼，這種編碼含有這世上大部分語言的字元，理論上可以處理所有你想放文字內容，因此建議大家都要使用這種編碼，它能幫你免去許多煩惱。
7. `<title></title>`: title 元素。這是用來設定網頁名稱的，它會顯示在分頁標籤上，當你將該網頁加入書籤或加入最愛時，則是用來形容這個網站。
8. `<body></body>`: body 元素含括了*所有*你想要給網頁瀏覽者看到的內容，不管是文字、圖片、遊戲、可以播放的音樂或其他東西。

（上述內容擷取自 https://developer.mozilla.org/zh-TW/docs/Learn/HTML/Introduction_to_HTML/Getting_started）

**註解**
cmd(ctrl) + / 

    <!-- This is a comment -->


 **👉 動手做**
 

1. `<script></script>`: 在瀏覽器中執行 Javascript 程式
2. 在 Head 中加入 Aframe 的 script


    <head> 
      <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
    </head>

參考說明：
https://aframe.io/aframe/dist/

**其他 Element:** 

![HTML Scene](https://user-images.githubusercontent.com/674727/52090525-79b04d80-2566-11e9-993f-7a8b19ca25b1.png)


**單引號 vs 雙引號？**
都可以！


## Entity-Component-System

**Entity**
Entity 代表一個空物件（元素：a-entity），可以把 component 加在上面，讓他長成不同樣子
空物件：

    <a-entity>
    </a-entity> 

將位置（component）加在空物件（entity）上：

    <a-entity position="1 2 3">
    </a-entity>

**Component**
Component 是可以重複利用的模組，能夠被綁定在 entity 上提供外觀、行為等功能。除了 Aframe 內建的 component，也能夠自己撰寫、或使用他人寫好的 component 來使用。

**Primitives**
Primitives 是 Aframe 打包好的一些實用的物件。透過把 Entity 和某些 Component 包裝在一起，讓他人能夠快速使用。


# 場景
## scene

使用元素 `<a-scene>` 替 Aframe 建立基礎場景，所有 WebVR 裡的 entity 都要放在它底下。

    <a-scene>
        .....
    </a-scene> 


- 設定初始的相機、光線
- 設置好 WebVR / XR API
- 加入 Enter VR 的按鈕
https://aframe.io/docs/1.2.0/core/scene.html

## background component

使用 component `background` 設定背景顏色。


    <a-scene background="color: red"> 
    </a-scene>

 💡 background 是 aframe 中的 component，但對 HTML 來說，他就是a-scene 這個 tag 的 attribute 屬性。
 

## Asset Management System

Aframe 提供一個統一管裡 asset（圖片、model、音檔）的地方：

- 預先 loading
- 處理快取，加快效能
- 讓後面的 html 編寫更好讀


    <a-assets>
        <!--這裡放 asset-->  
    </a-assets>

a-assets 裡面放置的元素包括：

- `<a-asset-item>` ： 3D 模型
- `<audio>` ： 聲音檔案
- `<img>` ： 圖片檔案
- `<video>` ： 影片檔案


    <a-scene>
      <!-- Asset management system. -->
      <a-assets>
        <img id="texture" src="texture.png">
      </a-assets>
    
      <!-- Scene. -->
      <a-box src="#texture"></a-box>
    </a-scene>

id 代表元素的名稱（每個元素的 id 不得重複！）
取用的時候，要在前面加上 ＃ 字號。

# 360° 圖片
https://www.dropbox.com/s/vb99u8ynvik0mmu/assets.zip?dl=0

## a-sky

a-sky 也可以設定顏色：

    <a-scene>
      <a-sky color="#6EBAA7"></a-sky>
    </a-scene>

但如果只要設定顏色的話建議用 backgorund componnet

設定圖片：

    <a-scene>
      <a-sky src="sky.jpg"></a-sky>
    </a-scene>


## 360 圖片

盡量選擇 equirectangular 等距長方投影的圖片，背景看起來才會接得好

- https://hdrihaven.com/
- https://www.flickr.com/groups/equirectangular/


# 360° 影片
    <a-videosphere src="video.mp4">
    </a-videosphere>


    <a-assets> 
        <video id="video" autoplay loop="true" src="video.mp4">
        </video>
    </a-assets>
    <a-videosphere src="#video">
    </a-videosphere>


# 發布 - 什麼是 Glitch？

Glitch 是一個給創作者、開發者的協作平台，讓人可以直接在網頁中寫網頁，並立刻發佈！

https://glitch.com/



# 參考
https://aframe.io/docs/1.2.0/introduction/


