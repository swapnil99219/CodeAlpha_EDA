# Superstore Exploratory Data Analysis (EDA)

Exploratory analysis of the Sample Superstore dataset using Python to study sales, profit, products, customers, regions, and trends.

## Tools

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook / Google Colab

## Dataset

The saved report describes 9,994 records and 25 columns. The notebook preview currently shows 9,994 rows and 21 columns, so verify the final imported dataset and report before publishing a definitive schema description. The report also records no missing values and no duplicate rows; rerun the checks to confirm.

## Project files

| File | Purpose |
|---|---|
| `CodeAlpha_Superstore_EDA.ipynb` | Analysis notebook |
| `Superstore_EDA_Report.txt` | Summary report |
| `superstore_eda_summary.csv` | KPI summary |
| `superstore_category_analysis.csv` | Category analysis |

## Questions explored

- Which categories and regions generate the most sales?
- Which categories are most profitable?
- Which products generate the largest losses?
- How do sales change month by month?
- What relationship appears between discounting and profit?

## Reported summary metrics

The saved report lists total sales of **$2,297,200.86**, total profit of **$286,397.02**, 5,009 orders, 793 customers, and 37,873 units. These are reported outputs, not independently re-executed in this README update; rerun the notebook and reconcile definitions before relying on them.

## Findings recorded in the saved report

The saved report contains these results; rerun the notebook to independently verify them before presenting them as final conclusions.

1. **Technology leads in sales and profit** in the report, with sales of approximately $836,154 and profit of approximately $145,455.
2. **Furniture needs a profitability review:** the report lists about $742,000 in sales but only about $18,451 in profit, substantially below the other categories.
3. **Regional performance varies:** the West has the highest reported sales (about $725,458), while the South has the lowest (about $391,722).
4. **Some products show substantial losses:** the report lists the Cubify CubeX 3D Printer Double Head Print at about -$8,880 profit.
5. **Sales vary by month:** the report's highest listed monthly sales value is approximately $118,448 in November 2017.

## Business recommendations to validate

- Investigate furniture sub-categories and discount levels to understand low profitability before changing pricing.
- Review loss-making products alongside discount, shipping, and sales-volume data; do not assume discount alone caused the loss.
- Compare regional product mix and order volume to understand the West–South sales gap.
- Check seasonality and inventory planning around stronger sales months.
- Add a chart or table reference for each recommendation after re-running the notebook.

## How to run

1. Download the notebook and source dataset.
2. Open the notebook in Jupyter or Google Colab.
3. Update the dataset path for your environment.
4. Run all cells from top to bottom.
5. Compare the notebook outputs with the saved report and CSV summaries.

## Skills demonstrated

Data loading and quality checks, exploratory data analysis, aggregation, visualization, category and regional analysis, and business interpretation.

## Author

Swapnil Rathod
