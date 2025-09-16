# Gemini Email Writer

A Spring Boot project that integrates with **Google Gemini API** to auto-generate professional emails.

## Features
- REST API with Spring Boot
- Uses Gemini API (`gemini-2.0-flash`) for text generation
- WebClient for HTTP requests

## Setup
1. Clone this repo
2. Add your Gemini API key in `application.properties`
3. Run the project: `mvn spring-boot:run`
4. Test with Postman at `POST /api/email/generate`
