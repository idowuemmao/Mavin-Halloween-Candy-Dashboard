# Mavin-Halloween-Candy-Dashboard


### Maven Analytics Challenge: Candy Selection for Halloween

This is my first attempt at a Maven Analytics challenge, and it has truly brought out the best in me. It allowed me to apply everything I've learned so far in Power BI while enjoying the challenge of delivering actionable insights. In this project, I played both the analyst and stakeholder roles, which helped me self-examine and justify my choices, balancing the benefits for both myself and the trick-or-treaters. My goal was to ensure that all trick-or-treaters leave with a treat they love while maintaining cost efficiency.

### **Project Goal:**
The objective was to use online votes ranking 85 types of candy to select three treats to give out on Halloween. The challenge was to guarantee that trick-or-treaters of all tastes would find something they love, while presenting data-backed decisions.

### **Steps Taken:**
1. **Data Loading & Transformation**:
   - Imported the dataset into Power BI and cleaned it for analysis.
   - Added columns to classify sugar, price, and win percentages into ranges: Low, Medium, or High.
   
2. **DAX Calculations**:
   - Developed several measures: `Total Candies`, `Top10SugarPercent`, `Top10PricePercent`, `Top10WinPercent`, `Avg Sugar Percent`, `Avg Win Percent`, `Avg Price Percent`.
   - Used conditional columns for candy categories.
   
3. **Field Parameters**:
   - Implemented field parameters to toggle between top 10 candies based on `Sugarpercent`, `Winpercent`, and `Pricepercent`.

4. **Visual Design**:
   - Created visually appealing dashboards with custom backgrounds, images, titles, and navigation buttons for ease of use.

### **Business Requirements**:
The selection process focused on:
- **Popularity**: Ensuring candies are well-liked by the majority of trick-or-treaters, measured by win percentage.
- **Variety**: Including different candy types (chocolate, fruity, crunchy) to cater to diverse tastes.
- **Cost-effectiveness**: Balancing price efficiency while maintaining appeal.
- **Moderate Sugar Content**: Prioritizing taste and enjoyment while factoring in moderate sugar content.

### **Analysis and Insights**:
- **Data Exploration**: Analyzed candy attributes like `Winpercent`, `Pricepercent`, and `Sugarpercent` to identify top-performing treats.
- **Ranking and Filtering**: Filtered and ranked the top candies based on popularity, price, and variety.
- **Visual Presentation**: Presented the insights through charts and tables in an interactive Power BI report, allowing for easy comparison and decision-making.

### **Key Results**:
- **Average Sugar Content**: 47.86% (almost half of the content in most candies is sugar).
- **Most Popular Candy**: Reese's Peanut Butter Cup leads with an 84.18% win percentage, offering the perfect balance of taste and popularity.
- **Best Budget-Friendly Option**: Nestle Smarties, with 97.60% price efficiency, are ideal for large crowds.
- **Top Chocolate Option**: Twix emerged as the overall best candy, offering a high price efficiency rate (91%), an impressive win rate (82%), and a moderate sugar level (55%).

### **Dashboard Overview**:
#### **Page 1: Overview**:
- **Top 10 Candies by Sugar, Win, and Price**: A line chart visualizing the top 10 candies based on `Winpercent`, `Sugarpercent`, and `Pricepercent`, using a slicer to toggle between attributes.
- **Candy Content Breakdown**: Cards showing totals and types of candies (e.g., chocolate, caramel, fruity).
- **Navigation Button**: A button to navigate to the selection page.

#### **Page 2: Selection**:
- **Candy Information Table**: Displays candy names, sum of values, sugar percentage, win percentage, price efficiency, and ranges.
- **Summary Cards**: Average sugar, price, and win percentages.
- **Navigation Button**: Returns to the home page.

### **Conclusion**:
- **Twix** emerged as the best overall candy, striking a perfect balance between price, popularity, and sugar content.
- **Reese's Peanut Butter Cup** is the most popular candy, while **Nestle Smarties** offer the best price efficiency for budget-conscious trick-or-treaters.
- This project allowed me to combine data-driven insights with creative visualization to ensure a well-rounded candy selection for Halloween.
