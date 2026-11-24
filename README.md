# plp-da-a4-student-eda-and-board-repo
"""# Student EDA & Board Report Dashboard (Assignment Submission)
This repository holds the deliverables for both Engagement 1 (County Education Office Student Performance EDA) and Engagement 2 (Duka Electronics Board Report Visual Summary).

## Table of Contents
1. [Engagement 1 Summary](#engagement-1-summary)
2. [Five Key EDA Insights](#five-key-eda-insights)
3. [Engagement 2 Summary](#engagement-2-summary)
4. [150-Word Board Summary](#150-word-board-summary)
5. [How to Run the Project](#how-to-run-the-project)
6. 
## Engagement 1 Summary
This project provides the County Director of Education with evidence on which learners are most at risk of academic failure. It categorizes students into Performance Bands based on their calculated average score across Math, Reading, and Writing, identifies performance bottlenecks, and builds predictive models.

## Five Key EDA Insights
1. **High Impact of Study Hours**: Weekly study hours show an exceptionally strong positive correlation with overall average scores (slope = 1.39 points per hour, R² = 0.74).
2. **The School Type Gap**: Private school students consistently outperform public school peers across all attendance bands and study hour segments.
3. **Mombasa is the Highest-Risk County**: Mombasa has the highest percentage of 'At Risk' students (~14.45%), making it the prime target for initial funding.
4. **Critical Outliers**: Multiple students study significantly longer hours than average (up to 49 hours) without experiencing a negative plateau, though return levels diminish slightly at extremums.
5. **Gender Performance Balance**: Overall academic achievement remains remarkably balanced across genders, with average scores varying by less than 1%.

---

## Engagement 2 Summary
This deliverable provides the Duka Electronics Board of Directors with a high-impact, single-page, non-technical visual report reviewing performance in the first half of 2026. 

### Embedded Board Report
![Duka Board Report](reports/duka_board_report.png)

---

## 150-Word Board Summary
Duka Electronics completed the first half of 2026 with $2.9M in total revenue, displaying steady upward momentum. Performance was heavily anchored by the Nairobi region, which generated approximately 40.5% of total sales, followed closely by Rift Valley (25.3%). In terms of product lines, 'Phones & Tablets' ($1.71M) and 'Laptops & Computers' ($1.16M) remain our primary growth engines, while 'Home Appliances' and 'Accessories' showed lower volume metrics relative to regional pricing dynamics. Rift Valley remains a high-value territory with the highest average unit prices, presenting an optimal market for premium product launches. Conversely, the Lake Region represents our smallest market footprint (14.7%). To sustain margin health and expand overall market share in H2 2026, the board should direct targeted marketing investments towards Nairobi and Rift Valley laptops, while initiating inventory clearance strategies for lower-margin categories in lagging regions.

---

## How to Run the Project
1. Ensure Python 3.8+ is installed.
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. To generate the datasets, run:
   ```bash
   python generate_data.py
   ```
4. Open and run all cells of `student_eda.ipynb` and `board_report.ipynb` end-to-end.
"""

with open('README.md', 'w') as f:
    f.write(readme_content)

print("Saved README.md to root directory!")
