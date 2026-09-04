<h1>📊 Sales Superstore Analysis</h1>

<h2>📌 Project Overview</h2>

<p>
  This project analyzes the <strong>Superstore Sales dataset</strong>
  using <strong>Python</strong> to explore sales performance, profitability,
  customer segments, discounts, seasonality, and shipping performance.
</p>

<p>
  The project covers the complete data analysis workflow, including
  data inspection, cleaning, validation, feature engineering, exploratory
  analysis, business insights, and data visualization.
  The cleaned dataset is also used to build an interactive
  <strong>Power BI dashboard</strong>.
</p>


<h2>🎯 Objectives</h2>

<ul>
  <li>📈 Analyze overall sales and profit performance.</li>
  <li>💰 Evaluate profitability and profit margins.</li>
  <li>📦 Analyze performance by category and sub-category.</li>
  <li>🗺️ Compare sales and profit across different regions.</li>
  <li>👥 Analyze customer segments.</li>
  <li>🏷️ Explore the relationship between discounts and profit.</li>
  <li>📅 Identify monthly, yearly, and quarterly sales trends.</li>
  <li>🚚 Evaluate shipping performance across different shipping modes and regions.</li>
  <li>🏆 Identify the Top 10 states by sales.</li>
  <li>📊 Generate business insights supported by the analyzed data.</li>
</ul>


<h2>🛠️ Tools &amp; Technologies</h2>

<ul>
  <li>🐍 Python</li>
  <li>🐼 Pandas</li>
  <li>🔢 NumPy</li>
  <li>📊 Matplotlib</li>
  <li>☁️ Google Colab</li>
  <li>📈 Power BI</li>
</ul>


<h2>📂 Dataset</h2>

<p>
  The project uses the <strong>Superstore Sales dataset</strong>,
  which contains information about orders, customers, products,
  sales, profit, discounts, and shipping.
</p>

<p>
  The main features include:
</p>

<ul>
  <li>🆔 Order ID</li>
  <li>📅 Order Date</li>
  <li>🚚 Ship Date</li>
  <li>🚛 Ship Mode</li>
  <li>🆔 Customer ID</li>
  <li>👤 Customer Name</li>
  <li>👥 Segment</li>
  <li>🌎 Country</li>
  <li>🏙️ City</li>
  <li>📍 State</li>
  <li>📮 Postal Code</li>
  <li>🗺️ Region</li>
  <li>🆔 Product ID</li>
  <li>📦 Category</li>
  <li>📦 Sub-Category</li>
  <li>🏷️ Product Name</li>
  <li>💵 Sales</li>
  <li>🔢 Quantity</li>
  <li>🏷️ Discount</li>
  <li>💰 Profit</li>
</ul>


<h2>🔍 Data Analysis Workflow</h2>

<ol>
  <li>📥 Load the dataset.</li>
  <li>🔎 Inspect the dataset structure, data types, missing values, and duplicates.</li>
  <li>🧹 Clean and prepare the data.</li>
  <li>📅 Convert date columns to the correct datetime format.</li>
  <li>✅ Validate data quality and business rules.</li>
  <li>⚙️ Perform feature engineering.</li>
  <li>📊 Calculate key sales and profitability metrics.</li>
  <li>📋 Analyze performance across categories, regions, segments, and sub-categories.</li>
  <li>🏷️ Analyze discounts and their relationship with profit.</li>
  <li>📅 Analyze sales trends and seasonality.</li>
  <li>🚚 Analyze shipping performance.</li>
  <li>📈 Create visualizations to communicate the main findings.</li>
  <li>💡 Generate data-driven business insights.</li>
  <li>📊 Build an interactive Power BI dashboard.</li>
</ol>


<h2>🧹 Data Cleaning &amp; Validation</h2>

<p>
  The dataset was inspected and validated before performing the analysis.
  The main steps included:
</p>

<ul>
  <li>Checking for missing values.</li>
  <li>Checking and inspecting duplicate records.</li>
  <li>Converting Order Date and Ship Date to datetime.</li>
  <li>Removing the unnecessary Row ID column.</li>
  <li>Rounding Sales and Profit values.</li>
  <li>Checking for invalid or negative sales values.</li>
  <li>Checking for invalid quantity values.</li>
  <li>Validating that discounts are within the expected range.</li>
  <li>Checking that Ship Date is not earlier than Order Date.</li>
</ul>


<h2>⚙️ Feature Engineering</h2>

<p>
  New features were created from the existing data to support deeper analysis:
</p>

<ul>
  <li>📅 Order Year</li>
  <li>📅 Order Month</li>
  <li>📅 Month Name</li>
  <li>📆 Order Quarter</li>
  <li>🗓️ Year-Month</li>
  <li>🚚 Shipping Days</li>
  <li>📊 Sales Level</li>
</ul>


<h2>📈 Key Analysis</h2>

