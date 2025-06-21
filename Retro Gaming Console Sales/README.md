# Gaming Console Sales Analysis

This project involved analyzing a dataset of historical gaming console sales data to derive insights into sales trends and console performance. The analysis was conducted as part of a tech boot camp (TripleTen) to demonstrate foundational Python skills.

<!--
🎥 **The Loom Video Overview** can be found [HERE]()
-->

## Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :---------: | ----- | ----------- |
| 1 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 2 | [Requirements.txt](https://github.com/Tiffany-Bergett/Data_Science_Projects/blob/main/Retro%20Gaming%20Console%20Sales/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 3 | [Retro_Gaming_Console_Sales.jpynb](https://github.com/Tiffany-Bergett/Data_Science_Projects/blob/main/Retro%20Gaming%20Console%20Sales/Retro_Gaming_Console_Sales.ipynb) | Jupyter Notebook file with analytical work and recommendations. |
| 4 | [gaming_consoles.csv](https://github.com/Tiffany-Bergett/Data_Science_Projects/blob/main/Retro%20Gaming%20Console%20Sales/gaming_consoles.csv) | Raw data used for this project. |

---

## Table of Contents for README
| Section Title | Description |
| ------------- | ----------- |
| [Description](https://github.com/Tiffany-Bergett/Data_Science_Projects/tree/main/Retro%20Gaming%20Console%20Sales#description) | Describes the final product's purpose, software, format, and included visuals. |
| [Process](https://github.com/Tiffany-Bergett/Data_Science_Projects/tree/main/Retro%20Gaming%20Console%20Sales#process)    | Describes the process, including tools or tech used. |
| [Data](https://github.com/Tiffany-Bergett/Data_Science_Projects/tree/main/Retro%20Gaming%20Console%20Sales#data) | Describes the data source, including files, tables, and fields. |
| [Assumptions](https://github.com/Tiffany-Bergett/Data_Science_Projects/tree/main/Retro%20Gaming%20Console%20Sales#assumptions) | Describes assumptions to include those given by TripleTen and assumptions made. |
| [Findings](https://github.com/Tiffany-Bergett/Data_Science_Projects/tree/main/Retro%20Gaming%20Console%20Sales#findings)  | Insights learned from the data analysis. |
| [Recommendations](https://github.com/Tiffany-Bergett/Data_Science_Projects/tree/main/Retro%20Gaming%20Console%20Sales#recommendations) | Recommended direction for the stakeholders based on the final analysis. |

### Description:
-   Python via Google Colab (.ipynb notebook).
-   7 coding tasks completed, plus scenario and recommendations.  
**The project** can be found [HERE](https://colab.research.google.com/drive/1FCqJE0bfATR18SmTReZ_5otqV8zucTWv?usp=sharing) 

### Process:
1)   Accessing and displaying data from the nested list.  
2)   Calculating metrics such as total units sold and console lifespan.  
3)   Sorting data based on calculated metrics.  

### Data
The primary data source is a nested list named `console_data`.

-   `'console_data'`:  A nested list containing information about various gaming consoles.  
    -   `'console'`: The name of the gaming console.  
    -   `'company'`: The company that manufactured the console.  
    -   `'release_year'`: The year the console was released.  
    -   `'discontinued_year'`: The year the console was discontinued.  
    -   `'release_price'`: The release price of the console.  
    -   `'units_sold'`: The number of units sold.  

### Assumptions:
1)   The primary assumption is that the provided dataset is accurate and complete.
2)   Calculations are based solely on the data within the `console_data` list.

### Findings:
-   Key insights include sales performance metrics (total units sold, revenue) and console lifespan.
-   Analysis reveals trends in console popularity and revenue generation.

### Recommendations:
-   Recommendations are provided for inventory prioritization and pricing strategies based on the analysis.
-   Further analysis could include incorporating additional data such as repair costs and sales volume over time.
