# RideAlike API Testing Collection

This repository contains a Postman collection for testing the RideAlike API endpoints related to profiles, cars, trips, payments, bookings, and miscellaneous services (like Zoho integration).

## 📂 Contents

- `RideAlike Http.postman_collection.json`: Postman collection file containing organized API endpoints.
- `README.md`: Instructions and descriptions for using and modifying the API tests.

## 🚀 How to Use

1. **Import Collection**:
   - Open Postman.
   - Click on "Import" and select the `.json` file.

2. **Set Environment**:
   - Configure variables such as `BaseURL`, `Token`, etc., in a Postman environment.
   - Replace hardcoded tokens in the requests with `{{token}}`.

3. **Execute Tests**:
   - Choose the desired API request and click **Send**.
   - Check the response and validate against expected output.

4. **Modify Requests**:
   - Update URL, headers, or body as needed.
   - Click **Save** after editing a request.

## 📌 API Groups

- **Profile APIs**:
  - Verify with Certn
  - Get Certn Applicant Info
  - Update, Submit, Get Profile
  - Set Verification Status

- **Car APIs**:
  - Get All Cars
  - Set About Section
  - Get All Car Listings

- **Trip APIs**:
  - Cancel Trip
  - Accept Trip Change
  - Get Trip by ID
  - Get All Trips

- **Payment APIs**:
  - Pay Due Amount

- **Booking APIs**:
  - Accept Manual Booking
  - Get Booking by ID
  - Get Pricing

- **Misc APIs (Zoho Integration)**:
  - Call Zoho API
  - Get Zoho Auth URL
  - Exchange Zoho Auth Code
  - Track Sign-In
  - Revoke Sync
  - Start Car/Trip Sync

## 🛠 Modify Requests

To change:
- **Token**: Replace the `"value"` under `auth.bearer` with your own.
- **Payload**: Modify the JSON body as per new testing needs.
- **Endpoint URL**: Update `localhost` or dev URLs if needed.

## 📧 Support

For any issues or queries, please contact 'redoankhan777@gmail.com'.
