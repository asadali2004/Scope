# Scope

## Overview

**Scope** is a platform designed to help students, particularly first-year students, navigate their academic and professional journeys with ease. Many students struggle to find the right resources and guidance for their studies and career preparation, often wasting time on irrelevant information. Scope solves this issue by centralizing essential tools that provide personalized academic roadmaps, skill-building, and professional development resources—all in one place.

## Features

1. **Roadmap Builder**: Provides personalized learning paths based on students' academic goals.
2. **AI Code Editor**: An AI-powered environment to help students practice and improve programming skills.
3. **Resume Builder with ATS Tester**: Assists students in building professional resumes optimized for Applicant Tracking Systems (ATS).
4. **Mock Interview Simulator**: AI-driven tool for practicing job interviews.
5. **AI Bot**: A virtual assistant to answer queries and offer study guidance.
6. **Hackathon Scraper**: Helps students discover relevant hackathons and coding challenges.
7. **Job Scraper**: Aggregates job opportunities tailored to students' skills and qualifications.

## Problem Statement

First-year students often face challenges in finding relevant academic and professional resources, leading to wasted time and lack of direction. Scope addresses this problem by offering a centralized hub for personalized guidance, skill development, and career opportunities, ensuring students have the tools they need to succeed.

## Technology Stack

- **Frontend**: React.js, Material-UI (MUI)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **APIs**: On-demand.io agents and custom integrations
- **AI Tools**: OpenAI API for chatbot and AI code editor features

## Installation

To set up the project locally, follow these steps:

### Prerequisites
- Node.js (v14 or above)
- MongoDB (local or cloud)
- npm or yarn package manager

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/scope.git
   cd scope
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory and add the following variables:
     ```env
     MONGO_URI=your_mongodb_connection_string
     OPENAI_API_KEY=your_openai_api_key
     PORT=5000
     ```

4. Run the application:
   ```bash
   npm start
   ```

5. Open the app in your browser at `http://localhost:5000`.

## Usage

Once installed, users can explore the various tools such as the roadmap builder, AI code editor, and more, to aid in their academic and professional development.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.
