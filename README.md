<h1>Data science/Data Analytics Internship at Brainwave_Matrix_Solutions </h1>
<br>
<h2>Sale data analysis of commercial store.</h2>
    <p>The data set (data.csv) that has been used in this project has been downloaded from an online platform.</p>
    <p> Aim of this project is to identify the underlying patterns by performing EDA using python on the data.csv and gather useful insights that will be beneficial for anyone that wishes to use the same data for further analysis.</p>
<h2>Objective</h2>
    <p>this data can be used for the following analysis</p>
     <h3>Sales Analysis</h3>
        <ul>
            <li>Track sales trends over time.</li>
            <li>Identify top-selling products.</li>
            <li>Analyze sales performance by country.</li>
        </ul>
    <h3>Customer Analysis</h3>
        <ul>
            <li>Identify key customers(country wise) based on their spending.</li>
            <li>Analyze customer purchase patterns.</li>
        </ul>
    <h3>Inventory Management</h3>
        <ul>
            <li>Identify fast selling items.</li>
        </ul>
    <h3>Marketing Insights</h3>
        <ul>
            <li>Understand customer preferences.</li>
            <li>Identify products that can be used future for expansion.</li>
        </ul>
<h2>Dataset Information</h2>
    <ul>
        <li><strong>InvoiceNo:</strong> A unique identifier for each transaction or invoice.</li>
        <li><strong>StockCode:</strong> A unique identifier for each product or item.</li>
        <li><strong>Description:</strong> A textual description of the product or item.</li>
        <li><strong>Quantity:</strong> The number of units of the product sold in each transaction.</li>
        <li><strong>InvoiceDate:</strong> The date and time when the transaction occurred.</li>
        <li><strong>UnitPrice:</strong> The price per unit of the product.</li>
        <li><strong>CustomerID:</strong> A unique identifier for each customer.</li>
        <li><strong>Country:</strong> The country where the customer resides.</li>
        <li><strong>TotalValue:</strong>total amount spend.</li>
    </ul>
<h2>Steps taken in this project</h2>
    <h3>Collect and Load Data</h3>
        <p>Collected data from an online platform and loaded the data into jupyter notebook (used Python language and its libraries that are needed for the analysis).</p>
    <h3>Data Cleaning</h3>
    <ul>
        <li>Handle Missing Values</li>
        <p>There are missing values available for the fields Description and CustomerID.Those record has been removed for further analysis </p>
        <li>Correct Data Types</li>
        <p>Date field has been converted to date and time format to standardize the data.Also, CustomerID and InvoiceNo have been converted to int datatype for removing any false data available</p>
        <li>Remove Duplicates</li>
        <p>Duplicate data can make skew results and lead to incorrect conclusions, So duplicates have been removed from the data before analysis</p> 
    </ul>
    <h3>Exploratory Data Analysis (EDA)</h3>
    <ul>
        <li>Understand data structure and summary statistics</li>
        <p>As the first step we need to understand the type of data.Data doesnot follow a specific order,So it can be determined as nominal data.To understand a quick summary of data Mean has been identified for UnitPrice and Quantity fields. Standard deviation has been identified for the same fields to indicate how spread out the values are from the mean</p>
        <li>Visualize distributions (e.g., histograms)</li>
        <p>Histogram is created with Seaborn(which is very effective for quickly creating visually appealing plots) to visualize the data distibution of Quantity field</p>
        <li>Identify relationships (e.g., scatter plots, pair plots)</li>
        <p>Pair plot is created to identify the pairwise relationships between Quantity and UnitPrice fields with respect to Country. It shows the diagonal distribution of a single variable in one graph.Scatter plot is created to display the relationship for the fields Quantity and UnitPrice for a set of data.It is off-diagonal plots which shows the relationship between two variables in a graph</p>
        <li>Detect outliers</li>
        <p>Outliers are identified for the field Quantity using  InterQuartile Range method and are removed from the data to avoid the variations </p>
    </ul>
    <h3>Data Transformation</h3>
    <ul>
        <li>Create new features (e.g., Totalvalue)</li>
        <p>Total value of each product has been identified and added to the dataset for further analysis. We can easily understand the price of each product which is bought by a single customer using this field </p>
    </ul>
    <h3>Visualization and Reporting</h3>
    <ul>
        <li>Create visualizations to showcase findings (e.g., bar charts,Scatter Plots).</li>
        <li>Generate reports summarizing key insights.</li>
    </ul>
<h2>Observation</h2>
    <ul>
        <li>It is identified that there are 2532 unique products are available in the store.</li>
        <li>Products has been sold out to 18 different countries from the store</li>
        <li>The highest expense amounting to approximately 424,884, is spend by customers belong to United Kingdom. In contrast, the lowest amount of 192 which is spend by customers from the Netherlands.It implies that UK has the most number of customer possibly due to it being the primary market or location of the business.
        Countries such as Iceland, Australia, Italy, Channel Islands, Belgium, Switzerland, Poland, and the Netherlands have occasional customers, so the items are sold out least to these countries among others.To increase the sales in these countries, it may be a  good practice to consider niche marketing strategies or targeted campaigns.By adding specialized products or limited-time offers might attract the customers, which is a benefit to sales</li>
        <li>The product "WORLD WAR 2 GLIDERS ASSTD DESIGNS" is considered the most popular and valuable among the available products.Decorative pieces are the most selling categories ,so adding new product to the category will ensure a hike in sales</li>
        <li>CustomerID:18102 spend more than 25000, who spend the most money among other customers</li>
        <li>It is clear that most items are sold out on first day of each month,Salary will be credited on starting of the month which can be reason for the highest sale during this period.To increase the sale, ensure to restock the items and include new items before the starting of month.
        <li>Continuously monitor sales data and customer feedback from all markets. Adapt strategies based on performance and emerging trends to ensure sustained growth and customer satisfaction. Introduce limited edition products from different countries to attract wide variety of customers.Introduce weekend sales so that it can attract more customers due to work off day,family spending time and conduct surveys and lighting deals on weekend especially to increase customer.Midnight sale is also effective. </li>
    </ul>

<p>Through this project, I have successfully analyzed the store sales dataset. This project serves as a demonstration of data preprocessing, transformation and exploratory data analysis.</p>

<h2>Contact Information</h2>
    <p>For feedback  and queries regarding this project, please contact.</p>
    <p>LinkedIn:</p><a href="https://www.linkedin.com/in/akash-p-nair-b63b46318?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"></a>https://www.linkedin.com/in/akash-p-nair-b63b46318?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app</p>
    <p>Email:akashpbsc.cs2021@gmail.com</p>
