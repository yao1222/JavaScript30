# Day 5 Flex Panel Gallery

流程：
1. 排版左到右一欄
2. 點選各別區塊產生動畫，add class動畫
3. 再次點選回復原狀

操作：
1. 使用flex排列區塊，flex-grow分配區塊，調整置中
    - 第一層：panels
    - 第二層：panel
    - 第三層：p
2. JS動作，第一個讓區塊變大：click & add class
3. JS動作，第二個讓上下排字出現：transitionend(等前一個動畫結束)。

注意事項：
1. transitionend會針對不同事件作觸發，比如包含兩個事件的和三個事件的結束會造成不同結果。所要加入if做判斷看是要偵測哪一個事件。
2. 練習flex的網站[flexbox froggy](https://flexboxfroggy.com/)


