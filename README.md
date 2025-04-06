# 🎵 Music Data Analysis with Pandas and Visualization

This project involves the exploration and analysis of a dataset containing information about songs, including features like popularity, danceability, energy, genre, year, and artist. Using Python libraries such as `pandas`, `matplotlib`, and `seaborn`, we perform data manipulation and generate visual insights.

---

## 📂 Dataset

- File used: `songs_normalize.csv`
- Contains data about thousands of songs including:
  - `artist`, `song`, `year`, `genre`
  - `popularity`, `danceability`, `energy`, `tempo`, etc.

---

## 🔍 Key Analyses

1. **Rihanna's Songs by Year**
   - Number of songs released by Rihanna each year
   - Displayed as a pink bar chart

2. **Top Pop Artists in 2011**
   - Artists with the highest number of pop songs released in 2011
   - Displayed in descending order

3. **Calvin Harris Genre Frequency**
   - Genres Calvin Harris has worked in more than once

4. **Feature Selection**
   - A new DataFrame with selected columns for focused analysis:
     `popularity`, `danceability`, `energy`, `year`, `tempo`, and `song`

5. **Popularity Score Calculation**
   - Custom score based on normalized values of popularity, danceability, and energy
   - Songs are ranked within each year by this score

6. **Top Songs in 2009**
   - Top 4 songs in 2009 based on the calculated score
   - Duplicate check applied

7. **Top 5 Least Danceable Songs**
   - Sorted by lowest danceability values
   - Visualized with a seaborn bar plot

---

## 📊 Visualizations

- Bar plot showing Rihanna's songs by year
- Seaborn barplot for top 5 tracks with the lowest danceability

---

## 🛠 Technologies Used

- Python
- pandas
- matplotlib
- seaborn

---

## 📌 How to Run

1. Make sure you have Python 3 installed
2. Install the required packages:
   ```bash
   pip install pandas matplotlib seaborn
