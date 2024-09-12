# Fixed Income Portfolio Modeling and Risk Analysis of Treasury Bonds

## Project Overview
This project focuses on bond portfolio management and risk analysis using historical Treasury bond data. The analysis covers various aspects of fixed income securities, including yield curve analysis, bond pricing, duration calculation, and portfolio optimization.

## Key Findings and Methodologies

1. **Yield Curve Analysis**: Identified six distinct periods in the yield curve data for 2-, 5-, 10-, and 30-year Treasury bonds between January 2018 and March 2022.

2. **Bond Pricing**: Implemented a function to price fixed-coupon bonds, validating the results against given prices. The analysis showed a strong correlation between computed and given prices.

3. **Yield Computation**: Developed a method to deduce yields from market prices, demonstrating the inverse relationship between bond prices and yields.

4. **Macaulay Duration**: Calculated and analyzed Macaulay duration for each bond, revealing the relationship between duration, maturity, and other bond characteristics.

5. **Interest Rate Sensitivity**: Used first-order Taylor expansion to estimate price changes in response to a 50 basis point shift in the yield curve, highlighting the greater price sensitivity of longer-maturity bonds.

6. **Portfolio Optimization**: 
   - Allocated $100,000 between two bonds to achieve target portfolio durations of 4 and 8 years, considering potential Federal Reserve interest rate increases.
   - Extended the optimization to include four bonds while targeting an 8-year portfolio duration, using Moore-Penrose pseudoinverse to solve the under-determined linear system.

## Conclusion
This project demonstrates the application of various financial engineering techniques in fixed income portfolio management. It highlights the importance of understanding the relationships between bond characteristics, market conditions, and portfolio performance. The methodologies used, particularly in portfolio optimization and duration management, provide valuable insights for managing interest rate risk and constructing balanced fixed income portfolios.

## Tools and Techniques Used
- R and Excel for data analysis and visualization
- Fixed-coupon bond pricing models
- Macaulay duration calculations
- First-order Taylor expansion for price sensitivity analysis
- Moore-Penrose pseudoinverse for portfolio optimization

This project serves as a comprehensive exploration of bond portfolio management techniques, offering practical applications of financial theory in real-world scenarios.
