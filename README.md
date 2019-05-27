# Securing the IoT end-to-end
Fabrikam, Inc. creates innovated IoT solutions for the oil and gas manufacturing industry. It is beginning work on a new, predictive maintenance solution that targets rod pumps (the iconic pivoting pumps that dot oil fields around the world). With their solution in place, companies will be able to monitor and configure pump settings and operations remotely, and only send personnel onsite when necessary for repair or maintenance when the solution indicates that something has gone wrong. However, Fabrikam wants to go beyond reactive alerting- they want to want to enable the solution with the ability to *predict* problems so they can be averted before a fault occurs and damage is done.

Using Machine Learning gives Fabrikam's solution the ability to analyze readings from various elements of the rod pump mechanism and sense patterns that indicate a possible impending mechanical failure or a deviation from the pump’s optimal operating conditions. In that case, the controller can modify the operating parameters of the pump to avoid or mitigate the impact of the unexpected changes. Or, if necessary, it can shut down the pump before any damage occurs and notify the company that repairs are necessary—protecting the machinery, and preventing potential environmental damage.

Their goal in the use of such predictive models is to increase operator efficiency and safety. Addressing a typical maintenance issue takes several people and at least three days of system downtime at a cost of up to $20,000 USD a day, not including parts and labor. "By proactively identifying pump problems through predictive analytics, companies reduce unplanned downtime, which decreases costs, increases production, and increases the agility of maintenance services." says Fabrikam's Chief Engineer. He adds that the majority of industry accidents don’t happen at the well site, they happen when personnel are driving between sites. By eliminating the need for many site visits, they can reduce those accidents.

In designing their machine learning solution, Fabrikam is interested to learn how automated machine learning might help them reduce the time it takes them to create new models.

They would like to start by building a proof of concept that performs the predictive analytics in the cloud. While their machine learning will initially happen in the cloud, they would like to design their solution with an eye towards the future so it could be enhanced to run the models at the edge. 

## Target audience
-	Cloud Solution Architect
-   Data Scientist
-   Data Engineer


## Abstract

### Workshop
In this workshop, you will look at the process for designing and implementing a predictive maintenance solution for oil and gas manufacturing.

### Whiteboard design session
In this workshop, you will look at designing a predictive maintenance solution for oil and gas manufacturing.

#### Outline: Key Concerns for Customer situation ####
- Is there an out of the box SaaS solution we can use to jumpstart the creation of our solution (e.g., we need web based access to metadata management, configurable dashboards, collection and export of real-time telemetry, and security).
- Can this SaaS solution enable our data scientists to leverage their expertise to build custom models against timeseries telemetry, and to plug their models in to the near-real time streams collected by the SaaS solution? 
- How would data engineers get at rod pump streaming telemetry? 
- How can data engineers collect historical streaming telemetry for use in modeling by the data scientists?
- What service would the data scientists use for for training their model that could support the potentially large scale?
- How could data scientists plug their model into a real-time predictive analytics pipeline to detect potential failures?
- How can the data scientists leverage automated machine learning to expedite their modeling? What services would they use? Would they be constrained to any particular algorithms? Would it work for both machine learning and deep neural networks? How would they be able to scale the automated machine learning process?
- How would alerts be generated and delivered when the model predicts a failure?
- How can the operators view the current status of the rod pumps in a single dashboard?


### Hands-on lab 
In this hands-on lab, you will look at implementing a predictive maintenance solution for oil and gas manufacturing.

#### Outline: Hands-on lab exercises
- Exercise 0: Before the hands-on lab
- Exercise 1: Configuring IoT Central
- Exercise 2: Running the rod pump simulator
- Exercise 3: Monitoring and analytics using IoT Central
- Exercise 4: Enabling Continuous Export from IoT Central
- Exercise 5: Exploring the exported data using Azure Databricks
- Exercise 6: Creating a first anomaly detection model in Azure Databricks
- Exercise 7: Expediting hyper-parameter tuning with automated machine learning
- Exercise 8: Integrating the predictive maintenance model into the solution

## Azure services and related products
-	Azure Databricks
-   Azure Event Hubs
-	Azure IoT Central
-	Azure IoT Hub
-	Azure Machine Learning

## Related references
- [MCW](https://github.com/Microsoft/MCW)
- For the lab: Predictive maintenance solution for manufacturing, see https://azure.github.io/LearnAI_Azure_ML/
- 
