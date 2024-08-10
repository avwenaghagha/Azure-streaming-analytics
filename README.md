# Azure-streaming-analytics
## Processing Stream Data With SQL
## INTRODUCTION
This project demonstrates how to ingest real-time sensor data from a Raspberry Pi IoT simulator into Azure IoT Hub, process the streaming data using Azure Stream Analytics, and store the filtered output in Azure Blob storage for further analysis and visualization in Power BI.
By leveraging Azure's IoT and data analytics services, this project showcases an end-to-end pipeline for collecting, processing, and storing IoT data at scale, enabling valuable insights and decision-making based on the streaming sensor information.
## TECHNOLOGY USED 
- Azure IoT Hub: A cloud service that facilitates communication between IoT applications and devices.
- Azure Stream Analytics: A real-time analytics service for processing streaming data from various sources.
- Azure Blob Storage: A storage solution for saving large amounts of unstructured data, such as the output from your stream analytics job.
- Raspberry Pi IoT Simulator: A web-based simulator that mimics the behavior of a Raspberry Pi device to send data to Azure IoT Hub without needing physical hardware.
- SQL Query language.
- These technologies work together to create a robust streaming analytics pipeline for IoT data.
 ## CHALLENGES FACED
- Configuration Errors: Incorrectly set connection strings or misconfigured application settings can prevent successful connections. Ensure the connection string is accurate and that the IoT Hub is properly configured to accept the device.
- Network Connectivity: The device must have a stable internet connection. Issues like firewalls or proxy settings can block communication between the Raspberry Pi and Azure IoT Hub, leading to connection failures
## Step-by-Step Guide
-  IMPLEMENTATION IN STEPS 
1. Set up Azure Resources.
- Create an IoT Hub to ingest device data
- Create a Stream Analytics job for real-time processing
- Create a Blob Storage account to store processed output.
 2. Configure IoT Hub Input
- Set up the Raspberry Pi IoT simulator to send data to IoT Hub
- Ensure proper connection string and authentication is configured.
  3. Design Stream Analytics Job
- Define the input source as the IoT Hub
- Write a SQL-like query to filter, aggregate or transform the streaming data
- Configure the output to write to the Blob Storage account.
 4. Test and Validate
- Run test data through the pipeline
- Verify the processed output is correctly landing in Blob Storage.
 5. Visualize in Power BI
- Connect Power BI to the Blob Storage account
- Build dashboards and reports to visualize the IoT data insights.
  ## CONCLUSION
  - The key learnings and benefits of your data engineering project on streaming analytics using Azure IoT simulator, Raspberry Pi, Blob Storage, Stream Analytics job, and IoT Hub include:
  - Real-Time Data Processing
  - Seamless Integration of Azure Services.
  - Cost-Effective Solutions.
  - Visualization Capabilities.
  - Hands-On Experience with IoT Technologies.
  - Scalability and Flexibility.
  - These learnings emphasize the effectiveness of Azure's ecosystem for building robust streaming analytics solutions that can handle the complexities of modern IoT data environments.
