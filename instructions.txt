# SPARK-TRADING


1 Alpha vantage
2 Spark stream
3 (optionnel) Kafka
4 traitement données stream (affichage, calculs + affichage etc...)

1.a get api key
1.b choose the api to use

2.a setup spark stream
2.b use it with the answer of the api stream

3.a find a way to inject kafka after the stream reading from AV API
3.b persist data with kafka between I/O of the pipeline
3.c use persisted data

4.a use stream data (visualize, calculus, ...)
