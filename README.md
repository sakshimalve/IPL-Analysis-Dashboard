# IPL Analysis Dashboard (2008-2025)

An **IPL Analysis Dashboard** built using **Power BI** to analyze IPL data from **2008 to 2025**.  
This dashboard provides insights into team performances, player statistics, and overall tournament trends.

---

## 📊 Features
- **Season-wise analysis (2008-2025)** with dynamic filtering
- **Champions & Runner-up** details for each season
- Key metrics:
  - Total Matches
  - Total Teams
  - Total Venues
  - Total 4's and 6's
  - Centuries and Half-Centuries
- **Player Insights:**
  - *Orange Cap* – Top run-scorer with total runs and team
  - *Purple Cap* – Top wicket-taker with total wickets and team
  - Top Fours and Sixes Leaders
- **Team Performance Table** showing matches played, won, lost, tied, and no-result

---

## 🛠 Tech Stack
- **Power BI** – Dashboard creation and data visualization
- **Excel/CSV** – IPL dataset storage and preprocessing
- **GitHub** – Version control and project sharing

---

## 📝 How I Created This Project

Here’s the process I followed to create this IPL Analysis Dashboard:

### 1. **Data Collection**
- Collected IPL datasets from **trusted sources** such as Kaggle and ESPN Cricinfo.
- Data included:
  - Match details (teams, venues, dates, results)
  - Player performance stats (runs, wickets, sixes, fours)
  - Season winners and runner-ups

### 2. **Data Cleaning & Preparation**
- Used **Excel** to clean the dataset:
  - Removed duplicate entries
  - Fixed missing or incorrect values
  - Standardized team and player names
- Created separate sheets for:
  - Match details
  - Player stats
  - Season summary

### 3. **Importing Data into Power BI**
- Loaded the cleaned data into Power BI.
- Connected multiple tables using **relationships**:
  - Matches table linked to teams and players.
  - Season summary table linked to year filters.

### 4. **Building the Dashboard**
- Designed different **visuals**:
  - Cards for Total Runs, Fours, Sixes, Venues, etc.
  - Tables for team performance.
  - Player images and stats for Orange Cap & Purple Cap.
  - Slicer for filtering data by season.
- Used **DAX (Data Analysis Expressions)** for calculated fields like:
  - Total matches
  - Total fours and sixes
  - Centuries and half-centuries

### 5. **Formatting & Styling**
- Applied a clean **theme** for better readability.
- Added team logos and player images for a professional look.
- Used background images and layouts to match IPL branding.

### 6. **Testing**
- Verified data accuracy by cross-checking with original sources.
- Ensured all filters and slicers worked correctly.

### 7. **Publishing & Sharing**
- Saved the `.pbix` file and uploaded it to **GitHub**.
- Added a project preview screenshot (`Screenshot (15).png`).

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/ipl-analysis.git
