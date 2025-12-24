# REST API Testing with Postman Validation, negative scenarios, and schema checks

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
```
postman/
├── collections/
│   ├── Weather API Testing Openweathermap.postman_collection.json
│   └── Weather API Testing Open-meteo.postman_collection.json
│
├── environments/
│   ├── openweather.postman_environment.json
│   └── open-meteo.postman_environment.json
│
└── README.md
```

## How to Run
1. Import the required collection into Postman
2. Import the corresponding environment
3. Set your API key locally (for OpenWeather)
4. Run requests via Collection Runner or manually

Note:
This project is primarily intended for demonstration and review.
Collections are fully executable but not designed as a ready-to-run public tool.

## Notes
- API keys are not stored in the repository for security reasons
- Negative tests dynamically override parameters via pre-request scripts
- The project runs entirely inside Postman without external dependencies

## Author
Polina Guller — QA Automation Engineer
