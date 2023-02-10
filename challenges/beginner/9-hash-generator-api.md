# Backend Challenge - Hash Generator API

## Introduction

Create a web service that generates cryptographic hashes for input strings.

This challenge is tech-agnostic. Choose your preferred programming language and framework. For beginner level, no database required.

### Objectives

- Implement hashing algorithms
- Handle different hash types
- Ensure secure output

### Instructions

1. **Environment Setup**:
    - Programming language and web framework

2. **Implementation Details**:
    - Create a GET endpoint at `/hash` that accepts `text` and `algorithm` parameters
    - Support algorithms like MD5, SHA256, etc.

3. **Testing**:
    - Test with: `GET /hash?text=hello&algorithm=sha256`

### Possible Improvements

- Add salt support
- Implement HMAC
- Provide encoding options

## Conclusion

By completing this challenge, you will understand cryptographic operations in APIs.

Happy coding!