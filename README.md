# Privacy Policy — BookmarkMemo（書籤備忘錄）

**Last updated:** 2026-09-24  
**Developer:** bookmarkmemo  
**Product:** BookmarkMemo / 書籤備忘錄 (Chrome Extension)  
**Contact:** https://github.com/bookmarkmemo/privacy-policy/issues  

This file is a local backup of the public privacy policy.  
Public URL (GitHub Pages): https://bookmarkmemo.github.io/privacy-policy/

---

## 1. Summary

BookmarkMemo (書籤備忘錄) helps you browse Chrome bookmarks with optional guide images, text notes, and on-page screenshot annotations.

- We do **not** operate a backend server that collects your bookmarks or notes.
- Data created by the extension is stored in **your browser** (Chrome storage) on your device.
- Optional “Buy me a coffee” opens a third-party site only when **you** click the link; it is voluntary support and does **not** unlock Pro.
- Optional **Pro** (one-time) unlocks full local backup export/import. Checkout and license activation use **Polar**.
- Chrome Web Store: https://chromewebstore.google.com/detail/bookmarkmemo/dmihfdbbcdkmaejgdmgjejihnjgjhmde

---

## 2. Information we access

### 2.1 Chrome bookmarks
With your permission, the extension reads your bookmark titles, URLs, and folder structure to show them in the panel and match the current page. With Pro import, it may also create missing bookmarks you choose to restore.

### 2.2 Tabs and browsing context
The extension may read the active tab URL and navigation-related events so it can:
- highlight the current / sticky bookmark;
- show or hide the floating panel;
- open a bookmark in the current tab when you click it in the panel.

### 2.3 Web page content (content script)
On `http://` and `https://` pages, a content script may run to display the floating UI and, if you start capture mode, to help annotate a screenshot of the visible tab.

### 2.4 Screenshots (only when you use the feature)
If you use “Capture & annotate”, the extension may capture the **visible area of the current tab** and store the resulting image (and your annotations) in Chrome local storage on your device, associated with a bookmark URL you choose.

### 2.5 Favicons
The extension may request site favicons through Chrome’s favicon facility to display icons next to bookmarks.

### 2.6 Settings and user content you create
Stored locally (examples):
- custom guide images you import;
- text notes you write;
- panel open/closed preference;
- docked vs fixed sidebar mode;
- panel width;
- per-tab “sticky” bookmark selection (session storage);
- Pro license key cache and validation timestamps (if you activate Pro).

### 2.7 Pro license (optional)
If you buy Pro and activate a license key, the extension sends the **license key** and a **device instance id** to Polar’s License API to activate/validate. It does **not** send your bookmarks, notes, or images to Polar or to the developer.

---

## 3. How information is used

Data is used only to provide extension features on your device:
- list and search bookmarks;
- show guides / notes;
- keep UI preferences;
- annotate and save guide screenshots you create;
- (Pro) export/import a local backup file you choose;
- (Pro) verify your license with Polar.

We do **not** sell your data.  
We do **not** use it for advertising profiles.

---

## 4. Data storage and sharing

| Data | Where stored | Sent to our servers? |
|---|---|---|
| Bookmarks (via Chrome API) | Chrome (your profile) | No |
| Notes, guide images, preferences | `chrome.storage.local` on your device | No |
| Temporary sticky / caches | `chrome.storage.session` on your device | No |
| Screenshots you capture | `chrome.storage.local` on your device | No |
| Pro license cache | `chrome.storage.local` on your device | No |
| License key + instance (on activate/validate) | — | Sent only to Polar API |

The extension does **not** upload your bookmarks, notes, or screenshots to a developer-operated server.

