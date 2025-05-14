# Skin Condition Diagnosis Front-End

![HTML](https://img.shields.io/badge/HTML-5-orange.svg)
![CSS](https://img.shields.io/badge/CSS-3-blue.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)
![Vercel](https://img.shields.io/badge/Vercel-Deployed-black.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## Overview

The `skin-condition-diagnosis-rag` front-end is a web application built with HTML, CSS, and JavaScript to enable users to analyze skin conditions. Users can upload images and provide text descriptions, which are sent to a FastAPI backend for AI-driven diagnosis powered by the Groq API. The application is deployed on Vercel and provides a user-friendly interface for skin condition analysis.

## Features

- **Image Upload**: Allows users to upload skin images (e.g., `.jpg`, `.png`) for analysis.
- **Text Input**: Supports text descriptions of skin conditions.
- **Backend Integration**: Sends data to the backend API at `https://skin-diagnosis-backend.onrender.com/analyze/` for processing.
- **Responsive Design**: Styled with CSS for a clean, modern look across devices.
- **Error Handling**: Displays user-friendly error messages for invalid inputs or failed requests.

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6)
- **Deployment**: Vercel
- **Backend API**: FastAPI (hosted on Render)
- **API Integration**: Communicates with the Groq API via the backend

## Installation

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox)
- Git
- (Optional) A local server for development

### Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/****-username/skin-condition-diagnosis-rag.git
