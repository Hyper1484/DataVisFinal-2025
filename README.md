Legend : 
Main graph - Blue: Electric power industry, Green: Industry, Orange: Transportation, Red: Residential, Purple: Commercial, Brown: Agriculture, Gray: Gross total 
Left graph - Uses the same legend as the main
Middle Graph - Black - total emissions, Red line - zero reference line
Right Graph - Same legend as Main Graph





Key Findings
Analysis of Pennsylvania's greenhouse gas emissions from 1990 to 2022 reveals complex environmental progress and challenges. The data visualization highlights several key trends:

Overall Decline in Emissions: Pennsylvania's greenhouse gas emissions have decreased by approximately 15-20% over this period, with the most significant reductions being after 2005.
Electric Power: The electric power industry has shown the most change, with emissions declining by nearly 30% since 1990, with drops occurring after 2015.
Transportation: Transportation emissions have remained relatively stable throughout the 32-year period, with temporary decreases during economic downturns (2008-2009 and 2020), followed by rebounds.
Change in Sector Proportions: While electric power emissions have decreased, transportation has maintained its share, resulting in transportation becoming a larger proportion of total emissions in recent years.
Industrial Sector: Industrial emissions show patterns generally aligned with economic expansion.
Pandemic Impact: A notable drop in emissions is visible in 2020 across multiple sectors, corresponding to COVID-19 pandemic restrictions, followed by a partial uptake in 2021-2022.
These patterns demonstrate the progress across sectors, with success in reducing electric power emissions, while transportation remains a stubborn source of greenhouse gases that will require more work to reduce.

Data and Method : 
This analysis draws on data from the U.S. Environmental Protection Agency's Greenhouse Gas Inventory, providing a reliable 32-year record of Pennsylvania's emissions across economic sectors measured in million metric tons of CO2 equivalent. The raw data, downloaded in CSV format from the EPA website, required significant transformation to convert from its original wide format(with years as columns into a structure suitable for visualization. This processing included calculating percent changes using 1990 as the baseline year, applying the formula ((current_year_value / baseline_year_value) - 1) × 100 to get the shifts in emissions over time for each sector. The visualization itself was created using matplotlib in Python, with a multi-panel approach that has a main stacked area chart showing emissions by sector over time, and three specialized panels: a line chart highlighting trends among top emitting sectors, a percent change chart revealing relative changes since 1990, and a pie chart displaying the proportional sector distribution for 2022. Throughout the design process, attention was paid to maintaining a consistent color scheme across all graphs, allowing it to be easier understood, and the final figure was generated at high resolution to keep detail in the printed report.





Significance Statement : 
This visualization offers information on Pennsylvania's climate impact as the fourth-largest carbon emitter in the United States. The three-decade perspective reveals not just where emissions reductions have been achieved but also highlights trouble spots requiring targeted work, mainly in the transportation sector, where emissions have remained consistent despite technological advances. Pennsylvania's industrial industry and its energy transformation make it an ideal case study for understanding how states with diverse energy resources can navigate the path toward lower emissions while maintaining a strong economic system. For policymakers, businesses, and people, this visualization serves as a record of past efforts and an insight for future climate action, highlighting what's worked and which sectors require more approaches. Moreover, the multi-panel visualization approach demonstrates how complex environmental data can be presented in a way that shows patterns and relationships that might otherwise remain hidden, providing valuable insights for other researchers working to translate climate data into actionable understanding by using data visualization.
