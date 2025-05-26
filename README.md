# Tracking-Number-Generator
Generates unique tracking numbers for parcels

## Features

- RESTful API using Spring Boot
- Thread-safe tracking number generation
- Validates and accepts multiple parameters
- Ensures unique tracking numbers
- Designed for scalability and horizontal scaling

## API Specification

**Endpoint**:  
GET /next-tracking-number

### Response
{
  "trackingNumber": "REDBX1KF9NAJD9L7",
  "createdAt": "2025-05-26T12:00:00+08:00"
}

### Prerequisites:
- Java 17+
- Maven 3+

# Clone the repo
git clone https://github.com/akkarao/Tracking-Number-Generator.git
