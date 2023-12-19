# Index Fund to Track NASDAQ-100 Index

## Project Overview
This project focuses on constructing an Index Fund with the objective of tracking the NASDAQ-100 index. Using advanced optimization techniques, the project aims to develop a fund that closely mirrors the index movements while considering practical constraints like transaction costs and the number of stocks to be included.

## Methodology
- **Data Processing**: We begin by reading the stock price data for the years 2019 and 2020. This data is then processed to calculate returns and correlations, which are critical inputs for our optimization models.
- **Optimization Techniques**: The project employs integer programming for the selection of stocks and linear programming for determining the optimal weights of these stocks in the portfolio.

## Technical Details
- **Libraries Used**: The implementation leverages several Python libraries including Gurobi for optimization, Pandas for data handling, NumPy for numerical computations, and Matplotlib and Seaborn for visualizations.
- **Key Code Snippets**: The notebook includes snippets demonstrating the setup of optimization problems, data manipulation, and graphical representation of results.

## Results and Analysis
- **Performance Analysis**: We evaluated the performance of our constructed index fund against the actual NASDAQ-100 index for both 2019 and 2020. This included a comparison of returns and tracking efficiency.
- **Visualizations**: The report is enriched with various charts and graphs that illustrate the performance metrics and provide insights into the effectiveness of our fund.

## Conclusion
In conclusion, this project highlights the application of optimization techniques in financial portfolio management. The results showcase the potential of mathematical models in replicating market indices and offer insights into the trade-offs involved in index fund construction.

## Appendices
Additional notes, detailed methodology, and extended analysis can be found in the latter sections of the notebook.

---
