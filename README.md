# PowerBi_Uber Data Analytics Dashboard

# 🚖 Uber Ride Booking Dataset 2024

This comprehensive dataset contains detailed ride-sharing data from Uber operations for the year 2024, providing rich insights into booking patterns, vehicle performance, revenue streams, cancellation behaviors, and customer satisfaction metrics.

The dataset captures 148,770 total bookings across multiple vehicle types and provides a complete view of ride-sharing operations including successful rides, cancellations, customer behaviors, and financial metrics.
This dataset contains detailed information about ride bookings, cancellations, trip performance, and customer/driver interactions. It is designed for **data analysis, visualization, and dashboard creation** (e.g., Power BI, Tableau, Python, SQL).

---

## 📊 Dataset Schema

| **Column Name**                | **Description**                                                                 |
|--------------------------------|---------------------------------------------------------------------------------|
| Date                           | Date of the booking                                                             |
| Time                           | Time of the booking                                                             |
| Booking ID                     | Unique identifier for each ride booking                                         |
| Booking Status                 | Status of booking (Completed, Cancelled by Customer, Cancelled by Driver, etc.) |
| Customer ID                    | Unique identifier for customers                                                 |
| Vehicle Type                   | Type of vehicle (Go Mini, Go Sedan, Auto, eBike/Bike, UberXL, Premier Sedan)    |
| Pickup Location                | Starting location of the ride                                                   |
| Drop Location                  | Destination location of the ride                                                |
| Avg VTAT                       | Average time for driver to reach pickup location (in minutes)                   |
| Avg CTAT                       | Average trip duration from pickup to destination (in minutes)                   |
| Cancelled Rides by Customer    | Customer-initiated cancellation flag                                            |
| Reason for cancelling by Customer | Reason for customer cancellation                                             |
| Cancelled Rides by Driver      | Driver-initiated cancellation flag                                              |
| Driver Cancellation Reason     | Reason for driver cancellation                                                  |
| Incomplete Rides              
Payment Method	Method used for payment (UPI, Cash, Credit Card, Uber Wallet, Debit Card)
