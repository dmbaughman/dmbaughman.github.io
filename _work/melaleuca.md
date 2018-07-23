---
title: Melaleuca
order: 1
tags: [NodeJS, AngularJS, Elasticsearch, AWS Lambda, SASS, Gulp]
images: [melaleuca-search-bar.jpg, melaleuca-search-results.jpg, melaleuca-category-page.jpg, melaleuca-clean-gleam.jpg]
link: http://www.melaleuca.com
---

The main project I've worked on at Melaleuca is replacing their eCommerce search engine with Elasticsearch running on AWS.  I was responsible for setting up the search engine itself, the data stream from a NoSQL database, the REST API and the front-end application that ran on melaleuca.com.  The setup scripts for Elasticsearch and other AWS services were all written in NodeJS, heavily utilizing the AWS JavaScript SDK and other Node packages.  I created resourceful solutions to problems like accurate query suggestions and product relevance ranking using analytics data.  I leveraged the scripting capabilities of Elasticsearch to simplify client requests and standardize search requests across various applications.

On the front-end side, I made significant improvements over the prior product search experience by converting the search bar and results page to a single-page application, creating reusable components to standardize how product information is displayed, and introducing a localization pattern to minimize code maintenance.  I also identified key applications (e.g. product category page) where the search engine could be used to convert those pages to single-page applications.
