# 🧠 Mental Health & Social Media Lifestyle Dashboard

A Power BI Analysis of Screen Time, Emotional Wellbeing, and Digital Behavior Patterns

This project presents an end-to-end Power BI dashboard built by merging and transforming two Kaggle datasets related to social media usage and mental health indicators. Through data cleaning, model building, and visualization design, the project explores how digital behaviors influence emotional wellbeing, distraction levels, sleep quality, and stress.

## 📊 Dashboard Preview

### Dashboard 1: Emotional & Behavioral Wellbeing
![Dashboard Screenshot](https://github.com/Tatheer-Za-ra/Power-Bi-Project-Mental-Health-and-Social-Media-Dataset/blob/main/Dashboard%201.png)

- **Avg Happiness Index**
- **Avg Depression Score**
- **Depression Score Distribution**
- **Sleep Quality by Platform**
- **Worry Levels by Age**
- **Screen Time vs Stress Correlation**

### Dashboard 2: Digital Habits & Lifestyle Metrics
![Dashboard Screenshot](https://github.com/Tatheer-Za-ra/Power-Bi-Project-Mental-Health-and-Social-Media-Dataset/blob/main/Dashboard%202.png)

- **Avg Daily Screen Time**
- **Avg Distraction Score**
- **% Using Social Media Without Purpose**
- **Avg Days Without Social Media**
- **Screen Time by Platform**
- **Happiness & Exercise Frequency by Occupation**
- **Restlessness vs Validation Seeking by Platform**

---

## 🎯 Project Objective

To turn raw survey data into meaningful, actionable insights about how social media habits, platform choices, and digital routines correlate with mental wellbeing.

The dashboards aim to:
- **Measure emotional wellness** (happiness, worry, depression)
- **Understand lifestyle habits** (exercise frequency, device usage, screen time)
- **Identify platform-based behavioral patterns**
- **Explore distraction, restlessness, and validation-seeking tendencies**
- **Highlight potential digital wellbeing risks**

---

## 🧩 Dataset Overview

Two datasets from Kaggle were merged using `User_ID` as the key:

### Dataset 1: Social Media Usage & Mental Health Survey
**Source:** [Social Media and Mental Health Dataset](https://www.kaggle.com/datasets/souvikahmed071/social-media-and-mental-health?select=smmh.csv)

| Original Column | Refined Name (for documentation) | Description |
|----------------|----------------------------------|-------------|
| User_ID | User_ID | Unique identifier for each respondent |
| 1. What is your age? | Age | Respondent's age |
| 2. Gender | Gender | Gender identity |
| 3. Relationship Status | Relationship_Status | Current relationship status |
| 4. Occupation Status | Occupation_Status | Professional/student status |
| 5. What type of organizations are you affiliated with? | Affiliated_Organizations | Organizational affiliations |
| 6. Do you use social media? | Social_Media_Usage | Yes/No response |
| 7. What social media platforms do you commonly use? | Social_Media_Platforms | Platform preferences |
| 8. What is the average time you spend on social media every day? | Daily_Social_Media_Time | Hours spent daily |
| 9. How often do you find yourself using Social media without a specific purpose? | Purpose_less_Usage_Frequency | Scale 1-5 |
| 10. How often do you get distracted by Social media when you are busy doing something? | Distraction_Frequency | Scale 1-5 |
| 11. Do you feel restless if you haven't used Social media in a while? | Restlessness_Without_SM | Scale 1-5 |
| 12. On a scale of 1 to 5, how easily distracted are you? | Distractibility_Score | Scale 1-5 |
| 13. On a scale of 1 to 5, how much are you bothered by worries? | Worry_Score | Scale 1-5 |
| 14. Do you find it difficult to concentrate on things? | Concentration_Difficulty | Scale 1-5 |
| 15. On a scale of 1-5, how often do you compare yourself to other successful people through the use of social media? | Social_Comparison_Frequency | Scale 1-5 |
| 16. Following the previous question, how do you feel about these comparisons, generally speaking? | Comparison_Feeling | Qualitative response |
| 17. How often do you look to seek validation from features of social media? | Validation_Seeking_Frequency | Scale 1-5 |
| 18. How often do you feel depressed or down? | Depression_Frequency | Scale 1-5 |
| 19. On a scale of 1 to 5, how frequently does your interest in daily activities fluctuate? | Interest_Fluctuation | Scale 1-5 |
| 20. On a scale of 1 to 5, how often do you face issues regarding sleep? | Sleep_Issues_Frequency | Scale 1-5 |

### Dataset 2: Lifestyle & Wellbeing Metrics
**Source:** [Social Media and Mental Health Balance Dataset](https://www.kaggle.com/datasets/ayeshaimran123/social-media-and-mental-health-balance/data)

| Column | Description |
|--------|-------------|
| User_ID | Unique identifier for each respondent |
| Age | Respondent's age |
| Gender | Gender identity |
| Daily_Screen_Time(hrs) | Total daily screen time in hours |
| Sleep_Quality(1-10) | Self-reported sleep quality score |
| Stress_Level(1-10) | Self-reported stress level |
| Days_Without_Social_Media | Average days without social media per week |
| Exercise_Frequency(week) | Weekly exercise frequency |
| Social_Media_Platform | Primary social media platform used |
| Happiness_Index(1-10) | Self-reported happiness score |

### Data Preparation Highlights
- **Full merge** on `User_ID`
- **Cleaned text responses** and standardized categorical values
- **Converted Likert scales** into consistent numeric formats
- **Created age buckets** for demographic analysis
- **Built calculated measures** for distraction, happiness, worry, purpose-less usage, etc.
- **Designed optimized data model** for Power BI visualization

---

## 🔑 Key Performance Indicators (KPIs)

### From Dashboard 1

| KPI | Value/Insight |
|-----|---------------|
| Avg Happiness Index | Ranges ~8.3–8.9 across platforms |
| Avg Depression Score | Mostly mid-range (3–4) dominance |
| Sleep Quality by Platform | X(Twitter) highest; Instagram lowest |
| Screen Time vs Stress | Stress increases sharply at 7–10 hrs/day |
| Worry Levels by Age | Younger users report more frequent worrying |

### From Dashboard 2 (Newly Added)

| KPI | Description |
|-----|-------------|
| Avg Daily Screen Time | Approx. 6 hours |
| Avg Distraction Score | 3/5 average |
| % Using Social Media Without Purpose | 82% |
| Avg Days Without Social Media | 3 days per week |
| Avg Time Spent per Platform | Instagram & Facebook highest (6 hrs) |
| Happiness Index by Occupation | Retired users report highest happiness |
| Exercise Frequency by Occupation | University students show most consistent exercise |
| Restlessness & Validation Seeking by Platform | TikTok & Twitter users show highest totals |

---

## 📈 Insights Breakdown

### Digital Behavior Trends
- **Most users spend 6 hours/day** on social media
- **82% report using social media** without any clear purpose
- **Users take 3 days off** social media per week on average

### Platform-Specific Findings
- **Instagram & Facebook** lead daily time usage
- **TikTok users** show the highest restlessness and validation-seeking patterns
- **Professional platforms** like LinkedIn show comparatively stable emotional indicators

### Wellbeing Patterns
- **Higher screen time correlates strongly** with higher stress
- **Happiness levels vary slightly** across occupation types, with retired individuals scoring highest
- **Exercise frequency impacts happiness scores** in multiple groups

### Younger Age Groups
- **Higher worry levels**
- **Increased distraction**
- **Heavier platform usage patterns**

---

## 🧭 Project Workflow

1. **Importing Data** from both Kaggle datasets
2. **Cleaning & Transforming** in Power Query
3. **Merging datasets** using `User_ID` as primary key
4. **Data Modeling** (star-schema layout)
5. **Creating DAX Measures** for advanced calculations
6. **Designing Interactive Dashboards**
7. **Publishing Professional-Grade Insights**

---

## 🚀 How to Use This Project

- **Clone the repository**
- **Open the `.pbix` file** in Power BI Desktop
- **Explore interactive filters** for Age, Gender, Occupation, Platform
- **Interact with visual elements** to uncover behavioral & emotional insights
- **Use drill-through features** for detailed analysis

---

## 💡 Future Enhancements

- **Build a "Digital Wellbeing Recommendation" engine** based on user profiles
- **Include cohort-wise drill-down navigation** for deeper demographic insights
- **Add real-time data connectivity** for ongoing monitoring

---

## 👩‍💻 Author

**Tatheer Zahra**  
Beginner BI Developer | Data Enthusiast
