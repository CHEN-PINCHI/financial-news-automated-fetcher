# Financial News Automated Fetcher (國際金融快報自動化工具)

This project utilizes **n8n** to build an automated workflow that aggregates financial news from multiple international sources, categorizes them using JavaScript, and generates a structured daily report.
本專案利用 **n8n** 打造自動化工作流，整合多家國際財經新聞來源，並透過 JavaScript 進行資料分類與去重，最終產出結構化的每日簡報。

## 🚀 Features (功能特點)
* **Multi-source Integration**: Automatically fetches RSS feeds from Google News (US), CNBC (Intl), and Yahoo Finance (TW).
    **多來源整合**：自動抓取 Google News (美股)、CNBC (國際) 與 Yahoo 奇摩股市 (台股) 的 RSS 來源。
* **Smart Categorization**: Uses custom JavaScript logic to deduplicate news and categorize articles into US, International, and Taiwan markets.
    **智能分類**：使用自定義 JavaScript 邏輯進行資料去重，並將新聞精準歸類至美股、國際及台股市場。
* **Automated Reporting**: Generates a daily "Global Finance Snapshot" and saves it directly to Google Docs.
    **自動化報表**：每日定時生成「全球金融重點快報」並自動儲存至 Google Docs。

## 🛠️ Technical Stack (技術棧)
* **Automation Tool**: n8n
* **Language**: JavaScript (for data processing)
* **Storage**: Google Docs API
* **Data Format**: RSS / JSON

## 📂 How to Use (如何使用)
1.  Download the `N8N_國際金融快報.json` file from this repository.
    下載本專案中的 `N8N_國際金融快報.json` 檔案。
2.  Import the JSON file into your n8n instance.
    將 JSON 檔案匯入至你的 n8n 環境中。
3.  Configure your own **Google Docs credentials** in the nodes.
    在節點中設定你自己的 **Google Docs 憑證**。
4.  Activate the **Schedule Trigger** to start receiving daily updates.
    開啟 **Schedule Trigger** 即可開始接收每日更新。