### Third parties
- **Google / Chrome**: browser APIs and (if you install from) Chrome Web Store are governed by Google’s policies.
- **Polar** (`polar.sh` / `api.polar.sh`): used for Pro checkout and license activate/validate when you choose to purchase or enter a key. Payment and refund terms are those of Polar and the seller. Device activation limit is configured on the product (currently **2**).
- **Buy Me a Coffee** (`buymeacoffee.com/No.9Li`): opened only if you click the tip link; voluntary support **without** Pro entitlement; that site has its own privacy policy and payment processing (e.g. Stripe).

### Refunds / devices (summary)
Pro is a one-time unlock for backup export/import. Refunds follow Polar / seller policy. A license may be activated on a limited number of devices (see store listing). Uninstalling the extension removes local data and does not automatically back it up—export while Pro is active if you need a copy.

For Pro license details (local unlock, offline continuation after activation, Chrome/Web Store change limits), see:  
https://bookmarkmemo.github.io/privacy-policy/TERMS.md

---

## 5. Permissions (why they are needed)

- **bookmarks** — list and use your bookmarks; Pro restore may create missing bookmarks  
- **storage / unlimitedStorage** — save notes, images, settings, and license cache locally  
- **tabs / activeTab / scripting / webNavigation** — panel behavior across tabs, open bookmarks, inject UI, capture when you request it  
- **favicon** — show bookmark icons  
- **Host access to websites** — show the floating panel and capture/annotate on normal web pages  
- **api.polar.sh** — activate/validate Pro license keys  

---

## 6. Data retention and deletion

Data remains in your browser until you clear it or remove the extension.

You can delete extension data by:
- removing custom images / notes inside the extension where available; and/or  
- removing the extension in `chrome://extensions` (Chrome will remove its storage).

---

## 7. Children’s privacy

The extension is not directed at children under 13. Do not use it to submit children’s personal information.

---

## 8. Changes

We may update this policy. The “Last updated” date will change. Continued use after changes means you accept the updated policy.

---

## 9. Contact

Questions: open an issue at  
https://github.com/bookmarkmemo/privacy-policy/issues  

Pro checkout:  
https://buy.polar.sh/polar_cl_pVr9BMe8GNKmnQRN17EM2SAQk2pDPBM1HEacI1P65nu  

Chrome Web Store:  
https://chromewebstore.google.com/detail/bookmarkmemo/dmihfdbbcdkmaejgdmgjejihnjgjhmde  

Tip / support page (optional, user-initiated, no Pro):  
https://buymeacoffee.com/No.9Li  

---

# 隱私權政策 — BookmarkMemo（書籤備忘錄）

**最後更新日期：** 2026-09-24  
**開發者：** bookmarkmemo  
**產品：** BookmarkMemo／書籤備忘錄（Chrome 擴充功能）  
**聯絡方式：** https://github.com/bookmarkmemo/privacy-policy/issues  

本檔為公開隱私權政策的本機備份。  
公開網址（GitHub Pages）：https://bookmarkmemo.github.io/privacy-policy/

---

## 1. 摘要

書籤備忘錄（BookmarkMemo）讓您以浮層檢視 Chrome 書籤，並可自行加入說明圖、文字說明與頁面截圖標記。

- 我們**沒有**營運會收集您書籤或筆記的後端伺服器。  
- 擴充產生的資料存在**您的瀏覽器／裝置**（Chrome storage）。  
- 「請我喝咖啡」僅在您**主動點擊**時開啟第三方網站；屬自願支持，**不含 Pro**。  
- 可選 **Pro**（一次買斷）解鎖整包本機匯出／匯入；結帳與授權驗證透過 **Polar**。
- Chrome Web Store：https://chromewebstore.google.com/detail/bookmarkmemo/dmihfdbbcdkmaejgdmgjejihnjgjhmde

---

## 2. 我們會存取的資訊

### 2.1 Chrome 書籤
經您授權後，擴充會讀取書籤標題、網址與資料夾結構以顯示列表並對應目前頁面。若使用 Pro 匯入，在您確認後可補建備份中缺少的書籤。

