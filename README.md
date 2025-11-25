## 🚀 Getting Started

To set up and run the application locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    https://github.com/itssandhyaa/Serverless-Scientific-Calculator.git
    cd Serverless-Scientific-Calculator
    ```

2.  **Install dependencies and build:**
    ```bash
    # Ensure you are using Node 18 or higher
    npm install
    npm run build
    ```

3.  **Run the service:**
    ```bash
    $ npm start
    ```
    You should see the following output:
    ```console
    > Starting server...
    Server listening on http://localhost:3000
    ```
# 📘 Serverless Scientific Calculator 

 This project is a serverless scientific calculator built using HTML, CSS, and JavaScript on the frontend, and AWS services on the backend. The calculator sends user input to an API Gateway endpoint, which triggers an AWS Lambda function that processes all scientific calculations. The results are returned to the frontend, and each calculation is stored in DynamoDB for history tracking. The entire application is hosted and deployed using AWS Amplify, making it fast, scalable, and easy to manage. This project demonstrates how to connect a simple UI to a fully serverless backend using core AWS services.

 ## Features
 

 - **Scientific Calculations:** Supports trigonometric functions, logarithms, exponentiation, square roots, percentages, factorials, and other advanced operations.

