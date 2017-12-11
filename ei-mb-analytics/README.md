# Enterprise Integrator: Reliable Messaging Scenario with Analytics
In this setup, there are three mock services developed using msf4j, which will perform as a usage recording system, invoice generation system and a payment gateway. When a customer wants to settle a phone bill, he has to send his id, region and card number. Then the system will make three blocking calls to each of the above systems and then return the status of the payment to the customer.

## Versions
- v1.0.0 : This setup uses integration, broker, msf4j and analytics profiles from WSO2 Enterprise Integrator 6.1.1.

## How to run
1. Install docker into your environment
2. Clone this Git repository
3. Depending on the dependencies specified in the demo version, download the desired Enterprise Integrator pack (wso2ei-*.*.*.zip).
4. Copy wso2ei-*.*.*.zip into ei-setup, ei-mb-setup and ei-analytics-setup folders.
5. Goto v*.*.* and execute the following command.
   ```bash
   docker-compose build && docker-compose up
   ```

