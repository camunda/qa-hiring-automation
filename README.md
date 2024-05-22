# Coding Challenge: Software Engineer - Quality

## Objective
Use Playwright and TypeScript to automate the following workflow: sign into Camunda 8, create a process with a REST Connector using the Web Modeler, run an instance of the process, and verify its successful completion in Operate.

## Instructions

1. **Sign up for Camunda 8**
   - If you don't already have an account, you can register [here](https://camunda.com/get-started/).

2. **Explore the REST Connector**
   - Follow the guide for configuring the REST Connector in Camunda 8 available [here](https://docs.camunda.io/docs/components/connectors/protocol/rest/).
   - Make sure you understand how to interact with external APIs using this connector.
   - You can also use this [video](https://academy.camunda.com/c8-h2-configure-rest-connector) for support.

3. **Automate the following test case using Playwright and TypeScript**
   1. Sign into Camunda 8 platform
   2. Navigate to the Web Modeler
   3. Create a process with a REST Connector
   4. Run an instance of the process
   5. Assert that this process has successfully completed in Operate

## Submission Guidelines

1. Write your automation code in TypeScript using Playwright.
2. Submit your code to your personal private GitHub repository.
3. Add the following reviewers' email addresses: 
   - sara.lolatte@camunda.com 
   - michael.schoettes@camunda.com
4. Submission must occur within one week of receiving the coding challenge.

## Evaluation Criteria

1. **Correctness of the Automation**
   - Make sure that all steps are accurately automated, including signing in, process creation, instance running, and completion assertion.

2. **Code Quality**
   - Write clean, maintainable code with proper error handling and comments.

3. **Adherence to Best Practices**
   - Follow best practices for automated testing, TypeScript, and Playwright.

4. **Completion of Additional Features or Improvements**
   - Bonus points may be awarded for implementing additional features or optimizations beyond the basic requirements.

## Additional Notes

- For the automated test, you can assume that the environment already has a healthy cluster setup. However, for local development, you will need to create one manually. You can follow instructions [here](https://docs.camunda.io/docs/guides/create-cluster/).
- Make sure your code is well-documented and easy to understand.
- If you encounter any issues or have questions, feel free to reach out to the provided email addresses for assistance.
