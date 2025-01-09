Automobile Sales Statistics Dashboard

Overview

The Automobile Sales Statistics Dashboard is an interactive web application built using Python and the Dash framework. It provides insightful visualizations and analytics on automobile sales data from 1980 to 2024. The dashboard allows users to explore key trends, such as yearly statistics and recession-period statistics, through various charts and graphs.

Features
	•	Yearly Statistics: View detailed automobile sales data for each year.
	•	Recession Period Statistics: Analyze automobile sales trends during recession periods, including:
	•	Average sales by vehicle type.
	•	Advertising expenditure breakdown.
	•	Interactive Dropdown Menus: Filter data by year and type of statistics.
	•	Dynamic visualizations using Plotly, including line charts, bar charts, and pie charts.

Technology Stack
	•	Python: Core programming language.
	•	Dash: Framework for building the web application.
	•	Plotly: Library for interactive visualizations.
	•	Pandas: Data manipulation and analysis.
	•	HTML/CSS: Layout and styling.
	•	Seaborn & Matplotlib: For data exploration and supplementary visualizations.

Installation
	1.	Clone the repository:

git clone https://github.com/your-username/automobile-sales-dashboard.git


	2.	Navigate to the project directory:

cd automobile-sales-dashboard


	3.	Install the required dependencies:

pip install -r requirements.txt


	4.	Run the application:

python app.py


	5.	Open your browser and navigate to:

http://127.0.0.1:8050/



Usage
	1.	Select the type of statistics from the dropdown menu: Yearly Statistics or Recession Period Statistics.
	2.	Choose a specific year to view data for that period.
	3.	Explore the interactive charts to gain insights into automobile sales trends.

Dataset

The application uses a dataset containing the following fields:
	•	Date: Sales date.
	•	Year/Month: Breakdown of time.
	•	Recession: Indicator for recession periods.
	•	Consumer Confidence: Economic confidence index.
	•	Seasonality Weight: Adjustments for seasonal changes.
	•	Price: Average price of vehicles.
	•	Advertising Expenditure: Marketing spending.
	•	Competition: Competitive index.
	•	GDP Growth Rate: Growth rate of GDP.
	•	Unemployment Rate: Employment data.
	•	Automobile Sales: Total sales numbers.
	•	Vehicle Type: Categories such as cars, trucks, etc.
	•	City: Sales by geographic location.

Visualizations
	•	Line Charts: Trends over time (e.g., sales during recessions).
	•	Bar Charts: Breakdown by vehicle type or other categories.
	•	Pie Charts: Share of advertising expenditure.

File Structure
	•	app.py: Main application file.
	•	data/: Folder containing the dataset.
	•	assets/: Folder for custom CSS or images.
	•	notebooks/: Jupyter notebooks for data exploration.

Future Enhancements
	•	Add more advanced filters (e.g., by city or vehicle type).
	•	Include predictions using machine learning models.
	•	Optimize performance for large datasets.

Contribution

Contributions are welcome! Please fork the repository and submit a pull request.

License

This project is licensed under the MIT License.

Contact

For questions or support, feel free to reach out:
	•	Email: Rahmanayo8@gmail.com
	•	GitHub: Ayobamiiiii
