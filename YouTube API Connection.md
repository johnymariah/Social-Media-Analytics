# 🛠️ YouTube API Connection & Ingestion
YouTube API → Databricks CE (Community Edition)

File to be updated with steps to connect to youtube API.

✅ What Worked

Accessing YouTube API
Created a Google Cloud project and enabled YouTube Data / Analytics API.
Generated OAuth 2.0 tokens.
Successfully fetched channel data, video statistics, and analytics using Python locally.
Uploading Data to Databricks CE
Successfully read YouTube data into Databricks using Spark / Pandas.


❌ What Did Not Work

Used the Default Cluster in CE for running notebooks.
CE limitations: databricks-connect configure removed in latest versions
Could not run notebooks on CE automatically from local Python/Scheduling Notebooks (CE limitation)
API-based scheduling attempts failed.

