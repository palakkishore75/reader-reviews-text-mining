
# Reader Reviews & Publishing Trends: A Big Data NLP Project

This project explores how qualitative reader reviews can drive strategic decisions in publishing. Using NLP techniques like sentiment analysis and BERTopic, we analyzed over 21,000 reviews to uncover genre trends, emotional drivers, and thematic clusters relevant for editorial and marketing teams.

## Files Included

### 1. SQL Notebooks
- `Part1_Data_Acquisition.ipynb` – Web scraping from Hardcover and querying Google Books API using ISBNs.
- `Part2_TextAnalysis_TopicModelling.ipynb` – Text cleaning, sentiment scoring using VADER, and topic modeling using BERTopic with UMAP + HDBSCAN.

### 2. Project Report and Presentation
- `Project_Report.pdf` – Full documentation of our methods, pipeline, analysis, and recommendations.
- `Slides.pptx` – Key insights presented visually for quick review.

## Data Sources

- Hardcover.app: User-submitted book reviews from 2014–2024.
- Google Books API: Book metadata including average rating, genre, and ratings count.

## Techniques Used

- Web Scraping – BeautifulSoup, requests
- Text Processing – spaCy, VADER sentiment analysis
- Topic Modeling – BERTopic with UMAP and HDBSCAN
- Visualization – WordCloud, matplotlib, seaborn

## Key Insights

- Fiction, Fantasy, and Young Adult are top engaging genres with rich topic diversity.
- Sentiment and topic clusters reveal critical factors like emotional responses to endings and audiobook experiences.
- Global review clusters (Spanish, Dutch) highlight international expansion opportunities.

## Business Impact

Publishers can apply these insights to:
- Tailor book acquisitions and editorial focus.
- Strengthen series/franchise investments.
- Launch localized or format-specific campaigns.
- Use reader-driven feedback for trend detection and risk mitigation.

## Team & Course Info

- Course: Enterprise Cloud Computing & Big Data (BUDT758J)
- Instructor: Prof. John Silberholz
- Team Members: Anushka Jain, Loveleen Kaur, Megha Mudigonda, Manasvi Surasani, Palak Kishore
