# Power Calculator Web Application

## Project Overview

The Power Calculator Web Application is a simple tool that allows users to calculate the power of any number. It's designed to showcase the integration of various AWS services to provide a seamless and reliable user experience.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Architecture](#architecture)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Demo

Visit the live demo of the Power Calculator Web Application [here](https://dev.d1est5fg7jrh52.amplifyapp.com/).

## Features

- Calculate the power of any number using a base and exponent.
- Real-time calculation and result display.
- User-friendly interface.

## Architecture

The Power Calculator Web Application is built using a serverless architecture on AWS. Here's how the services are utilized:

1. **Frontend**: Built using React.js and deployed to Amazon S3.
2. **Backend**: AWS Lambda functions handle the calculation logic.
3. **API Gateway**: Manages the communication between the frontend and Lambda functions.
4. **AWS DynamoDB**: Stores calculation history for each user.
5. **Amazon Cognito**: Manages user authentication.

![Architecture Diagram](architecture-diagram.png)

## Technologies Used

- Frontend:
  - React.js
  - Axios (for API requests)
  
- Backend:
  - Node.js for Lambda functions

- AWS Services:
  - Amazon S3
  - AWS Lambda
  - Amazon API Gateway
  - Amazon DynamoDB
  - Amazon Cognito

## Getting Started

Follow these steps to set up the project locally.

### Prerequisites

- Node.js and npm
- AWS CLI configured with necessary permissions
- Amazon DynamoDB table and Amazon Cognito user pool set up

### Installation

1. Clone this repository: `git clone https://github.com/your-username/power-calculator.git`
2. Navigate to the project directory: `cd power-calculator`
3. Install dependencies: `npm install`

## Usage

1. Run the frontend: `npm start`
2. Access the application at `http://localhost:3000`

## Contributing

Contributions are welcome! If you'd like to contribute, please follow the [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
