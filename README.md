# AWS School Data Processing Project

![AWS Logo](https://upload.wikimedia.org/wikipedia/commons/9/93/Amazon_Web_Services_Logo.svg)
![AWS Project Architecture](https://github.com/abdullahasm99/AWS-School-Data-Processing-Project/assets/153215733/0193bdb8-cd1a-4b07-8d26-5758275dbfa2)


This repository contains the codebase and configuration files for an AWS project aimed at optimizing data processing workflows for a school application. Leveraging various AWS services, the project efficiently manages data extraction, transformation, loading, and analysis tasks.

## Key Features

- **EC2 Hosting:** Set up an EC2 instance to host a Flask-based school application, serving as the primary data source.
- **DynamoDB Integration:** Established connections with DynamoDB to organize student and marks data into two tables, linked via student_id for seamless data retrieval.
- **Lambda Function for Data Movement:** Orchestrated a Lambda function to automate the movement of data from DynamoDB to an S3 data lake, with batch processing capabilities for enhanced efficiency.
- **ETL with Glue and Spark:** Utilized AWS Glue service to run Extract, Transform, Load (ETL) tasks using Spark, preparing the data for advanced analytics and reporting.
- **S3 Data Warehouse:** Directed processed data to an S3 data warehouse, laying the groundwork for comprehensive data analysis and visualization.
- **Crawler and Athena Integration:** Triggered crawlers and utilized Athena for seamless querying and analysis of data, empowering stakeholders with actionable insights.
- **Optimized Data Pipelines:** Implemented optimized data pipelines to streamline workflows and enhance data-driven decision-making within the educational domain.

## Resources

- [AWS Documentation](https://docs.aws.amazon.com/)
- [Flask Documentation](https://flask.palletsprojects.com/en/2.0.x/)
- [Apache Spark Documentation](https://spark.apache.org/documentation.html)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
