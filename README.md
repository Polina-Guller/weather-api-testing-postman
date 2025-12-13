# Weather API Testing (Postman)

This project demonstrates API testing using Postman with a focus on functional and negative test scenarios.
It covers weather data validation for public weather APIs and is designed as a portfolio project for QA Automation.

## APIs Covered
- OpenWeather API  
  - Current Weather
  - 5-Day Forecast
- Open-Meteo Historical Weather API

## Key Features
- Positive and negative API test scenarios
- Environment-based configuration
- Pre-request scripts for dynamic negative testing
- JSON Schema validation
- Structured test naming and logging
- Collection Runner support

## Tools & Technologies
- Postman
- JavaScript (Postman scripts)
- JSON Schema validation
- Public Weather APIs

## Project Structure
postman/
├── collections/
│ ├── openweather_collection.json
│ └── open_meteo_collection.json
├── environments/
│ ├── openweather_environment.json
│ └── open_meteo_environment.json

## How to Run
1. Import collections and environments into Postman
2. Select the required environment
3. Set your API key (for OpenWeather) locally in Postman
4. Use Collection Runner to execute tests

## Notes
- API keys are not stored in the repository for security reasons
- Negative tests dynamically override parameters via pre-request scripts
- The project runs entirely inside Postman without external dependencies

## Author
Polina — QA Automation Engineer
