# Postman Automated API Testing Suite

This repository demonstrates a comprehensive suite of automated API tests using Postman. It includes:

- A well-structured Postman collection with various HTTP methods
- Test scripts for validating responses
- Data-driven testing using external JSON files
- Environment variables for flexible configurations

## 🚀 Getting Started

1. Clone this repository or download the files.
2. Open Postman.
3. Import the collection and environment files:
   - `Demo_API_Collection.json`
   - `Demo_Environment.json`
4. For data-driven tests, import the `test_data.json` file into Postman Runner.
5. Execute the collection using the Collection Runner or schedule automated runs.

## 📁 Folder Structure

- `Postman_Collections/`: Contains the Postman collection file.
- `Postman_Environments/`: Contains environment variable configurations.
- `Test_Data/`: JSON file for data-driven testing.
- `Sample_Responses/`: Example JSON responses for reference.

## 🧪 Test Scenarios

The collection includes tests for:

- Validating response status codes
- Checking for required fields in JSON responses
- Verifying response times
- Data-driven testing with multiple input sets

## 🔄 Automation

Automate your test executions by:

- Using Postman Monitors for scheduled runs.
- Integrating with CI/CD pipelines using Newman, the Postman CLI tool.

Feel free to explore and contribute!
