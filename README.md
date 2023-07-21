# Stock-market-realtime-project

### Project Overview
This project presents a comprehensive end-to-end data engineering and analysis solution for real-time stock market data. Leveraging Python for data generation, Apache Kafka for real-time data streaming, and Amazon Web Services (AWS) for data storage, processing, and analysis, the project showcases a powerful and scalable approach to market data analytics. The project also includes setting up an EC2 instance on AWS and installing Kafka for stream processing.

### Project Highlights
- Utilize Python to simulate real-time stock market data with attributes like stock prices, trading volumes, and company identifiers.
- Stream the generated data seamlessly to an Apache Kafka cluster running on a provisioned EC2 instance, ensuring real-time ingestion and processing.
- Employ AWS services like Amazon S3 to store the streaming data, ensuring durability and accessibility for future analysis.
- Utilize AWS Glue for automatic data crawling and building a comprehensive data catalog, simplifying metadata management.
- Use Amazon Athena for interactive SQL-based querying and analysis of the stock market data stored in Amazon S3.

### Technologies Used
- Python: Data generation and simulation of real-time stock market data.
- Apache Kafka: Real-time data streaming and message queuing for data consumption.
- Amazon Web Services (AWS):
- Amazon S3: Durable and scalable object storage for raw and processed data.
- AWS Glue: Automatic data cataloging and metadata management for data stored in S3.
- Amazon Athena: Interactive SQL querying and analysis of data in S3.
- Amazon EC2: Provisioning and management of the Kafka cluster.
- SQL: Query language for data analysis and exploration.

![Architecture image](https://github.com/divyasree25/stock-market-realtime-project/blob/main/Architecture.jpg)

### License
This project is under MIT License.
