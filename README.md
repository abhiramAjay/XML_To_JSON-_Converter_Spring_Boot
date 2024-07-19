# XML to JSON File Converter

This is a Spring Boot application that converts XML files to JSON format. The application provides an API endpoint for the conversion.

## Prerequisites

- Java 8 or higher
- Maven
- Spring Boot

## Getting Started

### Clone the Repository

```sh
git clone https://github.com/yourusername/xml-to-json-converter.git
cd xml-to-json-converter
curl -X POST \
  http://localhost:8080/convert \
  -H 'Content-Type: application/xml' \
  -d @input.xml
