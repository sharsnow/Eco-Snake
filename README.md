- [系統架構與實作](#系統架構與實作)
  - [系統簡介](#系統簡介)
  - [系統架構](#系統架構)
  - [開發工具](#開發工具)
- [教育特色](#教育特色)
- [遊戲特色](#遊戲特色)
- [關卡設計](#關卡設計)
- [網頁demo](#網頁demo)
- [電腦Window PC(完整版)) (#電腦Window PC完整版)
## 系統架構與實作

### 檔案內容
可將此內容直接拉進 **Asset**資料夾並移除 AttachFiles  
AttachFiles 內含有zip檔可直接下載遊玩

### 系統簡介

本系統名為 **Eco-Snake**，是一款透過遊戲化學習方式進行環境教育的數位學習平台。靈感源自經典貪食蛇遊戲，並在原有玩法上進行大幅度改編，加入環保主題。玩家在不同的場景中操作貪食蛇收集垃圾，學習垃圾分類、回收知識及環境保護觀念。
![play](AttachFiles/img/play.png)

### 系統架構

Eco-Snake 運用貪食蛇經典操作機制，設計關卡讓學習者於城市、海灘與工廠等情境中進行垃圾收集與分類，提升其對環境議題的認識與實踐能力。

### 開發工具

- **開發平台**：Unity3D 2022.3.42f1  
- **程式語言**：C#  
- **視覺設計**：Canva  
- **資料儲存**：使用 JSON 檔案儲存進度  
- **執行平台**：Windows PC  

---

## 教育特色

- 教導玩家正確的垃圾分類方法，強化回收概念。
- 認識垃圾對環境造成的危害，如海洋污染與城市污染。
- 培養決策判斷力與環保意識。
- 透過互動與即時反饋，提高環保責任感。

---

## 遊戲特色

- 三種環境場景：城市（基礎）、海灘（隨機漂浮與沉沒）、工廠（煙霧障礙）。
- 即時回饋機制：正確分類加分、錯誤扣分。
- 資訊查詢功能：可查詢垃圾分類資訊。
- 客製化功能：可更換貪食蛇造型與外觀。
- 獎章系統：激勵玩家蒐集與重複遊玩。
![badgeSystem](AttachFiles/img/badgeSystem.png)
![selectSnake](AttachFiles/img/selectSnake.png)
---

## 關卡設計

- 每次遊戲時限為 **2 分鐘**，需在時間內累積 **20 分**才可進入下一關。
- 收集**可回收物品**可加分並使蛇身變長。
- 收集**不可回收物品**會扣分並使蛇身變短。
- 海灘關卡加入**上下浮動垃圾**設計。
- 工廠關卡新增**煙霧障礙物**，若碰觸將結束遊戲。
![SpecialPlay](AttachFiles/img/SpecialGamePlay-1.png)
![SpecialPlay](AttachFiles/img/SpecialGamePlay-2.png)

###  網頁版demo
- link
https://eco-snake.vercel.app/

## 電腦Window PC完整版
- link
https://drive.google.com/file/d/1kx2TjZPnvDombMUjUlY7eLfW9kGWxdIz/view?usp=sharing

