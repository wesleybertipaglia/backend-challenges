# Backend Challenge - Roman Numeral Converter API

## Introduction

Create a web service that converts numbers to Roman numerals and vice versa.

This challenge is tech-agnostic. Choose your preferred programming language and framework. For beginner level, no database required.

### Objectives

- Implement conversion algorithms for Roman numerals
- Handle both directions: number to Roman and Roman to number
- Validate input formats

### Instructions

1. **Environment Setup**:
    - Programming language and web framework

2. **Implementation Details**:
    - Create GET endpoints at `/to-roman` (accepts `number`) and `/from-roman` (accepts `roman`)
    - Implement logic to convert between Arabic and Roman numerals

3. **Testing**:
    - Test with: `GET /to-roman?number=2023` and `GET /from-roman?roman=MMXXIII`

### Possible Improvements

- Add range validation (1-3999 for standard Roman numerals)
- Support subtractive notation
- Handle invalid inputs gracefully

## Conclusion

By completing this challenge, you will learn algorithmic thinking and string manipulation in web services.

Happy coding!