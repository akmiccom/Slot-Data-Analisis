# Slot Data Analisis

スロットデータを収集して分析するツール

## アプリ構成

- Github Actions
- Supabase
- Streamlit

## フォルダ構成

<pre>

C:.
│  .gitignore
│  README.md
│  requirements.txt
│  secret.json
│  
├─.venv
├─data
│  ├─csv
│  │      halls.csv
│  ├─db
│  │      minrepo_02.db
│  └─log
│          minrepo.log
├─notebooks
├─scraper
│  │  config.py
│  │  df_clean.py
│  │  df_to_db.py
│  │  halls.yaml
│  │  logger_steup.py
│  │  scraper.py
│  │  scraping_date_page.py
│  │  scraping_hall_page.py
│  │  scraping_model_page.py
│  │  utils.py
│  │  
│  └─__pycache__
│
├─trash
│
└─utils
        create_databese.py
</pre>
