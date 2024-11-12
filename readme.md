# Pat.io

## Synopsis

Pat.io is an AI chatbot fine-tuned to provide migrants with easy access to essential information about Social Security Numbers (SSN), Individual Taxpayer Identification Numbers (ITIN), and New York City’s Local Law 30. Pat.io offers a user-friendly experience to assist migrants in navigating the often complex processes involved in obtaining these identification numbers. Equipped with multi-language functionality, Pat.io can communicate in multiple languages, both in text and voice, making information accessible to a broader audience. By leveraging reliable resources, government data, and a customized AI language model, Pat.io ensures that users receive accurate, up-to-date answers to common questions about eligibility, documentation, and application procedures.

## Links

- **Live Link**: https://pat-io.netlify.app/
- **Frontend Repo**: https://github.com/evrajireddy/pat.io-frontend
- **Backend Repo**: https://github.com/BryanA0418/pat-io
- **Backend Server**: https://pat-io.onrender.com/

## Technology Utilized

- **PostgreSQL**: Database for storing and managing data on identification resources
- **Express**: Backend framework to handle API requests and manage data processing
- **React**: Frontend framework for building an intuitive and responsive user interface
- **Node.js**: Server environment for executing JavaScript on the backend
- **OpenAI Model 4.0 Mini**: Provides customized language model responses tailored to migrant needs
- **Google Cloud Text-to-Speech API**: Enables text-to-speech functionality for multilingual audio output
- **Google Cloud Translate API**: Facilitates translation services for multiple languages
- **Google Cloud Speech-to-Text API**: Allows users to input queries through speech, converted to text for processing
- **Tailwind CSS**: CSS framework for building a responsive and visually appealing interface
- **i18next**: Localization framework for translating and managing multilingual content
- **Zippopotam API**: Provides geolocation data for enhanced location-based services
- **Web Speech API**: Facilitates in-browser speech recognition for voice-based interactions

## Features

- 🧑‍⚖️ **Legal Compliance**: Provides information aligned with U.S. government guidelines to ensure accuracy
- 🔍 **Eligibility Checker**: Helps users understand if they meet criteria for SSN or ITIN
- 📑 **Documentation Guidance**: Offers a list of required documents and instructions for both SSN and ITIN applications
- 🌐 **Multi-Language Access**: Equipped with language functionality that allows Pat.io to communicate in multiple languages, both in text and voice, to assist non-English speakers, in line with Local Law 30 requirements for NYC
- 🤖 **AI Chatbot Assistance**: Delivers personalized responses in real-time to answer common questions about identification processes
- 📍 **Location-Based Services**: Uses geolocation to provide relevant local resources and services

## Technical Details

Pat.io leverages an extensive technology stack to create a comprehensive and supportive user experience for migrants:

1. **Eligibility and Documentation Checker**:
   - Provides dynamic responses based on user input regarding eligibility and required documentation.
   - Uses backend processing with Express to validate input and retrieve relevant guidelines.

2. **Multi-Language Functionality**:
   - Utilizes Google Cloud Translate API and i18next to support text translation and localization.
   - Employs Google Cloud Text-to-Speech and Speech-to-Text APIs, along with the Web Speech API, to enable both text and voice interactions in multiple languages.

3. **Data Processing**:
   - Integrates government resources organized into an accessible, easily understandable format within a PostgreSQL database.
   - Ensures quick access to information and efficient data retrieval, optimized with React and Express.

4. **User-Friendly Interface**:
   - Designed with Tailwind CSS for a responsive, visually appealing interface.
   - Features an intuitive layout with accessibility options, including language selection for enhanced usability.

5. **AI Language Model**:
   - Leverages OpenAI Model 4.0 Mini for accurate, relevant responses based on migration-specific queries.
   - Provides language diversity, allowing users to interact with Pat.io in their preferred language, making information more accessible.

## Fine-Tuning Process

The fine-tuning process for Pat.io involved customizing OpenAI’s Model 4.0 Mini to meet the specific informational needs of migrants regarding SSN, ITIN, and NYC Local Law 30. Here’s an overview of how the model was trained and refined:

1. **Data Collection**:
   - We gathered a large dataset focused on frequently asked questions and information about SSN, ITIN, and Local Law 30 requirements, sourced from government publications, trusted migrant resources, and commonly searched queries.
   
2. **Dataset Preparation**:
   - The collected data was carefully processed to include questions and answers formatted to reflect natural conversational language. Each entry was structured to allow the model to respond to both simple queries and more complex, contextual questions.

3. **Model Training**:
   - Using OpenAI’s fine-tuning API, the model was trained on this custom dataset, ensuring it could accurately interpret and answer user queries within the scope of SSN, ITIN, and Local Law 30 topics.
   - Special emphasis was placed on handling nuanced questions, eligibility criteria, and procedural details, enabling the model to provide detailed, user-friendly guidance.

4. **Testing and Evaluation**:
   - The model’s responses were tested extensively in simulated conversations to evaluate accuracy, relevance, and tone. Adjustments were made to improve clarity, friendliness, and precision.
   - User feedback was incorporated to refine answers and ensure that responses were not only correct but also easy to understand and culturally sensitive.

5. **Language Adaptation**:
   - Additional fine-tuning was conducted to ensure smooth integration with Google Cloud’s translation APIs and i18next, enabling seamless multilingual interactions.
   - Pat.io’s model is continuously monitored and updated with new data to maintain accuracy and reflect changes in policies or application procedures.

## Usage

Pat.io is designed to offer a natural, conversational experience, allowing you to interact with the chatbot as you would with a knowledgeable assistant. Whether you're checking eligibility, looking for specific documentation, or need answers in a different language, Pat.io is here to help you navigate these essential identification processes with ease.

1. Open Pat.io in your web browser and start a conversation with the chatbot interface.
2. **Ask Questions**: Inquire directly about Social Security Numbers (SSN), Individual Taxpayer Identification Numbers (ITIN), or New York City’s Local Law 30.
3. **Eligibility Checker**: Ask, “Am I eligible for an SSN?” or similar questions for personalized guidance on eligibility.
4. **Documentation Guidance**: Request specific information by asking, “What documents do I need for an SSN?” The chatbot will provide a detailed list and step-by-step instructions.
5. **Multi-Language Support**: Select a language option or speak to Pat.io; it can respond in both text and voice, making the experience accessible for non-English speakers.
6. **Location Services**: Enable location services to receive location-specific recommendations, such as nearby SSN support centers or relevant local resources.
7. **General Inquiries**: For additional help, type or speak your question to Pat.io, and it will respond with clear, reliable information tailored to your needs.

## Team Members

- [Abraham Zambrano Tablante - UX/UI Designer](https://www.linkedin.com/in/Abrahamzambranotablante/)
- [Bryan Alcantara - Backend Developer](https://www.linkedin.com/in/bryan-alcantara-643479281/)
- [Runquan (Ray) Zhou - Full Stack Developer](https://www.linkedin.com/in/runquanrayzhou/)
- [Steven Rouse - UX/UI Designer](https://www.linkedin.com/in/StevenRouse/)
- [Venkata Raji Reddy Eda - Frontend Developer](https://www.linkedin.com/in/evrajireddy/)
