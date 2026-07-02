# Day 9 – NutriScope: MVP vs Enhanced Version

## 📌 Objective

The goal of Day 9 was to understand the power of **prompt iteration** by building two versions of the same AI-generated application using Claude. The first prompt generated a Minimum Viable Product (MVP), while the second prompt enhanced the application with improved design, features, and user experience.

---

# 🛠️ Project Overview

NutriScope is an AI-generated nutrition dashboard that helps users explore nutritional information through an interactive web application. This project demonstrates how iterative prompting can significantly improve an application's quality, usability, and functionality.

---

# 🚀 Version 1 – MVP

### Features

* Basic nutrition dashboard
* Essential input fields
* Simple nutritional analysis
* Functional user interface
* Core HTML, CSS, and JavaScript implementation

### Screenshot

<img width="1743" height="855" alt="Screenshot 2026-07-02 163616" src="https://github.com/user-attachments/assets/58f2cb05-af98-4af6-882f-6d0f934e1bae" />

### Generated HTML File

[nutriscope.html](https://github.com/user-attachments/files/29594677/nutriscope.html)

---

# ✨ Version 2 – Enhanced

### Improvements

* Modern and responsive UI
* Improved user experience
* Better data visualization
* Enhanced recommendations
* Additional interactive components
* Cleaner layout and styling
* Optimized frontend logic

### Screenshot

<img width="1137" height="705" alt="Screenshot 2026-07-02 163740" src="https://github.com/user-attachments/assets/bb2e7053-36fb-4a90-a875-984ec1abafb6" />

### Generated HTML File

[nutriscope_enhanced.html](https://github.com/user-attachments/files/29594708/nutriscope_enhanced.html)

---

# 📊 MVP vs Enhanced Comparison

| Feature                     | NutriScope (MVP)                                                                                      | NutriScope Enhanced                                                                                                                                    |
| --------------------------- | ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Food Database**           | 20 foods                                                                                              | 68 foods (20 original + 48 new)                                                                                                                        |
| **Nutrients Tracked**       | 10 nutrients (Calories, Protein, Carbs, Fat, Fiber, Iron, Calcium, Vitamin C, Vitamin D, Vitamin B12) | 16 nutrients (adds Potassium, Magnesium, Zinc, Sodium, Vitamin A, Folate)                                                                              |
| **Food Logging**            | Manual food entry, editable table, remove entries                                                     | Manual logging + CSV upload (drag & drop/click), fuzzy food matching, import summary report                                                            |
| **Charts & Visualizations** | Macronutrient doughnut chart and Energy bar chart                                                     | Enhanced doughnut and bar charts (center totals, gradients, styled tooltips) + Micronutrient Radar Chart + 7-Nutrient Balance Bar Chart                |
| **Dashboard**               | KPI cards, nutrient table, deficiency and excess indicators                                           | Reorganized dashboard with a modern tabbed interface and additional sections                                                                           |
| **Meal Planning**           | Not available                                                                                         | Dedicated 2-Day Meal Planner with Balanced, High Protein, Iron Focus, and High Fiber plans including Breakfast, Lunch, Snack, and Dinner               |
| **Risk Analysis**           | Not available                                                                                         | Risk Analysis tab with Overall Balance Score, 8 nutrient risk cards, and Watch/Monitor/Stable status badges                                            |
| **Recommendations**         | Additions, Food Swaps, Portion Tips                                                                   | Includes all MVP recommendations plus Timing & Pattern guidance, Nutrient Pairing, and Priority Focus recommendations                                  |
| **Disclaimer**              | Small footer disclaimer                                                                               | Prominent educational disclaimer banner displayed above the dashboard                                                                                  |
| **Data Sources**            | Not specified                                                                                         | Dedicated Sources tab referencing IFCT 2017, USDA FoodData Central, Mifflin-St Jeor Equation, ICMR-NIN RDAs, NIH ODS, WHO/FAO, and project limitations |
| **Navigation**              | Single scrolling page                                                                                 | Multi-tab navigation (Dashboard, Meal Planner, Risk Analysis, Sources)                                                                                 |
| **Design & Technology**     | Dark theme, Chart.js, single HTML file, no backend                                                    | Improved dark theme, enhanced UI, Chart.js visual improvements, single HTML file, no backend                                                           |

### 🏆 Overall Improvement

The Enhanced version significantly expands the MVP by introducing a larger food database, more nutrient tracking, advanced charts, CSV import support, meal planning, risk analysis, improved recommendations, transparent data sources, and a better-organized tabbed interface. While the MVP demonstrates the core functionality of NutriScope, the Enhanced version transforms it into a more comprehensive, interactive, and user-friendly nutritional analysis dashboard.


---

# 💡 Key Insights

* Prompt refinement significantly improves AI-generated applications.
* Iterative development helps transform a simple prototype into a polished product.
* Better prompts lead to cleaner code and more intuitive interfaces.
* AI can accelerate frontend development while reducing manual effort.
* Comparing multiple versions highlights the impact of structured prompt engineering.

---

# 📚 Key Learnings

* Learned how to build an MVP using AI-generated code.
* Understood the importance of prompt chaining and iterative prompting.
* Explored how UI and UX can be improved through better instructions.
* Practiced testing, comparing, and documenting multiple application versions.
* Strengthened GitHub documentation and project organization skills.

---

# 🎯 Conclusion

Day 9 demonstrated how prompt engineering and iterative AI development can dramatically improve an application's design, functionality, and user experience. By comparing the MVP and Enhanced versions of NutriScope, I gained practical experience in refining AI-generated applications and learned the value of structured prompting for building higher-quality software.
