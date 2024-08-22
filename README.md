This project is a simple API for the More Torque (MT) taxi service company. The first implemented endpoint decodes a Vehicle Identification Number (VIN) using the NHTSA API.
Endpoint Documentation
1. GET /vehicles/decode/:vin
Description: Decodes a VIN to retrieve vehicle details (manufacturer, model, year).
Rate Limiting: Limits API calls to NHTSA to 5 requests per minute.
Testing:
Open Swagger UI and use the GET /vehicles/decode/{vin} endpoint.
Enter a VIN (e.g., 1HGCM82633A123456) and click "Execute" to view the decoded details.

link of video : https://drive.google.com/file/d/1pEA4X8aijf9ns4RH702E8ZnRgZQAXgml/view?usp=drivesdk
