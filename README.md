# Interactive Chatbot with Amazon Lex
## 🎓 Coursera: Johns Hopkins University | Chatbots Specialization

[![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)

### 📝 Project Overview
Developed an **interactive floral-ordering chatbot** designed for real-world scalability on **AWS**. By combining **Amazon Lex's** dialogue management with **Python-based Lambda functions** and **BERT** for advanced text processing, I created a functional automation tool that reduces manual overhead and improves user engagement.

---

### 🛠 Technologies Used
* **Conversational AI:** Amazon Lex (V2)
* **Compute:** AWS Lambda (Serverless Backend)
* **Programming:** Python (Logic), R (Data Analysis)
* **Machine Learning:** TensorFlow, BERT (Bidirectional Encoder Representations from Transformers)
* **Environment:** AWS Management Console & CloudWatch

---

### 💡 Key Design Principles
To ensure a robust and user-centric experience, the following principles were implemented:

1.  **Understand User Intent**
    * Designed the chatbot to accurately interpret user queries and intents.
    * Leveraged **NLP** to improve understanding of varied phrasing and slang.

2.  **Provide Relevant Responses**
    * Ensured the chatbot delivers accurate and contextually appropriate answers.
    * Integrated a **knowledge base** to support dynamic response generation.

3.  **User-Friendly Interaction**
    * Focused on conversation flows that are easy to follow and engaging.
    * Utilized simple language to enhance accessibility for all user types.

4.  **Error Recovery & Graceful Degradation**
    * Implemented strategies for handling misunderstandings without breaking the session.
    * Designed **clarifying questions** and alternative options for when intent confidence is low.

5.  **Feedback and Continuous Learning**
    * Incorporated mechanisms for users to rate or provide feedback on responses.
    * Used feedback loops to refine the **BERT classifier** and Lex intent triggers.

6.  **Performance Metrics (KPIs)**
    * Tracked critical indicators: **Response Time**, **User Satisfaction**, and **Resolution Rates**.
    * Analyzed metrics via CloudWatch to identify bottlenecks in the conversational flow.

7.  **Testing and Iteration**
    * Conducted **UAT (User Acceptance Testing)** to gather real-world interaction insights.
    * Iterated on the logic based on edge cases found during the testing phase.

---

### 🚀 Implementation Highlights


* **Custom Slot Validation:** Real-time checking of flower availability (Roses, Lilies, Tulips) and business-hour verification for pickup timing.
* **Advanced Classification:** Integrating BERT logic to categorize complex text inputs that standard keyword matching might miss.
* **Fulfillment Logic:** Used **AWS Lambda** to process orders and return personalized confirmation messages to the user.

---

### 📁 Repository Structure
* `/src`: Contains the `lambda_function.py` used for order validation and fulfillment.
* `/models`: Contains scripts/notebooks for the BERT text classifier.
* `/docs`: Exported Amazon Lex JSON bot definition.

---
*Reference : Created as part of the Chatbots Specialization by Johns Hopkins University.
[1]“Chatbots,” Coursera, 2018. https://www.coursera.org/learn/chatbots (accessed Feb. 22, 2026).
‌*
