# API Automation Test - Restful Booker

## Objective
This project aims to automate API tests for creating and deleting bookings using Postman. 

## Steps to Run
1. **Set Up Postman Environment**
   - Install Postman.
2. **Import the Postman Collection**
   - Import the `restful-booker-collection.json` file into Postman.
3. **Select End Point That Will Be Execute**
   On Run collection feature, select the following endpoints:
   - Auth - CreateToken
   - Booking - CreateBooking
   - Booking - DeleteBooking
3. **Load Data File**
   - In the Postman Collection Runner, upload the `restfull-booker_postman_booking_data.csv` file.
4. **Run the Collection and Verify Results**
   - Run the collection.
   - Ensure that assertions for each request pass as expected.

## Files Included
- **`restful-booker-collection.json`**: Postman collection file containing the API requests.
- **`test_plan.pdf`**: Detailed test plan outlining test objectives, scenarios, and expected results.
- **`restfull-booker_postman_booking_data.csv`**: CSV file with sample booking data for dynamic testing.
- **`restful_booker_api_automation_test.mp4`**: Screen recording of the test execution, showcasing the steps and results.

## Prerequisites
- Postman installed on your system.
