# ColdEmailGPT: From Job Link to Perfect Outreach Message

### I developed an intelligent system that helps job seekers streamline cold outreach. By simply pasting a job link, the AI extracts key skills and requirements, matches them with the user's portfolio, and automatically generates a personalized cold email that can be sent to the hiring manager — saving time while increasing the chances of engagement.




## 🏗️ Project Architecture: AI-Powered Cold Email Generator

![Project Architecture](project%20architecture.png)


### 1. Frontend (User Interface)
- Input field to paste job posting URL
- Button to trigger email generation
- Section to display the generated cold email

### 2. Backend (API & Logic Layer)
- **Job Scraper**: Extracts job description and requirements from the URL
- **Resume Parser**: Extracts user skills and experience from resume/portfolio
- **Matching Engine**: Matches relevant skills to job requirements
- **Prompt Builder**: Crafts a tailored prompt for the AI
- **Email Generator**: Calls AI model (e.g., GPT) to generate the cold email

### 3. AI Layer
- OpenAI GPT model for generating professional emails

### 4. Database (ChromaDB)
- Stores user data (profile, skills)
- Tracks job links and email drafts
- Enables user session history (if extended)

### 5. Integrations
- OpenAI API (text generation)
- BeautifulSoup / Requests (web scraping)


### 6. Deployment
- **Frontend**: Streamlit (for simplicity and speed)
- **Version Control**: Git & GitHub






















