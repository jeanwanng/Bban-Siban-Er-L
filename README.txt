B班四班二輪｜免費 iPhone PWA｜2026–2040

功能
- 2026/01/02～2040/12/31 共 5,478 天預先產生班表
- 做二休二
- 1–2 月夜班、3–4 月早班、5–6 月夜班……依原規則輪替
- 早班 08:00–20:10；夜班 20:00–隔日 08:10
- 點日期直接看今天上班時間
- 鬧鐘設定、每日記事
- 農曆、生肖、干支、節氣（使用 lunar-javascript CDN）
- 國定假日標示
- 深色模式
- 可加入 iPhone 主畫面

免費上線方式
GitHub Pages 可在 GitHub Free 的公開 repository 使用。把本資料夾內容上傳到公開 repository，Settings → Pages → Deploy from a branch → main / root，即可取得 https://帳號.github.io/專案名/ 網址。
GitHub 官方文件：https://docs.github.com/en/pages/quickstart

iPhone 安裝
1. 用 Safari 開啟網站。
2. 按「分享」。
3. 選「加入主畫面」。
4. 點主畫面的「B班四班二輪」即可像 App 一樣開啟。

重要限制
- 這是免費 PWA，不是 App Store 原生 .ipa。
- iPhone 網頁 App 無法保證像系統「時鐘」一樣在背景準時響鈴，也不能批次建立原生鬧鐘。
- 「加入提醒」會使用 iPhone 分享功能，把當天上班資訊交給提醒事項等 App。
- 農曆／節氣首次載入需要網路取得 lunar-javascript；班表本身已預先放在本機 JSON。
