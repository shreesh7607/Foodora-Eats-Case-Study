# Foodora Eats – Restaurant Analytics (Dataverse Case Study)

This repository contains the complete analysis and deliverables for the **Dataverse Business Analytics Challenge – Foodora Eats Case Study**.  
The objective of this project is to analyse a real world multi country restaurant dataset, diagnose quality and engagement gaps, and recommend actionable strategies to improve discovery, customer experience, and platform efficiency.

---

## Project Overview

- Analysed **9.5k restaurants × 22 features** across multiple countries using Python (`pandas`, `numpy`, `matplotlib`, `seaborn`).
- Merged and cleaned:
  - `Foodora Data.csv`
  - `Country Code.xlsx`
- Resolved missing cuisines, handled duplicates, standardised city/locality fields, and engineered new variables including:
  - Country & city identifiers  
  - Operational attributes  
  - Cuisine categories  
  - Engagement metrics (votes, ratings)
- Delivered a **3 slide executive deck** covering:
  1. Data Understanding  
  2. Key Insights  
  3. Final Recommendations  

---

## Key Analyses & Insights

### **1. Country & City Performance**
- India stands out as a **high engagement but under optimised** market.  
- It has many restaurants and strong voting activity, yet ratings fall below the global benchmark.

### **2. New Delhi Deep Dive**
- Largest city by restaurant count.  
- High customer engagement but comparatively **low average rating**.  
- Offers the **largest leverage** for quality uplift and supply curation.

### **3. Locality-Level Clusters**
Identified high supply but low rating zones such as:
- Shahdara  
- Mayur Vihar Phase 1  
- Mahipalpur  
- Krishna Nagar  
- Mukherjee Nagar  

These localities are prime candidates for **targeted interventions** (quality improvement, merchant programs, curated listings).

### **4. Cuisine Matrix (Delhi)**
High-demand cuisines:
- North Indian  
- Chinese  
- Fast Food  
- Mughlai  

These show systemic **quality deficiencies** despite strong demand and high vote volumes, signalling opportunity for:
- Quality improvement  
- Partner training  
- Better ranking logic  

### **5. Operational Levers**
- Availability of **online delivery** and **table booking** correlates with **higher ratings and higher engagement**.  
- Extremely low price restaurants often show **trade-offs in quality**, while mid range segments deliver stronger “value for money”.

### **6. Hidden Gems Identification**
- Implemented rule based logic to detect:
  - Highly rated  
  - Affordable  
  - Underrated/low visibility  
  restaurants.
- Supports creation of a **“Hidden Gems” discovery layer** and **quality weighted ranking strategy**.

---
