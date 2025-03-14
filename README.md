# Summer Olympics Data Analysis Dashboard

![image alt](https://github.com/Sadat-Shakeeb/Olympics-Analysis-Web-app/blob/b14f976fc8497b6e7410c275ad76f809b5157ec3/Olympic-Logos-1.png)

Welcome to the **Summer Olympics Data Analysis Dashboard** – an interactive web application built with Python that explores the rich history of the modern Olympic Games. This project provides insights into the evolution of the Olympics through visualizations, tables, and interactive filters, all presented in a sleek, user-friendly dashboard powered by Streamlit.

---

## Table of Contents

- [Overview](#overview)
- [Live Demo](#live-demo)
- [Dataset Details](#dataset-details)
- [Features & Analysis](#features--analysis)
  - [Medal Tally](#medal-tally)
  - [Overall Analysis](#overall-analysis)
  - [Country-wise Analysis](#country-wise-analysis)
  - [Athlete-wise Analysis](#athlete-wise-analysis)
- [Technologies Used](#technologies-used)
- [Installation & Setup](#installation--setup)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This project dives into a historical dataset covering the modern Olympic Games from **Athens 1896** to **Rio 2016**. It is designed to help you explore trends, performances, and interesting facts about the Summer Olympics. The interactive dashboard allows users to filter data, view dynamic visualizations, and analyze key metrics with ease.

> **Note:** While the dataset includes both Summer and Winter Games, this analysis focuses solely on **Summer Olympics** data.

---

## Live Demo

Experience the dashboard live on Streamlit:  
[Visit the Live Dashboard](https://sadat-shakeeb-olympics-analysis-web-app-app-ykdnfo.streamlit.app/)

---

## Dataset Details

### Context

The dataset is a comprehensive historical record of the modern Olympic Games. It was scraped from [sports-reference.com](https://www.sports-reference.com) in May 2018. The original R code used for scraping and data wrangling is also available on GitHub, and I encourage you to check it out for more context and methodology.

**Important Details:**

- **Time Span:** Athens 1896 to Rio 2016
- **Data Composition:**  
  - Contains **271,116 rows** and **15 columns**.
  - Each row represents an individual athlete's participation in an Olympic event.

- **Key Columns:**
  - **ID:** Unique identifier for each athlete.
  - **Name:** Athlete's full name.
  - **Sex:** Gender (M or F).
  - **Age:** Age of the athlete (integer).
  - **Height:** In centimeters.
  - **Weight:** In kilograms.
  - **Team:** Team or country name.
  - **NOC:** National Olympic Committee 3-letter code.
  - **Games:** Year and season.
  - **Year:** The year of the event.
  - **Season:** Summer or Winter.
  - **City:** Host city.
  - **Sport:** Sport category.
  - **Event:** Specific event.
  - **Medal:** Medal won (Gold, Silver, Bronze, or NA).

> **Note:** Up until 1992, both Winter and Summer Games were held in the same year. Post-1992, the games have been staggered with Winter Games starting from 1994, followed by Summer in 1996, and so on. This project focuses solely on the Summer Olympics.

---

## Features & Analysis

The dashboard offers four main interactive analysis sections accessible from the sidebar:

### Medal Tally

- **Description:**  
  Analyze the medal distribution across different years and countries.
- **User Inputs:**  
  - Dropdown to select **Year**.
  - Dropdown to select **Country**.
- **Output:**  
  A dynamic table displaying the number of **Gold**, **Silver**, and **Bronze** medals for the selected criteria.

### Overall Analysis

- **Description:**  
  Get a bird’s-eye view of the Olympics with key performance indicators and trends.
- **Key Statistics (KPIs):**  
  - Editions (Years)
  - Hosts
  - Sports
  - Events
  - Nations
  - Athletes
- **Visualizations:**  
  - **Line Plot:** Participating Nations over the years.
  - **Line Plot:** Number of Events over the years.
  - **Line Plot:** Athletes participation over the years.
- **Additional Feature:**  
  A dropdown menu to select a specific sport and view a table of the **Most Successful Athletes** in that sport, sorted in descending order based on medals won.

### Country-wise Analysis

- **Description:**  
  Dive into a country-specific analysis to understand performance trends.
- **Visualizations & Outputs:**  
  - **Line Graph:** Country's medal tally trend over the years.
  - **Heatmap:** Visual representation of the sports in which the country excels.
  - **Data Table:** Top 10 athletes representing the selected country.

### Athlete-wise Analysis

- **Description:**  
  Explore individual athlete performance and demographics.
- **Visualizations:**  
  - **Age Distribution Graph:** Age profile of athletes participating in the Olympics.
  - **Sports-specific Age Distribution:** Age distribution of gold medalists across different sports.
  - **Line Graph:** Trends in **Men vs. Women** participation over the years.

---

## Technologies Used

- **Python** – The primary programming language for data analysis and application development.
- **numpy** – For efficient numerical computations.
- **pandas** – Data manipulation and analysis.
- **matplotlib** – Creating static, publication-quality visualizations.
- **Plotly** – Building interactive graphs.
- **seaborn** – Statistical data visualization.
- **Streamlit** – Rapid web application development for interactive dashboards.

---

## Installation & Setup

To set up and run the project locally, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/olympics-data-analysis.git
   cd olympics-data-analysis

