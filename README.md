# LodgeLink: AI Driven Boarding House Booking and Management System

## Project Overview

**LodgeLink** is an innovative web application designed to provide a seamless, immersive, and efficient booking experience for both seekers and owners. The system leverages advanced technologies such as **augmented reality (AR), artificial intelligence (AI), and machine learning (ML) to deliver four key features: AR Room Previews, Predictive Booking and Vacancy Trends, AI-Powered Advanced Search and Filters, and AI-Powered Dynamic Pricing.**

The web application serves as the user interface for both seekers and owners, integrating AR for immersive previews, **AI/ML** models for predictive trends and dynamic pricing, and **NLP** for advanced search capabilities. The backend is supported by robust databases and AI/ML frameworks, ensuring efficient data processing and seamless functionality. This solution aims to enhance user experience, optimize property management, and maximize revenue, revolutionizing the boarding house booking industry.

## Features

### **AR Room Previews**

The AR Room Previews feature enables seekers to explore boarding house rooms through immersive 360-degree views created using augmented reality (AR). Owners upload room images, which are processed with advanced stitching algorithms to generate seamless, high-quality panoramas. Seekers can interact with these views, inspecting room layouts and dimensions virtually, providing a realistic and engaging booking experience.

This feature builds trust by helping seekers make informed decisions and enhances listings for owners, attracting more users. Integrated into the web app using tools like OpenCV and AR frameworks, it revolutionizes room exploration and booking confidence.

### **Predict Future Bookings and Vacancy Trends**

- **Predict Future Bookings**

  predicts the number of bookings expected for the boarding house over a specified time period. It provides insights into how many rooms are likely to be occupied, helping owners plan their operations and optimize occupancy rates.

- **Predict Vacancy Trends**

  predicts the number of rooms expected to remain unoccupied over a given time period. It highlights availability trends, helping boarding house owners identify periods of low demand and take proactive measures to fill vacancies, such as offering discounts or promotions.

- **Projected Revenue**

  estimates the revenue that will be generated based on the predicted bookings. It gives a financial forecast, enabling owners to make strategic decisions regarding pricing, marketing, and budgeting.

### **AI-Powered Advanced Search and Filters**

Enhances the search experience by utilizing NLP techniques to process user queries and deliver precise, personalized results. It analyzes queries to extract key elements like location, amenities, and price preferences. Users can search naturally, such as "boarding house near SLIIT with Wi-Fi and kitchen," and receive relevant results. The system offers query suggestions and supports voice input for accessibility. This improves efficiency by providing tailored results, saving users time, and enhancing decision-making while ensuring a seamless and intuitive search experience.

### **Dynamic Pricing**

The Dynamic Pricing Allocation module leverages advanced algorithms to automatically adjust boarding house prices based on key factors such as proximity to the university, amenities offered, and prevailing weather conditions. The system analyzes these variables in real-time to provide an optimal price that reflects both market demand and the unique features of each listing.

This feature benefits both seekers and owners by ensuring competitive pricing while maximizing value. Seekers receive transparent and fair pricing, while owners can optimize their pricing strategy to attract more bookings. The module is seamlessly integrated into the web app and uses data analytics tools to continuously refine pricing models, offering an intelligent and responsive booking experience that adapts to changing conditions.

## Additional Features

- **User Registration**
- **Boarding House Owner Dashboard**
- **List Boarding House**
- **Book a room**
- **Notification System**
- **Chat System**

## Technology Stack

- **Frontend**: React.js, Tailwind CSS, Shadcn UI
- **Backend**: Node.js, Express.js, Python
- **Machine Learning**: TensorFlow/PyTorch for AI-driven features
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Version Control**: Git, GitHub
- **Cloud Services**: AWS/GCP for storage and deployment

## Architecture

![Architecture Diagram](https://github.com/Research-Project-Team/Research_BHBS/blob/Sahan/Architecture%20Diagram.jpg?raw=true)

LodgeLink is built on **MERN** stack, offering a robust and adaptable platform for web applications. The backend handles data management, API endpoints, and core functionality, while the frontend delivers a user-friendly interface. Machine learning models are incorporated into the backend to analyze and process data, providing users with valuable insights.

## Installation

### Prerequisites

- **Node.js**: [Download and Install](https://nodejs.org/)
- **MongoDB**: [Download and Install](https://www.mongodb.com/)
- **Python**: [Download and Install](https://www.python.org/)
- **Git**: [Download and Install](https://git-scm.com/)

### Setup the project

### Backend Setup

1. Download project from each branch

   [Project Repository](https://github.com/Research-Project-Team/Research_BHBS.git)
   
3. Navigate to backend directory

   `cd backend`

4. Install Dependencies
5. Configure Environment Variables
6. Run the Server

   `python app.py`

### Frontend Setup

1. Navigate to Frontend Directory

   `cd frontend`

2. Install Dependencies
3. Configure Environment Variables
4. Run the Frontend

   `npm run dev`