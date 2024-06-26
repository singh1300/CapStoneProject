# Capstone Project Proposal

# Project Title
Punjab: The Era of Maharaja Ranjit Singh

## Overview
### What is your app?
An interactive educational app that provides an immersive experience into the history of Punjab during the reign of Maharaja Ranjit Singh. Users can explore various aspects of the era, including key figures, cultural contributions, and significant events through detailed descriptions, images, and interactive features.

## Problem
### Why is your app needed?
There is a lack of accessible and engaging resources for learning about the rich history of Punjab, particularly the period of Maharaja Ranjit Singh. Many educational materials are either too dense or fail to capture the interest of a younger audience. This app addresses the need for a comprehensive yet engaging tool for students, historians, and anyone interested in this pivotal era of Punjab’s history.

## User Profile
### Who will use your app?

#### Students: 
To supplement their history curriculum with interactive content.

#### Historians: 
For a consolidated resource of information on Maharaja Ranjit Singh’s era.

#### General Public: 
Anyone with an interest in learning more about Punjab’s history in an engaging manner.

### Special Considerations:

The app must be intuitive and easy to navigate.
Content should be accessible to users of varying ages and educational backgrounds.
It should include multimedia elements (images, videos) to enhance learning.

### Features
#### Interactive Timeline
Users can explore major events in the timeline of Maharaja Ranjit Singh’s reign.
#### Key Figures
Profiles of significant individuals from the era, including images and detailed descriptions.
### Cultural Insights
Sections on art, literature, architecture, and traditions of the time.
### Daily Life
Descriptions and images of the daily lives of common people during this period.

### Implementation
### Tech Stack

#### Frontend: 
React Native (for cross-platform mobile app development)
#### Backend: 
Node.js with Express (for server-side logic and API integration)
#### Database: 
MySQL (for storing user data and content)

#### Libraries:
Axios (for API calls)
Redux (for state management)
Sequelize (for MySQL ORM)


### APIs

#### Historical Data API: 
For accessing a database of historical facts and images.
#### Image Library API: 
To integrate high-quality historical images.

### Sitemap
#### Home Page
Overview of the app and featured content.
#### Timeline
Interactive timeline of events.
#### Key Figures
List and profiles of notable individuals.
#### Cultural Insights
Detailed sections on art, literature, and architecture.
#### Daily Life
Descriptions and images of common people's lives.

#### Mockups

Use Figma to create detailed mockups of each screen.
Include hand-drawn sketches for initial design ideas.

### Data

#### Entities: 
Events, People, Cultural Aspects, Daily Life Descriptions, Quiz Questions.
#### Relationships:
Events related to People (one-to-many).
People related to Cultural Aspects (many-to-many).
Daily Life Descriptions related to Events (one-to-many).

### Endpoints

#### GET /events
Retrieve a list of historical events.
#### GET /people
Retrieve profiles of key figures.
#### GET /culture
Retrieve cultural insights.
#### GET /user
Retrieve user profile information.

#### Auth

Implement JWT for user authentication.
Users can create accounts and log in to save their progress.
#### Roadmap
Scope your project as a sprint. Break down the tasks that will need to be completed and map out timeframes for implementation.

### Week 1:

#### Day 1-2: 
Research and gather content; design mockups.
Collect historical information, images, and resources.
Create hand-drawn sketches and digital mockups using Figma.
#### Day 3-4: 
Set up the backend and database.
Configure Node.js, Express, and MongoDB.
Develop user authentication with JWT.
#### Day 5-7: 
Develop the frontend.
Build the main pages (Home, Timeline, Key Figures).
Integrate APIs and connect to the backend.

### Week 2:

#### Day 8-10: 
Complete frontend development.
Finalize pages for Cultural Insights, Daily Life, Quizzes, and User Profile.
Ensure all interactive elements are functioning.

#### Day 11-12: 
Testing and debugging.
Conduct thorough testing to identify and fix bugs.
Perform user testing to gather feedback and make improvements.

#### Day 13-14: 
Final revisions and deployment.
Implement any remaining changes based on feedback.
Deploy the app to a suitable platform.

### Nice-to-haves

#### Multilingual Support: 
Include translations in Punjabi and Hindi.
#### Augmented Reality (AR) Features: 
Interactive AR experiences of historical sites.
