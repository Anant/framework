# Assessment for Candidates

This is an assessment we use to see what your level of aptitude is with industry tools that are freely available on the internet. 
We send this assessment to candidates we feel are good at the basic knowledge and are able to communicate. The goal is to see how you can use existing
documentation to achieve this or to figure something out. A big part of our company's work is to learn new tools, teach it internally, and communicate it to clients. 

What we're looking for is how well you reviewed the links, did additional research as needed, and how far you were able to go. Pick one track and let us know how far you get in 24-48 hours. You can take longer but we are making decisions soon so we're looking for folks who can quickly get started with instructions like this and start to figure things out.


- ## Data & Analytics / Batch Platform Data Engineering (anant.us)
  - **[Demonstrate basic knowledge of dev ops tooling](https://docs.datastax.com/en/docker/doc/index.html)**
    - [Bring up DSE on Docker](https://docs.datastax.com/en/docker/doc/docker/dockerQuickStart.html) 
    - Demonstrate working DSE OpsCenter Front End
    - Demonstrate working DSE Studio Front End w/ Spark, SparkSQL, Graph
    - Demonstrate working CQLSH/Nodetool commands in Docker exec
  - **[Demonstrate knowledge of using basic Spark to Import Data](https://docs.datastax.com/en/dse/6.7/dse-admin/datastax_enterprise/spark/usingDSESpark.html)**
    - Find a data set online or use Datastax Examples
    - Create a schema of use Datastax Example schema
    - Create a Spark Script (Python or Scala) OR Spark Job to import data into DSE
  - **Demonstrate knowledge of using basic Spark or SparkSQL to get counts**
    - Using imported data set show how to use Spark to do basic aggregations/ filtering
    - Can use Spark or Spark SQL
  - **Demonstrate knowledge of using an external tool to use CQL and SQL** 
    - Use an external tool like DBeaver or otherwise to show how to query data via CQL
    - [Start AlwaysOnSQL in DSE](https://docs.datastax.com/en/dse/6.7/dse-admin/datastax_enterprise/spark/alwaysOnSql.html)
    - [Use an external tool like DBeaver or otherwise to connect via JDBC and query data via SQL](https://docs.datastax.com/en/dse/6.7/dse-admin/datastax_enterprise/spark/simbaJdbcDriver.html)
  - **Demonstrate advanced knowledge of Spark Streaming on cloud Spark Platform**
    - Create an account on a Public Cloud that offers a ready to go Spark instance for free. 
      - Amazon EMR
      - Databricks Community
      - Google Cloud 
    - Consume a public stream from the internet via Spark Streaming and persist it. If you can’t find it create random data using faker libraries. 
      - Distributed DB
        - Amazon MCS
        - Azure Cosmos DB
        - Cassandra on Docker
        - Datastax Cloud
      - Distributed File Systems
        - S3
        - Azure Blob
        - GFS
    - Create a batch process that analyzes the data and creates a report / or visualization. 
      - Descriptive 
        - Aggregate SQL queries on information 
        - Histograms 
        - Time Series Visualization 
      - Predictive
        - Classification 
        - Regression 
        - Sentiment Analysis 
    - Deliver data 
      - Notebook Interface 
      - API 
      - Visualization 

- ## Data & Analytics / Streaming Platform Data Engineering (anant.us)
- **Demonstrate knowledge of distributed data systems**
  - [Work with DataStax Astra DB](https://docs.datastax.com/en/astra-db-serverless/index.html)
    - Connect to Astra DB (Cassandra) using CQLSH.
    - Perform basic CRUD operations.

- **Demonstrate knowledge of data streaming platforms**
  - [Work with DataStax Astra Streaming](https://docs.datastax.com/en/astra-streaming/index.html)
    - Create Astra Streaming (Pulsar)  topics and write a simple producer and consumer.
    - Connect to Astra Streaming (Pulsar) using Kafka producer / consumer. 

- **Advanced: Build a data pipeline**
  - [Integrate AstraDB to Astra Streaming](https://github.com/datastax/astra-streaming-examples) 
    - Create a CDC Connector from AstraDB (Cassandra) Table 1 to a Astra Streaming (Pulsar) Topic 1
    - Create a data producer that adds data to the Table 1, so data comes into the Topic 1
    - Create a Pulsar Function that performs an aggregation, or an enhancement on data in Topic 1 and saves it to Topic 2
    - Connect Topic 2 to save data to AstraDB (Cassandra) Table 2


- ## Data & Analytics / Platform Operator (anant.us)
  - **Demonstrate knowledge of cloud services and infrastructure with modular infrastructure as code**
    - Utilize AWS, Azure, or GCP to deploy data services.
    - Set up instances using Terraform
      - Create a jumpbox/ bastion node 
      - Create a set of 3 virtual machines with public and private IPs
      - Protect the public IP with firewall rules to only applicable rules for the application you are hosting
  - Demonstrate basic knowledge of configuration management
    - Using ansible, deploy a distributed application of your choice. 
      - Apache Cassandra / Datastax 
      - Apache Kafka / Confluent
      - Apache Spark 
    - Using ansible, deploy monitoring stack of your choice. 
      - ELK / BEK Stack
      - Prometheus / Grafana
  - Run a basic load on the distributed platform 
    - Using a load generator create traffic / load on the platform
    - Show how load is distributed evenly / unevenly on platform   


- ## Customer Experience / Platform Engineer
  - Demonstrate basic knowledge of modern dev ops tooling
    - [Bring up Wallabag on Docker](https://doc.wallabag.org/en/admin/installation/installation.html#installation-with-docker) 
    - Demonstrate working Wallabag Front End without any CSS Issues
    - Demonstrate working Wallabag API via Postman
  - [Demonstrate knowledge of using REST API to send Data](https://doc.wallabag.org/en/developer/api/readme.html)
    - [Authenticate external front end or back end application](https://doc.wallabag.org/en/developer/api/oauth.html)
    - Create a front end or back end tool in any language or using an [existing API wrapper](https://doc.wallabag.org/en/developer/api/resources.html)
    - Tool should be able to take a copied /pasted text
    - Tool should parse out all the links (http , https) 
    - Tool should parse any other text as "tags"
    - [Tool should import the links into the API using the URL and the Tags](https://doc.wallabag.org/en/developer/api/methods.html)
  - Demonstrate knowledge of using REST API to retrieve Data
    - [Authenticate external front end or back end application](https://doc.wallabag.org/en/developer/api/oauth.html)
    - [Given a "tag" retrieve and display URL, Tags, and if Applicable the Image Preview](https://doc.wallabag.org/en/developer/api/methods.html)
 
- ## Information Systems / Business Analyst / Platform Engineer
  - Demonstrate basic knowledge of cloud systems
    - Identify and sign up for a software as a service which has a developer API (CRM, Project Management, etc.)
     - Salesforce, Hubspot, etc. 
     - Jira, Asana, [Trello](http://leaves.anant.us/leaves/#!/?tag=trello)
    - Identify and sign up for a platform as a service on which you can deploy front end, back end code
     - Heroku, Zeit, AWS Lambda
     - [Netlify](http://leaves.anant.us/leaves/#!/?tag=netlify), Zeit, AWS CloudFront
    - Identify and signup for a infrastructure as a service on which you can manage virtual machines
     - DigitalOcean, AWS, Azure
  - Demonstrate basic knowledge general rapid prototyping no code platform as a service(https://www.g2.com/categories/no-code-development-platforms)
    - [Using a rapid prototyping platform create a form to collect data from a potential job seeker (name, email, LinkedIn, GitHub, address, zip)](http://leaves.anant.us/leaves/#!/?tag=nocode)
     - [Airtable](http://leaves.anant.us/leaves/#!/?tag=airtable), Google Forms, etc. 
     - Zoho App Creator, etc.
  - Demonstrate basic knowledge general automation platform platforms as a service
    - Using a general automation platform take data from a source system when data is entered and send it to a destination system in real-time
     - [Zapier](http://leaves.anant.us/leaves/#!/?tag=zapier), Tray.io
     - Microsoft Flow, Zoho Flow
  - Demonstrate basic knowledge of general integration platforms platforms as a service
    - Using a general automation platform take data from a source system, transform it, and then import it into a database
     - StitchData, XPlenty, Databox
  - Demonstrate basic knowledge of general business intelligence platforms as a service
    - Using a general business integration platform as a service retrieve data from an outside source such as an API or a database and visualize it in some way 
     - Domo, Tableau, Redash, Metabase

- ## Customer Experience / Platform Engineer (Enterprise)
    - Demonstrate Basic Knowledge of Sitecore
      - Create a ASP.NET MVC Accordion View
      - Create a controller to retrieve Data 
      - Use C# to connect your control to your View
      - Pull Accordion entry data from SQL
    - Demonstrate Basic Knowledge of Sitecore
      - Install Sitecore on Premise
      - Install Sitecore in the Cloud [ AWS | Azure ]
      - Develop and Deploy a View Rendering 
      - Develop and Deploy a Control Rendering 
      - Basic Understanding of Sitecore Packagaes 
      - Basic Understanding of Unicorn
      - Basic Understanding of TDS
  - Demonstrate Advanced Knowledge of Sitecore
    - Sitecore CICD CM & CD Deployment 
    - Personalization
    - Search
    - xDB installation, customization, and  maintenance   
    - Demonstrate the ability to Create aSsitecore Form
    - Demonstrate Integrating Sitecore with Third-Party APIs

- ## Customer Experience / Platform Architect (Enterprise)
    - Demonstrate Enterprise Architecutre Knowledge 
      - Demonstrate best practice knowledge for Sitecore, EpiServer, or Kentico
      - Demonstrate Cloud deployment knowledge
      - Demonstrate Horizontal & Vertical Scaling knowledge
      - Demonstrate Tier & CICD Deployment knowledge
      - Demonstrate the ability to communicate with the Client
  - Demonstrate Enteprise Architecture of Sitecore
    - Strong knowledge of On-Prem and Cloud Deployments
    - Strong knowledge on all features of Sitecore
    - Strong knowledge on Integrating Sitecore with Third-Party APIs
    - xDB installation, customization, and  maintenance    
