# Dataset: 2017 Yellow Taxi Trip Data (sample)

## Overview
This project uses a dataset called **`2017_Yellow_Taxi_Trip_Data.csv`**. The data were gathered by the **New York City Taxi & Limousine Commission (TLC)** and published by the **City of New York** as part of the **NYC Open Data** program.

To improve the learning experience and shorten runtimes, this project uses a **sample** drawn from the full 2017 Yellow Taxi Trip Data table (the full table contains ~113 million rows).

## Dataset shape (sample)
- **Rows:** 408,294 (each row represents a taxi trip)
- **Columns:** 18

---

## Data dictionary

| Column name | Description |
|---|---|
| **ID** | Trip identification number. |
| **VendorID** | Code indicating the TPEP provider that provided the record. `1 = Creative Mobile Technologies, LLC`; `2 = VeriFone Inc.` |
| **tpep_pickup_datetime** | Date and time when the meter was engaged. |
| **tpep_dropoff_datetime** | Date and time when the meter was disengaged. |
| **Passenger_count** | Number of passengers in the vehicle (driver-entered value). |
| **Trip_distance** | Elapsed trip distance in miles reported by the taximeter. |
| **PULocationID** | TLC Taxi Zone where the taximeter was engaged (pickup). |
| **DOLocationID** | TLC Taxi Zone where the taximeter was disengaged (dropoff). |
| **RateCodeID** | Final rate code in effect at end of trip. `1 = Standard rate`; `2 = JFK`; `3 = Newark`; `4 = Nassau or Westchester`; `5 = Negotiated fare`; `6 = Group ride`. |
| **Store_and_fwd_flag** | Indicates whether the trip record was held in vehicle memory before being sent to the vendor (“store and forward”) because the vehicle did not have a connection to the server. `Y = store and forward`; `N = not a store and forward trip`. |
| **Payment_type** | Numeric code indicating how the passenger paid. `1 = Credit card`; `2 = Cash`; `3 = No charge`; `4 = Dispute`; `5 = Unknown`; `6 = Voided trip`. |
| **Fare_amount** | Time-and-distance fare calculated by the meter. |
| **Extra** | Miscellaneous extras and surcharges (includes $0.50 and $1 rush hour and overnight charges). |
| **MTA_tax** | $0.50 MTA tax triggered based on the metered rate in use. |
| **Improvement_surcharge** | $0.30 improvement surcharge assessed at flag drop (began in 2015). |
| **Tip_amount** | Tip amount (auto-populated for credit card tips; cash tips not included). |
| **Tolls_amount** | Total amount of all tolls paid in trip. |
| **Total_amount** | Total amount charged to passengers (does not include cash tips). |

---

## Notes
- This dataset is a **sample** of the full TLC 2017 Yellow Taxi trip data.
- Some categorical columns use numeric codes (e.g., `VendorID`, `RateCodeID`, `Payment_type`) as described above.
