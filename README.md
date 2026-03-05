

Gitika Makheja
24070521024

Harman Saini
24070521024

February Development Tasks (Task 6 – Task 10)
Google colab link : https://colab.research.google.com/drive/1JkpGL2UOyBdiIpANFrJaC4pbsZllly8D?usp=sharing

Task 6: Entity Extraction for Dates and Courses
Description
In this task, the chatbot was improved to recognize important information from student queries. This process is known as entity extraction, where the chatbot identifies key elements such as semester numbers, course codes, and exam-related keywords from a question.
Students usually ask questions such as “When is SEM 5 CS exam?” or “When is AIML exam?”. The chatbot must be able to identify that the question contains information about a specific course and semester. By extracting these entities, the chatbot can understand the user’s request more accurately and provide an appropriate response.
Objective
The objective of this task is to enable the chatbot to automatically detect course names, semester numbers, and exam-related information from student queries.
Output
After implementing entity extraction, the chatbot can successfully identify important keywords in a query and use them to generate relevant responses about exam schedules or course-related information.
________________________________________
Task 7: Context Handling for Follow-Up Queries
Description
In real conversations, users often ask follow-up questions without repeating the complete information. Therefore, the chatbot must be able to remember previous parts of the conversation and use them to understand the next question. This concept is called context handling.
For example, a student might first ask about a course exam and later mention the semester in a separate message. The chatbot should remember the previously mentioned course and combine it with the new information to provide a meaningful response.
Context handling helps the chatbot maintain a conversation state, making the interaction more natural and similar to human communication.
Objective
The objective of this task is to allow the chatbot to maintain conversation memory so that it can understand and respond to follow-up queries effectively.
Output
After implementing context handling, the chatbot is able to remember previously mentioned details such as course names and respond correctly when the user provides additional information later in the conversation.
________________________________________
Task 8: Fallbacks and Human Handover
Description
There are situations where the chatbot may not understand the user’s question because it is outside the scope of the chatbot’s knowledge. In such cases, the chatbot must provide a fallback response instead of giving incorrect or misleading information.
Fallback responses are polite messages that inform the user that the chatbot could not understand the query. The chatbot may also suggest contacting a human advisor, academic office, or support service for further assistance.
This ensures that the chatbot maintains reliability and avoids providing wrong answers.
Objective
The objective of this task is to design a mechanism that allows the chatbot to handle unknown or unclear queries safely by providing fallback responses and suggesting human assistance when necessary.
Output
The chatbot responds appropriately to unsupported questions and provides a clear message indicating that the query could not be understood, along with suggestions for further assistance.
________________________________________
Task 9: Multichannel Deployment Mockup
Description
Modern chatbots are often deployed across multiple platforms such as websites, mobile applications, and messaging services. In this task, the chatbot was designed to simulate how it would behave on different communication channels.
Instead of creating a full graphical interface, the chatbot responses were displayed in different formats to represent platforms such as web chat, mobile chat, and messaging platforms like WhatsApp.
This task demonstrates that the chatbot’s core logic can work across different platforms with minimal modifications.
Objective
The objective of this task is to simulate the chatbot’s deployment across multiple communication platforms and demonstrate how the same system can be used in different environments.
Output
The chatbot successfully simulates interactions across multiple platforms, showing how it can function on web interfaces, mobile applications, and messaging services.
________________________________________
Task 10: Analytics and Continuous Improvement
Description
In this task, the chatbot system records and analyzes user interactions in order to improve its performance. All conversations between users and the chatbot are logged so that common queries and patterns can be studied.
A small sample of these queries is categorized into different types such as exam queries, course queries, or unknown queries. By analyzing these interactions, developers can identify questions that the chatbot cannot answer and update the system accordingly.
This process helps in continuously improving the chatbot by adding new responses, refining patterns, and expanding its knowledge base.
Objective
The objective of this task is to enable continuous improvement of the chatbot system by analyzing conversation logs and identifying areas where the chatbot can be enhanced.
Output
The chatbot records interaction data, identifies common types of queries, and highlights unsupported questions. Based on this analysis, improvements such as new responses or additional features can be proposed.
________________________________________
Conclusion
The February development phase focused on improving the chatbot’s intelligence, conversational ability, and adaptability. Entity extraction allowed the chatbot to recognize important information from user queries, while context handling enabled it to manage multi-turn conversations more effectively. The fallback mechanism ensured that the chatbot responds safely to unknown queries without providing incorrect information.
The multichannel deployment simulation demonstrated that the chatbot system can operate across different platforms such as web, mobile applications, and messaging services. Finally, the analytics and continuous improvement module allowed developers to analyze chatbot interactions and identify opportunities for future enhancements.
Overall, these tasks helped in building a chatbot system that is more accurate, reliable, and capable of handling real-world student queries in a university environment.
