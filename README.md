# 0001_howto_elasticsearch_storage

Metrics Collection and Dashboards used in the making of https://www.youtube.com/watch?v=nKUpfJCBiS4

## What is the best storage technology for Elasticsearch?

SSDs or spinning harddrives? NVMe or SATA/SAS? To RAID or not to RAID? In this video we will evaluate various local storage options for Elasticsearch using real world workloads.

[![0001_es_storage](https://user-images.githubusercontent.com/10326954/76195348-61d6de80-61e8-11ea-951d-1694d2e0392b.png)](https://www.youtube.com/watch?v=nKUpfJCBiS4)

## Monitoring Elasticsearch

For the making of this video, the Elasticsearch application and the server on which it were running was monitored using Telegraf, InfluxDB and Chronograf (the TIC of "TICK" Stack).

This repository includes the necessary Telegraf configuration to collect the needed metrics, and the Chronograf dashboard seen in the video.

![es_ingest_samsung_970pro_512gb](https://user-images.githubusercontent.com/10326954/78004541-8848ef00-733a-11ea-9bcd-ff9a6370b609.png)
