## ✅ Swipe Right On Data
A data engineering + behavioral analysis of modern dating apps

This project combines AWS cloud pipelines, analytical review data, and pyschological research to reveal the emotional patterns, attachment dynamics, algorithmic bias, and burnout behind today's "swipe culture".

## ⭐️ Project Overview

Online dating apps dominate modern dating, but behind the convenience are deeper issues:

	•	Fake profiles + catfishing
	•	Algorithmic bias
	•	Dating fatigue
	•	Dopamine-driven reward cycles
	•	Privacy + governance concerns
	•	Emotional burnout and ghosting patterns

This project analyzes real reviews from Bumble, Hinge, and Tinder, using a fully cloud-based data pipeline to uncover patterns hidden in the data — and proposes a redesigned, privacy-first dating app concept.

## ☁️ Cloud Architecture (AWS Pipeline)

This project uses a full AWS data engineering pipeline:

Raw Data → Amazon Textract → CSV Processing → S3 Storage → Glue Crawler → Athena Queries → Analysis

AWS Services Used:

	•	Amazon S3 – structured data storage
	•	AWS Glue – automated schema detection + cataloging
	•	Athena – SQL querying across all datasets
	•	CSV → Parquet conversion (optional step)

Three Independent Pipelines (One for Each Dating App):

	•	Pipeline A: Bumble (Complete)
	•	Pipeline B: Hinge (Complete)
	•	Pipeline C: Tinder (Complete)

Each pipeline includes:

	•	Cleaned CSV UTF-8 files
	•	AWS S3 folder structure
	•	Glue crawler + database mapping
	•	Athena table for querying
	•	Sample SQL insights






