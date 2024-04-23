# Event_Driven_Sales_Data_Processing

This project involves implementing a robust data pipeline to manage incoming order data from JSON files stored in an S3 bucket. Effectively categorized orders based on the presence of contact information, directing those with contact details to a DynamoDB database for storage, and routing orders without contact information to a Dead Letter Queue (DLQ) for further analysis.
