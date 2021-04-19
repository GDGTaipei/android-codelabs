author: GDG Taipei - 
summary: 
id: jetpack-compose-basics
categories: android
environments: android studio
status: Published
feedback link: https://github.com/GDGTaipei/android-codelabs/issues
analytics account: 

# Jetpack Compose 基礎知識
## 開始之前的說明
Duration: 0:01:00

[Jetpack Compose](https://developer.android.com/jetpack/compose) 是一套設計用來簡化使用者介面開發的現代化工具包，其結合了反應式程式設計模型與簡明易用的 Kotlin 程式語言。它完全是宣告式的，意即您可以藉由使用一系列將資料轉換為 UI 階層架構的函式來描述您的使用者介面。當底層資料更改時，框架會自動重新使用這些函式，從而為您更新 View 的層次架構。

Compose 應用程式由可組合函式所組成，其中的函式只是帶有 `@Composable` 標記且可以呼叫其他可組合函式的常規函式。創建新的 UI 元件只需要一個函式。該標記告訴 Compose 為該功能添加特殊支援，以隨著時間的推移來更新和維護您的使用者介面。透過 Compose，您可以將程式碼分成小區塊。可組合函式通常簡稱為「可組合物 (Composables)」。

透過編寫可重複使用的小型組合物，您可以輕鬆建構應用程式中使用的 UI 元件函式庫。每個組合物都負責螢幕的一部分，並且可以單獨進行編輯。

Positive
: 注意：在本 codelab 中，「UI 元件」、「可組合函式」及「可組合物」等術語可交互使用以代表同一概念。

### 先決條件
* 有使用 Kotlin 語法的經驗，包含 lambdas

### 您的任務
在此 codelab 中，您會學到：
* 什麼是 Compose
* 如何使用 Compose 來建構使用者介面
* 如何在可組合函式中管理狀態
* Compose 中的資料流處理規則

### 您會需要
* [Android Studio 最新的 Canary 版本](https://developer.android.com/studio/preview)

Positive
: 注意：Jetpack Compose 還在功能預覽階段，而且對 Compose 的支援僅在 Android Studio 的 Canary 版中提供。

## 開始一個新的 Compose 專案
Duration: 0:02:00

## 開始使用 Compose
Duration: 0:03:00

## 宣告式使用者介面
Duration: 0:08:00

## Compose 中的 State 狀態
Duration: 0:11:00

## 彈性版型設計
Duration: 0:09:00

## 讓你的列表動起來
Duration: 0:05:00

## 設定 App 的佈景主題
Duration: 0:08:00

## 恭喜！
Duration: 0:01:00