# Netflix Data Analysis

This project analyzes Netflix titles using Python and visualizations to uncover trends and insights about the platform's content.

## 📂 Project Structure

Netflix_Project/
│
├─ data/
│ └─ netflix_titles.csv # Dataset
│
├─ notebooks/
│ └─ netflix_analysis.ipynb # Main analysis notebook
│
├─ images/ # Optional: exported charts
│
├─ requirements.txt # Python dependencies
└─ README.md # Project description

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud
- Jupyter Notebook

## 📊 Analysis and Visualizations

1. **Top 5 Genre Trends Over Years**  
   Shows how the popularity of the top 5 Netflix genres has changed over time.

2. **Ratings Distribution by Content Type**  
   Compares how content ratings are distributed across Movies and TV Shows.

3. **Top 10 Most Productive Directors**  
   Highlights directors with the most Netflix titles (excluding 'Unknown').

4. **Top 10 Most Popular Actors**  
   Shows actors appearing in the highest number of titles.

5. **Number of Titles Added Each Year**  
   Displays growth trends of Netflix content over the years.

6. **Duration Analysis by Content Type**  
   Compares the duration of Movies vs TV Shows using boxplots.

7. **Word Cloud of Descriptions**  
   Visualizes the most common words in Netflix content descriptions.

## ✅ Key Findings
- Certain genres like `Dramas` and `Comedies` dominate Netflix content.  
- Netflix has consistently added more content over the years, especially in recent years.  
- Some directors and actors contribute disproportionately to the library.  
- Content rating distribution reveals Netflix's target audience.  
- Duration analysis shows Movies tend to have longer runtimes than TV Shows.  
- Word cloud highlights recurring themes in content descriptions.

## 📥 Dataset
The dataset `netflix_titles.csv` includes:
- Title, Director, Cast
- Country, Date Added, Release Year
- Rating, Duration, Listed In (Genres), Description

## 📌 How to Run
1. Clone the repository:
git clone https://github.com/yourusername/Netflix-Data-Analysis.git
2. Install Dependencies
pip install -r requirements.txt
3. Open the notebook and run analyses:
jupyter notebook notebooks/netflix_analysis.ipynb
