# Amazon Sales Analysis

This project provides a concise sales analysis for an Amazon merchant using their exported sales data. The analysis focuses on key metrics and insights to help the merchant understand their sales performance and make informed decisions.

## Key Questions Addressed

1.  How many sales were made with amounts exceeding 1000?
2.  How many sales belong to the "Tops" category and have a quantity of 3?
3.  What are the total and average sales by category?
4.  What is the average sales amount by category and status?
5.  What are the total sales by fulfillment and shipment type?

## Instructions

1.  **Prerequisites:** Ensure you have Python installed on your system.
2.  **Setup:**
    *   Create a virtual environment (recommended): `python -m venv venv`
    *   Activate the virtual environment:
        *   Windows: `venv\Scripts\activate`
        *   macOS/Linux: `source venv/bin/activate`
    *   Install required libraries: `pip install pandas openpyxl`
3.  **Data:** Place your `sales_data.xlsx` file in the `data` folder.
4.  **Execution:**
    *   Open the `analysis.ipynb` Jupyter Notebook.
    *   Run the cells sequentially to perform the analysis.

## Key Findings

*   **Sales Over 1000:** 8863 sales exceeded an amount of 1000.
*   **Tops Sales (Quantity 3):** There were no sales in the "Tops" category with a quantity of 3.
*   **Total and Average Sales by Category:**
    | Category   |   Total Sales |   Average Amount |
    |:-----------|--------------:|-----------------:|
    | Blouse     |  1.4392e+07    |          459.516  |
    | Bottom     |  81386         |          368.262  |
    | Dress      |  6.46408e+06   |          774.605  |
    | Scarf      |  915           |          305      |
    | Set        |  2.55744e+07   |          836.531  |
    | Top        |  3.81143e+06   |          534.188  |

*   **Average Amount by Category and Status:** All categories have a single status ('Shipped'), and their average amounts are consistent with the overall category averages.
*   **Total Sales by Fulfillment and Shipment Type:**
    |                         |      Amount |
    |:------------------------|------------:|
    | ('Amazon', 'Expedited') | 5.02896e+07 |
    | ('Amazon', 'Standard')  | 34606       |

## Additional Notes

*   This analysis is based on the provided `sales_data.xlsx` file.
*   The findings are specific to the merchant's sales data and may not be generalizable to other Amazon sellers.
*   Further analysis and customization can be done by modifying the `analysis.ipynb` notebook.
