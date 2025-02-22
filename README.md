# AI Product Recommendation Agent

## Overview
An AI-powered system designed to recommend products by automating search, scraping, and comparison. Built with **CrewAI**, **AgentOps**, **Tavily**, and **ScrapeGraphAI**, it performs the following tasks:

1. **Query Generation**: Creates optimized search terms from user input.
2. **Product Search**: Finds products across multiple e-commerce platforms.
3. **Data Scraping**: Extracts detailed product information such as price, features, and ratings.
4. **Report Generation**: Compares products and highlights the best deals.

## Key Features
- **Multi-agent workflow** for seamless task execution.
- Scrapes and analyzes data from **multiple e-commerce platforms**.
- Generates **user-friendly comparison reports**.

## How It Works

### 1. User Input
The user provides a description or name of the product they are looking for.

### 2. Query Generation
The first agent processes the user input and generates optimized search queries and keywords.

### 3. Product Search
The second agent uses the generated queries to search for products across multiple e-commerce platforms.

### 4. Data Scraping
The third agent scrapes detailed product information (e.g., price, features, reviews) from the identified websites.

### 5. Report Generation
The final agent compiles the scraped data into a comparison report, highlighting the best deals and key differences between products.
#

# Generated report exmple

# Procurement Report: Coffee Machines

## Executive Summary

This report summarizes the procurement process for coffee machines, comparing prices and features from various online retailers in Egypt. Key findings include price variations across platforms and the availability of discounts on certain models. Recommendations are provided to optimize procurement decisions.

## Introduction

This report aims to provide a comprehensive overview of available coffee machines and their pricing in the Egyptian market. The scope includes identifying potential suppliers, comparing product specifications, and recommending the most cost-effective options for procurement.

## Methodology

The methodology involved searching for coffee machines on popular e-commerce websites in Egypt, such as Noon, Jumia, CairoSales, and Ubuy. Product details, including prices, specifications, and customer reviews, were collected and compared. The data was analyzed to identify price trends and potential cost savings.

## Findings

The following table presents a comparison of coffee machines and their prices from different websites:

| Product | Website | Current Price (EGP) | Original Price (EGP) | Discount (%) | Specifications | Agent Recommendation Rank | Agent Notes |
|---------|---------|---------------------|----------------------|--------------|----------------|---------------------------|-------------|
| ![NESPRESSO Essenza Mini](https://f.nooncdn.com/p/v1637142818/N12520634A_1.jpg?format=avif&width=800) NESPRESSO Essenza Mini 0.6 L 1310 W D030RE/EN85.R Red | Noon | 11000.0 | N/A | N/A | - Capacity: 0.6 L<br> - Power: 1310 W<br> - Color: Red | 3 | - Compact design<br> - Good for small spaces |
| ![Delonghi Dedica Espresso Coffee Machine](https://eg.jumia.is/unsafe/fit-in/500x500/filters:fill%28white%29/product/39/9459811/1.jpg?7251) Delonghi Dedica Espresso Coffee Machine, Silver EC685.M | Jumia | 8990.0 | 9100.0 | 1.0 | - Brand: De'Longhi<br> - Model: EC685.M<br> - Color: Silver | 4 | - Highly rated with 5 out of 5 stars<br> - Currently on discount. |
| ![Delonghi Dedica Espresso Coffee Machine](https://btech.com/media/catalog/product/cache/9ac35d44fbf9ab480e3973716ba09643/2/2/223687_oj4n6wcuvrvvp6sk.png) Delonghi Dedica Espresso Coffee Machine, Silver EC685.M | Jumia | 8990.0 | 9100.0 | 1.0 | - Rating: 5 out of 5(2) | 3 | - Good reviews |
| ![DeLonghi Dedica Pump Espresso Coffee Machine](https://cairosales.com/113638-large_default/delonghi-dedica-pump-espresso-coffee-machine-15-bar-ec685-bk.jpg) DeLonghi Dedica Pump Espresso Coffee Machine 15 Bar EC685 BK | CairoSales | 9499.0 | 11175.0 | 15.0 | - Model: EC685 BK<br> - Color: Black<br> - Warranty: International Warranty<br> - Coffee tamper: Accessory<br> - Weight (Kg): 4.2 | 4 | - Discounted price<br> - International warranty |
| ![Saeco Xelsis Fully Automatic Espresso Coffee Machine](https://f.nooncdn.com/p/v1576650542/N32598803A_1.jpg?format=jpg&width=240) Saeco Xelsis Fully Automatic Espresso Coffee Machine 1.7 L SM7683/00 Black | Noon | 0.0 | N/A | N/A | - Colour Name: Black<br> - Capacity: 1.7 L<br> - Model Number: SM7683/00 | 2 | - Fully automatic<br> - Large capacity |
| ![Barista Espresso Machine](https://f.nooncdn.com/p/v1635188547/N14047025A_1.jpg?format=avif&width=240) Barista Espresso Machine 1700.0 W BES870 Black | Noon | 0.0 | N/A | N/A | - Material: Stainless Steel<br> - Installation: Countertop<br> - Colour Name: Black<br> - Energy Used: Electric<br> - Wattage: 1700 W | 4 | - Stainless steel<br> - High wattage |
| ![Breville Barista Espresso Machine](https://f.nooncdn.com/p/v1607612986/N30157259A_1.jpg?format=jpg&width=240) Breville Barista Espresso Machine 1700W 2.0 L 1700.0 W BES870CRN Cranberry | Noon | N/A | N/A | N/A | - Material: Stainless Steel<br> - Installation: Freestanding<br> - Colour Name: Cranberry<br> - Product Length: 40.7 cm | 3 | - Stainless steel<br> - High wattage |

## Analysis

The analysis reveals that the Delonghi Dedica Espresso Coffee Machine (EC685.M) is available on Jumia and CairoSales, with slight price variations. Jumia offers a small discount. The Saeco Xelsis and Breville Barista machines on Noon have prices listed as 0.0 or N/A, indicating potential unavailability or listing errors. The PHILIPS 3200 Series on Ubuy appears to have an unusually low price, which may require further investigation.

## Recommendations

1. Prioritize the Delonghi Dedica Espresso Coffee Machine from Jumia due to the current discount and positive reviews.
2. Verify the availability and pricing of the Saeco Xelsis and Breville Barista machines on Noon before making a decision.
3. Investigate the unusually low price of the PHILIPS 3200 Series on Ubuy to ensure its authenticity and reliability.
4. Consider the specific needs of the users (e.g., capacity, features) when selecting a machine.

## Conclusion

This procurement report provides a detailed comparison of coffee machines available in the Egyptian market. By considering the findings and recommendations, informed decisions can be made to procure the most suitable and cost-effective coffee machines.
