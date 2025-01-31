---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
redirect_from:
  - /portfolio
---

## 📦 Warehouse Management System (WMS)
**Company:** JSC "Ukrposhta"  
**Position:** Python Backend Engineer

During my work at Ukrposhta, I developed Frappe-based WMS for [pharmaceutical](https://apteka.ukrposhta.ua/) warehouse management.

Key Components:
- **Stock control**: Comprehensive control over the quantity of goods in the warehouse, their transfers and replenishment;
- **Optimal Route Algorithm**: Integration algorithms for calculating the optimal routes for picking and placing items in the warehouse;
- **Orders Manipulations**: Processing and managing orders, including packing, unpacking, and handling discrepancies.
- **UIS**: Integrating with the [UIS system](https://uislab.com/uk/) for sorting and processing orders, including preparing and packing orders in UIS line.
- **Inventoryzation**: Integrated warehouse inventory system;
- **System flexibility**: Adaptability of the system for different warehouses, which made it possible to use the WMS core for other Ukrposhta tasks.

![Warehouse Management System](/images/uis.png)

---
<br>

## 🛒Order Management System (OMS)
**Company:** JSC "Ukrposhta"  
**Position:** Python Backend Engineer

Also were developed complex systems for managing orders, products, and related operations such as reporting and integration with external APIs. The systems were designed to streamline backend processes for web stores [Ukrposhta Pharmacy](https://apteka.ukrposhta.ua/) and [Postmark](https://postmark.ukrposhta.ua/).

The system is built using the Frappe framework, which is a full-stack web application framework written in Python and JavaSctipt.

Key Components:
- **Order Management**: process the entire order cycle from creation on the web store to receipt by the customer;
- **Integration with External APIs**: FastAPI-based APIs for integration with ERP systems, Logistics management system, Web Store;
- **MIS**: Working with prescriptions for medicines in the Medical Information System [SKARB](https://skarb.ua/);
- **Reporting**: processing large amounts of data to automate reporting.


![Order Management System](/images/oms.png)

---
<br>

## 🏦 Fiscalization Service
**Company:** JSC "Ukrposhta"  
**Position:** Python Backend Engineer  

Key Components:
- Integrated OMS with **[State Fiscal Service](https://tax.gov.ua/)** via FastAPI;
- Enabled online & offline fiscalization, receipt cancellation, and Z-report generation;
- The project integrates with a Java library using the **JPype library** to handle RRO operations.


![Fiscalization Service](/images/fiscalization.png)

---
<br>


## 📄 Summarization API
**Company:** CGS-team  
**Position:** Junior AI Engineer

This project is a **Flask-based** API for summarizing financial memos using **GPT-4o**. It processes PDF files to extract and summarize relevant financial information into structured JSON responses.

Key Features:
- Produce structured financial memos;
- Generates summaries and extracts stock tickers;
- Extracts key sections such as thesis summary, business model, exit value, moat, risks, stakeholders, and bear case;
- Provides detailed verbose output including cost and token usage;
- Supports different environments (dev and prod) for OpenAI API keys;
- Provides a Flask-based API for interacting with the memo summarization.


![Summarization API](/images/summarization.png)

---
<br>

## ֎ RAG System
**Company:** CGS-team  
**Position:** Junior AI Engineer

My second project in CGS-team is an application that leverages **FastAPI**, **Pinecone**, and OpenAI to provide document embedding and real-time chat functionalities. The application is designed to handle document uploads, process and embed the content using **HuggingFace** embeddings, and store the embeddings in a Pinecone vector store.

Additionally, it features a WebSocket-based chat interface that allows users to interact with an AI assistant, which generates responses based on the context retrieved from the embedded documents.

Technologies used:
- **Pinecone**: For storing and querying document embeddings;
- **OpenAI**: For generating enhanced context-aware responses;
- **HuggingFace**: For using all-MiniLM-L6-v2 to embed documents and queries;
- WebSockets: For real-time communication in the chat interface;
- FastAPI: For building the web application and handling HTTP requests.

![RAG System](/images/rag.png)

