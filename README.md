# Data Market Overview: Global Survey Analysis

### Project Overview
What does the data job market really look like right now? To find out, I analyzed a global survey of **630 data professionals**. I wanted to move past the hype and uncover the actual trends in salaries, work-life balance, and the skills that are getting people hired.

I transformed the raw survey responses into an interactive 3-page dashboard that answers the big question: **"Is Data a viable career path, and how hard is it to actually break in?"**

---

### The Dashboards

#### 1. Executive Summary (The Big Picture)
This page gives the 10,000-foot view of the global market.
* **What I looked for:** Where are the jobs? How much do they pay? How old is the average worker?
* **Key Finding:** The "Break-in Difficulty" gauge shows that **43% of people** found it moderately difficult to enter the field—validating that while the barrier to entry exists, it is not impossible.

#### 2. Workforce & Well-being (The Human Side)
Here, I dug into the "people" side of the data—diversity, happiness, and burnout.
* **The Reality Check:** While professionals generally have a good work-life balance (5.74/10), **Salary Satisfaction** was actually the lowest-rated metric (4.27/10).
* **The Irony:** "Better Salary" is the #1 reason people look for new jobs, yet it’s the area they are currently least happy with.

#### 3. Career & Skills (The Strategy)
A guide for anyone trying to switch careers or level up.
* **The Toolkit:** I analyzed which tools are actually being used daily.
* **The Switcher's Path:** I tracked the journey of **372 career switchers** to see where they landed. The verdict? The vast majority started as **Data Analysts**, proving it is the most reliable entry point.

---

### What I Discovered

* **The "Analyst" is the Gateway:** Despite the buzz around Data Science and Engineering, **Data Analyst** remains the standard entry-level role (381 respondents).
* **The US Influence:** The **United States** is still the dominant employer in this dataset, which heavily influences the global average salary of **$53.9k**.
* **Python is King:** If you are debating which language to learn, the data is clear: Python (420 users) significantly outpaces R (101 users) and SQL for general usage.
* **The "Switcher" Strategy:** For those changing careers, the data suggests you shouldn't aim for "Data Architect" on day one. Out of 372 switchers, 246 landed Data Analyst roles—making it the statistically safest bet.
* **The Gender Gap:** The industry still has work to do, with a roughly **74% Male / 26% Female** split across technical roles.

---

### Who is this for?

* **Aspiring Analysts:** Use the *Career & Skills* page to prioritize your learning (Hint: Focus on Python over R).
* **Recruiters:** Use the *Workforce* page to understand that money is the main driver for turnover (297 votes). If you want to retain talent, salary satisfaction needs to be addressed.
* **Career Switchers:** Use the *Switcher Destinations* chart to validate your roadmap.

---

### Behind the Scenes (Tools Used)

* **Power BI:** The core engine for the visualizations and interactivity.
* **Power Query:** I used this to handle the messy reality of survey data—standardizing inconsistent country names and cleaning up job titles.
* **DAX:** Used for the complex logic, including `Top N` rankings and dynamic text labels (like the "Top Pain Point" calculator).
* **Data Modeling:** I opted for an optimized flat-file architecture here to ensure fast performance and accurate aggregation across the demographic filters.

---

#### Executive Summary
![Executive Summary](https://github.com/roegzychux/Data-Market-Overview/blob/8b8a54e6749a9ba0e9cf8f81518b728c351b2bc3/Summary.png?raw=true)

#### Workforce & Well-being
![Workforce](https://github.com/roegzychux/Data-Market-Overview/blob/8b8a54e6749a9ba0e9cf8f81518b728c351b2bc3/Workforce%20and%20wellbeing.png?raw=true)

#### Career and Skills
![Career](https://github.com/roegzychux/Data-Market-Overview/blob/8b8a54e6749a9ba0e9cf8f81518b728c351b2bc3/Career%20%20skills.png?raw=true)

---

### How to View
* **Static Preview:** Check out the high-resolution screenshots above.
* **Interactive Mode:** Want to play with the data? Clone this repo and open the `.pbix` file in Power BI Desktop to explore the dashboards yourself.

### Author

**Aruogu Chukwunenye**
* [LinkedIn Profile](https://www.linkedin.com/in/chukwunenye-aruogu-09773022b)
* [X (Twitter)](https://x.com/roegzychux)

---
*This project is open-source. Feedback and contributions are welcome!*
