# Day1 JavaScript Drum Kit

#### 操作流程：
1. 偵測到對應的鍵盤按鈕按下去的動作
2. 觸發播放音樂事件
3. 觸發CSS變化事件
4. 結束CSS變化事件

#### Note:

##### 1. what's the `window` ?

要了解JavaScript如何針對一個新的瀏覽器做操作，則需要了解一個新的觀念 – BOM(Browser Object Model) – BOM允許JavaScript能與瀏覽器做溝通（操控瀏覽器和得知瀏覽器裡的資訊）。
Window指的就是瀏覽器下的Window。假使當我們在Chrome瀏覽器開啟一個window的物件(在console區打上window)，會發現跟瀏覽器有關的所有資訊都會繼承在這個window的物件下，而這個Window物件可以支援所有的瀏覽器使用： `console.log(window)`

[w3school window](https://www.w3schools.com/js/js_window.asp)

##### 2. getElement* or querySelector* ?
getElement* 為動態; querySelect* 為靜態。若沒有要考慮IE8相容問題就用querySelector*
所為靜態就是指當初他取得多少個就是多少個，除非你再取一次。

[中文解釋](https://www.zhihu.com/question/24702250) / [英文解釋](https://javascript.info/searching-elements-dom)

##### 3. nodeList?

NodeList 會經由 `querySelectorAll()`,`childNodes` 產生
HTMLCollection 會經由 `getElementsByTagName()`,`children` 產生

這兩種皆為類陣列,無法使用陣列型別的method,但仍可使用索引存取內容

NodeList 為 Browser API，Array 則為 JS API
`querySelectorAll()`,`getElementsByTagName` 也為Browser API
因此其他的語言亦可使用,如Python

[it邦](https://ithelp.ithome.com.tw/articles/10211876) / [MDN](https://developer.mozilla.org/en-US/docs/Web/API/NodeList)

##### 4. Template String(ES6)

[MDN](https://developer.mozilla.org/zh-TW/docs/Web/JavaScript/Reference/Template_literals)

##### 5. < kbd >

HTML Keyboard Input element (< kbd >)

[MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/kbd)


