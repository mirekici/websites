# Google Play 購買問題

整個購買過程都發生在 Google Play 中，**應用程式的開發人員無法控制它**，因此所有這些解決方案都是經驗之談。

### 多賬號問題

如果你登入了多個賬號，Play 商店可能會使用錯誤的賬號。開發人員無法控制。通常使用購買時的賬號重新安裝即可解決。

### 使用欺騙程式

諸如「L**** Patcher」之類的欺騙程式會劫持應用程式與 Play 商店之間的連線，最終導致錯誤。

### Code 7

購買記錄儲存在 Play 商店的快取中。Code 7 意味著記錄丟失了。

通常，清除 Play 商店的快取可以解決該問題。

### Code 3

當前 Google 賬號所在的地區不支援購買。請參閱 [Google 的幫助頁面](https://support.google.com/googleplay/android-developer/table/3541286)。

請自行搜尋如何確認（改變）賬號區域。記住，地區與你的網路環境無關。

### Code 6

購買是一個應用程式與 Play 商店互動的過程。許多定製系統預設啟用一些限制導致該過程受阻。比如，MIUI 需要為 Play 商店允許「在背景顯示界面」權限。