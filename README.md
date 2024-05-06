# Health Insurance Plan Information Service

This project provides a Health Insurance Plan Information Service that stores and manages information about health insurance plans, including cost shares and linked plan services. The service is built using Java, Spring Boot, Elasticsearch, and MongoDB.

## Overview

The Health Insurance Plan Information Service allows users to access detailed information about health insurance plans, including:

- Plan cost shares such as deductible and copay.
- Linked plan services, including their cost shares.

The service is designed to provide comprehensive and up-to-date information to help users make informed decisions about their health insurance plans.

## Plan Data Structure

The health insurance plan data is structured as follows:

- **Plan Object**:
  - Plan ID: Unique identifier for the plan.
  - Plan Type: Type of plan (e.g., in-network).
  - Creation Date: Date when the plan was created.

- **Plan Cost Shares**:
  - Deductible: The amount that must be paid by the insured before the insurance company begins to pay.
  - Copay: The fixed amount paid by the insured for covered services.
  
- **Linked Plan Services**:
  - Linked Service: Information about a specific service linked to the plan.
  - Service Name: Name of the linked service.
  - Service Cost Shares: Cost shares associated with the linked service, including deductible and copay.

## Technologies Used

- Java
- Spring Boot
- Elasticsearch
- MongoDB

## Usage

To use the Health Insurance Plan Information Service, clone or download the repository and follow the instructions in the project documentation to set up and run the service on your local machine or server.

## Contributions

Contributions to this project are welcome! If you have suggestions for enhancements, improvements, or additional features, feel free to open an issue or submit a pull request.
