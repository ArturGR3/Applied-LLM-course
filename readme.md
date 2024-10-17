# Applied-LLM Course Syllabus Part 1

## Course Description

**What is this course about?**: 
This course is designed to provide students with practical experience in building applications using Large Language Models (LLMs). 

**What will you learn?**: 
1. **Code Generation**: Using Cursor for AI-assisted coding to boost productivity and learn new programming concepts
2. **LLM APIs**: Overview and hands-on integration with popular services like OpenAI and Groq
3. **Prompt Engineering**: Basics and optimization techniques to effectively communicate with LLMs
4. **MVP Iteration**: Rapid prototyping of LLM-powered applications to quickly test ideas and iterate
5. **Simple UI**: Creating user-friendly interfaces for LLM applications with Gradio/Streamlit or CLI(Command Line Interface)
6. **RAG (Retrieval Augmented Generation)**: Enhance LLM outputs with external knowledge
7. **Deployment**: Deploying LLM applications to the cloud

**What this course is not about?**: 
1. This course is not about the theory behind LLMs. It is absolutely fine if you don't know what a transformer is. This course is about practical experience in building applications using LLMs.
2. This course is not about the details of prompt engineering. While we will discuss what makes a good prompt, the course will not go deep into the theory and practice of prompt engineering.
3. This course will not teach you how to code, but rather provide ways how you can learn new programming concepts and technologies with AI assistance.

By the end of this course, students will be able to build their own applications and deploy them. They will create a portfolio of 2-3 projects to showcase their skills, demonstrating practical experience in this cutting-edge technology.

## Prerequisites

- Basic understanding of Python programming (imports, variables, classes, functions, loops, conditionals)
- Cursor 1 month subscription (20 USD)
- Groq API or OpenAI API (5 USD)

## Target audience

- Students who want to get more practical experience in building LLM applications
- Working professionals who want to switch careers or get more technical or just become 3x more productive at work
- Anyone who wants to learn how to build their own LLM applications

## Course Outline

### Week 1. Introduction & Setup
In this week, students will get inspired by the potential of LLMs and gain an understanding of where the technology is heading. We will also set up the development environment to start building right away.

- Showcase of potential projects to get inspired, including real-world applications of LLMs in various industries
- What are LLMs? Basics of NLP neural networks, including an overview of transformer architecture and its impact on AI (very high-level overview)
- Setting up the dev environment:
  - WSL (Ubuntu) on Windows for a Linux-based development experience
  - Cursor (free 2 week trial + 1 month paid subscription (20 USD)) for AI-assisted coding
  - Groq (free tier) or OpenAI (5 USD) for access to powerful LLM APIs

### Week 2. AI Code Assistance with Cursor
This week focuses on using AI to assist in coding tasks, dramatically increasing productivity and learning new programming concepts.

- Introduction to Cursor:
  - Basic usage and best practices for effective AI-assisted coding

- Learning to code via prototyping (Application: Data Analytics report with 5 charts in Python in 10 min.):  
  - Creating a Data Analytics report with 5 charts in Python in 10 min, demonstrating the speed of AI-assisted development
  - Understanding the code that was generated, including data manipulation with pandas and visualization with matplotlib/seaborn
  - Iterating on the generated code to get the desired output, learning how to guide the AI to produce more accurate results

### Week 3. LLM APIs
Students will learn how to interact with LLM APIs, understanding key concepts like tokens and pricing. We'll use the Groq API free tier for hands-on experience.

- Introduction to LLM APIs:
  - Overview of OpenAI and Groq APIs
  - Setting up API keys
  - Basic Usage of APIs, including concepts like streaming, temperature, max_tokens, and understanding different roles (system, user, assistant)

- Basics of Prompt Engineering:
  - What is a prompt? Understanding how to effectively communicate with LLMs
  - Some simple techniques: Chain of thought, few-shot prompting for improved results

- Structured Output: 
  - Introduction to Instructor library for generating structured responses
  - Examples

- What is an MVP and why it is important especially in rapid prototyping.
    - Creating a simple MVP (Application: YouTube video summary)
    - Iterating on the MVP

### Week 4. RAG Applications
This week covers Retrieval Augmented Generation (RAG), a powerful technique for enhancing LLM outputs with external knowledge.

- Introduction to RAG:
  - Overview of RAG and its main components, understanding how it improves LLM performance
  - Retrieval:
    1. LanceDB (examples: Semantic, text and hybrid search) for efficient vector storage and retrieval
    2. Ground truth data generation for retrieval evaluation
    3. Evaluation of retrieval methods
  - Generation: Techniques for effectively combining retrieved information with LLM outputs
  - Setting up monitoring: 
    1. PostgreSQL DB for storing user interactions with application
    2. Simple monitoring using Python to track system performance

### Week 5. Deployment
Learning how to take LLM applications from development to production environments.

- Short intro to Docker and Docker Compose for containerization and orchestration
- Setting up a Streamlit app and deploying it to the cloud, making the application accessible to users

### Week 6. Final Project 

Students will work on their MVPs, focusing on creating functional backends with simple UIs. They should be prepared to discuss potential improvements and extensions if given more time. It is encouraged to work in groups of up to 3 people to share ideas and help each other.

### Week 7. Evaluation

- Presentation of the project (10 min presentation + 5 min Q&A) showcasing their LLM-powered applications
- Teacher provides feedback and discusses potential improvements, relating the projects to real-world applications and industry trends

### Assessment

- Students will be evaluated based on their final project:
    - Idea (20%)
    - MVP (30%)
    - Potential next steps (20%) 
    - Presentation & Teamwork (30%)

