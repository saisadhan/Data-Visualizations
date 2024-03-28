### Welcome to the Flight Delays Visualization Dashboard
[Link to Tableau Public Visualization](https://public.tableau.com/app/profile/sai.sadhan.saravanan/viz/shared/ND77K68JX)

#### Introduction
This repository hosts a collection of data visualization dashboards crafted to delve into insightful analyses of flight delays across various airlines. Our primary focus lies in dissecting the nuances of departure delays, offering users a comprehensive tool to explore and understand the data with clarity.

#### Dataset Overview
The dataset utilized for this visualization endeavor is sourced from the U.S. Department of Transportation, compiling data on the performance metrics of major airlines operating domestic flights. Specifically, we have extracted the "FlightDelays.xlsx" file, encompassing flight delay records for all U.S. domestic flights in January 2016.

#### Purpose
Our objective is to design an interactive dashboard that facilitates exploration of departure delays. By empowering users to select an airport of origin and an airline, our dashboard provides invaluable insights into:
- The volume of flights to each domestic airport.
- Average departure delay times experienced by travelers in January 2016.

#### Key Features
- **Customization**: Users can tailor their exploration by choosing specific airports and airlines of interest.
- **Geospatial Visualization**: Leveraging latitude and longitude data, our dashboard offers intuitive geospatial representations.
- **Comprehensive Data Fields**: The dashboard encapsulates a myriad of fields from the dataset, ensuring a holistic analysis.

#### Fields in FlightDelays.xlsx
- **FlightID**: Unique identifier for each flight.
- **City, State**: Location details.
- **Latitude, Longitude**: Geospatial coordinates.
- **Type**: Origin or destination indicator.
- **Origin-Dest**: Origin airport code to destination airport code.
- **FlightDate**: Date of the flight.
- **AirlineID**: Unique identifier for each airline.
- **Airline**: Name of the airline.
- **URL**: URL of the airline.
- **OriginAirportID, OriginAirportCode, OriginCityState**: Origin airport details.
- **DestAirportID, DestAirportCode, DestCityState**: Destination airport details.
- **SchDepTime, DepTime**: Scheduled and actual departure times.
- **DepDelay**: Departure delay in minutes.
- **SchArrTime, ArrTime**: Scheduled and actual arrival times.
- **ArrDelay**: Arrival delay in minutes.
- **Canceled**: Binary variable indicating flight cancellation.
- **FlightNo**: Flight number.

#### Development Process
Our departure dashboard was meticulously crafted through the following steps:
1. Data Extraction: Acquiring the pertinent dataset from the U.S. Department of Transportation.
2. Data Preprocessing: Cleaning and organizing the dataset for seamless visualization.
3. Dashboard Design: Iterative design process to create an intuitive and user-friendly interface.
4. Implementation: Utilizing Tableau to translate our design into a functional dashboard.
5. Testing and Refinement: Thorough testing to ensure accuracy and usability, followed by refinements based on user feedback.

#### Conclusion
With this repository, we aim to provide a powerful tool for exploring and understanding flight delays, ultimately contributing to enhanced decision-making processes within the aviation industry. We invite you to explore the dashboard and unlock valuable insights within the data. Happy analyzing!
