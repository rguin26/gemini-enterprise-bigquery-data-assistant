# 📊 AI Data Assistant with BigQuery & Gemini Enterprise Agent Platform

An end-to-end AI Data Engineering project demonstrating how to connect **Google BigQuery** analytics with the **Gemini Enterprise Agent Platform** using the `google-genai` Python SDK to generate automated business insights and operational recommendations.

---

## 📌 Project Overview

Modern data engineering goes beyond querying databases—it involves turning raw data into actionable enterprise intelligence. 

This project extracts order metrics from the public `thelook_ecommerce` dataset stored in Google BigQuery, structures the contextual data, and routes it to a custom **Gemini Enterprise Assistant** engine. The result is an automated, AI-driven executive breakdown and recommendation report for e-commerce operational managers.

---

## 🛠️ Architecture & Tech Stack

* **Data Warehouse:** [Google BigQuery](https://cloud.google.com/bigquery) (`bigquery-public-data.thelook_ecommerce`)
* **AI & Agent Platform:** [Gemini Enterprise Agent Platform](https://cloud.google.com/blog/products/ai-machine-learning/the-new-gemini-enterprise-one-platform-for-agent-development)
* **SDK:** `google-genai` (Official Unified Python SDK)
* **Environment:** Python 3.x, Jupyter Notebook (`.ipynb`), Pandas

---

## 🚀 Key Features

* **Live Data Extraction:** Executes SQL queries directly against BigQuery public e-commerce order data (`order_items`).
* **Context Formatting:** Cleans and formats tabular query results into optimal context windows for Large Language Models.
* **Gemini Enterprise Integration:** Leverages enterprise configuration parameters (`project_id`, `location`, `engine_id`) with `enterprise=True` routing via the unified client API.
* **Automated Insight Generation:** Generates executive summaries and tailored operational strategies based on revenue performance.

---

## 💻 Getting Started

### Prerequisites

1. A **Google Cloud Platform (GCP)** project with BigQuery API enabled.
2. An active engine configuration on the **Gemini Enterprise Agent Platform**.
3. Python 3.10+ installed locally or in Google Colab / Vertex AI Workbench.

### Installation & Execution

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/rguin26/gemini-enterprise-bigquery-data-assistant.git](https://github.com/rguin26/gemini-enterprise-bigquery-data-assistant.git)
   cd gemini-enterprise-bigquery-data-assistant
