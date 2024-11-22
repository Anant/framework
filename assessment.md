# Assessment for Candidates

This is an assessment we use to see what your level of aptitude is with industry tools that are freely available on the internet. 
We send this assessment to candidates we feel are good at the basic knowledge and are able to communicate. The goal is to see how you can use existing
documentation to achieve this or to figure something out. A big part of our company's work is to learn new tools, teach it internally, and communicate it to clients. 

What we're looking for is how well you reviewed the links, did additional research as needed, and how far you were able to go. Pick one track and let us know how far you get in 24-48 hours. You can take longer but we are making decisions soon so we're looking for folks who can quickly get started with instructions like this and start to figure things out.


- ## Data & Analytics / Batch Platform Data Engineering @[Anant.us](https://anant.us)
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

- ## Data & Analytics / Streaming Platform Data Engineering @[Anant.us](https://anant.us)
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


- ## Data & Analytics / Platform Operator @[Anant.us](https://anant.us)
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


- ## Data & Analytics / Generative AI / LLM Engineering @[Anant.ai](https://anant.ai)
- **Demonstrate knowledge of vector databases**
  - [Set up and use PGVector with PostgreSQL](https://github.com/pgvector/pgvector)
    - Store and query vector embeddings.
  - [Explore Qdrant for similarity search](https://qdrant.tech/documentation/quick_start/)
    - Index sample data and perform vector searches.

- **Demonstrate knowledge of AI frameworks**
  - [Implement LangChain for LLM applications](https://langchain.readthedocs.io/en/latest/)
    - Develop a simple application chaining language model prompts.
  - [Use LlamaIndex to connect LLMs with external data](https://github.com/run-llama/llama_index)
    - Build an index and query it using an LLM.
  - Able to use other technologies if you are more comfortable
    - Crew.AI, Semantic Kernel, Haystack

- **Advanced: Build an AI-powered application**
  - Combine vector databases and LLMs.
    - Create a semantic search application.
    - Implement a chatbot that provides context-aware responses.

- **Demonstrate LLM fine-tuning**
  - Fine-tune a language model for a specific task.
    - Use OpenAI or other cloud LLM Service
    - Document the fine-tuning process and results.
  - Advanced: Fine-tune a language model for a specific task.
    - Use open-source models compatible with your hardware.
    - Document the fine-tuning process and results.

## Customer Experience / No-Code Platform Engineer @[Appleseed.works](https://appleseed.works)
- **Demonstrate knowledge of no-code platforms**
  - [Build an app using Bubble.io](https://bubble.io/academy)
    - Create a data-driven application with user authentication.
  - [Develop a website with Webflow](https://university.webflow.com/)
    - Design a responsive site with interactive elements.

- **Integrate backend services**
  - [Use Xano as a backend](https://www.xano.com/learn/)
    - Connect your no-code front end to Xano's APIs.
  - [Implement Supabase for authentication and data](https://supabase.com/docs/guides/getting-started)
    - Set up user authentication and real-time data updates.

- **Incorporate Gen AI features**
  - [Integrate OpenAI's API](https://help.openai.com/en/articles/5112595-best-practices-for-api-key-safety)
    - Add AI-driven functionality to your app (e.g., chatbots, content generation).

- **Advanced: Deploy a full-stack application**
  - Combine front-end and back-end no-code tools.
    - Implement complex workflows and data integrations.
    - Ensure scalability and responsiveness.

- ## Customer Experience / Platform Engineer @[Appleseed.works](https://appleseed.works)
  - **Demonstrate basic knowledge of modern dev ops tooling**
    - [Bring up Wallabag on Docker](https://doc.wallabag.org/en/admin/installation/installation.html#installation-with-docker) 
    - Demonstrate working Wallabag Front End without any CSS Issues
    - Demonstrate working Wallabag API via Postman
      
  - **[Demonstrate knowledge of using REST API to send Data](https://doc.wallabag.org/en/developer/api/readme.html)**
    - [Authenticate external front end or back end application](https://doc.wallabag.org/en/developer/api/oauth.html)
    - Create a front end or back end tool in any language or using an [existing API wrapper](https://doc.wallabag.org/en/developer/api/resources.html)
    - Tool should be able to take a copied /pasted text
    - Tool should parse out all the links (http , https) 
    - Tool should parse any other text as "tags"
    - [Tool should import the links into the API using the URL and the Tags](https://doc.wallabag.org/en/developer/api/methods.html)
      
  - **Demonstrate knowledge of using REST API to retrieve Data**
    - [Authenticate external front end or back end application](https://doc.wallabag.org/en/developer/api/oauth.html)
    - [Given a "tag" retrieve and display URL, Tags, and if Applicable the Image Preview](https://doc.wallabag.org/en/developer/api/methods.html)


- ## Automation Engineer / Automation Platform Engineer @[Kono.team](https://kono.team)

- **Demonstrate knowledge of RPA tools**
  - Automate tasks with [RPA Framework](https://rpaframework.org/) or [RobotFramework]([https://www.uipath.com/rpa/academy](https://robotframework.org/)
    - Create an automation that performs data entry or web scraping.
  - [Use Python for scripting automation](https://automatetheboringstuff.com/)
    - Write scripts to automate repetitive tasks.

- **Implement Gen AI automation**
  - [Leverage AI services in automation]([https://cloud.google.com/ai-platform](https://www.make.com/en/integrations/openai-gpt-3))
    - Integrate AI completion in an Automated Workflow

- **Demonstrate API integration**
  - [Create workflows with Make](https://www.make.com/en/academy)
    - Connect apps and automate multi-step processes.
  - [Use Zapier for business automation](https://zapier.com/learn/)
    - Set up Zaps to automate tasks between different services.

- **Advanced: Build a business automation solution**
  - Combine RPA, AI, and API integrations.
    - Automate a complex business process end-to-end.
    - Document the workflow and tools used.
 
- ## Information Systems / Business Analyst / Platform Engineer @[Kono.team](https://kono.team)
  - **Demonstrate basic knowledge of cloud systems**
    - Identify and sign up for a software as a service which has a developer API (CRM, Project Management, etc.)
     - Salesforce, Hubspot, etc. 
     - Notion, Jira, Todoist, Trello
    - Identify and sign up for a platform as a service on which you can deploy front end, back end code
     - Heroku, Vercel, AWS Lambda
     - [Netlify](https://www.netlify.com), Vercel, Render
    - Identify and signup for a infrastructure as a service on which you can manage virtual machines
     - DigitalOcean, AWS, Azure
  
  - **Demonstrate basic knowledge general rapid prototyping [no code platform as a service](https://www.g2.com/categories/no-code-development-platforms)**
    - Using a rapid prototyping platform create a form to collect data from a potential job seeker (name, email, LinkedIn, GitHub, address, zip)
     - [Airtable](http://airtable.com), Google Forms, etc. 
     - Zoho App Creator, etc.
       
  - **Demonstrate basic knowledge general automation platform platforms as a service**
    - Using a general automation platform take data from a source system when data is entered and send it to a destination system in real-time
     - [Zapier](https://zapier.com), [Make](Make.com)
     - Microsoft Flow, Zoho Flow
       
  - **Demonstrate basic knowledge of general integration platforms platforms as a service**
    - Using a general automation platform take data from a source system, transform it, and then import it into a database
     - StitchData, XPlenty, Databox
       
  - **Demonstrate basic knowledge of general business intelligence platforms as a service**
    - Using a general business integration platform as a service retrieve data from an outside source such as an API or a database and visualize it in some way 
     - Domo, Tableau, Redash, Metabase

**Please submit:**

- Documentation of your work (code snippets, screenshots, write-ups) in a presentation or a document. 
- A brief explanation of your approach and any challenges faced.
- Any additional research or resources you utilized.
  

