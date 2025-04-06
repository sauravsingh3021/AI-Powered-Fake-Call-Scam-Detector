# AI-Powered Fake Call & Scam Detector

## Problem Statement

Scammers trick people over phone calls using social engineering and voice manipulation. Existing apps like Truecaller rely on number databases and often fail against new or spoofed scam numbers. Billions of dollars are lost every year due to such scams.

## Solution Overview

This project is an AI-powered mobile/web app that detects scam calls in real-time by analyzing live conversations. It uses Google Speech-to-Text API to transcribe the call and Google Gemini API to detect scam intent from the conversation. The user receives a warning alert and risk score during the call.

## Features

- Real-time scam detection using Gemini AI
- Works with unknown numbers
- Supports multiple languages
- Provides scam risk score and warning alerts
- Customizable detection logic
- Built using privacy-first design (no personal data stored)

## Architecture

Frontend: Android/Web App  
Backend: Firebase for user settings  
AI Processing: Gemini API + Vertex AI  
Data Flow:  
Call Audio → Speech-to-Text API → Gemini AI → Risk Score and Alerts  
Data Storage: Only scam patterns are stored, not personal data  
Development and Hosting: Google IDX

Refer to the `architecture_diagram_light.png` for a visual representation.

## Technologies Used

- Google Speech-to-Text API
- Google Gemini API
- Google Firebase
- Vertex AI
- Google IDX (for frontend development and hosting)

## How to Run

1. Clone the repository  
   `git clone https://github.com/sauravsingh3021/AI-Powered-Fake-Call-Scam-Detector.git`

2. Set up environment variables  
   Create a `.env` file and add your API keys:


3. Install dependencies  
`pip install -r requirements.txt`

4. Run the app (details depend on the platform: web or Android)

## MVP Snapshots

Add screenshots of your working app or prototype under the `/screenshots` folder.

## Future Scope

- Add scam SMS detection
- Partner with telecom providers for deeper scam intelligence
- Train a custom AI model using real-world scam call patterns
- Expand support for regional languages

## Useful Links

- GitHub Repo: https://github.com/sauravsingh3021/AI-Powered-Fake-Call-Scam-Detector  
- Demo Video: (Add your demo video link here)  
- MVP Live Link: (Add your hosted app link here)

## Team

Team Name: GoogleMasters  
Team Lead: Saurav Singh  
Team Member: Devendra Khachane
Project for: Google Solution Challenge 2025
