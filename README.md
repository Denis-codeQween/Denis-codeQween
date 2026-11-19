# Hi, I'm Denis — Python Developer | Web Scraping, ETL Pipelines & Data Automation 👋

I build high-throughput **Web Scraping**, **ETL Pipelines**, **Data Analytics**, and **AI Automation** systems engineered for speed, low memory footprint, and production reliability.

### Core Engineering Focus
* **High-Speed Web Scraping & API Reverse Engineering:** Bypassing slow browser bottlenecks via asynchronous API extraction (`asyncio`, `curl_cffi` with TLS fingerprinting) and hybrid browser automation (`Playwright`) with checkpoint recovery.
* **Big Data ETL & OLAP Analytics:** Processing multi-million-row datasets and massive XML/CSV/database dumps in seconds without out-of-memory (OOM) errors using `DuckDB`, `Pandas`, and streaming parsers (`lxml.iterparse`).
* **Automated Reporting & RAG Systems:** Delivering executive multi-tab Excel workbooks (`OpenPyXL`), automated Telegram/CSV alerting, and grounded LLM/RAG assistants (`Google Gemini API`, `Streamlit`).

---

### Tech Stack
* **Languages & Core:** Python 3.11+, SQL, Asyncio
* **Scraping & Extraction:** `curl_cffi`, `Playwright`, `HTTPX`, `BeautifulSoup4`, `lxml`
* **Data Processing & Storage:** `DuckDB`, `Pandas`, `NumPy`, `OpenPyXL`, `SQLite`, `PostgreSQL`
* **AI & Interfaces:** `Google Gemini API`, `Streamlit`, `Telegram Bot API`

---

### Featured Production Pipelines

| Domain | Project | Key Architecture & Scale |
| :--- | :--- | :--- |
| **Big Data & SQL Analytics** | [US-Hospital-Price-Transparency-DuckDB-Analytics](https://github.com/Denis-codeQween/US-Hospital-Price-Transparency-DuckDB-Analytics) | Ingested & normalized **1.7M+ priced rate rows** (3M+ raw records) in DuckDB; standardized **18,725+ medical billing codes** into a 10-tab Excel report. |
| **Async API Lead ETL** | [acnc-66k-lead-etl-pipeline](https://github.com/Denis-codeQween/acnc-66k-lead-etl-pipeline) | Replaced multi-day browser scraping with async `curl_cffi` API extraction (`Chrome124` TLS spoofing), cutting runtime from 5+ days to **~5 hours** for **95k+ records**. |
| **Streaming XML ETL** | [High-Performance-XML-Streaming-and-DGR-Validation-Pipeline](https://github.com/Denis-codeQween/High-Performance-XML-Streaming-and-DGR-Validation-Pipeline) | Zero-OOM streaming parser (`lxml.iterparse`) validating massive multi-gigabyte XML archives in constant memory. |
| **Bulk Registry ETL** | [High-Performance-ABR-Bulk-Data-ETL-Pipeline](https://github.com/Denis-codeQween/High-Performance-ABR-Bulk-Data-ETL-Pipeline) | High-speed ingestion, filtering, and normalization of **1M+ registry records** into clean structured outputs. |
| **E-Commerce Automation** | [One-Click-ECommerce-Price-Tracker-Automation](https://github.com/Denis-codeQween/One-Click-ECommerce-Price-Tracker-Automation) | Automated competitor price monitoring with delta detection, structured Excel exports, and real-time Telegram alerts. |
| **Scraping & Backtesting** | [High-Performance-Data-Pipeline-Predictive-Strategy-Backtesting-Engine](https://github.com/Denis-codeQween/High-Performance-Data-Pipeline-Predictive-Strategy-Backtesting-Engine) | Resilient data acquisition pipeline paired with a statistical backtesting and strategy evaluation engine. |
| **AI / RAG Assistant** | [Techstore-ai-chat](https://github.com/Denis-codeQween/Techstore-ai-chat) | Hallucination-free RAG customer support assistant powered by Google Gemini API and Streamlit. |

---

### Let's Work Together
Available for freelance contracts in **Web Scraping, Custom ETL Pipelines, Data Cleaning/Analytics, and Python Automation** via [Upwork](https://www.upwork.com/freelancers/~016d90efe332ebf89d).