<ul>
  <li>💵 Total Sales</li>
  <li>💰 Total Profit</li>
  <li>📦 Total Quantity</li>
  <li>🏷️ Total Discounts</li>
  <li>🧾 Total Orders</li>
  <li>📊 Average Sales</li>
  <li>📦 Category Performance</li>
  <li>📦 Sub-Category Performance</li>
  <li>🗺️ Regional Performance</li>
  <li>👥 Segment Performance</li>
  <li>🏆 Top 10 States by Sales</li>
</ul>


<h2>💰 Profitability Analysis</h2>

<p>
  Profitability was analyzed by comparing total sales and total profit
  across different categories. Profit margin was calculated to evaluate
  how efficiently each category converts sales into profit.
</p>

<pre><code>Profit Margin (%) = (Total Profit / Total Sales) × 100</code></pre>


<h2>🏷️ Discount Analysis</h2>

<p>
  Discounts were analyzed to explore their relationship with sales and profit.
  The analysis includes average profit, total profit, total sales, and the
  number of transactions at different discount levels.
</p>

<p>
  Correlation was also used to measure the association between
  <strong>Discount</strong> and <strong>Profit</strong>.
  The correlation is interpreted as an association and not as evidence
  of causation.
</p>


<h2>📅 Seasonality &amp; Trend Analysis</h2>

<p>
  Sales were analyzed over time to identify patterns and changes in
  business performance.
</p>

<ul>
  <li>📅 Monthly Sales Trend</li>
  <li>📆 Sales by Month</li>
  <li>📈 Sales by Year</li>
  <li>🗓️ Sales by Quarter</li>
</ul>


<h2>🚚 Shipping Performance</h2>

<p>
  Shipping performance was analyzed using the number of days between
  the order date and ship date.
</p>

<pre><code>Shipping Days = Ship Date - Order Date</code></pre>

<p>
  Average shipping time was compared across:
</p>

<ul>
  <li>🚛 Ship Modes</li>
  <li>🗺️ Regions</li>
</ul>


<h2>📊 Data Visualizations</h2>

<p>
  Matplotlib was used to create visualizations for the main analysis,
  including:
</p>

<ul>
  <li>📊 Total Sales by Category</li>
  <li>💰 Total Profit by Category</li>
  <li>📈 Profit Margin by Category</li>
  <li>🗺️ Total Sales by Region</li>
  <li>📊 Sales Distribution</li>
  <li>📅 Monthly Sales Trend</li>
  <li>📆 Sales by Month</li>
  <li>🏷️ Average Profit by Discount</li>
  <li>🚚 Average Shipping Days by Ship Mode</li>
  <li>🏆 Top 10 States by Sales</li>
</ul>


<h2>💡 Business Insights</h2>

<p>
  The analysis generates data-driven insights about:
</p>

<ul>
  <li>🏆 The category generating the highest sales.</li>
  <li>💰 The category generating the highest profit.</li>
  <li>📈 The category with the highest profit margin.</li>
  <li>🗺️ The highest-performing region by sales.</li>
  <li>📅 The month with the highest sales.</li>
  <li>🚚 The ship mode with the shortest average shipping time.</li>
  <li>🏷️ The association between discounts and profit.</li>
</ul>


<h2>📊 Power BI Dashboard</h2>

<p>
  The cleaned and analyzed dataset is also used to create an interactive
  <strong>Power BI dashboard</strong>.
</p>

<p>
  The dashboard presents the main sales, profit, product, customer,
  regional, and discount insights in an interactive format to support
  business decision-making.
</p>


<h2>▶️ How to Run</h2>

<h3>1️⃣ Install Required Libraries</h3>

<p>
  Install the required Python libraries:
</p>

<pre><code>pip install pandas numpy matplotlib</code></pre>


<h3>2️⃣ Run the Notebook</h3>

<p>
  Open <strong>Sales_Analysis.ipynb</strong> using Google Colab
  or Jupyter Notebook and run the cells in order.
</p>


<h3>3️⃣ Cleaned Dataset</h3>

<p>
  After the cleaning and feature engineering process, the cleaned dataset
  is exported as:
</p>

<pre><code>Superstore_cleaned.csv</code></pre>

<p>
  This dataset can then be used for further analysis and visualization.
</p>


<h3>4️⃣ Power BI Dashboard</h3>

<p>
  Import the cleaned dataset into <strong>Power BI</strong>
  to explore the interactive dashboard and its business insights.
</p>


<h2>📝 Conclusion</h2>

<p>
  This project demonstrates a complete data analysis workflow using Python,
  from data inspection and validation to feature engineering, exploratory
  analysis, visualization, and business insight generation.
</p>

<p>
  The analysis goes beyond basic sales reporting by exploring
  <strong>profitability, discount patterns, seasonality, and shipping performance</strong>.
  Power BI is used to transform the analyzed data into an interactive
  dashboard that makes the main findings easier to explore and communicate.
</p>
