# Vodacom-Heartbeat-POC
This repository shows you how to do sentiment analysis on NPS verbatim files. This notebook assumes jNPS files but this method can be used for any NPS verbatim. The only difference is the ingestion and post processing as this will depend on the structure of the file.

In this notebook, you are going to ingest a csv file for jNPS data from an Amazon S3 bucket, run the topic extraction and sentiment analysis on the data in the NPS verbatim column, and finally export the data back into an Amazon S3 bucket for further analysis.