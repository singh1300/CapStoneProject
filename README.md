Capstone Project Proposal
Project Title
Punjab: The Era of Maharaja Ranjit Singh

Overview
What is your app?
An interactive educational app that provides an immersive experience into the history of Punjab during the reign of Maharaja Ranjit Singh. Users can explore various aspects of the era, including key figures, cultural contributions, and significant events through detailed descriptions, images, and interactive features.

Problem
Why is your app needed?
There is a lack of accessible and engaging resources for learning about the rich history of Punjab, particularly the period of Maharaja Ranjit Singh. Many educational materials are either too dense or fail to capture the interest of a younger audience. This app addresses the need for a comprehensive yet engaging tool for students, historians, and anyone interested in this pivotal era of Punjab’s history.

User Profile
Who will use your app?

Students: To supplement their history curriculum with interactive content.
Historians: For a consolidated resource of information on Maharaja Ranjit Singh’s era.
General Public: Anyone with an interest in learning more about Punjab’s history in an engaging manner.
Special Considerations:

The app must be intuitive and easy to navigate.
Content should be accessible to users of varying ages and educational backgrounds.
It should include multimedia elements (images, videos) to enhance learning.
Features
Interactive Timeline
Users can explore major events in the timeline of Maharaja Ranjit Singh’s reign.
Key Figures
Profiles of significant individuals from the era, including images and detailed descriptions.
Cultural Insights
Sections on art, literature, architecture, and traditions of the time.
Daily Life
Descriptions and images of the daily lives of common people during this period.
Quizzes and Challenges
Interactive quizzes to test users’ knowledge and keep them engaged.
Implementation
Tech Stack

Frontend: React Native (for cross-platform mobile app development)
Backend: Node.js with Express (for server-side logic and API integration)
Database: MongoDB (for storing user data and content)
Libraries:
Axios (for API calls)
Redux (for state management)
Mongoose (for MongoDB object modeling)
APIs

Historical Data API: For accessing a database of historical facts and images.
Image Library API: To integrate high-quality historical images.
Quiz API: For managing interactive quizzes.
Sitemap

Home Page
Overview of the app and featured content.
Timeline
Interactive timeline of events.
Key Figures
List and profiles of notable individuals.
Cultural Insights
Detailed sections on art, literature, and architecture.
Daily Life
Descriptions and images of common people's lives.
Quizzes
Interactive quizzes and challenges.
User Profile
User information and progress tracking.
Mockups

Use Figma to create detailed mockups of each screen.
Include hand-drawn sketches for initial design ideas.
Data

Entities: Events, People, Cultural Aspects, Daily Life Descriptions, Quiz Questions.
Relationships:
Events related to People (one-to-many).
People related to Cultural Aspects (many-to-many).
Daily Life Descriptions related to Events (one-to-many).
Endpoints

GET /events
Retrieve a list of historical events.
GET /people
Retrieve profiles of key figures.
GET /culture
Retrieve cultural insights.
POST /quiz
Submit quiz responses.
GET /user
Retrieve user profile information.
Auth

Implement JWT for user authentication.
Users can create accounts and log in to save their progress.
Roadmap

Week 1-2: Research and gather content; design mockups.
Week 3-4: Set up backend and database; develop user authentication.
Week 5-6: Develop frontend; integrate APIs.
Week 7: Testing and debugging.
Week 8: Final revisions and deployment.
Nice-to-haves

Multilingual Support: Include translations in Punjabi and Hindi.
Augmented Reality (AR) Features: Interactive AR experiences of historical sites.
Social Sharing: Allow users to share their progress and favorite content on social media.
