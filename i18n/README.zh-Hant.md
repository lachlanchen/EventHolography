[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


# EventHolography

[![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](./LICENSE)
![Status](https://img.shields.io/badge/Status-Documentation--First-orange)
![Repository](https://img.shields.io/badge/Repository-Early--Stage-lightgrey)
![i18n](https://img.shields.io/badge/i18n-Directory%20Present-success)

用於 **Event-assisted Holographic Imaging** 專案資料的儲存庫。

> 保留的原始專案描述（canonical base）：
> `The repo for the paper Event-assited Holographic Imaging`

## 概覽 🔍

`EventHolography` 目前是一個以文件為先的儲存庫，聚焦於論文／專案主題 **Event-assisted Holographic Imaging**。

在撰寫本文時，儲存庫主要包含：

- 一份精簡的根目錄 README（此處為了清楚起見已擴充）
- Apache 2.0 授權條款
- 專案層級的 `.gitignore`
- 用於多語 README 版本的 `i18n/` 目錄

目前尚未提交原始碼、相依性清單或可執行流程。

## 功能 ✨

- 為 Event-assisted 全像成像研究提供清楚的專案定位與範圍
- 採用 Apache 2.0 授權，便於開放使用與貢獻
- 透過 `i18n/` 提供多語文件架構
- 擴充後的 README 結構，便於後續導入程式碼／資料

## 專案結構 🗂️

```text
EventHolography/
├── README.md
├── LICENSE
├── .gitignore
└── i18n/
```

| Path | Purpose | Current State |
|---|---|---|
| `README.md` | 專案主要文件 | 已存在並持續維護 |
| `LICENSE` | 法律條款 | Apache License 2.0 |
| `.gitignore` | 本機／建置產物忽略規則 | 已存在 |
| `i18n/` | 語言專屬 README 檔案 | 目錄已存在；檔案可隨時間陸續新增 |

說明：

- `i18n/` 已存在，並保留給語言專屬 README 檔案使用。
- `.auto-readme-work/` 作為流程產生的工作上下文目錄存在，目前不屬於公開專案介面的一部分。

## 先決條件 ✅

目前儲存庫狀態僅需要基本工具：

- `git`（用於複製與追蹤變更）
- Markdown 檢視工具（GitHub 介面或本機編輯器）

選用（依 `.gitignore` 模式推測的未來方向）：

- 之後可能會導入 Python 工具鏈，但目前已提交的專案檔案不需要 Python 執行環境／相依套件。

## 安裝 🛠️

複製儲存庫：

```bash
git clone <your-repo-url> EventHolography
cd EventHolography
```

如果你已經在本機有這個儲存庫，請在編輯文件或新增專案資產前，先確認目前位於目標分支。

## 使用方式 ▶️

目前尚無可執行的進入點。當前使用方式以文件導向為主：

```bash
# Inspect repository contents
ls -la

# Read project overview
cat README.md
```

隨著程式碼、資料集或 notebooks 加入，本節應擴充為精確的執行指令。

## 設定 ⚙️

目前尚未定義執行期設定。

未來規劃的設定範例（待實作後補上）：

- 資料路徑
- 模型／checkpoint 路徑
- 相機／事件感測器參數
- 重建／全像實驗設定

## 範例 📌

目前可實作的範例是儲存庫檢查任務：

```bash
# Confirm license
head -n 5 LICENSE

# Check language folder status
ls -la i18n
```

如果你原本期待訓練／推論／展示範例，在目前這個儲存庫快照中尚不可用。

## 開發說明 🧪

- 這是一個早期階段的儲存庫骨架。
- 新增技術性敘述時，請與已提交檔案連結（程式碼、設定、腳本、資料集、notebooks 或論文相關材料）。
- 建議對本 README 採漸進式更新，而非整段替換，以保留歷史脈絡。

## 疑難排解 🩺

### “There is nothing to run yet”

這在目前狀態屬於預期情況；尚未提交可執行工作流程。

### “I expected translated READMEs”

`i18n/` 已存在，但可能尚未包含語言檔案。可在該目錄下按需求新增各語言 README。

### “The project title spelling differs in places”

原始描述包含 `Event-assited`（已逐字保留）。新文字優先使用 `Event-assisted` 這個拼法。

## 路線圖 🗺️

規劃中的文件與儲存庫成長方向：

- 補上論文引用中繼資料（BibTeX 與發表連結，待可取得後加入）
- 新增實作程式碼與可重現實驗說明
- 新增資料集／前處理文件
- 在 `i18n/` 下新增多語 README 檔案
- 新增 issue/PR 範本與貢獻流程細節

## 貢獻 🤝

歡迎貢獻。

在專用貢獻範本加入之前，請使用標準 GitHub 工作流程：

1. Fork 這個儲存庫
2. 建立功能／文件分支
3. 提交聚焦且訊息清楚的變更
4. 開啟 Pull Request，說明動機、變更內容與驗證方式

若引入新的技術指引，請盡可能附上可執行指令與預期輸出。

## 引用 📚

此儲存庫目前尚未提供引用資訊。

若此儲存庫對應到已發表論文，請在本節加入 `BibTeX` 條目與官方發表連結。

## 致謝 🙏

目前儲存庫檔案尚未定義致謝內容。

若你有機構支持、合作夥伴或資金來源需要致謝，可在後續更新中補上。

## 授權 📄

本專案採用 Apache License 2.0 授權。請參閱 [LICENSE](./LICENSE)。
