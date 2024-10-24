# EcoEngage

- [Project summary](#project-summary)
  - [The issue we are hoping to solve](#the-issue-we-are-hoping-to-solve)
  - [How our technology solution can help](#how-our-technology-solution-can-help)
  - [Our idea](#our-idea)
- [Technology implementation](#technology-implementation)
  - [IBM watsonx product(s) used](#ibm-ai-services-used)
  - [Solution architecture](#solution-architecture)
- [Presentation materials](#presentation-materials)
  - [Project development roadmap](#project-development-roadmap)
- [Additional details](#additional-details)
  - [How to run the project](#how-to-run-the-project)
- [About this template](#about-this-template)
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)



## Project summary

### The issue we are hoping to solve

EcoEngage addresses the awareness deficit for sustainable practice waste reduction. It is one area many find hard to translate actual steps into everyday usage. The chatbot utilizes practical sustainability tips that guide users in doing what is best by having the right choice when ensuring a positive environmental impact

### How our technology solution can help

Our solution provides sustainability tips to promote eco-friendly daily habits.

### Our idea

In today’s world, environmental degradation is accelerating due to factors such as overconsumption, improper waste management, and unsustainable practices. While there is growing awareness about climate change, many individuals struggle to translate their concerns into meaningful actions that can help reduce their environmental footprint. This gap exists primarily due to a lack of clear, accessible guidance on how to make sustainable choices in everyday life. Furthermore, existing solutions are often either too complex for the average user or too broad to provide actionable advice. This is where Eco Engage comes in.

EcoEngage is a chatbot designed to provide practical and easy-to-implement sustainability tips to users. The chatbot focuses on helping people adopt eco-friendly habits by offering guidance on waste reduction, responsible disposal practices, and simple changes to make their lives more sustainable. Our goal is to make sustainability accessible to everyone, regardless of their technical or environmental knowledge.

**Real-world Problem** : The real-world problem we identified is twofold: (1) people often don’t know where to begin when trying to reduce their environmental impact, and (2) existing solutions tend to either overwhelm users with too much information or offer generic advice that isn’t helpful in practice. This creates a barrier for individuals who want to live more sustainably but don’t have the time or knowledge to research and implement the necessary changes.

**Technological solution**:Our technological solution is a user-friendly chatbot built using AI . The chatbot interacts with users through a simple conversational interface, providing them with personalized, step-by-step guidance on how to reduce their waste and live more sustainably. For example, users can ask the chatbot for tips on reducing plastic use, conserving water, or recycling more effectively. The chatbot responds with practical advice that can be easily applied in daily life.

Key features include:
1. **Sustainability Tips:** The chatbot delivers actionable advice on topics such as reducing single-use plastic, composting at home, minimizing food waste, and energy conservation.
2. **Waste Disposal Guidance:** Users can learn how to properly dispose of various types of waste, from electronics to household items, helping reduce the negative impact of improper disposal on the environment.
3. **Simple and Accessible Interface:** Designed for ease of use, the chatbot is accessible to anyone, regardless of technical proficiency. It uses simple language and clear instructions to make sustainability approachable for all.
4. **Real-time Suggestions:** Although the chatbot doesn’t provide localized guidance, it still offers relevant tips that users can implement wherever they are, empowering them to make a difference in their communities and beyond.

EcoEngage improves on existing solutions by focusing on practicality and accessibility. Unlike many environmental platforms that overwhelm users with complex data or large-scale solutions, our chatbot breaks down sustainability into simple, achievable steps that fit seamlessly into everyday life. It eliminates the need for users to sift through vast amounts of information and provides quick, personalized responses to their questions.

Additionally, the chatbot’s conversational interface makes the experience engaging and interactive, which encourages users to keep coming back for more tips and information. By building habits through repeated engagement, EcoEngage fosters long-term behavioral change that contributes to a healthier planet.

In summary, EcoEngage addresses the pressing need for actionable sustainability advice by delivering personalized, easy-to-follow tips. Through this chatbot, we hope to make sustainability an achievable goal for all individuals, leading to a broader, collective effort in reducing environmental harm.


## Technology implementation

### IBM watsonx product(s) used

**Featured watsonx products**

- [watsonx.ai](https://www.ibm.com/products/watsonx-ai) - We utilized watsonx.ai to enhance the chatbot's understanding capabilities. This allows the chatbot to interpret user queries and provide relevant sustainability tips based on the context of the conversation. By leveraging the AI's machine learning algorithms, the chatbot can improve its responses over time, ensuring users receive increasingly accurate and helpful information.


- [watsonx Assistant](https://cloud.ibm.com/catalog/services/watsonx-assistant) - The watsonx Assistant product was integral in creating the conversational interface of EcoEngage. It enables the chatbot to engage users in a natural dialogue, making the experience intuitive and user-friendly. We implemented various intents and entities to allow the chatbot to understand different user requests related to sustainability topics, ensuring it can deliver tailored advice efficiently.

### Solution architecture

![EcoEngage architechture](https://github.com/sai-varshaa/EcoEngage/blob/main/images/EcoEngage%20architechture%20diagram.jpg)

Step-by-step description of the flow of our solution:

1.User Interaction:
Users interact with EcoEngage via a web-based interface or chatbot on any device to ask questions about sustainability.

2.Request Processing:
The user’s query is processed by the front-end application and forwarded to the back-end services.

3.Watsonx Assistant:
IBM Watsonx Assistant interprets the user’s natural language queries and matches them with relevant intents.

4.AI-Driven Data Analysis (Watsonx.ai):
Watsonx.ai analyzes user behavior and query patterns to generate personalized sustainability tips.

5.Knowledge Database:
The system queries a centralized knowledge database for accurate and up-to-date information on sustainability practices.

6.Feedback Loop:
User interactions are logged and analyzed to refine responses and adapt to user preferences.

7.Response to User:
Watsonx Assistant sends back actionable eco-friendly practices, which are displayed on the user’s device.

8.Optional Integration with APIs:
Future versions may include APIs for real-time data on environmental initiatives in the user’s locality.


### Project development roadmap

The project currently includes the following features:

**Sustainability Tips**: Provides users with practical advice on waste reduction, energy conservation, and other eco-friendly practices.
Waste Disposal Guidance: Offers recommendations on how to properly dispose of various types of waste to minimize environmental harm.
User-Friendly Interface: Delivers an interactive chatbot experience that makes sustainability tips easily accessible through simple conversations.
In the future, we plan to:

**Expand Content**: Add more detailed and diverse sustainability tips, covering topics such as water conservation, green energy options, and eco-friendly shopping.
User Feedback Mechanism: Implement a feature where users can provide feedback on the tips received, allowing the system to improve and adapt over time.
Interactive Quizzes: Introduce quizzes that test users' knowledge of sustainability topics, providing an engaging way to learn and take action.
Integration with External Data Sources: Explore integrating real-time environmental data to offer more dynamic and personalized suggestions.

Proposed Schedule for Future Development After Call for Code 2024 Submission:

1. Expand sustainability content library and implement user feedback mechanisms.
2. Develop interactive quizzes and integrate external data sources.
3. Launch upgraded version with enhanced features and wider content coverage.


![EcoEngage roadmap](https://github.com/sai-varshaa/EcoEngage/blob/main/images/EcoEngage%20roadmap.jpg)

### How to run the project

To run EcoEngage locally for development and testing or deploy it in a production environment, follow the steps outlined below.

1.Local Development Setup:

    1.1 Clone the project repository
    
    1.2 Install the required dependencies
    
    1.3 Configure the environment variables:
  
        WATSONX_API_KEY= t7AnA7sx-yJxPnpqo84lmMW5wTPgbiE_eO0gvlSpliUO
        WATSONX_ASSISTANT_ID= 41e13166-2818-450e-a490-d9a1bb0aed31
        WATSONX_URL= https://api.au-syd.assistant.watson.cloud.ibm.com/instances/1f43a176-85b0-4991-8642-6ecb14ed4f17
        
    1.4 Start and access the application 

2. Deployment in Production:

   2.1 Use IBM Cloud:
       Confirm that the watsonx Assistant and watsonx.ai services have been successfully deployed on IBM Cloud.
       Generate production-level API keys, updating environment variables to reflect the configuration for the production setup.

    2.2 Deploy the Application:
        Publish the application on a cloud provider such as Heroku, Netlify, or any other. 
        Ensure that you define variables for your production environment and activate all required security measures and scaling options appropriate for production environments.

    2.3 Monitor and Maintain:
        After the implementation, monitoring tools must be set up to track performance, manage logs, and ensure continuous availability. Periodic updates as well as feedback loops need to happen          to maintain the quality of service.

## About this template

### Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

### Authors

<a href="https://github.com/Call-for-Code/Project-Sample/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=Call-for-Code/Project-Sample" />
</a>

- **Billie Thompson** - _Initial work_ - [PurpleBooth](https://github.com/PurpleBooth)

### License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).
