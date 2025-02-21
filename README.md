# mule4-mysql-salesforce

MySQL to Salesforce - Bulk Patient Data Sync
This MuleSoft project enables bulk data operations between MySQL and Salesforce:

Flows
- Bulk Create: Retrieves all patient records from MySQL and inserts them into Salesforce.
- Bulk Delete: Uses Salesforce's Query All operation to delete specific records in bulk.
- Update Sync: Listens for modifications in Salesforce Patient Opportunity and updates relevant patient records in MySQL.
