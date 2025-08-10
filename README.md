# College Grads Job & Skills Insights

## 📌 Objective
Analyze 2025 college graduate data to:
- Identify factors influencing employment outcomes
- Determine which skills and experiences improve hiring rates
- Build a predictive model for job status
- Provide actionable recommendations for universities and students

## 🛠 Tools & Libraries
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Jupyter Notebook**: For interactive analysis
- **Excel**: Dataset preparation

## 📂 Dataset
The dataset `college_grads.csv` contains:
| Column | Description |
|--------|-------------|
| Graduate_ID | Unique ID for each graduate |
| Major | Field of study |
| GPA | Grade Point Average |
| Skills | Comma-separated skills list |
| Internship_Experience | Yes/No flag |
| Job_Status | Hired / Not Hired |
| Salary | Salary offered (if hired) |

The dataset is intentionally small for demonstration but designed to simulate realistic hiring patterns.

## 🧹 Data Cleaning
- Standardized skills format
- Filled missing salaries with `0` for non-hired graduates
- Encoded categorical variables
- Created `Skill_Count` feature

## 📊 Exploratory Data Analysis
- **GPA vs Job Status** (Boxplots)
- **Internship Impact on Hiring**
- **Most Common Skills** (Frequency Barplot)
- Salary distributions by major

## 🤖 Machine Learning Model
- **Logistic Regression** to predict `Job_Status`
- Features: GPA, Internship Experience, Skill Count, Major
- Train/test split with model evaluation (accuracy, precision, recall)

## 💡 Key Insights
1. Internships significantly boost hiring chances.
2. Top 3 skills linked to jobs: Python, SQL, Data Analysis.
3. GPA has a positive impact, but skills matter equally.

## 📈 Recommendations
- Encourage internship participation
- Focus on top-demand technical skills
- Provide targeted career support for lower-employment-rate majors


