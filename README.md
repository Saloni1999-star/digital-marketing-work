# Digital Marketing Analytics Workspace

This workspace provides a complete pipeline for analyzing digital marketing campaign performance using Python and Jupyter Notebook.

## Features

- **Data Cleaning & Preparation:** Handles missing values and standardizes column names.
- **Metric Calculation:** Computes ROI, CTR, CPR, and other key metrics.
- **Segmentation:** Analyzes ROI by campaign, age, gender, and platform.
- **Visualization:** Generates charts for ROI, CTR, CPR, and more.
- **Correlation Analysis:** Identifies which metrics most influence ROI.
- **Export:** Outputs summary tables and charts for stakeholders.

## Project Structure
eldeco-report-May-1-2025-to-May-31-2025 (1).xlsx eldeco-report.xlsx 
full_data_export.csv
 main.ipynb
 platform_performance.csv
README.md roi_by_age.csv 
roi_by_age.png 
roi_by_campaign.csv 
roi_by_campaign.png 
roi_by_gender.csv 
roi_by_gender.png 
roi_by_platform.png 
roi_results.csv 
roi_results.xlsx 
roi_summary.txt 
top_roi_drivers.csv 
top_roi_drivers.png 
valid_campaigns.csv 
workspace/digital marketing


## How to Use

1. **Install dependencies**  
   Run in a notebook cell:
   ```python
   %pip install pandas matplotlib seaborn openpyxl

2.Add your data
   lace your tab-separated data file in the workspace/ directory.

3. Run the analysis
   Open main.ipynb and run all cells to process data, calculate metrics, and generate outputs.

4.Review outputs

  -Summary tables: roi_by_campaign.csv, roi_by_gender.csv, roi_by_age.csv, platform_performance.csv, top_roi_drivers.csv
  -Charts: roi_by_campaign.png, roi_by_gender.png, roi_by_age.png, roi_by_platform.png, top_roi_drivers.png
  -Full export: full_data_export.csv
  -Summary report: roi_summary.txt

Customization
  -Adjust grouping columns and metric calculations in main.ipynb as needed.
  -Update the extract_platform function to match your campaign naming conventions.

License
For internal and educational use only.

For questions or suggestions, please contact the project maintainer.

