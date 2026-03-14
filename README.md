# Netflix Movies & TV Shows - Exploratory Data Analysis & Strategic Insights

![Netflix Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/0/08/Netflix_2015_logo.svg/320px-Netflix_2015_logo.svg.png)

Exploratory analysis of the Netflix catalog (`netflix_titles.csv`) with visualizations and **business-oriented strategic recommendations** for content acquisition and production.

**Last updated**: March 2026  
**Dataset**: Netflix Titles (~8,807 entries)

## 🎯 Project Objectives

- Understand the distribution of **Movies** vs **TV Shows**
- Identify the top content-producing countries
- Analyze content growth trends over time
- Explore the most and least represented genres
- Provide actionable strategic recommendations for Netflix

## Key Files

| File                            | Description                                            |
|---------------------------------|--------------------------------------------------------|
| `Netflix-trends-analysis.ipynb` | Main Jupyter Notebook (EDA + visualizations + insights) |
| `netflix_titles.csv`            | Original dataset (~8,807 titles)                       |
| `README.md`                     | This file                                              |

## Main Analyses Performed

- **Movies** (~70%) vs **TV Shows** (~30%) breakdown
- Top production countries: United States, India, United Kingdom, Canada, France...
- Dominant genres: International Movies, Dramas, Comedies
- Underrepresented genres: Stand-Up Comedy, Sports Movies, Classic & Cult Movies...
- Production trends (peak around 2017–2019, recent years 2020–2021)
- Average duration / number of seasons by genre
- Rating distribution (TV-MA and TV-14 strongly dominant)

## Strategic Business Recommendations (Summary)

1. **Heavily invest in dominant & high-demand genres**  
   → International Movies, Dramas, Comedies

2. **Accelerate growth in promising mid-tier categories**  
   → International TV Shows, Documentaries, Action & Adventure

3. **Increase catalog diversity** by developing underrepresented areas  
   → Stand-Up Comedy, Sports Movies, Classic Movies, Cult Films

4. **Significantly increase the proportion of TV Shows**  
   → Better long-term viewer retention & subscription loyalty

5. **Expand investment in emerging production markets**  
   → South Korea, Spain, Japan, Mexico, Turkey, Germany...

6. **Strengthen family-friendly & younger audience content**  
   → Increase titles rated TV-PG, TV-Y, TV-Y7, etc.

## Technologies Used

- Python 3.9+
- pandas
- matplotlib
- seaborn
- missingno (missing values visualization)

## How to Run the Project

1. Clone the repository
```bash
git clone https://github.com/your-username/netflix-analysis.git
cd netflix-analysis
