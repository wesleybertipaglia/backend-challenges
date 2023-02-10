# Backend Challenge - Currency Converter API

## Introduction

Build a web service that converts amounts between different currencies using fixed exchange rates.

This challenge is tech-agnostic. Choose your preferred programming language and framework. For beginner level, no database required.

### Objectives

- Handle currency conversion logic
- Manage multiple currency pairs
- Provide accurate calculations

### Instructions

1. **Environment Setup**:
    - Programming language and web framework

2. **Implementation Details**:
    - Create a GET endpoint at `/convert` that accepts `amount`, `from`, and `to` parameters (e.g., from=USD, to=EUR)
    - Use fixed exchange rates (e.g., 1 USD = 0.85 EUR)

3. **Testing**:
    - Test with: `GET /convert?amount=100&from=USD&to=EUR`

### Possible Improvements

- Fetch real-time rates from an external API
- Support more currencies
- Add historical conversion

## Conclusion

By completing this challenge, you will learn to implement financial calculations in web services.

Happy coding!