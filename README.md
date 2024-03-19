# NYC Taxi Trip Analysis

[Dashboard](https://lookerstudio.google.com/reporting/72b3cf92-b1f6-477e-92f6-dc76135a2bb4)

[Presentation](https://www.canva.com/design/DAF_6YPs4dM/BaX6P6Nvs9AmFLx_oemNjg/edit?utm_content=DAF_6YPs4dM&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

This project aims to analyze the characteristic of taxi trips in New York City. Characteristics of taxi trips in NYC are depicted through data visualization

## Dataset Description

| Field Name             | Description                                                                                      |
|------------------------|--------------------------------------------------------------------------------------------------|
| VendorID               | A code indicating the TPEP provider that provided the record. <br>1= Creative Mobile Technologies, LLC; 2= VeriFone Inc.                                           |
| tpep_pickup_datetime   | The date and time when the meter was engaged.                                                    |
| tpep_dropoff_datetime  | The date and time when the meter was disengaged.                                                  |
| Passenger_count        | The number of passengers in the vehicle. This is a driver-entered value.                          |
| Trip_distance          | The elapsed trip distance in miles reported by the taximeter.                                     |
| PULocationID           | TLC Taxi Zone in which the taximeter was engaged.                                                 |
| DOLocationID           | TLC Taxi Zone in which the taximeter was disengaged.                                               |
| RateCodeID             | The final rate code in effect at the end of the trip.  <br> 1= Standard rate<br>2=JFK<br>3=Newark<br>4=Nassau or Westchester<br>5=Negotiated fare<br>6=Group ride 
| Store_and_fwd_flag     | This flag indicates whether the trip record was held in vehicle memory before sending to the vendor.<br>Y= store and forward trip<br>N= not a store and forward trip                                      |
| Payment_type           | A numeric code signifying how the passenger paid for the trip.<br>1= Credit card<br>2= Cash<br>3= No charge<br>4= Dispute<br>5= Unknown<br>6= Voided trip          |
| Fare_amount            | The time-and-distance fare calculated by the meter.                                                |
| Extra                  | Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges. |
| MTA_tax                | $0.50 MTA tax that is automatically triggered based on the metered rate in use.                  |
| Improvement_surcharge  | $0.30 improvement surcharge assessed trips at the flag drop. The improvement surcharge began being levied in 2015. |
| Tip_amount             | Tip amount – This field is automatically populated for credit card tips. Cash tips are not included. |
| Tolls_amount           | Total amount of all tolls paid in trip.                                                          |
| Total_amount           | The total amount charged to passengers. Does not include cash tips.                                |
| Congestion_Surcharge   | Total amount collected in trip for NYS congestion surcharge.                                       |
| Airport_fee            | $1.25 for pick up only at LaGuardia and John F. Kennedy Airports.                                 |

## Conclusion

Based on Exploratory Data Analysis: 

1. While most taxi users travel short distances (0 - 2 miles), there are also taxi users who travel distances greater than 50 miles. 

2. Taxi fares are heavily influenced by the distance traveled and trip durations, with the average user typically opting for short-distance trips.

3. Most taxi users travel alone, but there are also taxi trips with either no passengers or more than five passengers.

4. When viewed during the day, the number of taxi trips is nearly equal. However, when examining taxi trips by the hour, the majority of them occur after work hours

5. Taxi users typically take 0 to 20 minutes to reach their destination, but there are also instances where taxi users take more than 240 minutes to reach their destination.

6. Most taxi users utilize credit cards as a payment method, but there are also a small number of taxi users with No Charge and Dispute payment types.

7. Most taxi users typically pay fares ranging from 0 to 20 USD, but there are also instances of negative taxi fares.

8. The occurrence of the highest average taxi fare at 11 PM suggests a notable trend in transportation demand during late-night hours. Several factors could contribute to this peak in fares.

Based on the insights gathered from our analysis of NYC taxi trips, we propose the following recommendations to enhance the efficiency and effectiveness of taxi services in New York City:

1. **Optimize Fleet Allocation**: Utilize real-time data analytics to allocate taxi fleets strategically, ensuring that vehicles are deployed to areas with the highest demand during peak hours. 

2. **Implement Dynamic Pricing**: Introduce dynamic pricing mechanisms that adjust fares based on demand and supply dynamics, time of day, and traffic conditions. 

3. **Improve Payment Systems**: Streamline payment systems to offer more convenient and secure payment options, including mobile payment platforms and digital wallets.

4. **Expand Service Coverage**: Expand taxi service coverage to underserved areas and neighborhoods, particularly those with limited access to public transportation options. 
