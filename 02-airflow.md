# Airflow

## 問題出現

在 Linux 中，工作排程一般使用 crontab，但這個設定通常很分散，並且如果其中一個掛掉，也很難分清楚先後順續。因此，如何讓「工作排程」更容易設定與管理，就是 Airflow 出現的原因。

## Airflow 是什麼

Apache Airflow 於 2014 年 10 月由 Airbnb 工作師推出的開源軟件，透過 Python 編寫的有向無環圖 (DAG) 來描寫工作流程之間的關係之後，進行自動執行，管理及回報。使用者亦可透過使用用戶操作介面（UI）來輕易進行管理操作和瀏覽。

> DAG：是「有向無循環圖」的縮寫。依照連接任務的箭頭產生順序與方向，且不能循環。DAG中的每個節點都對應著一個任務，而任務為資料處理的方式。是Apache中Airflow工具的核心。