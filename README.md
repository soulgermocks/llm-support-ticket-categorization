# LLM Support Ticket Categorization

## Project Overview
In this project, I developed a Generative AI application using Large Language Model (LLM) to automate the classification and processing of support tickets. The application predicts ticket categories, assigns priority, estimates resolution times, and stores results in a structured DataFrame.

### Key Components:
- **Ticket Categorization**
- **Creating Tags**
- **Assigning Priority and ETA**
- **Generating Draft Responses**

### Model & Tools
- Model: `mistral-7b-instruct` (via llama-cpp)
- Dataset: Simulated Support Tickets
- Output: A structured DataFrame containing predictions, priorities, and draft responses.

### Business Context
This project addresses a common business need for automating customer support ticket handling. By using LLMs, the project imporves efficiency and response time, allowing organizations to enhance customer experinces.

### Steps:
1. **Data Loading and Overview**: Initial exploration and loading of the dataset.
2. **Model Building**: Loading a pre-trained model from Hugging Face and creating a response function.
3. **Ticket Categorization and Tagging**: Automatically assigning categories and tags based on ticket content.
4. **Priority & ETA Assignment**: Predicting ticket priority and suggesting estimated resolution times.
5. **Draft Response Generation**: Generating automatic responses for the customer support team.
