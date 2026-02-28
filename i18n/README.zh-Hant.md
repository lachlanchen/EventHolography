[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


[![LazyingArt banner](https://github.com/lachlanchen/lachlanchen/raw/main/figs/banner.png)](https://github.com/lachlanchen/lachlanchen/blob/main/figs/banner.png)

# EventHolography

[![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-3776ab?style=for-the-badge&logo=apache&logoColor=white)](./LICENSE)
![Focus: Documentation-First](https://img.shields.io/badge/Focus-Documentation--First-FCA121?style=for-the-badge)
![Repository Stage](https://img.shields.io/badge/Stage-Early--Stage-lightgrey?style=for-the-badge)
![i18n](https://img.shields.io/badge/i18n-Directory%20Present-2ea44f?style=for-the-badge)
![Status](https://img.shields.io/badge/Repository-Documentation%20First-0f766e?style=for-the-badge&logo=markdown&logoColor=white)
![Audience](https://img.shields.io/badge/Audience-Researchers%20%26%20Contributors-22c55e?style=for-the-badge&logo=google-translate&logoColor=white)

---

這是 **Event-assisted Holographic Imaging** 專案資料的文件倉庫。

> 保留原始專案描述（canonical base）：
> `The repo for the paper Event-assited Holographic Imaging`

## 🧭 快速導覽

| 區域 | 連結 |
|---|---|
| 🎯 概覽 | [概覽](#overview-) |
| 🗂️ 範圍 | [專案結構](#project-structure-) |
| ✅ 先決條件 | [先決條件](#prerequisites-) |
| ▶️ 使用方式 | [使用方式](#usage-) |
| 🧪 貢獻 | [貢獻](#contributing-) |
| ❤️ 支持 | [❤️ Support](#-support) |
| 📜 授權 | [授權條款](#license-) |

## 概覽 🔍

<a id="overview-"></a>
`EventHolography` 是一個以 **documentation-first** 為核心的文件倉庫，專注於論文／專案主題 **Event-assisted Holographic Imaging**。

在這個儲存庫快照中，它的定位是入門與溝通窗口，而非可執行套件。

- 主要狀態：研究文件早期腳手架
- 公開焦點：論文背景、設定假設與多語導引
- 範圍：儲存庫結構、貢獻流程、以及未來程式碼/資料工作可延展的準備

## 儲存庫快照 📈

| 項目 | 說明 | 狀態 |
|---|---|---|
| `README.md` | 主要專案文件 | 已存在且持續維護 |
| `LICENSE` | 法規與授權條款 | Apache License 2.0 |
| `.gitignore` | 本機／建置產物忽略規則 | 已存在 |
| `i18n/` | 多語 README 檔案 | 已存在 |
| `.auto-readme-work/` | README 自動生成流程的中介資料 | 僅在草擬時產生 |

## 功能 ✨

<a id="features-"></a>
- 清楚界定 Event-assisted Holographic Imaging 專案資料的身分
- 採用 Apache 2.0 授權，便利開放且寬鬆的再利用
- 可延伸的多語 README 佈局（`i18n/`）
- 對使用者與貢獻者明確傳達 documentation-first 狀態
- 預留向前相容結構，可日後加入資料集、腳本、checkpoint 與可複現指引

## 專案結構 🗂️

<a id="project-structure-"></a>
```text
EventHolography/
├── README.md
├── LICENSE
├── .gitignore
├── i18n/
└── .auto-readme-work/
```

說明：

- `i18n/` 包含 README 的各語系版本，包含阿拉伯文、俄文等。
- `.auto-readme-work/` 在本次文件流程中產生，不是對外的正規介面。

## 先決條件 ✅

<a id="prerequisites-"></a>
目前儲存庫狀態只需要：

- `git`，用於 clone 與本機歷史／分支操作
- 支援 Markdown 的編輯器或 GitHub 檢視器

假設：

- 目前不需要 Python/Node/Rust 工具鏈或執行階段相依，因為尚未提交可執行管線。

## 安裝 🛠️

<a id="installation-"></a>
複製並進入專案：

```bash
git clone <your-repo-url> EventHolography
cd EventHolography
```

選用的編輯環境：

```bash
git checkout -b docs/improve-onboarding
```

如果你的目標是更新翻譯，請同時編輯 `README.md` 與對應的 `i18n/README.xx.md`。

## 使用方式 ▶️

<a id="usage-"></a>
目前尚未提供可執行進入點，因此使用方式仍以文件為主：

```bash
# 檢視儲存庫內容
ls -la

# 閱讀專案概覽
cat README.md
```

當實作資產到位後，這個章節應改為可執行說明（資料集、模型、train/infer 指令）。

## 設定 ⚙️

<a id="configuration-"></a>
目前尚未提供執行時設定介面。

未來預計的設定範圍（程式到位後補上）：

- 資料集根目錄路徑
- 模型與輸出目錄
- 全息重建參數
- 事件感測器元資料與校準選項
- 可複現預設（seed、split、資料增強）

## 範例 📌

<a id="examples-"></a>
在本儲存庫快照中，實務範例如下列儲存庫探索指令：

```bash
# 確認授權標頭
head -n 5 LICENSE

# 驗證語系文件覆蓋情況
ls -la i18n

# 檢視自動化生成內容（可選）
ls -la .auto-readme-work
```

若你期待訓練／推論範例，這個儲存庫目前尚未提供。

## 開發說明 🧪

<a id="development-notes-"></a>
- 這是一個以文件為先的早期儲存庫腳手架。
- 將技術敘述限定在已提交資源（樹內檔案）範圍內。
- 保持 README 為增量更新，保留歷史上下文並維持翻譯一致性。
- 若你加入程式碼，請在文件中同步加入實作細節、預期輸出與可複現步驟。

## 疑難排解 🩺

<a id="troubleshooting-"></a>
### 「目前還沒有可執行內容」

這在目前狀態屬於預期。尚未提交可執行腳本、設定、notebook 或資料集。

### 「翻譯版 README 哪裡找？」

請查看 `i18n/` 目錄。若缺少目標語言，請新增 `i18n/README.<lang>.md`，並同步更新語言導覽列。

### 「為何標題拼字不同？」

上游舊筆記中的原始字串是 `Event-assited`（少一個 s），故在保留歷史行為的引文中維持原拼法。本 README 新撰文則採用修正後的 `Event-assisted`。

### 「我該使用 `.auto-readme-work/` 嗎？」

將其視為 README 草擬時的產生型中介資料。除非你正在處理文件自動化流程，一般貢獻者通常不需要接觸。

## 路線圖 🗺️

<a id="roadmap-"></a>
- 補上論文中繼資料（出版連結、DOI 與 BibTeX 引用區塊）
- 待資源到位後新增實作進入點與可複現使用說明
- 補充資料集、前處理與實驗設定文件
- 新增 issue／PR 模板與貢獻流程說明
- 與英文主版本持續同步各語系 README

## 貢獻 🤝

<a id="contributing-"></a>
歡迎貢獻。

在專用模板加入前，請先採用這套標準流程：

1. Fork 此儲存庫
2. 建立專案分支（例如 `docs/<topic>`）
3. 提交小而可複閱的修改，並撰寫清楚訊息
4. 開啟 PR，說明動機、精確檔案變更與任何驗證指令

若新增技術說明，請盡量附上命令級範例與預期輸出。

## 引用 📚

<a id="citation-"></a>
目前尚未在儲存庫中提供引用細節。

當對應論文可取得時，請在本節加入 `BibTeX` 區塊與出版連結。

## 致謝 🙏

<a id="acknowledgements-"></a>
目前專案檔案中尚未定義致謝。

若有支援機構、合作夥伴或贊助單位需致謝，請於後續更新中補上。

<a id="-support"></a>
## 授權 📄

<a id="license-"></a>
本專案採用 Apache License 2.0 授權。詳見 [LICENSE](./LICENSE)。


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |
