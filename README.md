# CLOUD SPLIT - Enhancing Security with Data Division and Replication

Cloud Split is a cloud security project that enhances data security by dividing data into multiple parts and replicating it across different cloud storage platforms. This approach ensures data integrity, availability, and security by preventing unauthorized access to complete datasets.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Architecture](#architecture)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Security Benefits](#security-benefits)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction
Cloud Split is designed to provide robust data security by splitting sensitive information into multiple parts and storing them across various cloud providers. By dividing data and replicating it securely, unauthorized access to complete datasets is prevented, ensuring enhanced security and availability.

---

## Features
- **Data Division**: Splits data into smaller chunks to enhance security.
- **Data Replication**: Replicates data parts across multiple cloud storage providers.
- **Redundancy and Availability**: Ensures high availability and fault tolerance through replication.
- **Encryption**: Encrypts data parts before uploading to the cloud for added security.
- **Secure Retrieval**: Reassembles data securely from multiple sources.

---

## Architecture
- **Data Division Module**: Splits data into multiple parts.
- **Encryption Module**: Encrypts each data part before uploading.
- **Replication Module**: Distributes and replicates data parts across multiple cloud providers.
- **Reconstruction Module**: Retrieves and reassembles data from different cloud sources securely.

---

## Technologies Used
- **Java**: Core programming language.
- **Spring Boot**: For building RESTful APIs and managing application logic.
- **Cloud Storage Providers**: AWS S3, Google Cloud Storage, and Azure Blob Storage.
- **JCA (Java Cryptography Architecture)**: For data encryption and decryption.
- **Maven/Gradle**: Dependency management and build automation.

---

## Installation
1. Clone the repository:
    ```
    git clone https://github.com/your-username/cloud-split.git
    ```
2. Navigate to the project directory:
    ```
    cd cloud-split
    ```
3. Build the project using Maven or Gradle:
    ```
    mvn clean install
    ```
    or
    ```
    ./gradlew build
    ```
4. Configure cloud storage credentials for AWS, GCP, and Azure in the application.properties file.

---

## Usage
1. Start the application:
    ```
    java -jar target/cloud-split.jar
    ```
2. Use the web interface or API endpoints to upload, split, and replicate data.
3. Securely retrieve and reassemble data using the reconstruction module.

---

## Security Benefits
- **Confidentiality**: Data is encrypted and split into smaller parts, reducing the risk of unauthorized access.
- **Integrity**: Replication ensures data integrity and availability even if one cloud provider is compromised.
- **Redundancy**: Data parts are replicated across multiple cloud platforms, ensuring high availability and fault tolerance.

---

## Contributing
Contributions are welcome! To contribute:
- Fork the repository
- Create a new branch (`git checkout -b feature-branch`)
- Commit your changes (`git commit -m 'Add new feature'`)
- Push to the branch (`git push origin feature-branch`)
- Open a pull request

---

## License
This project is licensed under the MIT License.

