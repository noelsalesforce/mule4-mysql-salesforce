# Mule 4 MySQL to Salesforce - Bulk Patient Data Sync

This MuleSoft project facilitates bulk data operations between MySQL and Salesforce for patient record management. It supports efficient, high-volume data transfer, deletion, and synchronization, ensuring seamless integration between these systems.

## Flows

### 1. **Bulk Create:**
- **Description**: Retrieves all patient records from MySQL and inserts them into Salesforce.
- **Process**:
  - Queries MySQL to gather patient data.
  - Transforms the data to match Salesforce object schema.
  - Bulk inserts patient records into Salesforce to ensure efficient data handling.
  
### 2. **Bulk Delete:**
- **Description**: Deletes specific patient records in bulk from Salesforce based on a predefined set of conditions.
- **Process**:
  - Uses Salesforce's **Query All** operation to identify the patient records.
  - Deletes records in bulk based on the provided criteria.
  
### 3. **Update Sync:**
- **Description**: Listens for modifications in Salesforce Patient Opportunity and updates relevant patient records in MySQL.
- **Process**:
  - Listens for updates to patient records in Salesforce.
  - Retrieves relevant changes.
  - Syncs the changes back to the corresponding patient records in MySQL, ensuring data consistency.
