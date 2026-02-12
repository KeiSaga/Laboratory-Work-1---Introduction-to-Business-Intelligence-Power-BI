# Laboratory-Work-1---Introduction-to-Business-Intelligence-Power-BI
POWER BI
Step 1: Quick Visualization
1. Drag Sales into canvas
2. Power BI automatically creates a visual
Question:
● What type of chart was created?
 - The chart shows Sum of Sales ≈ 0.2M (200,000+).
● What does it show?
 - Power BI automatically aggregated Sales using SUM, showing the total sales of the dataset.

Step 2: Create a Sales by Region Chart
1. Click blank canvas
2. Select Clustered Column Chart

3. Drag:
○ Region → X-axis
○ Sales → Values

Question:
● Which region has highest sales?
- West Region
Step 3: Sales by Category
1. Insert a Pie Chart
2. Drag:
○ Category → Legend
○ Sales → Values

Question:
● Which category dominates?
 -Electronics
● Is the distribution balanced?
 - Mostly yes, but North underperforms compared to others.

Step 4: Sales Over Time
1. Insert Line Chart
2. Drag:
○ Date → X-axis
○ Sales → Values

Question:
● Is there growth?
 - Nope, the sales go down
● Any noticeable trend?
 - Nope

 PART 4: Basic Data Insight Interpretation
Students must now interpret visuals.
Question:
● Which region contributes most revenue?
- West Region
● Which product category performs best?
- Electronics
● Are sales consistent across dates?
- Mostly yes, but North underperforms compared to others.
● What business recommendation can you suggest?
- Office Supplies

LABORATORY QUESTIONS
Part A – Technical Questions
1. What are the five columns in the dataset?
   ● Date
   ● Product
   ● Category
   ● Region
   ● Sales
2. What data type is assigned to the “Sales” column?
   - Decimal Number
3. Which Power BI view allows you to see raw data?
   - Data View
4. What chart type is best for showing trends over time?
   - Line Chart
5. What aggregation is automatically applied to Sales?
   - Sum (SUM)
     
Part B – Analytical Questions
6. Which region has the highest total sales?
 - West Region has the highest total sales.
7. Which category has the lowest performance?
 - Office Supplies has the lowest sales among the categories.
8. Are sales increasing, decreasing, or stable?
 - Decreasing Overtime 
9. If you were a manager, which region would you prioritize?
 - I would prioritize the West Region to maximize revenue since it performs best, while also improving strategies in the North Region, which has the lowest sales.
10. Provide one actionable recommendation based on the data.
 - Increase marketing and promotional efforts in the North region to boost sales, while continuing strong inventory and advertising support for Electronics, the top-performing category.

Task 1: Add a Card Visualization
1. Insert Card
2. Drag Sales
3. Format:
○ Increase font size
○ Change title to “Total Sales”

Question:
● What is the total sales amount?
 - 220k Total Sales
Task 2: Add Slicer
1. Insert Slicer
2. Drag Region
3. Test filtering
Question:
● What happens to other visuals when you click a region?
 - All other visuals on the report page automatically update to display data only for the selected region. Charts, totals, and graphs adjust instantly based on the filter.
● Why is filtering important in BI?
 - Filtering is important because it:
 ● Allows users to analyze specific segments of data
 ● Helps in comparing performance between regions
 ● Supports better decision-making
 ● Makes reports interactive and user-friendly

Enables quick identification of trends and issues in a selected area
Task 3: Sort Sales
1. Click Region Chart
2. Click three dots (...)
3. Sort by Sales Descending
Question:
● Does sorting improve readability?
 - Yes, sorting improves readability.
● Why?
   ●  It clearly shows highest to lowest performers at a glance
   ●  Makes comparison easier between regions
   ●  Helps users quickly identify top and low sales areas
   ●  Reduces confusion from random bar positions

Supports faster and better data-driven decisions
Task 4: Identify Outliers
● Which region is significantly higher or lower?
 -  The West Region is the highest-performing region.
 -  The North Region is the lowest-performing and stands out as an underperforming outlier.
● What might explain that difference?
Possible reasons include:
- Larger customer base in the West
- Stronger market demand
- Better marketing and promotional strategies
- More developed distribution channels
- Higher population or business activity
For the North region, lower sales may be due to:
- Limited market reach
- Lower demand
- Fewer promotional campaigns
- Economic or demographic factors
