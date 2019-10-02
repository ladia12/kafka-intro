# Kafka-In-A-Nutshell
Experimentations with Kafka

The repository has been divided into 3 parts.

## 1. Kafka-basics
This part deals with code for the following:

* a basic Kafka Producer
* Kafka Producer with Callback to give a notion of what exactly is being produced to Kafka
* Kafka Producer with keys to understand how messages would be written to speicfic partitions when keys are provided

## 2. Twitter Producer

Here, Twitter's Stream API has been used to fetch data related to specific topics such as "politics, share market" etc. from Twitter.

The fetched data is put into Kafka by creating a Producer for the same

## 3. Elasticsearch Consumer

Here, a 3-node Elasticsearch cluster has been created using free services from Bonsai.

The data produced into Kafka using from Twitter's streaming API is consumed into the Elasticsearch cluster with specific indices.

#### Credits
The code in this repository has been developed mostly based on my learning from Stephen Maarek's course and various other blogs on Kafka.