### 2.2 分頁與瀏覽脈絡
可能讀取作用中分頁網址與導覽相關事件，用以標示書籤、顯示／隱藏浮層、點擊後在目前分頁開啟書籤。

### 2.3 網頁內容（content script）
在 `http://`／`https://` 頁面可能執行腳本以顯示浮層；若您啟動截圖標記，則協助標註可見區域截圖。

### 2.4 截圖（僅在您使用該功能時）
「截圖標記」可能擷取**目前分頁可見區域**，並將結果存於本機，對應您選擇的書籤網址。

### 2.5 Favicon
可能透過 Chrome favicon 機制顯示書籤圖示。

### 2.6 設定與您建立的內容
本機儲存例如：自訂說明圖、文字備忘、面板偏好、側欄模式、寬度、黏住書籤，以及（若啟用 Pro）授權金鑰快取與驗證時間。

### 2.7 Pro 授權（可選）
購買並啟用時，擴充會將**授權金鑰**與**裝置 instance** 傳送至 Polar License API 以啟用／驗證。**不會**把書籤、備忘或圖片傳給 Polar 或開發者伺服器。

---

## 3. 資訊如何使用

僅用於提供本機功能：列表／搜尋、說明與備忘、偏好、截圖標記、（Pro）匯出／匯入備份、（Pro）授權驗證。我們不販售資料，也不用於廣告畫像。

---

## 4. 儲存與分享

| 資料 | 存放處 | 是否送到開發者伺服器 |
|---|---|---|
| 書籤（Chrome API） | Chrome 設定檔 | 否 |
| 備忘、說明圖、偏好 | 本機 `chrome.storage.local` | 否 |
| 暫時狀態 | 本機 `chrome.storage.session` | 否 |
| Pro 授權快取 | 本機 `chrome.storage.local` | 否 |
| 授權金鑰＋instance（啟用／驗證時） | — | 僅送至 Polar API |

### 第三方
- **Google／Chrome**  
- **Polar**：Pro 結帳與授權；退款與條款依 Polar／賣方；目前啟用上限 **2** 台裝置  
- **Buy Me a Coffee**：僅在您點擊時開啟；自願支持、**不含 Pro**

### 退款／裝置（概要）
Pro 為匯出／匯入之一次買斷。退款依 Polar／賣方政策。授權可啟用台數見商店說明。卸載擴充會清除本機資料且無法自動備份——需要請先匯出。

Pro 授權細節（本機解鎖、啟用後離線續用、Chrome／商店變更限制）見：  
https://bookmarkmemo.github.io/privacy-policy/TERMS.md

---

## 5. 權限說明

- **bookmarks** — 列表與使用書籤；Pro 還原時可補建  
- **storage／unlimitedStorage** — 本機備忘、圖片、設定、授權快取  
- **tabs／activeTab／scripting／webNavigation** — 浮層與截圖流程  
- **favicon** — 書籤圖示  
- **網站主機權限** — 在一般網頁顯示浮層與截圖標記  
- **api.polar.sh** — Pro 授權啟用／驗證  

---

## 6. 保留與刪除

資料留在您的瀏覽器，直到您清除或移除擴充。可於擴充內刪除內容，或至 `chrome://extensions` 移除擴充。

---

## 7. 兒童隱私

本擴充非針對 13 歲以下兒童。請勿用以提交兒童個人資料。

---

## 8. 變更

本政策可能更新；「最後更新日期」會一併變更。繼續使用即表示接受更新後政策。

---

## 9. 聯絡

問題請至：https://github.com/bookmarkmemo/privacy-policy/issues  

Pro 結帳：https://buy.polar.sh/polar_cl_pVr9BMe8GNKmnQRN17EM2SAQk2pDPBM1HEacI1P65nu  

Chrome Web Store：https://chromewebstore.google.com/detail/bookmarkmemo/dmihfdbbcdkmaejgdmgjejihnjgjhmde  

自願支持（不含 Pro）：https://buymeacoffee.com/No.9Li  
