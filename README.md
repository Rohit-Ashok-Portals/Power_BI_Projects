# Power_BI_Projects

Objective:
To create a live dashboard mimicking the Namma Yatri App's dashboard, displaying key metrics interactively.

Dataset Details:

Assembly Chart: Displays various assemblies of the city.

Payment Table: Discloses payment methods and their respective IDs.

Duration Table

Trips Table: Contains all trip data.

Trips_Detail Table: Records all journey searches, number of searches by users, searches that received estimates, trips where the driver did not cancel, quotes, trips completed, etc.

Report Highlights:

Trips Dashboard:

Conversion Rate: Calculated as sum[end_ride]/sum[conversion rate], displayed on a gauge chart showing a 45% conversion rate.

Line Charts:

Trips vs Duration

Fare vs Duration

Distance vs Duration

Geospatial Map: Displays trip counts by respective assemblies in Bangalore.

Matrix Chart: Created by inner joining the assembly table and trips_detail table.

Slicer: Allows selection of various assemblies for analysis.

KPIs: Completed trips, searches, estimates, etc.

Payment Dashboard:

Matrix Charts:

Top 10 assemblies by fare

Top payment method

Top 5 drivers

Line Charts

KPIs: Total drivers, top payment method, successful rides, etc.
