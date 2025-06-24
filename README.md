# Marketing-Data-Analysis-2023-2025
This project contains a Jupyter Notebook (`Code.ipynb`) that performs an in-depth analysis of marketing data for "Baby Smile" and its competitors from 2023 to 2025. The project aims to understand various aspects of sales, revenue, and advertising spend across different regions, age groups, and product categories.

## Table of Contents
- Project Overview
- Dataset
- Key Features
- Installation
- Usage
- Contributing
- License

### Project Overview
This project focuses on analyzing a comprehensive marketing dataset to derive insights into "Baby Smile" and its competitors' performance. The analysis includes exploring sales trends, revenue generation, and the impact of various marketing channels (e.g., TV, Radio, OOH, Meta Ads, Google Ads, Influencer Marketing) on overall business metrics. The notebook utilizes Python libraries such as Pandas for data manipulation, Matplotlib and Seaborn for data visualization, and Scikit-learn for potential linear regression modeling.

### Dataset
The analysis is based on the [`Data.xlsx`](https://docs.google.com/spreadsheets/d/14fy5kGVq01B6WfxL_sNk9fdqh1ROaE2B/edit?usp=sharing&ouid=114746191043386222233&rtpof=true&sd=true) Excel file, which is expected to be located in the `/content/` directory if running in a Colab environment. The dataset contains 292,400 rows and 30 columns, covering marketing activities and performance from April 2023 to March 2025.
#### Key Columns:
- `date`: Date of the record
- `region`: Geographical region
- `age_group`: Consumer age group
- `category`: Product category (e.g., Diaper, Baby Food, Skin Care, Clothes)
- `brand`: Brand name (e.g., BABY SMILE, Kuchela, Baby Naughty, Hug Me)
- `sales`: Sales figures
- `Revenue`: Revenue generated
- `spend_tv`: Spend on TV advertising
- `spend_radio`: Spend on Radio advertising
- `spend_ooh`: Spend on Out-of-Home advertising
- `spend_meta_ads`: Spend on Meta (Facebook/Instagram) ads
- `spend_google_ads`: Spend on Google Ads
- `spend_taboola_ads`: Spend on Taboola ads
- `spend_programmatic_ads`: Spend on Programmatic ads
- `spend_connected_tv`: Spend on Connected TV ads
- `spend_email`: Spend on Email marketing
- `spend_sms`: Spend on SMS marketing
- `spend_whatsapp_marketing`: Spend on WhatsApp marketing
- `spend_print_ads_newspapers`: Spend on Newspaper print ads
- `spend_print_ads_magazines`: Spend on Magazine print ads
- `spend_direct_buy`: Spend on Direct Buy campaigns
- `spend_influencer_marketing`: Spend on Influencer Marketing
- `day_of_week`: Day of the week
- `month`: Month
- `year`: Year
- `quarter`: Quarter of the year
- `spend_natural_search`: Spend on Natural Search
- `spend_direct_traffic`: Spend on Direct Traffic
- `Total Ad Spend`: Total advertising spend
- `spend_referral_traffic`: Spend on Referral Traffic

### Key Features
- Data Loading and Inspection: Initial loading and examination of the dataset structure, columns, and data types.
- Data Cleaning and Preprocessing: Renaming columns for consistency and ease of use (e.g., `spend_tv ('00s)` to `spend_tv`, `sales ('0000s)` to `sales`).
- Exploratory Data Analysis (EDA): Visualizations and statistical summaries to understand sales trends, revenue performance, and advertising effectiveness.
- Marketing Mix Modeling (Potential): The presence of `LinearRegression` suggests an intention to model the relationship between marketing spend and outcomes like sales or revenue.

### Installation
To run this notebook, you'll need a Python environment with the following libraries installed:
`pip install pandas matplotlib seaborn scikit-learn openpyxl`

### Usage
- Clone the repository:
`git clone https://github.com/YourUsername/Baby-Smile-Marketing-Data-Analysis.git
cd Baby-Smile-Marketing-Data-Analysis`
- Place the dataset:
Ensure the `Data.xlsx` file is placed in the same directory as the Jupyter Notebook, or update the path in the notebook accordingly. If you are using Google Colab, you might need to upload the file to your Colab environment or mount your Google Drive.
- Open the notebook:
Launch Jupyter Notebook or JupyterLab and open `Code.ipynb`.
- Run the cells:
Execute the cells sequentially to reproduce the analysis.

### Contributing
Feel free to fork this repository, open issues, or submit pull requests. Any contributions to improve the analysis or add new features are welcome!

### License
This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
