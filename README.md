# Daikibo-Project
## Task1 : Combine code into a unified format using Python
### Here is the background information on task 1
We have signed a new account - Daikibo Industrials, a global leader in the manufacturing of heavy machinery, founded and headquartered in Tokyo, Japan. They needed assistance with a variety of problems and were impressed to find out Deloitte could help in all verticals.

Daikibo is in the process of integrating IIoT (Industrial Internet-of-Things) devices to monitor, measure and analyze their manufacturing processes. Half of their infrastructure uses devices streaming telemetry data in one format, and the other half - in another. They need your help to combine the two.


Took the following steps to complete the task:

- Created an account at repl.it.
- Fork this project into my workspace.
- Get acquainted with the 2 data formats by exploring the files (hint: it's the same message, represented in 2 different formats):
data-1.json
![data1](https://github.com/user-attachments/assets/f79d9825-c20f-47a1-9ad7-44ea57e784b7)

data-2.json
![data2](https://github.com/user-attachments/assets/8941c049-fee1-4632-8db2-b75548b7b757)

- Explore the target unified format by looking at the file data-result.json
![dataresult](https://github.com/user-attachments/assets/9e3f2908-5f0d-4f80-b7ed-efc3c802a3d4)

- Completed the solution located in the file main.py.
- Found the 2 functions in need of implementation and finish them.
![main1](https://github.com/user-attachments/assets/621b8ec4-e94c-4151-aee4-8899bc521279)
![main2](https://github.com/user-attachments/assets/46487828-d785-4b2d-a868-4f5a997ace0a)
![main3](https://github.com/user-attachments/assets/39071d06-3820-47a2-9f11-7292712f54cf)
![main4](https://github.com/user-attachments/assets/8012fe39-e64a-49e1-b6b2-24c594b8b3d2)

- The result
![result](https://github.com/user-attachments/assets/6c687216-5ca9-4b31-9cb2-c3be0b6d4808)


## Task 2: Analyze the clients data by creating a dashboard using Tableau
### Background Information on Task2
Having your data unification algorithm, Daikibo's tech team has converted all telemetry data collected from the 4 factories of the company:

Daikibo Factory Meiyo (Tokyo, Japan)
Daikibo Factory Seiko (Osaka, Japan)
Daikibo Berlin (Berlin, Germany)
Daikibo Shenzhen (Shenzhen, China)
Each location has 9 types of machines, sending a message every 10 min. Daikibo has been collecting this data for 1 month (May 2021) and they've just shared this data in the form of a single JSON file.

The reason this client wanted to collect telemetry was to answer 2 questions:

- In which location did machines break the most?
- What are the machines that broke most often in that location?
Your second task is to analyse the telemetry data collected by Daikibo (and unified with your algorithm) in a software called Tableau. Here are the steps that you need to take:

Steps to solving the task
- Downloaded the Tableau
- Install Tableau on my computer and register an account with the same email you i to download the software.
- Download the daikibo-telemetry-data.json.zip file -> unzip -> and import it in Tableau.
- Created a calculated measure field "Unhealthy" with the value of 10 for every unhealthy status (representing 10min of potential down time since the previous message).
- Created a bar-chart: Down Time per Factory.
- Created new sheet with a new bar-chart: Down Time per Device Type.
- Create a Dashboard with the 2 previous sheets and set the first chart to be used as a filter (selecting factory in the first chart, shows only the down time of the machines in this factory there in the second chart).
- Select the factory with the most down time (click on its bar), make a screenshot of the dashboard and upload it as a submission for this task.
  ![Screenshot (96)](https://github.com/user-attachments/assets/e8f9986c-5524-4a24-982c-80dbe7a3f7a3)

## Tsk 3: Write a proposal for creating a dashboard 
### Background Information on Task 3
Analyzing offline data is great, but having a real-time overview of processes and smart alerts when things break is even better. Our client would like us to build a real-time manufacturing status dashboard. The first task of this process is drafting a development proposal.
