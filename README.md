# Vaani-AI: Job Interview Preparation Powered by AI Voice Agents

Vaani-AI is an AI-powered job interview preparation platform designed to help users practice and improve their interview skills. Built using Next.js, Firebase, and Vapi AI voice agents, the platform offers a modern and interactive way to prepare for job interviews with real-time feedback.

## Table of Contents
- [Introduction](#introduction)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Installation](#installation)
- [Environment Variables](#environment-variables)

## Introduction
Vaani-AI allows users to practice mock job interviews powered by Vapi’s voice agents and Google Gemini. It provides real-time feedback and a detailed transcript of the interview to help you refine your answers. The platform is designed to be beginner-friendly, offering easy integration of AI models into your applications.

## Tech Stack
- **Frontend:** Next.js, Tailwind CSS
- **Backend:** Firebase for authentication and data storage
- **AI Integration:** Vapi AI voice agents, Google Gemini
- **UI/UX:** Shadcn/UI for modern design

## Features
- **Authentication:** Sign up and sign in using Firebase authentication (email/password).
- **Create Interviews:** Generate mock interviews with AI voice agents.
- **Real-Time Feedback:** Get instant feedback after each mock interview.
- **Dashboard:** View and manage all your previous interviews.
- **Modern UI/UX:** Responsive and user-friendly interface designed for all devices.
- **Transcripts:** Get a detailed transcript of each interview for review.

## Installation

### Prerequisites
Make sure you have the following installed:
- **Git**
- **Node.js** (Version 14.x or later)
- **npm** (Node Package Manager)

### Steps
1. Clone the repository:

    ```bash
    git clone https://github.com/akshat4k/Vaani-AI.git
    cd Vaani-AI
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

## Environment Variables

Before running the project, you need to set up your environment variables. Create a `.env.local` file in the root of your project and add the following variables:

```bash
NEXT_PUBLIC_VAPI_WEB_TOKEN=your_vapi_web_token
NEXT_PUBLIC_VAPI_WORKFLOW_ID=your_vapi_workflow_id
GOOGLE_GENERATIVE_AI_API_KEY=your_google_ai_api_key
NEXT_PUBLIC_BASE_URL=http://localhost:3000

NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_firebase_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_firebase_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_firebase_app_id

FIREBASE_PROJECT_ID=your_firebase_project_id
FIREBASE_CLIENT_EMAIL=your_firebase_client_email
FIREBASE_PRIVATE_KEY=your_firebase_private_key
