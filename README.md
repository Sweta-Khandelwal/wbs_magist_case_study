# wbs_magist_case_study
Feasibility assessment of whether ENIAC should enter the Brazilian e-commerce market via Magist.

## 🎯 Project Overview

Created as a group project at **WBS Coding School**, this study investigates the commercial viability of launching Eniac’s premium tech catalog on the Brazilian marketplace Magist. By conducting exploratory data analysis on order fulfillment, delivery times, and product categories, our team assessed potential operational risks and delivered a data-backed recommendation on whether Eniac should proceed with the partnership.

---

### Company Background

* **Eniac:** A Spain-founded online marketplace operating in several European countries, positioning itself as a premier destination for Apple products and curated accessories.
* **Magist:** A Brazilian SaaS company offering a centralized order management system that connects small and medium-sized stores with major Brazilian marketplaces.

---

### Key Stakeholder Questions

Using SQL and exploratory data analysis, our team addressed two critical business concerns:
1. **Product Compatibility:** Does Magist's platform cater to high-end, Apple-compatible tech products?
2. **Delivery Speed:** Does Magist's public Post Office fulfillment network meet Eniac’s standards for fast customer delivery?

---

### ⚡ Team Electricity Contributors

Team members who collaborated on this project:

* **Sweta Khandelwal** - [GitHub Profile](https://github.com/Sweta-Khandelwal)
* **Asli Ergün**
* **Catalina Mayer**

## 📊 Dataset & Sources

* **Source:** Snapshot of Magist's Dataset provided by [WBS Coding School](https://github.com/WBSCodingSchool) for the case study.
* **Size:** Relational database comprising **~100,000 orders** across **9 interconnected tables** spanning a time period of **2016 to 2018**.
* **Key Features / Variables Used:** 
  * `orders`: Order status, purchase timestamps, delivery dates, and estimated delivery dates.
  * `order_items`: Product ID, seller ID, price, and freight/shipping value.
  * `products`: Product category names, product dimensions, and weight attributes.
  * `order_reviews`: Review score (ratings) and review comments(used to analyze the impact of delivery delays on customer satisfaction).
  * `customers`: Customer city and state locations (zip code prefixes).
* **Data Limitations & Preprocessing Notes:** 
  * **Tech Category Filter:** To align with Eniac's product focus, analysis was filtered to tech-related categories (`computers_accessories`, `computers`, `pc_gamer`, `tablets_printing_image`, `telephony`, `fixed_telephony`, `electronics`, `audio`, `cine_photo`, and `consoles_games`).
  * Product category names were originally in Portuguese and required translation using the provided category translation table.


