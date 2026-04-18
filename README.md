# OWASP Top 10 Web Vulnerabilities Lab

## Overview

This project is an interactive learning platform designed to help students and security enthusiasts understand the OWASP Top 10 web vulnerabilities through practical, hands-on simulations.

Instead of relying only on theory, this application allows users to explore how vulnerabilities occur in real-world web applications, interact with simulated attack scenarios, and understand how each issue can be prevented.

## Objectives

* Provide a clear and simple understanding of OWASP Top 10 vulnerabilities
* Demonstrate how vulnerabilities are exploited in real applications
* Encourage hands-on learning through interactive simulations
* Teach secure development practices and mitigation techniques

## Features

* Interactive simulations for each OWASP Top 10 vulnerability
* Simple and beginner-friendly explanations
* Real-world attack scenarios (simulated safely)
* Challenge-based learning to reinforce understanding
* Clear demonstration of both vulnerable and secure implementations

## Covered Vulnerabilities

This lab focuses specifically on web application security and includes:

* A01: Broken Access Control (IDOR)
* A02: Security Misconfiguration
* A03: Software Supply Chain Failures
* A04: Cryptographic Failures
* A05: Injection (SQL Injection / XSS)
* A06: Insecure Design
* A07: Authentication Failures
* A08: Software/Data Integrity Failures
* A09: Security Logging and Alerting Failures
* A10: Exceptional Condition Handling

## How It Works

Each vulnerability module follows a consistent structure:

1. Explanation
   A simple and relatable description of the vulnerability.

2. Simulation
   A controlled environment where users can interact and observe how the vulnerability behaves.

3. Challenge
   A task that requires users to apply their understanding and exploit the issue in the simulation.

4. Mitigation
   Practical guidance and examples showing how to fix the vulnerability.

## Technology Stack

* Frontend: HTML, CSS, JavaScript
* Backend: Python (Flask or similar framework)
* Simulation: Mocked endpoints and controlled logic for safe demonstration

## Getting Started

### Prerequisites

* Python 3.x installed
* Basic understanding of web applications

### Installation

```bash
git clone https://github.com/your-username/owasp-top10-web-lab.git
cd owasp-top10-web-lab
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

Then open your browser and navigate to:

```
http://127.0.0.1:5000
```

## Important Note

This project is built strictly for educational purposes.

All vulnerabilities are simulated in a controlled environment using mock data. The application does not expose real systems or allow actual exploitation.

## Learning Use Cases

* Cybersecurity training sessions
* Classroom demonstrations
* Self-paced learning
* Hands-on lab exercises

## Future Improvements

* Integration with real tools (e.g., Burp Suite demonstrations)
* Advanced attack chaining scenarios
* Expanded challenges for deeper practice
* User progress tracking

## Contribution

Contributions are welcome. Suggestions for improving simulations, adding new scenarios, or enhancing learning flow are encouraged.

## License

This project is intended for educational use. Add an appropriate open-source license if you plan to distribute it publicly.
