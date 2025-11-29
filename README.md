<h1>Global Layoffs Data Cleaning Project (MySQL)</h1>

<h2>Project Description</h2>
For this project, I built a full SQL data-cleaning workflow using a real global layoffs dataset. I created a new MySQL database, imported raw CSV data, and built a proper staging table to safely perform transformations. I removed duplicate records using window functions and row-number logic, standardized inconsistent values across fields (such as company names, industries, and countries), and cleaned formatting issues like leading/trailing spaces and non-uniform text. I converted date fields from text to proper DATE datatypes using STR_TO_DATE, handled null and blank values through conditional joins and targeted updates, and populated missing attributes wherever the data allowed. Finally, I removed unusable records and dropped unnecessary columns to produce a clean, analysis-ready table that could be used for exploratory data analysis in a subsequent project.

<h2>Original Data </h2>

- <b>[Assessing Economic Impact of Flooding in Lodi, NJ (Paper)](https://docs.google.com/document/d/1bXy9mlvtMvpCCLWGbdVJc_rUofjPmnbp3kYyPhTesbw/edit?usp=sharing)</b> 

<h2> Full SQL data-cleaning workflow </h2>

- <b>[Assessing Economic Impact of Flooding in Lodi, NJ (Slides)](https://docs.google.com/presentation/d/1MAV-2lbqZ2YATibR9okDVTS-g_jrq5X8uFV38nTuZW0/edit?usp=sharing)</b>

<h2>Excel </h2>

- <b>[Cost calculations](https://docs.google.com/spreadsheets/d/1hsg_o4XD1K8Wryk4KN3FJoGBKK-IOTESx8-AtxYUdWY/edit?usp=sharing)</b>
- <b>[Survay Data](https://docs.google.com/spreadsheets/d/1Ry0JlrJwZzfLHGjwyr0d_mVcgXK8ALT41-NceoIt9_w/edit?usp=sharing)</b>
