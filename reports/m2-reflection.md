# Reflection at Milestone 2
Since last week, we have been able to continue the development of our dashboard. In Milestone 1, we presented our initial design for the dashboard, including a hand-drawn demo, as well as establishing the background for this dashboard proposal. We settled on a design for a crime-tracking dashboard in Vancouver. The centerpiece of our dashboard will be a map showing the locations of crimes in Vancouver and their types. Additionally, we will have a line chart, a pie chart, and a bar chart tracking different aggregations of the data. Our design is heavily influenced by existing crime-tracking apps. However, the first hurdle we encountered was the size of the data, which exceeded our server's capacity. This issue arose because the dataset we used provided live updates for each crime tracked over an extended period. We were able to overcome this problem by using a sampling method that preserves the time series structure of the data.

The second major change we applied to the dashboard was removing the pie chart and modifying the bar chart from stacked to unstacked. As the TA noted, the information provided by a stacked bar chart might cause an overflow of information due to the large number of crime types and neighborhood types. By unstacking the bar chart, we can provide a much cleaner and clearer view for the audience, which in turn made the pie chart redundant. This is the reason behind removing the pie chart.

Another significant change, also recommended by the TA, was to increase the number of dropdown menus from two to four. This adjustment was made because the controls for the map and line chart will be separate from the controls for the bar chart. This suggestion was made to avoid confusion if the dropdowns altered some plots but not others. Despite these major changes, we were able to complete the coding for the dashboard. We are also exploring ways to streamline the user interface, particularly by integrating the functionalities of the bar chart into a single dropdown menu, thereby reducing redundancy.