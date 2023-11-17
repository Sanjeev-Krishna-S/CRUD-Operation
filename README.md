# CRUD Operation

## CREATE Operation (POST)

1. Set the request type to POST.
2. Enter the URL: `http://localhost:3000/hospitals`.
3. Switch to the "Body" tab.
4. Choose "raw" and select JSON (`json`).
5. Enter the hospital data in the body. For example:

    ```json
    {
      "name": "New Hospital",
      "patientCount": 100,
      "location": "City"
    }
    ```

6. Click "Send." This will add the following parameters to the corresponding JSON file in the directory (`hospitalData.json`).

## READ Operation (GET)

1. Open Postman.
2. Set the request type to GET.
3. Enter the URL for getting all hospitals: `http://localhost:3000/hospitals`.
4. Click "Send."

#### READ Operation for a Specific Hospital:

1. Set the request type to GET.
2. Enter the URL for a specific hospital (replace `hospital_name` with the actual hospital name): `http://localhost:3000/hospitals/hospital_name`. <!-- Eg: http://localhost:3000/hospitals/GOKULAM-->
3. Click "Send."

## UPDATE Operation (PUT)

1. Set the request type to PUT.
2. Enter the URL for updating a specific hospital (replace `hospital_name` with the actual hospital name): `http://localhost:3000/hospitals/hospital_name`.
3. Switch to the "Body" tab.
4. Choose "raw" and select JSON (`application/json`).
5. Enter the updated hospital data in the body. For example:

    ```json
    {
      "name": "Updated Hospital",
      "patientCount": 150,
      "location": "New City"
    }
    ```

6. Click "Send."

## DELETE Operation (DELETE)

1. Set the request type to DELETE.
2. Enter the URL for deleting a specific hospital (replace `hospital_name` with the actual hospital name): `http://localhost:3000/hospitals/hospital_name`.
3. Click "Send."

**Note:** The CRUD operations outlined above are performed using Postman. Make sure to replace placeholders such as `hospital_name` with the actual hospital name in the URLs. 


