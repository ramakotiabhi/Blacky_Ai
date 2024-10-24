[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Community](https://img.shields.io/badge/Join-Community-blue)](https://developer.ibm.com/callforcode/solutions/projects/get-started/)

_INSTRUCTIONS: This GitHub repository serves as a template and example you can use to create a well documented README for your project for the [2024 Call for Code Global Challenge](https://developer.ibm.com/callforcode/global-challenge/)._

Your required deliverables and project descriptions should be officially submitted to your My Team > Submissions section of the [Call for Code Global Challenge web site](https://compete.callforcode.skillsnetwork.site/competitions/2024-call-for-code-global-challenge), but you can also optionally include them here for completeness, as it is good practice to clearly document your project in your README file. Replace the examples seen here with your own deliverable links.

Use the **Use this template** button to create a new version of this repository and start entering content for your own Call for Code submission project. Make sure you have [registered for the 2024 Call for Code Global Challenge](https://www.ibm.com/account/reg/signup?formid=urx-52643) to access resources and full project submission instructions. Remove any "INSTRUCTIONS" sections when you are ready to submit your project.

_New to Git and GitHub? This free online course will get you up to speed quickly: [Getting Started with Git and GitHub](https://www.coursera.org/learn/getting-started-with-git-and-github)_.

# Effective Climate Change Policies and Protections

- [Project summary](#project-summary)
  - [The issue we are hoping to solve](#the-issue-we-are-hoping-to-solve)
  - [How our technology solution can help](#how-our-technology-solution-can-help)
  - [Our idea](#our-idea)
- [Technology implementation](#technology-implementation)
  - [IBM watsonx product(s) used](#ibm-ai-services-used)
  - [Other IBM technology used](#other-ibm-technology-used)
  - [Solution architecture](#solution-architecture)
- [Presentation materials](#presentation-materials)
  - [Solution demo video](#solution-demo-video)
  - [Project development roadmap](#project-development-roadmap)
- [Additional details](#additional-details)
  - [How to run the project](#how-to-run-the-project)
  - [Live demo](#live-demo)
- [About this template](#about-this-template)
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

_INSTRUCTIONS: Below are the suggested sections to include in your README file to make sure your project is well documented. You can remove this instruction text._

## Project summary

### The issue we are hoping to solve

Climate change poses a significant threat to communities worldwide, particularly vulnerable populations. There is an urgent need for scalable, data-driven solutions that help governments and organizations develop, implement, and monitor climate change policies effectively. However, access to reliable environmental data, community input, and transparency in policy enforcement are often lacking, hindering equitable climate action. Our solution aims to address these challenges by leveraging AI, IoT, and blockchain technologies to create an accessible platform for real-time climate policy management.

### How our technology solution can help

By utilizing AI for predictive analytics, machine learning to interpret environmental data, and IoT sensors for real-time data collection, we can provide actionable insights for creating effective climate policies. Our platform incorporates community input through surveys, ensuring that the needs of local populations are included in policy formulation. Blockchain technology ensures transparency and trust in the monitoring and enforcement of these policies, allowing governments, communities, and organizations to track progress and make necessary adjustments. This comprehensive approach enables a more equitable, inclusive, and data-driven response to climate challenges.

### Our idea
We propose developing an AI-powered platform that integrates the following features:

#### Real-time Environmental Data Monitoring:
IoT sensors deployed across regions will collect data on key environmental indicators such as carbon emissions, pollution levels, and weather patterns.
#### Data Analytics and Predictive Insights:
Using AI and machine learning models, the platform will analyze collected data and generate insights to help formulate and adjust climate change policies.
#### Community Input Integration: 
Surveys and feedback mechanisms will enable the platform to incorporate local community concerns and needs into policy development, ensuring the policies are equitable and inclusive.
#### Blockchain for Transparency:
Blockchain technology will be used to create an immutable ledger of policy actions, enforcement measures, and progress reports, fostering trust and accountability among all stakeholders.

## Technology implementation

#### AI and Data Analytics:
IBM Watson AI will be utilized for predictive analytics, analyzing large datasets on environmental changes to provide actionable insights for policymakers.
#### IoT:
IoT sensors will collect real-time data on various environmental metrics like air quality, temperature, and carbon emissions. These sensors will be deployed in different regions to ensure comprehensive data collection.
#### Blockchain: 
A blockchain-based ledger will ensure transparency and accountability in tracking climate action and monitoring policy effectiveness. This will prevent any manipulation of data and ensure that governments and organizations are held accountable for their commitments.
#### Community Feedback:
Surveys and data input forms will be integrated to gather insights from local communities on their climate concerns, which will be used in conjunction with environmental data to drive policy changes.

### IBM watsonx product(s) used

#### IBM Watson AI: 
For analyzing environmental data and providing recommendations.
#### IBM Watson Natural Language Understanding (NLU): 
For analyzing and categorizing community feedback to help tailor climate policies to the needs of the people.

**Featured watsonx products**

- [watsonx.ai](https://www.ibm.com/products/watsonx-ai) - WHERE AND HOW THIS IS USED IN OUR SOLUTION

- [watsonx.governance](https://www.ibm.com/products/watsonx-governance) - WHERE AND HOW THIS IS USED IN OUR SOLUTION

- [watsonx Assistant](https://cloud.ibm.com/catalog/services/watsonx-assistant) - WHERE AND HOW THIS IS USED IN OUR SOLUTION

### Other IBM technology used

Other IBM Technology Used
#### IBM Blockchain Platform: 
To ensure transparency and security in tracking climate policies and progress.
#### IBM Cloud: 
To host the platform, providing scalability, security, and reliability for global use.
#### IBM Watson IoT Platform:
For the integration and management of IoT devices that collect environmental data

**Additional IBM AI services (Remove any that you did not use)**

- [Watson Machine Learning](https://cloud.ibm.com/catalog/services/watson-machine-learning) - WHERE AND HOW THIS IS USED IN OUR SOLUTION

- [Watson Studio](https://cloud.ibm.com/catalog/services/watson-studio) - WHERE AND HOW THIS IS USED IN OUR SOLUTION

- [Natural Language Understanding](https://cloud.ibm.com/catalog/services/natural-language-understanding) - WHERE AND HOW THIS IS USED IN OUR SOLUTION


### Solution architecture

#### IoT Layer: 
Deployed sensors collect real-time data from the environment (e.g., air quality, carbon emissions).
#### Data Layer: 
Data from IoT devices is sent to the IBM Cloud for storage and processing.
#### AI Layer: 
IBM Watson AI processes the environmental data, using predictive models to generate insights and recommendations for policy adjustments.
#### Blockchain Layer: 
IBM Blockchain tracks the policy actions, making progress transparent and auditable for governments and stakeholders.
#### UI/UX Layer: 
A web interface allows users (policymakers, organizations, and communities) to view the data, submit feedback, and monitor policy effectiveness.

## Presentation materials



### Solution demo video

[![Watch the video](https://raw.githubusercontent.com/Liquid-Prep/Liquid-Prep/main/images/readme/IBM-interview-video-image.png)](https://youtu.be/vOgCOoy_Bx0)

### Project development roadmap

The project currently does the following things.

- Feature 1
- Feature 2
- Feature 3

In the future we plan to...

See below for our proposed schedule on next steps after Call for Code 2024 submission.

![Roadmap](./images/roadmap.jpg)

## Additional details

### Policy Simulator
Overview: The Policy Simulator is an essential tool integrated into our climate change platform, designed to help governments, organizations, and communities assess the impact of different climate policies before they are implemented. The simulator provides insights into emissions reduction, cost efficiency, and overall policy intensity, helping decision-makers optimize strategies for maximum effectiveness and minimal financial burden.

#### Budget (USD)
Users can simulate climate policies across a wide range of budgets, from as low as $100 to as high as $10,000,000. This range accommodates both small community projects and large-scale governmental initiatives.

#### Timeline Adjustments:
The simulator allows users to set timelines for their policies, ranging up to 24 months, to understand how long it takes for the policy to deliver measurable impact.

#### Policy Intensity:
Users can adjust the intensity of policies, from 1% to 100%, meaning they can simulate various degrees of policy enforcement—from minimal to full-scale actions. This helps users evaluate whether small policy changes will suffice or if larger, more aggressive actions are necessary.

#### Emissions Reduction:
The simulator predicts the emissions reduction achievable through a proposed policy. For example, the simulator might show a potential 14.6% reduction in emissions for a specific policy configuration. This helps users understand the direct environmental impact of their actions.

#### Cost Efficiency:
The Policy Simulator also calculates the cost efficiency of each policy in terms of the amount of money spent per ton of CO2 emissions reduced. For instance, a sample simulation may indicate a cost efficiency of $307,377/ton. This metric allows users to evaluate whether their policies provide value for money or whether alternative strategies might be more economically viable.

### How It Works:
#### Data Input:
Users enter the budget, timeline, and intended intensity of their climate policy.
Real-time environmental data from IoT sensors and community input is fed into the simulator to provide contextual accuracy.

#### AI and Machine Learning Integration:
IBM Watson AI uses historical data and predictive models to estimate the policy’s effect on emissions and the cost of implementation. The AI adapts to changes in environmental conditions and policy adjustments, offering real-time updates as the simulation progresses.

#### Blockchain Integration:
The simulator tracks all simulated actions using blockchain, ensuring transparency and providing an immutable record of policy scenarios for future reference or auditing.

#### Simulation Output:
After running the simulation, the tool provides the following insights:
Estimated Emissions Reduction: Shows how much CO2 reduction the policy will achieve.
Cost Efficiency: Highlights how much it will cost to achieve the desired reduction.
Effectiveness Over Time: Provides a time-bound analysis, indicating when the most significant environmental impact will occur within the 24-month window.
Policy Recommendations: AI suggests fine-tuning of the policy intensity, budget allocation, and timeline to improve both emissions reduction and cost efficiency

### Use Case Example:
A government agency wants to implement a policy to reduce urban carbon emissions by 10% over 18 months with a budget of $5,000,000. They input these parameters into the simulator:

Budget: $5,000,000
Timeline: 18 months
Policy Intensity: 75%
The simulator calculates that this policy could lead to a 12.3% reduction in emissions with a cost efficiency of $280,000/ton of CO2 reduced. The AI then recommends that reducing the policy intensity to 65% might still achieve the 10% emission reduction target while improving the cost efficiency to $250,000/ton.

### Advantages of the Policy Simulator

#### Data-Driven Decision Making:
The simulator allows policymakers to test various scenarios, providing quantitative backing for their decisions, ensuring that policies are not only effective but also economically sound.

#### Real-Time Adjustments:
Environmental conditions can change rapidly, and this tool allows policymakers to re-run simulations with real-time data inputs to keep policies adaptable.

#### Inclusivity:
By incorporating community feedback into the simulations, the tool ensures that policies are equitable and reflect the needs of all stakeholders, especially vulnerable populations.

#### Long-Term Impact:
By simulating the long-term impact of policies, users can see the effects of their choices over time, ensuring that short-term actions align with long-term sustainability goals.


### How to run the project

Clone the Repository: Run git clone [] to download the code.
Set Up IBM Cloud Services: Register for IBM Cloud, set up Watson AI, IoT, and Blockchain services, and obtain API keys.
Install Dependencies: Install necessary libraries and frameworks (e.g., Flask, Watson SDK, IoT SDK).
Run the Application: Execute python app.py to start the platform.
Access the Dashboard: Navigate to the web-based dashboard to monitor environmental data, AI recommendations, and policy tracking.

### Live demo

You can find a running system to test at...

See our [https://magenta-hamster-ee4af8.netlify.app/) for climate polices change.

## About this template

This project template serves as a guide for building scalable, AI-driven solutions to assist governments and organizations in creating and monitoring climate policies. It provides a comprehensive approach to integrating real-time environmental data, community input, and transparent reporting to ensure equitable climate action

### Contributing

We welcome contributions from the community. Please follow the standard open-source contribution process:

1. Fork the repository.
2. Make your changes.
3. Submit a pull request.

### Versioning
We use Semantic Versioning for this project. Current version: 1.0.0.

### License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Based on We would like to thank the IBM Call for Code challenge for providing an opportunity to build solutions for critical global issues. Special thanks to the IBM Watson team for their cutting-edge AI tools.[Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).
