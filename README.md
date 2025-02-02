# Cold Email Generator - AI-Powered Tool for Personalized Cold Emails Using Generative AI and LLMs

🚀 **Cold Email Generator** is a cutting-edge tool designed to help businesses automatically generate personalized cold emails for job opportunities using **Generative AI** and **Large Language Models (LLMs)** like **Llama 3.3**. This platform scrapes job listings from websites, extracts job details, and creates tailored emails, offering a streamlined, automated process for business development teams.

## The Problem:
A **Business Development Team** at a tech consulting company is tasked with reaching out to potential clients who have job openings that align with their company's expertise. However, manually writing personalized cold emails for each job opportunity is time-consuming and inefficient.

## The Solution: Cold Email Generator

The **Cold Email Generator** uses **Generative AI** and **Large Language Models (LLMs)** to automate the process of crafting personalized cold emails for job postings. Here’s how it helps:

1. **Automatic Job Listing Scraping**:
   - The team can input a job listing URL from a company’s career page into the app.
   - The tool automatically scrapes the job description, extracting key details such as the role, required skills, experience, and job responsibilities.

2. **Relevant Portfolio Matching**:
   - The tool queries the company's portfolio to find relevant past projects and links that match the skills and requirements outlined in the job listing.
   - This ensures that the email highlights the most pertinent case studies, showcasing the company’s expertise in a targeted manner.

3. **Personalized Email Generation**:
   - Using the extracted data and portfolio links, the **AI-powered Cold Email Generator** crafts a personalized email tailored to the potential client’s needs.
   - The email emphasizes how the company's services can help with their specific requirements and includes links to relevant portfolio items.

4. **Efficient Outreach**:
   - With the cold email generated instantly, the Business Development Team can focus on reviewing and sending the emails rather than writing each one manually.
   - The process is significantly faster, allowing them to send more outreach emails in less time.

## ✨ Key Features

### 🧑‍💻 **AI-Driven Job Extraction**
- Automatically scrapes job listings from websites using Langchain's web scraping tools.
- Extracts essential job details such as role, skills, experience, and job description with precision.

### 📧 **Cold Email Generation**
- Uses the **Llama 3.3** language model to craft personalized cold emails based on extracted job data.
- The email includes relevant portfolio links that showcase the company’s capabilities in relation to the job posting.

### 🔗 **Portfolio Querying**
- Connects to a portfolio stored in **ChromaDB** and fetches the most relevant links based on the job's required skills.
- Matches job requirements with past work, showcasing the best-fit projects for the job posting.

### 🌍 **Responsive Web Design**
- Built using **Streamlit** to create an easy-to-use web interface.
- Fully responsive to ensure a smooth user experience on both desktop and mobile devices.

### 📦 **Cloud & Scalable Deployment**
- Hosted on **AWS EC2** for global accessibility, ensuring the platform's stability and scalability.
- Dockerized for consistent performance across different environments (development, testing, production).

### 🖥️ **User-Friendly Interface**
- Simple, intuitive UI built with **Streamlit** for seamless interaction.
- Users can input job URLs, trigger the email generation process, and view the result.

### 🔑 **Admin and User Flexibility**
- Admins can manage portfolio data to ensure relevant links are included in email generation.
- Users input job URLs and can review, edit, or copy the generated emails.

## 🎯 **Impact**

### 📝 **Streamlined Cold Email Process**
- Automates and simplifies the process of crafting personalized cold emails, saving time and increasing efficiency for business development teams.

### 🤝 **Targeted Outreach**
- Helps companies reach out to potential clients with emails tailored to specific job opportunities, improving outreach effectiveness.

### 💨 **Scalable, Secure, and Efficient**
- Scalable deployment ensures smooth performance even as the platform grows, with built-in security in the email generation process.

### 🌐 **Local and Cloud Deployment**
- Cloud hosting on **AWS EC2** ensures public accessibility and availability worldwide.

## 🛠️ **Tech Stack**

- **Python** 🐍
- **Streamlit** 🎨
- **Langchain** 🤖
- **Llama 3.3** 🤖
- **ChromaDB** 🗃️
- **AWS EC2** ☁️

## 🚀 **How to Run Locally**

### **1. Clone the Repository**
```bash
https://github.com/DhanushGD/Cold-Email-Generator.git
cd cold-email-generator
```

### **2. Set Up the Virtual Environment**
```bash
python3 -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate  # For Windows
```

### **3. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4. Set Up Environment Variables**
Create a .env file in the root directory and add your Groq API key:(which you can get from groq.console.com)
```bash
GROQ_API_KEY=your-api-key-here
```

### **5. Run the App**
```bash
cd /app/
streamlit run main.py
```

## 🌐 Deploying to Cloud (AWS EC2)
1. Set up an EC2 instance on AWS 
2. Clone the repository on your EC2 instance.
3. And navigate to app directory and run the following command
```bash
streamlit run main.py
```

## 🖼️ **Usage**

Here’s a brief overview of how the **Cold Email Generator** works, with screenshots of the web interface in action:

### 1. **Enter a Job URL from carrers page of the comapany**
Users input the job listing URL they want to generate an email for. This initiates the scraping and extraction process
![Screenshot 2025-02-02 231534](https://github.com/user-attachments/assets/b2453e72-8e2e-419d-8ca8-92d5ab783e43)
Give the link from company's carrer page and press submit.

### 2. **Generated Cold Email**
The AI generates a personalized cold email using the extracted job data and relevant portfolio links.
![Screenshot 2025-02-02 231620](https://github.com/user-attachments/assets/4c326714-6e93-4b71-84ae-ba4f8363d90a)







