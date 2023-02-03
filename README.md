# dmoney-api-jmx

## Technology Used
- Apache JMeter
- Java

## Scenario
Add following requests:
1. Login to user
2. Create a new agent
3. Give balance to the newly created agent from system
4. Create a customer
5. Search the newly created user by phone number
6. Deposit balance to the customer from the agent
7. Withdraw some money from the agent
8. Delete the user

## How to run this project
- clone this project
- save the DmoneyApi.jmx file into bin folder of installed location of Jmeter
- open the DmoneyApi.jmx file with jemeter & run the project
- to Generate report on the command prompt, delete the already copied .csv file and Report folder from the project
- hit the command:
- $ jmeter -n -t DmoneyApi.jmx -l DmoneyApi.csv -e -o Reports

## Html Report
![DmoneyHtmlReport](https://user-images.githubusercontent.com/50767962/216639170-84489245-2c91-48d4-9444-7d7b82444b4d.png)
