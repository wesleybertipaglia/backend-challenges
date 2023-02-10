# Backend Challenge - Time Zone Converter API

## Introduction

Create a web service that converts time between different time zones.

This challenge is tech-agnostic. Choose your preferred programming language and framework. For beginner level, no database required.

### Objectives

- Handle date and time manipulations
- Work with time zone offsets
- Format time appropriately

### Instructions

1. **Environment Setup**:
    - Programming language and web framework

2. **Implementation Details**:
    - Create a GET endpoint at `/convert-time` that accepts `time`, `from_tz`, and `to_tz` parameters
    - Use appropriate libraries for time zone conversions

3. **Testing**:
    - Test with: `GET /convert-time?time=2023-10-01T12:00:00&from_tz=America/New_York&to_tz=Europe/London`

### Possible Improvements

- Support multiple time formats
- Add daylight saving adjustments
- Provide current time in zones

## Conclusion

By completing this challenge, you will gain experience with time and date handling in APIs.

Happy coding!