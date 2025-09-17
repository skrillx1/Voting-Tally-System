# 🗳️ Voting Tally System

A simple **offline voting tally system** built with **HTML, Bootstrap, FontAwesome, and JavaScript**.  
It allows users to input votes, automatically tally results, and view live updates on a separate page.  
All data is stored in **localStorage** so that results persist even after refreshing the page.

---

## ✨ Features

- ✅ Add, Edit, and Remove Candidates  
- ✅ Input votes in a single line (e.g., `1 0 3 2`) where each number corresponds to a candidate per position  
- ✅ Skip a position by entering `0`  
- ✅ Live tally results on a separate `live.html` page (auto-updating without manual refresh)  
- ✅ Highlight new votes in the tally table  
- ✅ Show the **leading candidate** for each position with an icon ⭐  
- ✅ Export data to CSV:
  - `tally_results.csv` → full tally results  
  - `leading_candidates.csv` → top candidate per position  
- ✅ Reset data (clears localStorage)  
- ✅ Fully offline (Bootstrap & FontAwesome included locally)

---

## 🧑‍💻 Usage

### 1️⃣ Add Candidates
- Go to **index.html**  
- Enter candidate name in the input field and press **Enter** or click **Add**  
- Candidates can also be **edited** or **removed**

### 2️⃣ Input Votes
- Type a series of numbers in the voting input field  
  - Example: `1 0 3 2 4 6 7 0 9`  
  - The numbers represent candidate numbers (`1` = Candidate 1, `2` = Candidate 2, etc.)  
  - `0` means skip that position  
- Submit the votes → Tally table updates automatically  

### 3️⃣ Live View
- Open **live.html** in another browser tab or window  
- It will automatically show real-time tally updates  
- New votes will be **highlighted** in yellow for a few seconds  

### 4️⃣ Export Data
- Click **Export Data** in `index.html`  
- Two CSV files will be downloaded:
  - `tally_results.csv` → full table of votes  
  - `leading_candidates.csv` → only the leaders  

### 5️⃣ Reset Data
- Click **Reset Data** → Clears all votes and candidates from localStorage

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/skrillx1/Voting-Tally-System.git
Open index.html in your browser to manage candidates and votes

Open live.html in another browser tab to view live results
