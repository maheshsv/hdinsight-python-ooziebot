# OozieBot: Automated Oozie Workflow and Coordinator Generation

Introducing OozieBot - a tool to help customers automate Oozie job creation. OozieBot helps users generate Apache Oozie coordinators and Workflows for Hive, Spark and Shell actions and run them on a Linux based HDInsight cluster.

Setting up an Oozie job is a very tedious and time consuming process that involves defining workflows and enclosing coordinators, scraping through several cluster configurations to set up a properties file for the workflows to consume, setting up environment variables and copying all sources to Windows Azure Storage Blobs[WASB]/HDFS. OozieBot intends to automate most of these tasks and provide a configurable way for you to launch the job in a matter of a few minutes.

You can find detailed information on using the tool here:
https://azure.microsoft.com/en-us/documentation/articles/hdinsight-use-oozie-linux-mac/