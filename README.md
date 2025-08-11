# Airbnb Listing Optimization: A Data-Driven Analysis

### Interactive Dashboard: [https://your-username.github.io/airbnb-analytics-dashboard/](https://your-username.github.io/airbnb-analytics-dashboard/)
### Tableau Public Version: [Link to your Tableau Public Dashboard]

---

## 1. The Business Problem

Airbnb's success depends on its hosts' ability to secure bookings. A significant number of listings were identified as "redundant," failing to attract a single booking over a long period. My hypothesis was that a **low quantity of listing photos was a key driver of this underperformance.**

This project sought to validate this hypothesis and deliver a data-driven strategy to increase host success and booking volume across the platform.

---

## 2. My Analytical Approach

To solve this problem, I followed a structured analytical process:

* **Problem Identification:** Analyzed the "Open Listings" and "Redundant Listings" data to quantify the impact of low image counts on unbooked days.
* **Solution Analysis:** Determined the optimal number of images that correlates with the highest number of bookings for both "Regular Hosts" and "Superhosts."
* **Factor Analysis:** Investigated secondary factors, such as listing age, to understand their influence on the primary relationship between images and bookings.
* **Tool Development:** Moved beyond simple recommendations to build a practical tool that empowers hosts to act on these insights immediately.

---

## 3. Key Insights & Recommendations

My analysis confirmed the initial hypothesis and yielded several actionable insights presented in the interactive dashboard:

* **Insight 1:** Listings with 0-5 photos are the primary cause of unbooked days and account for the majority of "redundant" listings.
* **Insight 2:** The "sweet spot" for maximizing bookings is **11-15 images**. Performance drops off for listings with more than 20 images.
* **Recommendation:** Airbnb should implement a **mandatory minimum of 6 photos** to move listings out of the "redundant" category and strongly recommend **11-15 photos** as a best practice for maximizing revenue.

---

## 4. The Solution: An Interactive Dashboard with an AI-Powered Tool

Instead of a static report, I developed a fully interactive web application to present these findings.

* **Interactive Storytelling:** The dashboard uses **Chart.js** to guide stakeholders through the data, from the problem to the solution, in a clear and compelling narrative.
* **AI-Powered Action Plan:** The key innovation is the **"AI Photo Planner."** By integrating the **Google Gemini API**, this feature provides hosts with a custom, actionable shot list based on their property's unique features. This bridges the gap between insight and action.

---

## 5. Technologies Used

* **Data Visualization & Frontend:** HTML, Tailwind CSS, Chart.js
* **AI Integration:** Google Gemini API
* **Hosting:** GitHub Pages
