# Android Studio
## Android Studio 安裝教學及基本建立專案流程
### 複製後面網址，直接下載Android Studio 並點擊安裝。(https://developer.android.com/studio/)
* 基本安裝過程極為容易，沒什麼困難點，一直點Next即可安裝完畢，安裝路徑也可以修改為自己想自定義的安裝路徑，在看自己是否在桌面建立捷徑等等，安裝完成後，接著開始安裝Android SDK，基本點選Standard 再點Next 即可安裝完畢，接著會來到基本頁面，可以直接建立專案，點擊Start a new Android Studio project，即可準備開始建立自己第一個App囉！  
![](https://github.com/sheng19960125/Base-AndroidStudio/blob/master/android_studio_set_type.png)  
* 設定基本專案部分，會有幾項供使用者填寫，填寫內容類別如下：  
    * Application name：你的APP名稱  
    * Company Domain  ：公司或你自己的 domain 名稱，用來辨識這個APP的所有者是誰。  
    * Package name    ：專案的 Java 套件名稱，預設為Company Domain加Application nam組合，也可以點擊右方Edit修改自己喜歡的名稱。  
    * Project location：專案的儲存位置，建議可以建立一個專門存放APP專案的資料夾。  
    
* 接著會要求選擇Minimum API levels，基本我是選擇版本23(此版本是沒有權限問題，基本調用沒太多限制)，但隨著隱私崛起目前我都推薦使用版本26，在26版本後要調用例如：相機、GPS、資料夾的新增或是獲取、提示等等，都需要額外寫讓使用者同意的選擇框才能調用，點選Finish即可完成最基本的APP架設。  
  
## Android Studio 項目結構
* 在默認情況下，Android Studio會在Android項目視圖中顯示您的項目文件，如下圖所示。此視圖由模塊組織，以便快速訪問項目的關鍵源文件。  
  
* 所有構建文件都在Gradle Scripts下的頂層可見，每個app模塊包含以下文件夾：  
   * 清單：包含AndroidManifest.xml文件。  
   * java：包含Java源代碼文件及測試代碼。  
   * res：包含所有非代碼資源，例如XML佈局，UI字符串和圖像。  
  
* 磁盤上的Android項目結構與此展平表示形式不同。要查看項目的實際文件結構，請從Project下拉列表中選擇 Project，如下圖。  
  
* 您還可以自定義項目文件的視圖，以專注於應用程序開發的特定方面。  
