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

### Sample Request
http://localhost:8080/next-tracking-number?origin_country_id=MY&destination_country_id=ID&weight=1.234&created_at=2025-05-26T12:00:00+08:00&customer_id=de619854-b59b-425e-9db4-943979e1bd49&customer_name=RedBox Logistics&customer_slug=redbox-logistics

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
