## 🚀 Getting Started

To set up and run the application locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/my-project/my-app.git
    cd my-app
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

    <h1>📘 Serverless Scientific Calculator </h1>
<p>
 This project is a serverless scientific calculator built using HTML, CSS, and JavaScript on the frontend, and AWS services on the backend. The calculator sends user input to an API Gateway endpoint, which triggers an AWS Lambda function that processes all scientific calculations. The results are returned to the frontend, and each calculation is stored in DynamoDB for history tracking. The entire application is hosted and deployed using AWS Amplify, making it fast, scalable, and easy to manage. This project demonstrates how to connect a simple UI to a fully serverless backend using core AWS services.
 </p>
 <p>
 <ul>

 <li>Scientific Calculations: Supports trigonometric functions, logarithms, exponentiation, square roots, percentages, factorials, and other advanced operations.</li>

<li>Serverless Backend: All calculations are processed inside an AWS Lambda function, ensuring high performance without managing servers.</li>

<li>API-Driven Architecture: Uses AWS API Gateway to securely expose the backend as a REST API that the frontend can call.</li>

<li>Calculation History: Every expression and its result are stored in DynamoDB, allowing retrieval of past calculations.</li>

<li>Cloud Hosting: The frontend (HTML, CSS, JS) is hosted through AWS Amplify for fast, reliable, and globally accessible deployment.</li>

<li>Scalable & Low-Cost: Because the project is serverless, it automatically scales with traffic and costs almost nothing to run for small workloads.</li>

<li>Responsive Interface: Designed to work smoothly across desktop and mobile devices with a clean, simple UI.</li>
</ul>
</p>