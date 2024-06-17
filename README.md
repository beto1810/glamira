# GLAMIRA WEBSITE CRAWLING PROJECT


 ![image](https://scamminder.com/include/uploads/2024/06/glamira.pt.png)


# :books: Table of Contents <!-- omit in toc -->

- [:briefcase: Business Case and Requirement](#briefcase-business-case-and-requirement)
- [:bookmark_tabs:Example Datasets](#bookmark_tabsexample-datasets)
- [A. Analysis](#a-data-analysis)
- [B. Building Machine Learning Model](#)

- [📃 What can you practice with this case study?](#what-can-you-practice-with-this-case-study)

---

# :briefcase: Business Case and Requirement


As a Data Engineer working for an AI company, your task is to design and implement an efficient web crawling bot to gather product photos along with their descriptions and information on website [www.glamira.com](www.glamira.com) for the purpose of training a machine learning model for jewelry product detection. Here are the key requirements:

### 1. Efficient Crawling Bot:

Develop a web crawler that can efficiently and accurately extract product photos, descriptions, and other relevant information from targeted websites.
Ensure the crawler adheres to the websites' robots.txt rules and terms of service.
Implement mechanisms to handle dynamic content, pagination, and possible anti-crawling measures.
Optimize the crawler for speed and low resource consumption.
Product Information Dictionary:

### 2.Create a well-structured dictionary to store the crawled data.
The dictionary should include keys for storing product IDs, names, descriptions, image URLs, prices, categories, and any other relevant information.
Ensure the dictionary format is consistent and easily convertible to a structured data format like JSON or CSV for further processing.

---

# :bookmark_tabs:Example Product Dictionay

```python
"GLAMIRA Earring Varandus": {
        "14K Yellow Gold & Lab Grown Diamond": {
            "Product Name": "GLAMIRA Earring Varandus",
            "Product ID": "149768",
            "Product Full Link": "https://www.glamira.com/glamira-earring-varandus.html?accent=olivegreen&alloy=yellow-585&stone1=lab-grown-diamond&stone2=lab-grown-diamond",
            "Category ID": "1039",
            "Price": "$801.00",
            "Carat": "0.26 crt  - VS",
            "Detail": {
                "accent": "olivegreen",
                "alloy": "yellow-585",
                "stone1": "lab-grown-diamond",
                "stone2": "lab-grown-diamond"
            },
            "Descript": "14K Yellow Gold & Lab Grown Diamond",
            "Product Image Path": [
                "/Users/dai/Documents/Data_Engineer/DE_K9_demo/Glamira_photo/photo/image_149768_GLAMIRA-Earring-Varandus_accent=olivegreen&alloy=yellow-585&stone1=lab-grown-diamond&stone2=lab-grown-diamond_1",
                "/Users/dai/Documents/Data_Engineer/DE_K9_demo/Glamira_photo/photo/image_149768_GLAMIRA-Earring-Varandus_accent=olivegreen&alloy=yellow-585&stone1=lab-grown-diamond&stone2=lab-grown-diamond_2"
            ]
        }
```



