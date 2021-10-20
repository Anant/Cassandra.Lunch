# Cassandra.Lunch
Resources from weekly Zoom lunches revolving around Apache Cassandra and Apache Cassandra-related topics. Hosted by Anant Corporation.

[Join Cassandra Lunch Weekly at 12 PM EST Every Wednesday](https://www.meetup.com/Cassandra-DataStax-DC/events/)

If you would like to be a guest speaker, you can reach us at solutions@anant.us. If you would like to sponsor Cassandra Lunch, please reach us at the email listed above.

Check out the Cassandra.Lunch playlist on [Youtube](https://www.youtube.com/playlist?list=PLmZzyjM-vqX6f0WQYhHgIv5K-esMRcbyr)

- - -

## Table of Contents

| Jump To Topic | YouTube | SlideShare |
| --- | --- | --- |
| [Cassandra 4.0](#apache-cassandra-lunch-online-meetup-10-cassandra-40) | [YouTube](https://youtu.be/GfmApaHY04o) | |
| [Different Cassandra Distributions and Variants](#apache-cassandra-lunch-online-meetup-11-different-cassandra-distributions-and-variants) | [YouTube](https://youtu.be/d7H9LNHS27M) | [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-distributions-and-variants-237160052) |
| [Cassandra & Kubernetes](#apache-cassandra-lunch-online-meetup-12-cassandra--kubernetes) | [YouTube](https://youtu.be/fP8ZabIocNg) | [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-kubernetes) |
| [Jump Start Projects for Cassandra](#apache-cassandra-lunch-online-meetup-13-jump-start-projects-for-cassandra) | [YouTube](https://youtu.be/33CSFYwc52k) | [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-lunch-13-jump-start-projects-for-cassandra) |
| [Basic Cassandra Log Diagnostics with ELK/FEK/BEK](#apache-cassandra-lunch-online-meetup-14-basic-log-diagnostics-with-elkfekbek) | [YouTube](https://youtu.be/WL-Gs_2rAUY) | [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-lunch-14-basic-log-diagnostics-with-elkfekbek) |
| [Cassandra Backup and Restoration](#apache-cassandra-lunch-online-meetup-15-cassandra-backup-and-restoration) | [YouTube](https://youtu.be/ZSHye9USdJA) | [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-lunch-15-cassandra-backup-restoration) |
| [Cassandra Anti-Entropy, Repair, and Synchronization](#apache-cassandra-lunch-online-meetup-16-cassandra-anti-entropy-repair-and-synchronization) | [YouTube](https://youtu.be/Y1WB6_drmus) | [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-anti-entropy-repair-and-synchronization) |
| [Cassandra Tombstones](#apache-cassandra-lunch-online-meetup-17-cassandra-tombstones) | [YouTube](https://youtu.be/FgJ_LNplfIg) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-online-meetup-17-tombstones) |
| [Connecting Cassandra to Kafka](#apache-cassandra-lunch-online-meetup-18-connecting-cassandra-to-kafka) | [YouTube](https://youtu.be/g9ITZ_qyezs) |  |
| [Combined Use of Relational Databases and Apache Cassandra](#apache-cassandra-lunch-online-meetup-19-combined-use-of-relational-databases-and-apache-cassandra) | [YouTube](https://youtu.be/wJEukGjOPII) | [SlideShare](https://www.slideshare.net/AnantCorp/migrating-from-a-relational-database-to-cassandra-why-where-when-and-how) |
| [Cassandra Read / Write Path](#apache-cassandra-lunch-online-meetup-20-cassandra-read--write-path) | [YouTube](https://youtu.be/SP5v3BxEl6Y) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-20-cassandra-read-and-write-paths) |
| [Cassandra Stages / Thread Pools](#apache-cassandra-lunch-online-meetup-21-cassandra-stages--thread-pools) | [YouTube](https://youtu.be/ivPXKp5HqF4) | [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-lunch-21-cassandra-stages-thread-pools) |
| [Cassandra Deployment and Admin Tools](#apache-cassandra-lunch-online-meetup-22-deployment-and-admin-tools) | [YouTube](https://youtu.be/SvHXNjOu__U) | [SlideShare](https://www.slideshare.net/AnantCorp/how-to-build-a-multidc-cassandra-cluster-in-aws-with-opscenter-lcm) |
| [Lucene Based Indexes on Cassandra](#apache-cassandra-lunch-online-meetup-23-lucene-based-indexes-on-cassandra) | [YouTube](https://youtu.be/Z0NXWmZAB8s) | [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-lunch-23-lucene-based-indexes-on-cassandra) |
| [Cassandra Use Cases](#apache-cassandra-lunch-online-meetup-24-cassandra-use-cases) | [YouTube](https://youtu.be/5E5okjOS5Sk) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-24-cassandra-use-cases) |
| [Cassandra Use Cases - Reference Architectures](#apache-cassandra-lunch-online-meetup-25-cassandra-use-cases---reference-architectures) | [YouTube](https://youtu.be/ON63js4p8kI) | [SlideShare](https://www.slideshare.net/AnantCorp/realtime-business-platform-architecture-review) |
| [Cassandra Troubleshooting with Logs](#apache-cassandra-lunch-online-meetup-26-cassandra-troubleshooting-with-logs) | [YouTube](https://youtu.be/Pns8o4BbaRE) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-26-cassandra-troubleshooting-with-logs) |
| [Cassandra on Baremetal / Virtual Machines / Containers](#apache-cassandra-lunch-online-meetup-27-cassandra-on-baremetal--virtual-machines--containers) | [YouTube](https://youtu.be/5-7bz7es3Ac) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-27-cassandra-on-baremetal-virtual-machines-containers) |
| [Cassandra Backup / Restore Scenarios](#apache-cassandra-lunch-online-meetup-28-cassandra-backup--restore-scenarios) | [YouTube](https://youtu.be/Vhi_bXwj19g) | [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-lunch-15-cassandra-backup-restoration) |
| [Cassandra & Kubernetes Update](#apache-cassandra-lunch-online-meetup-29-cassandra--kubernetes-update) | [YouTube](https://youtu.be/DJ62eRi6eDY) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-29-cassandra-kubernetes-update) |
| [Cassandra and Spark Foundations](#apache-cassandra-lunch-online-meetup-30-cassandra-and-spark-foundations) | [YouTube](https://youtu.be/w3CPXTV4tmk) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-online-meetup-30-cassandra-and-spark-foundations) |
| [Business Intelligence with Cassandra](#apache-cassandra-lunch-online-meetup-31-business-intelligence-with-cassandra) | [YouTube](https://youtu.be/YmbtcbpfzPQ) | [SlideShare](https://www.slideshare.net/AnantCorp/open-source-bi-tools-and-cassandra-doing-sql-and-reporting-on-cassandra) |
| [Cassandra Data Operations – Common Ways to Move Data in Cassandra](#apache-cassandra-lunch-online-meetup-32-cassandra-data-operations--common-ways-to-move-data-in-cassandra) | [YouTube](https://youtu.be/LVK2PJYifDM) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-32-cassandra-data-operations-common-ways-to-move-data-in-cassandra) |
| [Cassandra Deployment – Ansible and Terraform with Cassandra](#apache-cassandra-lunch-online-meetup-33-cassandra-deployment--ansible-and-terraform-with-cassandra) | [YouTube](https://youtu.be/gaYAKf6SQNw) | [SlideShare](https://www.slideshare.net/AnantCorp/how-to-build-a-multidc-cassandra-cluster-in-aws-with-opscenter-lcm) |
| [Liquibase and Cassandra](#apache-cassandra-lunch-online-meetup-34-liquibase-and-cassandra) | [YouTube](https://youtu.be/okPTMB6B_Rw) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-34-liquibase-and-cassandra) |
| [Data Operations with Spark and Cassandra](#apache-cassandra-lunch-online-meetup-35-data-operations-with-spark-and-cassandra) | [YouTube](https://youtu.be/fo18FOLepTg) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-35-data-operations-with-spark-and-cassandra) |
| [Specialized Databases on Cassandra](#apache-cassandra-lunch-online-meetup-36-specialized-databases-on-cassandra) | [YouTube](https://youtu.be/6BUrpdB6ol4) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-36-specialized-databases-on-cassandra) |
| [CQL Copy for Data Operations](#apache-cassandra-lunch-online-meetup-37-cql-copy-for-data-operations) | [YouTube](https://youtu.be/qyD_M20K7Ic) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-37-cql-copy-for-data-operations) |
| [Cassandra SSTables and Spark](#apache-cassandra-lunch-online-meetup-38-cassandra-sstables-and-spark) | [YouTube](https://youtu.be/TPXaqL6HxOE) | [SlideShare](https://www.slideshare.net/AnantCorp/cassadralunch-38) |
| [General Apache Cassandra Updates](#apache-cassandra-lunch-online-meetup-39-general-apache-cassandra-updates) | [YouTube](https://youtu.be/05FvegMilXg) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-39-general-apache-cassandra-updates) |
| [Scylla Migrator for Cassandra Data Operations](#apache-cassandra-lunch-online-meetup-40-scylla-migrator-for-cassandra-data-operations) | [YouTube](https://youtu.be/B_nkxJsRIag) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-40-scylla-migrator-for-cassandra-data-operations) |
| [Cassandra on Kubernetes - Docker/Kubernetes/Helm - Part 1](#apache-cassandra-lunch-online-meetup-41-cassandra-on-kubernetes---dockerkuberneteshelm---part-1) | [YouTube](https://youtu.be/-I8cKQO_Qr0) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-41-cassandra-on-kubernetes-dockerkuberneteshelm-part-1) |
| [SSTable Files with SSTableloader](#apache-cassandra-lunch-online-meetup-42-sstable-files-with-sstableloader) | [YouTube](https://youtu.be/c8URCX4Zey8) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-42-sstable-files-with-sstableloader) |
| [DSBulk with Sed & Awk](#apache-cassandra-lunch-43-dsbulk-with-sed--awk) | [YouTube](https://youtu.be/gFSICPMxcqI) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-43-dsbulk-with-sed-and-awk) |
| [Docker/Kubernetes/Helm Fundamentals Part 2](#apache-cassandra-lunch-44-cassandra-on-kubernetes-dockerkuberneteshelm-fundamentals-part-2) | [YouTube](https://youtu.be/4woSDfVSkUY) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-44-cassandra-on-kubernetes-dockerkuberneteshelm-fundamentals-part-2) |
| [Alpakka Cassandra and Twitter](#apache-cassandra-lunch-45-alpakka-cassandra-and-twitter) | [YouTube](https://youtu.be/KEYO5DN9J1w) | [SlideShare](https://www.slideshare.net/AnantCorp/data-engineers-lunch-20-dataops-vs-devops) |
| [Apache Spark Jobs in Scala for Cassandra Data Operations](#apache-cassandra-lunch-46-apache-spark-jobs-in-scala-for-cassandra-data-operations) | [YouTube](https://youtu.be/UsIqNiSBY9I) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-46-apache-spark-jobs-in-scala-for-cassandra-data-operations) |
| [Airflow and Cassandra](#apache-cassandra-lunch-48-airflow-and-cassandra) | [YouTube](https://youtu.be/h2OCveciEIA) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-48-airflow-and-cassandra) |
| [Spark SQL for Cassandra Data Operations](#apache-cassandra-lunch-49-spark-sql-for-cassandra-data-operations) | [YouTube](https://youtu.be/eu7Rs9d4oFg) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-49-spark-sql-for-cassandra-data-operations) |
| [Machine Learning with Spark + Cassandra](#apache-cassandra-lunch-50-machine-learning-with-spark--cassandra) | [YouTube](https://youtu.be/myIX0kkpL9U) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-50-machine-learning-with-spark-cassandra) |
| [Cassandra Cluster Design & Architecture](#apache-cassandra-lunch-51-cassandra-cluster-design--architecture) | [YouTube](https://youtu.be/JWeKAu7XnYk) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-51-cassandra-cluster-design-architecture) |
| [Airflow and Cassandra - Cluster Management](#apache-cassandra-lunch-52-airflow-and-cassandra---cluster-management) | [YouTube](https://youtu.be/l6T735IxDiI) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-52-airflow-and-cassandra-for-cluster-management) |
| [Cassandra ETL with Airflow and Spark](#apache-cassandra-lunch-53-cassandra-etl-with-airflow-and-spark) | [YouTube](https://youtu.be/Bex__3cwiI0) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-53-cassandra-etl-with-airflow-and-spark) |
| [Machine Learning with Spark + Cassandra Part 2](#apache-cassandra-lunch-54-machine-learning-with-spark--cassandra-part-2) | [YouTube](https://youtu.be/3roCSBWQzRk) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-54-machine-learning-with-spark-cassandra-part-2/) |
| [Migrating PostgreSQL to Cassandra](#apache-cassandra-lunch-55-migrating-postgresql-to-cassandra) | [YouTube](https://youtu.be/weVVpcg716o) | [SlideShare](https://www.slideshare.net/AnantCorp/data-engineers-lunch-29-introduction-to-apache-nifi) |
| [Using Spark SQL Parquet Tables in DSEFS / DSE Analytics](#apache-cassandra-lunch-56-using-spark-sql-parquet-tables-in-dsefs--dse-analytics) | [YouTube](https://youtu.be/yaMB1FTSwUw) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-56-using-spark-sql-parquet-tables-in-dsefs-dse-analytics) |
| [Using Secondary Indexes in Cassandra - Anil Mittana](#apache-cassandra-lunch-57-using-secondary-indexes-in-cassandra---anil-mittana) | [YouTube](https://youtu.be/H0kdNk9qb5k) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-57-using-secondary-indexes-in-cassandra) |
| [Tools for Cassandra Titans](#apache-cassandra-lunch-58-tools-for-cassandra-titans) | [YouTube]() | [SlideShare]() |
| [Functions in Cassandra](#apache-cassandra-lunch-59-functions-in-cassandra) | [YouTube](https://youtu.be/0XKth-HG0Po) | [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-lunch-59-functions-in-cassandra) |
| [Apache Cassandra and Apache Nifi](#apache-cassandra-lunch-60-apache-cassandra-and-apache-nifi) | [YouTube]() | [SlideShare]() |
| [Elassandra](#apache-cassandra-lunch-61-elassandra) | [YouTube](https://youtu.be/jhmYb2xcdXo) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-61-elassandra) |
| [Grafana Dashboard for Apache Cassandra](#apache-cassandra-lunch-62-grafana-dashboard-for-apache-cassandra) | [YouTube](https://youtu.be/ATfKQ9YLfv8) | [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-62-grafana-dashboard-for-apache-cassandra) |
- - - 

### Apache Cassandra Lunch Online Meetup #10: Cassandra 4.0
- We discuss and take an in-depth look at the improvements and new features that come with Cassandra 4.0.
    - [YouTube](https://youtu.be/GfmApaHY04o)

- - -

### [Apache Cassandra Lunch Online Meetup #11: Different Cassandra Distributions and Variants](https://blog.anant.us/cassandra-lunch-11-different-cassandra-distributions-and-variants/)
- We discuss various Cassandra distributions ranging from Cassandra / Cassandra Compliant Databases on JVM, Cassandra Compliant Databases on C++, Cassandra as a Service / Managed Cassandra Based on Open Source Cassandra, and Cassandra as a Service / Managed Cassandra Based on Proprietary Technology. 
    - [YouTube](https://youtu.be/d7H9LNHS27M)
    - [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-distributions-and-variants-237160052)

- - -

### [Apache Cassandra Lunch Online Meetup #12: Cassandra & Kubernetes](https://blog.anant.us/cassandra-lunch-12-cassandra-kurbernetes/)
- We cover Kubernetes, discussing what it is and how it works with Docker and Cassandra. We also looked at some of Kubernetes' competitors and a variety of open sources tools for Kubernetes which will give you an insight as to why we picked Kubernetes to be a worth while investment when working with databases. 
    - [YouTube](https://youtu.be/fP8ZabIocNg)
    - [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-kubernetes)

- - -

### [Apache Cassandra Lunch Online Meetup #13: Jump Start Projects for Cassandra](https://blog.anant.us/cassandra-lunch-13-jump-start-projects-for-cassandra/)
- We discuss a number of projects and platforms that you can use to jumpstart your Cassandra projects. They make useful educational resources; as well as, good starting codebases for new projects. We also discuss a recent article on the Yugabyte blog about Cassandra.
    - [YouTube](https://youtu.be/33CSFYwc52k)
    - [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-lunch-13-jump-start-projects-for-cassandra)

- - -

### [Apache Cassandra Lunch Online Meetup #14: Basic Log Diagnostics with ELK/FEK/BEK](https://blog.anant.us/cassandra-lunch-14-basic-log-diagnostics-with-elk-fek-bek/)
- We discuss methods for finding and diagnosing issues in Cassandra clusters with ELK/FEK/BEK.
    - [YouTube](https://youtu.be/WL-Gs_2rAUY)
    - [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-lunch-14-basic-log-diagnostics-with-elkfekbek)

- - -

### [Apache Cassandra Lunch Online Meetup #15: Cassandra Backup and Restoration](https://blog.anant.us/cassandra-lunch-15-cassandra-backup-restoration/)
- We discuss Cassandra Backup / Restoration. We also discuss disaster avoidance, disaster recovery, and different tools that can be used for backup and restoration of your Cassandra data. Also, we discuss an example scenario of how someone has set up multi-node clusters and how they go about data backup and restoration. 
    - [YouTube](https://youtu.be/ZSHye9USdJA)
    - [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-lunch-15-cassandra-backup-restoration)

- - -

### [Apache Cassandra Lunch Online Meetup #16: Cassandra Anti-Entropy, Repair, and Synchronization](https://blog.anant.us/cassandra-lunch-16-anti-entropy-repair-synchronization/)
- We discuss Cassandra Anti-entropy which is a process of comparing the data of all replicas and updating each replica to the newest version. We also looked at repair and synchronization in Cassandra and how you can prepare for the unexpected. 
    - [YouTube](https://youtu.be/Y1WB6_drmus)
    - [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-anti-entropy-repair-and-synchronization)

- - -

### [Apache Cassandra Lunch Online Meetup #17: Cassandra Tombstones](https://blog.anant.us/cassandra-lunch-17-tombstones/)
- We discuss deletion and tombstones in Cassandra.
    - [YouTube](https://youtu.be/FgJ_LNplfIg)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-online-meetup-17-tombstones)

- - -

### [Apache Cassandra Lunch Online Meetup #18: Connecting Cassandra to Kafka](https://blog.anant.us/cassandra-lunch-18-connecting-cassandra-to-kafka/)
- Guest speaker, Ryan Quey, a full stack data engineer, discusses a personal project he has been working on called java-podcast-processor, which is a tool to find podcast metadata over an external API, store them, get their RSS feeds, and run ETL using Airflow, Kafka, Spark, and Cassandra. The particular Cassandra distribution used is Elassandra, which allows seamless integration with Elasticsearch. The data is also displayed using a Gatsby app and served using Flask.
    - [YouTube](https://youtu.be/g9ITZ_qyezs)

- - -

### [Apache Cassandra Lunch Online Meetup #19: Combined Use of Relational Databases and Apache Cassandra](https://blog.anant.us/cassandra-lunch-19-combined-use-of-relational-databases-and-cassandra/)
- We discuss the combined use of relational databases and Cassandra. We also discuss the advantages of using relational databases and Cassandra separately; as well as, covering the advantages and methods for using both concurrently. 
    - [YouTube](https://youtu.be/wJEukGjOPII)
    - [SlideShare](https://www.slideshare.net/AnantCorp/migrating-from-a-relational-database-to-cassandra-why-where-when-and-how)

- - -

### [Apache Cassandra Lunch Online Meetup #20: Cassandra Read / Write Path](https://blog.anant.us/apache-cassandra-lunch-20-read-and-write-paths/)
- We discuss Cassandra read and write paths, which is how Cassandra stores and retrieves data at high speeds. We do not cover how Cassandra replicates data because that its own subject, but we take a look at these four sub-topics: Write Path, Update / Delete, Maintenance Path, and Read Path. 
    - [YouTube](https://youtu.be/SP5v3BxEl6Y)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-20-cassandra-read-and-write-paths)

- - -

### [Apache Cassandra Lunch Online Meetup #21: Cassandra Stages / Thread Pools](https://blog.anant.us/cassandra-lunch-21-cassandra-stages-thread-pools/)
- We discuss Cassandra and Staged Event-Driven Architecture with an emphasis on Cassandra stages / thread pools. We also discuss a few different tools that we can use to monitor these stages and thread pools in order to keep your Cassandra running as smoothly as possible. 
    - [YouTube](https://youtu.be/ivPXKp5HqF4)
    - [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-lunch-21-cassandra-stages-thread-pools)

- - -

### [Apache Cassandra Lunch Online Meetup #22: Deployment and Admin Tools](https://blog.anant.us/cassandra-lunch-22-cassandra-deployment-and-administration-tools/)
- We discuss deployment and administration tools for Cassandra. We also discuss a number of tools for the installation, configuration, monitoring, and administration of Cassandra clusters.
    - [YouTube](https://youtu.be/SvHXNjOu__U)
    - [SlideShare](https://www.slideshare.net/AnantCorp/how-to-build-a-multidc-cassandra-cluster-in-aws-with-opscenter-lcm)

- - -

### [Apache Cassandra Lunch Online Meetup #23: Lucene Based Indexes on Cassandra](https://blog.anant.us/apache-cassandra-lunch-23-lucene-based-indexes-on-cassandra/)
- We discuss packaged and DIY methods for Lucene based indexes on Cassandra; as well as, give some pros and cons for using Lucene Based Indexes on Cassandra.
    - [YouTube](https://youtu.be/Z0NXWmZAB8s)
    - [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-lunch-23-lucene-based-indexes-on-cassandra)

- - -

### [Apache Cassandra Lunch Online Meetup #24: Cassandra Use Cases](https://blog.anant.us/apache-cassandra-lunch-24-cassandra-use-cases/)
- We discuss a number of use cases for Cassandra, focusing on Cassandra's place in running a digital business technology platform.
    - [YouTube](https://youtu.be/5E5okjOS5Sk)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-24-cassandra-use-cases)

- - -

### [Apache Cassandra Lunch Online Meetup #25: Cassandra Use Cases - Reference Architectures](https://blog.anant.us/apache-cassandra-lunch-25-cassandra-use-cases-reference-architectures/)
- We discuss how Cassandra is used for real-time data platforms; as well as, cover different reference architectures in which Cassandra is and can be used.
    - [YouTube](https://youtu.be/ON63js4p8kI)
    - [SlideShare](https://www.slideshare.net/AnantCorp/realtime-business-platform-architecture-review)

- - -

### [Apache Cassandra Lunch Online Meetup #26: Cassandra Troubleshooting with Logs](https://blog.anant.us/apache-cassandra-lunch-26-cassandra-troubleshooting-with-logs/)
- We discuss how Cassandra is used for real-time data platforms; as well as, cover different reference architectures in which Cassandra is and can be used.
    - [YouTube](https://youtu.be/Pns8o4BbaRE)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-26-cassandra-troubleshooting-with-logs)

- - -

### [Apache Cassandra Lunch Online Meetup #27: Cassandra on Baremetal / Virtual Machines / Containers](https://blog.anant.us/apache-cassandra-lunch-27-cassandra-on-baremetal-virtual-machines-containers/)
- We discuss different methods in which we can deploy Cassandra whether it be on Baremetal, Virtual Machines, or Containers; as well as, pros, cons, and deployment tools.
    - [YouTube](https://youtu.be/5-7bz7es3Ac)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-27-cassandra-on-baremetal-virtual-machines-containers)

- - -

### [Apache Cassandra Lunch Online Meetup #28: Cassandra Backup / Restore Scenarios](https://blog.anant.us/apache-cassandra-lunch-28-cassandra-backup-restore-scenarios/)
- We discuss specific scenarios for Cassandra's backup and restore, some methods for restoring data to a Cassandra cluster, and covered how factors like the topology of a cluster or the need for constant uptime can affect the backup/restore process. 
    - [YouTube](https://youtu.be/Vhi_bXwj19g)
    - [SlideShare](https://www.slideshare.net/AnantCorp/cassandra-lunch-15-cassandra-backup-restoration)

- - -

### [Apache Cassandra Lunch Online Meetup #29: Cassandra & Kubernetes Update](https://blog.anant.us/apache-cassandra-lunch-29-cassandra-kubernetes-update/)
- We discuss updates regarding Cassandra and Kubernetes after the recent KubeCon event.
    - [YouTube](https://youtu.be/DJ62eRi6eDY)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-29-cassandra-kubernetes-update)

- - -

### [Apache Cassandra Lunch Online Meetup #30: Cassandra and Spark Foundations](https://blog.anant.us/cassandra-lunch-30-cassandra-spark-foundations/)
- We discuss the basics of using Spark and Cassandra together, the advantages of each, and the advantages of using them together. We also discuss the potential drawbacks, and configuration methods for avoiding those drawbacks.
    - [YouTube](https://youtu.be/w3CPXTV4tmk)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-online-meetup-30-cassandra-and-spark-foundations)

- - -

### [Apache Cassandra Lunch Online Meetup #31: Business Intelligence with Cassandra](https://blog.anant.us/apache-cassandra-lunch-31-business-intelligence-with-cassandra/)
- We discuss open-source tools that can be used for BI with Cassandra including a live demo using DSE, Presto, and Metabase.
    - [YouTube](https://youtu.be/YmbtcbpfzPQ)
    - [SlideShare](https://www.slideshare.net/AnantCorp/open-source-bi-tools-and-cassandra-doing-sql-and-reporting-on-cassandra)

- - -

### [Apache Cassandra Lunch Online Meetup #32: Cassandra Data Operations – Common Ways to Move Data in Cassandra](https://blog.anant.us/apache-cassandra-lunch-32-cassandra-data-operations-common-ways-to-move-data-in-cassandra/)
- We discuss the various ways of moving data into and out of Cassandra clusters.
    - [YouTube](https://youtu.be/LVK2PJYifDM)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-32-cassandra-data-operations-common-ways-to-move-data-in-cassandra)

- - -

### [Apache Cassandra Lunch Online Meetup #33: Cassandra Deployment – Ansible and Terraform with Cassandra](https://blog.anant.us/apache-cassandra-lunch-33-cassandra-deployment-ansible-and-terraform-with-cassandra/)
- We discuss using Terraform and Ansible to set up the infrastructure for and handle the provisioning of a new Cassandra cluster
    - [YouTube](https://youtu.be/gaYAKf6SQNw)
    - [SlideShare](https://www.slideshare.net/AnantCorp/how-to-build-a-multidc-cassandra-cluster-in-aws-with-opscenter-lcm)

- - -

### [Apache Cassandra Lunch Online Meetup #34: Liquibase and Cassandra](https://blog.anant.us/apache-cassandra-lunch-34-liquibase-and-cassandra/)
- We discuss how to use Liquibase with Cassandra and DataStax Astra.
    - [YouTube](https://youtu.be/okPTMB6B_Rw)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-34-liquibase-and-cassandra)

- - -

### [Apache Cassandra Lunch Online Meetup #35: Data Operations with Spark and Cassandra](https://blog.anant.us/apache-cassandra-lunch-35-data-operations-with-spark-and-cassandra/)
- We discuss some basic data operations that you can do with Apache Spark and Cassandra.
    - [YouTube](https://youtu.be/fo18FOLepTg)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-35-data-operations-with-spark-and-cassandra)

- - -

### [Apache Cassandra Lunch Online Meetup #36: Specialized Databases on Cassandra](https://blog.anant.us/apache-cassandra-lunch-36-specialized-databases-on-cassandra/)
- We discuss various databases that can run on top of Cassandra.
    - [YouTube](https://youtu.be/6BUrpdB6ol4)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-36-specialized-databases-on-cassandra)

- - -

### [Apache Cassandra Lunch Online Meetup #37: CQL Copy for Data Operations](https://blog.anant.us/apache-cassandra-lunch-37-cql-copy-for-data-operations/)
- We discuss CQL Copy and how we can use it for Cassandra data operations.
    - [YouTube](https://youtu.be/qyD_M20K7Ic)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-37-cql-copy-for-data-operations)

- - -

### [Apache Cassandra Lunch Online Meetup #38: Cassandra SSTables and Spark](https://blog.anant.us/apache-cassandra-lunch-38-cassandra-sstables-and-spark/)
- We discuss Apache Spark projects that interact with Cassandra specifically through Cassandra’s SSTables
    - [YouTube](https://youtu.be/TPXaqL6HxOE)
    - [SlideShare](https://www.slideshare.net/AnantCorp/cassadralunch-38)

- - -

### [Apache Cassandra Lunch Online Meetup #39: General Apache Cassandra Updates](https://blog.anant.us/apache-cassandra-lunch-39-general-apache-cassandra-updates/)
- We discuss General Updates to Apache Cassandra and relevant articles of interest.
    - [YouTube](https://youtu.be/05FvegMilXg)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-39-general-apache-cassandra-updates)

- - -

### [Apache Cassandra Lunch Online Meetup #40: Scylla Migrator for Cassandra Data Operations](https://blog.anant.us/apache-cassandra-lunch-40-scylla-migrator-for-cassandra-data-operations/)
- We discuss Scylla’s Spark Migrator and walk through how we can use the Scylla Migrator for Cassandra Data Operations.
    - [YouTube](https://youtu.be/B_nkxJsRIag)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-40-scylla-migrator-for-cassandra-data-operations)

- - -

### [Apache Cassandra Lunch Online Meetup #41: Cassandra on Kubernetes - Docker/Kubernetes/Helm - Part 1](https://blog.anant.us/apache-cassandra-lunch-41-cassandra-on-kubernetes-docker-kubernetes-helm-part-1/)
- We discuss Cassandra on Kubernetes and give an introduction to Docker, Kubernetes, and Helm.
    - [YouTube](https://youtu.be/-I8cKQO_Qr0)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-41-cassandra-on-kubernetes-dockerkuberneteshelm-part-1)

- - -

### [Apache Cassandra Lunch Online Meetup #42: SSTable Files with SSTableloader](https://blog.anant.us/apache-cassandra-lunch-42-sstable-files-with-sstableloader/)
- We cover SSTable files, their relation to SSTableLoader, and we walk through an example using SSTableloader to load data taken from a cluster to a new, empty cluster.
    - [YouTube](https://youtu.be/c8URCX4Zey8)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-42-sstable-files-with-sstableloader)

- - -

### [Apache Cassandra Lunch #43: DSBulk with Sed & Awk](https://blog.anant.us/apache-cassandra-lunch-43-dsbulk-with-sed-and-awk/)
- We will introduce DSBulk or DataStax Bulk Loader, and show how we can use it with tools like sed and awk to do ETL on Cassandra data.
    - [YouTube](https://youtu.be/gFSICPMxcqI)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-43-dsbulk-with-sed-and-awk)

- - -

### [Apache Cassandra Lunch #44: Cassandra on Kubernetes - Docker/Kubernetes/Helm Fundamentals Part 2](https://blog.anant.us/apache-cassandra-lunch-44-cassandra-on-kubernetes-docker-kubernetes-helm-part-2/)
- We will introduce DSBulk or DataStax Bulk Loader, and show how we can use it with tools like sed and awk to do ETL on Cassandra data.
    - [YouTube](https://youtu.be/4woSDfVSkUY)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-44-cassandra-on-kubernetes-dockerkuberneteshelm-fundamentals-part-2)

- - -

### [Apache Cassandra Lunch #45: Alpakka Cassandra and Twitter](https://blog.anant.us/apache-cassandra-lunch-45-alpakka-cassandra-and-twitter/)
- In Apache Cassandra Lunch #45, we will discuss how you can stream tweets using Twitter4S (Scala Twitter client) and save them to Cassandra using Alpakka Cassandra. 
    - [YouTube](https://youtu.be/KEYO5DN9J1w)
    - [SlideShare](https://www.slideshare.net/AnantCorp/data-engineers-lunch-20-dataops-vs-devops)

- - -

### [Apache Cassandra Lunch #46: Apache Spark Jobs in Scala for Cassandra Data Operations](https://blog.anant.us/apache-cassandra-lunch-46-apache-spark-jobs-in-scala-for-cassandra-data-operations/)
- In Apache Cassandra Lunch #46, we will discuss how we can use Apache Spark jobs written in Scala to do Cassandra data operations, which will include a live walkthrough! 
    - [YouTube](https://youtu.be/UsIqNiSBY9I)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-46-apache-spark-jobs-in-scala-for-cassandra-data-operations)

- - -
### [Apache Cassandra Lunch #48: Airflow and Cassandra](https://blog.anant.us/apache-cassandra-lunch-48-airflow-and-cassandra/)
- In Cassandra Lunch #48, we will discuss using Airflow and Cassandra together. Airflow provides a Cassandra connection type and a Cassandra operator. We will explore what we can do to manage a Cassandra cluster via Airflow. 
    - [YouTube](https://youtu.be/h2OCveciEIA)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-48-airflow-and-cassandra)

- - -
### [Apache Cassandra Lunch #49: Spark SQL for Cassandra Data Operations](https://blog.anant.us/apache-cassandra-lunch-49-spark-sql-for-cassandra-data-operations/)
- We will discuss how to use Spark SQL to do Cassandra data operations such as moving data in Apache Cassandra tables.
    - [YouTube](https://youtu.be/eu7Rs9d4oFg)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-49-spark-sql-for-cassandra-data-operations)

- - -
### [Apache Cassandra Lunch #50: Machine Learning with Spark + Cassandra](https://blog.anant.us/apache-cassandra-lunch-50-machine-learning-with-spark-cassandra/)
- In Apache Cassandra Lunch #50, we will discuss how you can use Apache Spark and Apache Cassandra to perform basic Machine Learning tasks.
    - [YouTube](https://youtu.be/myIX0kkpL9U)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-50-machine-learning-with-spark-cassandra)

- - -
### [Apache Cassandra Lunch #51: Cassandra Cluster Design & Architecture](https://blog.anant.us/apache-cassandra-lunch-51-cassandra-cluster-design-and-architecture/)
- In Cassandra Lunch #51, we will discuss an overview of Cassandra cluster architecture, not to be confused with the Cassandra database architecture. Specifically, using Cassandra Datacenters to isolate workloads.
    - [YouTube](https://youtu.be/JWeKAu7XnYk)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-51-cassandra-cluster-design-architecture)

- - -
### [Apache Cassandra Lunch #52: Airflow and Cassandra - Cluster Management](https://blog.anant.us/apache-cassandra-lunch-52-airflow-and-cassandra-for-cluster-management/)
- In Cassandra Lunch #52, we will continue our discussion on using Airflow and Cassandra together. Last time we discussed the Cassandra operators and how they allow us to manipulate data on a Cassandra cluster. This time we will explore what other Cassandra processes we can manage from Airflow.
    - [YouTube](https://youtu.be/l6T735IxDiI)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-52-airflow-and-cassandra-for-cluster-management)

- - -
### [Apache Cassandra Lunch #53: Cassandra ETL with Airflow and Spark](https://blog.anant.us/apache-cassandra-lunch-53-cassandra-etl-with-airflow-and-spark/)
- We will discuss how we can set up a Cassandra ETL pipeline using Airflow and Spark
    - [YouTube](https://youtu.be/Bex__3cwiI0)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-53-cassandra-etl-with-airflow-and-spark)

- - -
### [Apache Cassandra Lunch #54: Machine Learning with Spark + Cassandra Part 2](https://blog.anant.us/apache-cassandra-lunch-54-machine-learning-with-spark-cassandra-part-2/)
- We will discuss how we can set up a Cassandra ETL pipeline using Airflow and Spark
    - [YouTube](https://youtu.be/3roCSBWQzRk)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-54-machine-learning-with-spark-cassandra-part-2/)

- - -
### [Apache Cassandra Lunch #55: Migrating PostgreSQL to Cassandra](https://blog.anant.us/apache-cassandra-lunch-55-migrating-postgresql-to-cassandra/)
- We will discuss the process and reasons for migrating your database from SQL(PostgreSQL) to NoSQL(Cassandra)
    - [YouTube](https://youtu.be/nNfq-XdcdNA)
    - [SlideShare](https://www.slideshare.net/AnantCorp/apache-cassandra-lunch-55-migrating-postgresql-to-cassandra)

- - -
