# Sales-Analysis-Excel

![Dashboard Screenshot](dashboard.png)

**About datasets**

Data consists of Amazon sales from 2025. I imported a messy dataset from Kaggle, which contains 14 columns, including Order ID, Date, Customer ID, Product Category, Product Name, Quantity, Unit Price, Total Sales Price, Payment Method, Delivery Status, Review Rating, Review Text, State, and Country.

**Data cleaning**

I used Power Query in Excel to clean the data by applying TRIM and formatting for consistency, removing duplicates, and standardizing the Date column. I handled missing values by calculating Unit Price as Total Sales ÷ Quantity, and replaced blank Customer IDs with “Guest_User” while keeping those records for analysis.

**Insights**

- The **Beauty** category generated the highest sales, totaling **227.9 M.**
- The **'COD'** payment method is used most frequently by our customers, compared to digital payment options.
- **Sikkim** is the top-performing state, leading in both total orders **1,313** and total Sale **98.7 M** .
- Market demand is highest for **Children’s Books** and **Perfume**, which lead in volume with **1,842** and **1,837 units** sold, respectively.
- - We lost **364.5 M** due to '**Returned'** delivery status, which accounts for approximately **32%** of our total gross sales.
- There are currently **5,055** orders marked as **'Pending**,' which require immediate logistical attention to complete the fulfillment process.
- **Vacuum cleaners** and **Water purifiers** had the lowest sales volume this period.
- **Home and Kitchen** is the lowest-performing category, generating **217.0 M** in total sales.

 ** Business Recommendation**

 - Investigate why **364.5 M** Crore is lost to returns; check if specific couriers have higher damage rates
- Assign a task force to clear the **5,055 pending** orders before they turn into cancellations.
- Run a "**Flash Sale**" for vacuum cleaners & water purifiers  to clear warehouse space for higher sales items.
- Shift marketing funds from the low-performing **Home & Kitchen category**  to high-growth areas like perfume.
- Since **Beauty** makes the most money (**227.9 M**), spend more on ads for these products to keep sales growing.
- **Sikkim** is your best state for sales. Keep more stock nearby and offer special deals there to reward your best customers
- Give small discounts to customers who pay online. This makes deliveries faster because the delivery boy doesn't have to spend time collecting and counting cash at every door. It also makes the process safer and more efficient for the team.
