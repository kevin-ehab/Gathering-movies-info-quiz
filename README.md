# 🎬 Rotten Tomatoes Top Movies Poster Scraper

## 📌 Project Description

This project uses **Python**, `wptools`, and `PIL` to scrape and download movie posters of some of the highest-rated films on **Rotten Tomatoes**, using their **Wikipedia** pages as a source. It compiles the data into a CSV file for easy reference and further analysis.

---

## 📦 What It Does

- Loops through a list of top movies from Rotten Tomatoes.
- Uses `wptools` to fetch Wikipedia page data.
- Attempts to download the movie poster image from the Wikipedia API.
- Saves the images in a local folder (`bestofrt_posters/`).
- Stores movie titles, rankings, and poster URLs in a CSV file (`movies.csv`).
- Logs movies that had poster fetching issues for debugging.

---

## 🛠️ Technologies Used

- Python
- libraries:
  - Pandas
  - wptools
  - Requests
  - Pillow (PIL)

---

## ⚠️ Notes

- Some movies could not be processed due to:
  - Wikipedia API errors (e.g., invalid titles).
  - Broken or unidentifiable image URLs.
- Errors are printed and saved to the `image_errors` dictionary.
