# Netflix Content Analysis

I wanted to know what's actually on Netflix: what kind of content it has, where it comes from, and how the catalogue has changed over the years. So I took a public Netflix dataset and dug in with Python.

This was done as a project during my data analytics course at Scaler.

## About the data

The dataset has **8,807 titles** and 12 columns, including type (movie or TV show), director, cast, country, date added, release year and genre.

## Questions I explored

- Does Netflix have more movies or TV shows?
- Which genres and countries dominate the catalogue?
- When are TV shows added during the year?
- How long does a movie take to land on Netflix after it's released, and does it depend on the genre?
- What does the content landscape look like for India, and how fast is it growing?
- Which director-cast pairs show up together the most?
- How do countries compare on content type and genre?

## What I did

1. **Cleaned the data:** handled missing values, converted dates and dropped columns I didn't need.
2. **Built new features:** such as the year added and the gap between release and arrival on Netflix.
3. **Explored one variable at a time:** with bar charts, count plots and histograms.
4. **Compared variables:** using pivot tables and heatmaps.
5. **Checked for outliers:** using the IQR rule and boxplots.
6. **Looked at correlation:** to see which genres tend to appear together.

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn and Google Colab.
