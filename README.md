# 💬 Fitness Buddy AI Coach

An AI-powered personal coach and digital assistant designed to guide users through their health and wellness journey. Utilizing **IBM watsonx.ai Studio** and a Retrieval-Augmented Generation (RAG) system, this intelligent assistant delivers trusted advice on workouts, nutrition, motivation, and habits, all customized to the user's specific needs and fitness level.


![Fitness-Buddy](Fitness-Buddy-AI.png)


## 🎯 Problem Statement

* In today’s fast-paced world, many individuals struggle to maintain a healthy lifestyle due to lack of personalized guidance, time constraints, and inconsistent motivation. Traditional fitness solutions often require expensive subscriptions, in-person consultations, or rigid schedules that don't adapt to personal preferences or daily routines. There is a growing need for an accessible, friendly, and intelligent virtual assistant that can provide on-demand fitness advice, healthy lifestyle suggestions, and basic nutrition guidance—all tailored to individual needs and available at any time.

## 💡 Solution
* **Fitness Buddy aims to solve this problem by offering a conversational, AI-powered health and fitness coach that can:**
    * Recommend home workouts and routines based on user input.
    * Provide motivational tips and daily fitness inspiration.
    * Suggest simple, nutritious meal ideas.
    * Encourage habit-building and consistency.

## 💻 Technologies Used

* **Platform:** IBM watsonx.ai Studio 🎨

* **AI Model:** IBM Granite (`granite-3-3-8b-instruct`), a foundational LLM optimized for instruction-following. 🤖

* **Knowledge Source:** A single, well-structured `.docx` file ([`Fitness_Buddy_Knowledge_Base.docx`](Fitness_Buddy_Knowledge_Base.docx)) containing all the project's data. 📂

* **Data Retrieval:** A Vector Index for RAG. 🔍

* **Storage:** IBM Cloud Object Storage 📦

## ☁️ IBM Cloud Services Used

* **watsonx.ai Studio:** The core development and deployment environment.

* **IBM Granite Model:** The large language model powering the agent's intelligence.

* **Watsonx Vector Index:** The service used to create and host the RAG knowledge base.

* **IBM Cloud Lite Account:** All services for this project were provisioned and utilized within the free tier. 🆓

* **IBM Cloud Object Storage:** Used for project asset storage and the knowledge base.

## ⭐ WOW Factors

* **RAG-Powered:** Fetches answers directly from a custom `.docx` file to ensure accuracy. 🎯

* **Built on IBM Cloud:** Entirely configured and deployed using powerful IBM watsonx tools. ☁️

* **Polite Redirection:** Handles unrelated questions gracefully, redirecting the user back to the project's focus. 🤗

* **Holistic Wellness:** The knowledge base covers a wide range of topics: workouts, nutrition, motivation, and habits. 🧘‍♀️

* **Level-Specific Advice:** The agent provides guidance tailored for Beginner, Intermediate, and Expert users. 📈

## 👥 End Users

* **Beginners:** Individuals taking their first steps into fitness. 🌱

* **Enthusiasts:** Users seeking to optimize their routine and break through plateaus. 💪

* **Everyone:** Anyone needing a digital partner for daily motivation and wellness tips. 🤗

* **Final Presentation:** The project is ready to be showcased. 🌟

## ✅ Key Features

* **Custom Q&A:** Answers specific user queries based on the vectorized knowledge base. 💬

* **LLM-Powered:** Uses an IBM Granite model for natural conversation. 🗣️

* **Built-in NLP Support:** Understands and processes natural language queries effectively.

* **Structured Advice:** Formats responses with lists, headings, and clear sections for readability. 📖

* **Adaptive Guidance:** Provides different levels of advice (Beginner, Intermediate, Expert) when requested. 📊

* **Responds Gracefully:** Provides helpful and polite answers, even for off-topic questions.

## ⚙️ How It Works

* A user submits a query to the agent (e.g., “What's a beginner workout?”). ✍️

* The IBM Granite model processes the user's request. 🤔

* The RAG system instantly searches the `Fitness_Buddy_Knowledge_Base.docx` for the most relevant information. 🔍

* If the answer is not found in the document, the agent uses its web search tool to find an accurate response. 🌐

* The agent uses the retrieved data to generate a coherent, encouraging, and accurate answer. ✅

## 📸 Screenshots

### 🔹 Setting up..
![Setup & preview image](Setup.png)
### 🔹 Quick Start Questions...
![Quick Start Questions](Quick-Start-Questions.png)
### 🔹 Agent Instructions...
![Agent Instructions](Agent-Instruction.png)
### 🔹 Common Instructions...
![Common Instructions](Common-Instruction.png)
### 🔹 Knowledge (Vector Index)...
![Knowlege](Vector-Index.png)
### 🔹 Tools Used & Testing...
![Tool Used & Testing](Tools-and-Testing.png)
### 🔹 Deployment...
![Deployment](Deployed.png)
### 🔹 API References after Deployment...
![API References](API-Reference.png)
### 🔹 Preview...
![Preview](Preview.png)
### 🔹 Resource List...
![Resource List](Resource-List.png)

## 🏃‍♀️ How to Run or Deploy

* Log in to IBM Cloud Lite Account: [`https://cloud.ibm.com`](https://cloud.ibm.com)
* Launch Watsonx.ai Studio
* Create a new AI Agent
* Upload your knowledge base document (`Fitness_Buddy_Knowledge_Base.docx`) to a Vector Index
* Configure agent instructions
* Test in the preview panel
* Deploy

## 🛣️ Future Scope

* **Voice Interface:** Integrate speech-to-text for hands-free use. 🗣️

* **API Integration:** Connect to third-party tools for tracking progress or calories. 📊

* **Multilingual Support:** Expand the knowledge base to support multiple languages. 🌍

## 🎉 Conclusion

The Fitness Buddy AI Coach is a successful project that demonstrates the power of the IBM watsonx.ai platform. It provides a functional, reliable, and personalized tool for promoting a healthier lifestyle, ready for a final project presentation. 🌟

## 🔗 Useful Links

* [IBM Cloud Lite](https://cloud.ibm.com)

* [IBM Watsonx.ai](https://www.ibm.com/watsonx)

* [IBM SkillsBuild](https://www.google.com/search?q=https://www.ibm.com/skills/skillsbuild)

## 📜 License

* This project is licensed under the [MIT License](LICENSE).

## 🤝 Connect

🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/rishikhandekar/)

---

> Created with ❤️ by **Rishi Khandekar** during the Edunet Foundation AICTE IBM SkillsBuild Internship 2025.
