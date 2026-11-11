# Salesforce-Project
The Customer Case Support with AI Enhancements (CCS+AI) project focused on developing an enterprise customer support management system for MicroDesk Solutions using Salesforce. 

The main objective was to improve how customer inquiries, complaints, and support requests are managed by automating repetitive processes, improving response times, and integrating AI-powered features.

The project began with the development of a data model connecting customers, support agents, customer cases, case activities, Service Level Agreements (SLAs), and AI insights. This structure allowed the organisation to store and manage customer information efficiently while maintaining relationships between different business objects.

Several business logic and workflow automations were implemented using Salesforce Flows. These included automatically assigning SLA policies based on customer tiers, case priorities, and categories, routing cases to the appropriate support queues, updating case statuses, monitoring SLA deadlines, and escalating cases requiring urgent attention. Validation rules were also introduced to ensure data accuracy and prevent incorrect case updates.

The project also incorporated AI capabilities through Salesforce Agentforce, including generating case insights, analysing customer sentiment, and producing automated case closure summaries. Additionally, a conversational AI service agent was developed to allow customers to retrieve existing case information or create new support requests through natural language interactions.

To improve customer accessibility, an Experience Cloud customer service portal was created, allowing users to interact with the AI agent and request assistance from a human support representative when necessary. An Apex REST web service was also developed to support external integration, enabling customer creation and case information retrieval through HTTP requests tested using Postman.

Overall, the project demonstrated how enterprise computing, workflow automation, AI integration, and API development can work together to create a more efficient and accessible customer support system. The solution aimed to reduce manual workloads, improve service consistency, support timely case resolution, and enhance the overall customer experience.
