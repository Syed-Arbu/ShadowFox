Advanced Task – ShadowFox Data Science Internship

This folder contains my submission for the Advanced Level Task of the ShadowFox Data Science Internship.

📌 Task Objective
The goal of this task was to perform fielding performance analysis in cricket using a dataset created from ball-by-ball observations. The task focused on collecting raw fielding data, cleaning and processing it, applying a weighted scoring formula, and generating meaningful player performance insights with visualizations.

🛠️ Work Done
Data Collection
Created a structured dataset (cricket_fielding.csv) using Google Sheets.
Each row represented a ball with fielding details such as player name, position, action (pick/throw), and runs saved.
Data Processing
Uploaded dataset into Colab and cleaned missing/invalid entries.
Generated indicator columns for each type of pick/throw event (e.g., CleanPick, DropCatch, RunOut, etc.).
Performance Score (PS) Calculation

Applied the given weighted formula:
PS = WCP*CP + WGT*GT + WC*C + WDC*DC + WST*ST + WRO*RO + WMRO*MRO + WDH*DH + RunsSaved

Computed a Performance Score (PS) for every player.
Ranked players based on overall performance.
Visualization & Insights
Created bar plots of Performance Score by player.
Analyzed player-wise contributions: catches, run-outs, drops, and runs saved.
Added 2–3 line summaries per top player explaining performance and recommendations.

📂 Files in this Folder

cricket_fielding.csv → Raw dataset (collected from Google Sheets).
fielding_player_summary.csv → Computed player-wise stats and PS values.
Cricket_Fielding_Analysis.ipynb → Colab notebook with full code and outputs.
Cricket_Fielding_Analysis.pdf → Exported PDF version of the notebook.
screenshots/ → Google Sheet proof and top plots.
README.md → Description of the Advanced Task.

✅ Outcome / Learning
Learned how to design and build a custom dataset from raw observations.
Gained experience in data cleaning, feature engineering, and scoring metrics.
Applied visualization techniques to compare player performance fairly.
Understood how fielding contributions can be quantified in cricket using data-driven methods.

👉 With this task, I completed the Advanced Level of the internship and built a real-world sports analytics project combining data collection, cleaning, scoring, and visualization.
