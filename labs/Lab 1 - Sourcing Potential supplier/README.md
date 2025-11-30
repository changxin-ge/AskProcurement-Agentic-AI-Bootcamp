# Lab 1 : Sourcing Potential Supplier

## Table of Contents
- [1. Introduction](#introduction)
- [2. Accessing Watsonx Orchestrate UI](#rfp-generation-agent)
- [3. Sourcing Potential Supplier Agent](#sourcing-potential-supplier-agent)

- [4. Testing the agent](#testing-agent)
- [5. Deploying the Agent (Optional)](#deploying-agent)
- [6. Summary](#summary)


<details open id="introduction">
<summary><h2>1. Introduction</h2></summary>

This lab focuses on automating the process of sourcing potential suppliers using Watsonx Orchestrate. The goal is to optimize procurement decisions by leveraging AI-driven workflows and enterprise system integrations.

The specific scenario involves identifying the best supplier for a given product based on key factors such as **cost** and **delivery time**. These decisions are critical for ensuring timely procurement and cost efficiency in large-scale operations.

In this lab, you will build an AI-powered agent within Watsonx Orchestrate that:

* Integrates with **SAP S/4HANA** using pre-built agents to access supplier data.
* Retrieves and analyzes supplier information including pricing and delivery timelines.
* Applies decision logic to recommend the most suitable supplier.
* Presents the recommendation in a clear, actionable format for procurement teams.

By automating supplier sourcing, procurement teams can:

* Eliminate manual comparison of multiple suppliers.
* Ensure data-driven, consistent decision-making.
* Accelerate procurement cycles and improve operational efficiency.

[← Back to Table of contents](#table-of-contents) 
</details>


<details open id="introduction">
<summary><h2>2. Accessing Watsonx Orchestrate UI</h2></summary>

1. To access the watsonx Orchestrate console, go to the [Resources list on the IBM Cloud homepage](https://cloud.ibm.com/resources).
 ![alt text](images/img1.png)

2. Expand the **AI / Machine Learning** section and select the resource that has **watsonx Orchestrate** in the Product column, as shown above. Then click **Launch watsonx Orchestrate**.

  ![alt text](images/img2.png)

This opens the watsonx Orchestrate console.

  ![alt text](images/img3.png)

[← Back to Table of contents](#table-of-contents)