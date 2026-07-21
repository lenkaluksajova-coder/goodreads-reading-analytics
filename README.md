![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-blue?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power_Query-green?style=for-the-badge)
![AI](https://img.shields.io/badge/AI-Assisted-purple?style=for-the-badge) 

# 📚 Goodreads Reading Analytics | Power BI Portfolio Project

> An end-to-end data analytics project built in Power BI, transforming a Goodreads export into an interactive dashboard through data enrichment, modeling, DAX, and storytelling.

---

# 📖 Project Overview

This project started with a simple question:

> **Can a basic Goodreads export be transformed into a professional analytical dashboard?**

The answer became this project.

The goal was not simply to create attractive charts, but to demonstrate the complete analytical workflow expected from a Data Analyst:

- collecting data
- identifying missing information
- enriching the dataset
- cleaning and transforming data
- creating a data model
- writing DAX measures
- designing an intuitive dashboard
- telling a meaningful story through data

The final result is an interactive Power BI dashboard that explores my reading history from multiple perspectives while demonstrating practical Power BI skills.

---

# 🎯 Objectives

The project had three main objectives:

- demonstrate practical Power BI skills
- practice end-to-end data analytics
- create a portfolio project suitable for job applications

Instead of presenting unrelated visualizations, every report page was designed around a specific analytical question.

---

# 📂 Data Source

The dataset originated from an exported Goodreads library.

The original export contained information such as:

- Title
- Author
- Rating
- Publication Year
- Number of Pages
- Reading Dates
- Publisher
- Language
- Format

While useful, the export lacked many attributes required for richer analysis.

---

# 🔍 Data Enrichment

One of the most interesting parts of this project was enriching the original dataset.

I initially explored several APIs hoping to retrieve additional information automatically, including:

- Author Country
- Author Gender
- Original Language
- Audiobook Length
- Missing ISBN Metadata

Although multiple APIs were tested, none provided a complete and reliable solution for my entire library. Some returned incomplete data, while others lacked important fields or had strict usage limitations.

Rather than manually researching hundreds of books, I chose a different approach.

Using a carefully engineered prompt, I delegated the enrichment process to an AI agent.

The AI agent searched, validated and completed the missing metadata across the dataset in approximately **15 minutes**, producing an enriched dataset that became the foundation of the Power BI model.

This experience highlighted an important lesson:

> Modern analytics is not only about writing code—it is also about selecting the most effective tool for solving a problem.

---

# 🛠 Data Preparation

The enriched dataset was further processed using Power Query.

The preparation included:

- cleaning inconsistent values
- standardizing formats
- removing duplicates
- creating calculated columns
- preparing dimensions for analysis
- validating publication years
- separating books from audiobooks where appropriate

---

# 📊 Dashboard Design

Rather than grouping visualizations by chart type, every page was designed around a business question.

---

## 📚 Reading Overview

### Question

> **What does my reading journey look like overall?**

This page provides a high-level summary of the entire reading history.

Key metrics include:

- Books Read
- Average Rating
- Pages Read
- Audiobook Hours
- Authors Read
- Countries Read

Together with the yearly trend, these KPIs provide an instant overview of reading activity.

---

## 📖 What Do I Read?

### Question

> **What kinds of books do I usually read?**

This page explores reading preferences through:

- Genres
- Fiction vs. Non-fiction
- Reading Languages
- Reading Formats
- Book Length Distribution
- Publication Timeline

The goal is to understand the composition of the reading library.

---

## ❤️ What Do I Love?

### Question

> **Which books do I enjoy the most?**

Instead of focusing on quantity, this page focuses on quality.

It highlights:

- Favourite Books
- Favourite Authors
- Favourite Publishers
- Favourite Genres
- Favourite Author Countries

Interactive filters allow the report to be explored from different perspectives.

---

## 📈 Reading Habits

### Question

> **How have my reading habits changed over time?**

This page focuses on behaviour rather than content.

It analyzes:

- Monthly Reading Trend
- Reading Formats Over Time
- Reading Speed

The purpose is to identify long-term reading patterns rather than individual books.

---

## 🌍 My Literary World

### Question

> **Where do the authors I read come from?**

This page visualizes the geographical diversity of my reading using a world map.

Each country displays:

- Number of Books Read
- Average Rating

This allows geographical reading preferences to be explored interactively.

---

## 🏅 Reading Highlights

### Question

> **What are the most interesting facts hidden in my reading history?**

Instead of traditional KPIs, this page presents memorable highlights, including:

- Longest Book
- Longest Audiobook
- Oldest Book
- Newest Book
- Most Read Author
- Average Rating by Book Length
- Author Gender Distribution

This page serves as the final summary of the reading journey.

---

# 💡 Challenges

Some challenges encountered during the project included:

- working with incomplete Goodreads metadata
- choosing between API integration and AI-assisted enrichment
- ensuring consistency across all report pages
- deciding which publication year should be used (original publication vs. edition year)
- designing visuals that remained informative without becoming cluttered

---

# 🧠 Skills Demonstrated

This project demonstrates practical experience with:

- Power BI
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- Data Modeling
- Data Enrichment
- Dashboard Design
- Interactive Reporting
- Data Storytelling
- Analytical Thinking
- AI-assisted data preparation

---

# ⚙️ Tech Stack

- Power BI Desktop
- Power Query
- DAX
- Goodreads Export
- AI-assisted Data Enrichment
- GitHub

---

# 🚀 Future Improvements

Potential future enhancements include:

- automatic metadata enrichment through APIs
- integration with Goodreads API (if available)
- reading goal tracking
- predictive reading analytics
- sentiment analysis of book reviews

---

# 👤 Author

**Lenka Luksajová**

Junior Data Analyst Portfolio Project

Created as part of my journey into Data Analytics and Power BI.
