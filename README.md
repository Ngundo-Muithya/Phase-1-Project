<img src="Images/Madrigal Logo.png" width="100%" />

# MADRIGAL ELECTROMOTIVES LOWEST RISK AIRCRAFT ANALYSIS

> **Author**: Ngundo Muithya
> **Email**: ngundolarrymuithya@gmail.com

## OVERVIEW

<img src="Images/Airplanes at an airport.jpeg" width="100%" />

Madrigal Electromotives seeks to expand its business portfolio by moving into the airplane business. As the chief data scientist, I have been tasked with finding the lowest risk airplanes that the company can invest in.

## BUSINESS PROBLEM
Finding the lowest risk aircraft for the comapnt to invest in

## DATA
The data was aviation accident data from the National Transport Safety Board on accidents from 1962 to 2023.

## METHODS
The main python library used in this analysis was Pandas.

I started by looking at the columns in the dataset:
<img src="Images/Columns.png" width="100%" />

From these I identified columns of interest:
<img src="Images/Columns of Interest.png" />

The dataset contained info on all kinds of aircraft from balloons to gyrocraft. I chose to focus solely on airplanes.

I then trimmed my airplane data to remain with data from the columns of interest only.

Using this dataset, I dropped all the null values and remained with 3201 records

I identified the safe airplanes from this dataset as those with 0 accidents

I then identified the super safe airplanes as those with 0 accidents as well low minor injuries and high uninjured.

I went further and identifed the safest models and the most critical phase of flight.

## RESULTS
### Number of accidents and incidents per weather condition
<img src="Images/Number of accidents per weather condition.png" />

<img src="Images/Number of incidents per weather condition.png" />

The weather condition associated with the most accidents and incidents was **Visual Meteorological Condition(VMC)** weather i.e. when the sky is clear which seems counterintuitive. Either way pilots need to be very careful when the sky is clear as they would if it were not.

### Number of incidents per phase of flight
<img src="Images/Number of incidents per phase of flight.png" />

The phase of flight associated with the most incidents was **Takeoff**. This makes sense as Takeoff is when the plane is closest to the ground where multiple objects could interfere with it and is notoriously the most dangerous phase of flight.

### Threat level per make of airplane
<img src="Images/Threat level per make of airplane.png" />

I compared Boeing to Airbus to see which was safer. **Airbus** came out on top.

## Conclusions

