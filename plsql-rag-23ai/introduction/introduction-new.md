# Build RAG Applications with Oracle AI Vector Search and PL/SQL

## About this Workshop

In this workshop, you'll get hands-on experience building the workflow of a RAG application using PL/SQL. This sample application is meant to be a simplified version of a typical chatbot. Initially, you're interacting with a generic LLM. However, as you upload your own data, the application uses RAG to familiarize the model with the data and produce higher quality responses.

Once you better understand the impact of RAG, we explain how the backend workflow of the application was built to achieve the demoed functionality. You'll get to understand the multi-step RAG workflow (as explained in the video below), while witnessing how Oracle Database 23ai makes this process a breeze!

<iframe  src="https://www.youtube.com/embed/pu79sny1AzY?si=RhghSWeXsachSiED" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> </br>


### **About Retrieval Augmented Generation (RAG)**

Retrieval Augmented Generation (RAG) plays a pivotal role in Generative AI, offering significant advantages to Gen AI applications. Here are three compelling reasons why integrating RAG into your Gen AI setup is paramount:

1. Minimize Hallucinations:  Large Language Models (LLMs) may generate inaccurate or irrelevant responses if they lack training on prompts. Re-training LLMs to align with desired responses incurs substantial costs.  
2. Safeguarding Confidentiality: LLMs are trained on publicly available information from the internet – they do not know about your company specific data. Do not send your company specific information across the internet as you are giving away your private information to a 3rd party.  Instead keep your enterprise data within your realm by using local LLMs within your data center or cloud tenancy.
3. Up to date information: LLMs are trained up to a certain date [eg Sept 2021 for ChatGPT], newer events/facts are unknown. The LLM can provide responses based on up-to-date facts in the form of prompts provided by your vector database.  This means that your LLM has the benefit of the latest data from your company without the need to train the LLM on your company data.

RAG addresses these challenges by enabling the inclusion of vital context alongside prompts provided to LLMs. In our laboratory scenario, this context comprises business information stored in Oracle Database 23ai as vectors. Using Oracle PLSQL and Oracle AI Vector Search makes implementing a RAG architecture simple.

![RAG image](images/rag_image.png)


**_Estimated Time: 45 min_**

### **About Oracle AI Vector Search**

Oracle AI Vector Search is a feature of Oracle Database 23ai.  It allows the  searching of AI vectors in the database.  Oracle AI Vector Search supports fast search with a number of indexing strategies and can handle very large amounts of vector data.

AI Vector Search makes it possible for LLMs to query private business data using a natural language interface and helps LLMs provide more accurate and relevant results. In addition, AI Vector Search allows developers to easily add semantic search capabilities to both new applications and existing applications.

### **Objectives**

In this workshop, you will:
* Get familiar with the new Vector Datatype & PLSQL packages for manipulating vector data and operations
* Using PLSQL for developing applications with Large Language Models [LLMs]
* Using Oracle AI Vector Search to store and search vectors in Oracle Database 23ai
* Access popular LLMs and generate output
* Run a complete sample application to implement all learnings

### **Prerequisites**

This workshop assumes you have:

- An Oracle LiveLabs Sandbox environment.

## Learn More

See below for more information on Oracle Database 23ai and Oracle AI Vector Search

* [Oracle Database 23ai Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/)
* [Oracle AI Vector Search User's Guide](https://docs.oracle.com/en/database/oracle/oracle-database/23/vecse/index.html)
* [Oracle AI Vector Search Blog](https://blogs.oracle.com/database/post/oracle-announces-general-availability-of-ai-vector-search-in-oracle-database-23ai)

You may now [proceed to the next lab](#next).

## Acknowledgements
* **Authors** - Milton Wan, Vijay Balebail, Douglas Hood
* **Contributors** - Brianna Ambler, Database Product Management
* **Last Updated By/Date** -  Milton Wan, May 2024
