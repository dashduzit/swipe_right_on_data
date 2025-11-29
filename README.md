## ✅ Swipe Right On Data
A data engineering + behavioral analysis of modern dating apps

This project combines AWS cloud pipelines, analytical review data, and pyschological research to reveal the emotional patterns, attachment dynamics, algorithmic bias, and burnout behind today's "swipe culture".

## 📌 Problem Statement

Modern dating apps generate millions of user interactions daily, yet persistent user dissatisfaction continues across platforms such as Tinder, Bumble, and Hinge. Despite algorithmic matching, users repeatedly report issues related to fake profiles, safety risks, inconsistent matching quality, aggressive monetization, and unexplained account bans. These complaints suggest that the problem extends beyond individual user experiences and reflects deeper failures in platform governance, trust, and data transparency.

This project investigates user-generated review data to identify recurring behavioral, psychological, and systemic patterns driving dissatisfaction. By leveraging a full AWS cloud-based data pipeline, this analysis seeks to transform unstructured review data into actionable insights that explain how dating app design, moderation practices, and monetization strategies influence user trust, emotional well-being, and platform credibility.



## ⭐️ Project Overview

Online dating apps dominate modern dating, but behind the convenience are deeper issues:

- Fake profiles + catfishing/bots
- Algorithmic bias
- Dating fatigue 
- Dopamine-driven reward cycles 
- Privacy + governance concerns 
- Emotional burnout and ghosting patterns

This project analyzes real reviews from Bumble, Hinge, and Tinder, using a fully cloud-based data pipeline to uncover patterns hidden in the data — and proposes a redesigned, privacy-first dating app concept.

## ☁️ Cloud Architecture (AWS Pipeline)

This project uses a full AWS data engineering pipeline:

Raw Data → Amazon Textract → CSV Processing → S3 Storage → Glue Crawler → Athena Queries → Analysis

AWS Services Used:

- Amazon S3 - structured data storage
- AWS Glue - automated schema detection + cataloging
- Athena - SQL querying across all datasets
- CSV - Parquet conversion 

Three Independent Pipelines (One for Each Dating App):

- Pipeline A: Bumble
- Pipeline B: Hinge
- Pipeline C: Tinder 

Each pipeline includes:

- Cleaned CSV UTF-8 Files
- AWS S3 folder structure
- Glue crawler + database mapping
- Athena table for querying
- Sample SQL insights

## 📊 Data Volumes & Scale Section 

- 63 OCR-processed raw screenshots
- 164,000+ unified review records after joining
- 3 dating platforms integrated (Tinder, Bumble, Hinge)
- Structured into AWS Glue + Athena for scalable querying

## ⚙️ Core SQL Operations 

- Schema validation using Glue generated tables
- Cross-platform JOINs across all three datasets
- Count-based data volume verification
- Aggregation of star ratings and sentiment indicators
- Platform-level comparative analysis

## 🔑 Key Findings

- Over 50% of reviews across platforms were rated 1 star
- Scams, bots, and fake profiles were the most recurring complaint
- Users reported significantly higher burnout and emotional fatigue than non-users
- Monetization pressure strongly correlated with low star ratings
- Platform governance failure (bans, moderation, transparency) were repeatedly cited

## 🌐 How to Reproduce 

1. Upload raw CSV or OCR output files to Amazon S3
2. Configure AWS Glue Crawlers for schema detection
3. Create Athena tables from Glue Data Catalog
4. Execute SQL queries in the 'sql/' directory
5. Run the Jupyter notebook in '/notebooks' for visualization 

## 💡 Proposed Solution 

New dating app that uses job application stylings to find love. Pictures will not be used to avoid catfishing and superficial values that other dating apps tend to use. 






