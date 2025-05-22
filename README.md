# brokerage-calculation-app
A Streamlit-based web app that calculates Upfront+Trail and Trail-only brokerages using data from RTA MIS, NAV files, and raw brokerage input files. Outputs a processed Excel file with brokerage values.
### 📂 Inputs Accepted
The app processes the most recent Excel files from the following sources:
- **RTA MIS**
- **NAV Files from Finance**
- **Brokerage Raw Data**

### 📊 Key Features
- Automatically fetches and processes the latest relevant files
- Applies business rules to calculate Upfront+Trail and Trail-only brokerages
- Handles complex date-based logic for Trail brokerage
- Generates a clean, structured output Excel file
- User-friendly file upload interface via Streamlit

### 🛠️ Tech Stack
- Python
- Streamlit
- Pandas
- openpyxl / xlsxwriter
