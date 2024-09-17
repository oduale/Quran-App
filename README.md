#Quran-App
Repository for Quran App Development

Quran-App is a mobile application designed for iOS and Android to help users improve their Quran recitation skills. The app aims to provide a comprehensive learning platform with tools for beginners and advanced users alike.

Features

With this application, users will be able to:

    Listen to the Quran: Stream recitations from a variety of Qaris.
    
    Watch Tutorials: Access video tutorials to learn to pronounce Arabic letlters.
    
    Take Tajweed Lessons: Learn and apply Tajweed rules through interactive lessons.
    
    Understand the Quran: Study the meanings behind verses with translations and Tafsir.
    
    Find Online Tutors: Connect with certified Quran tutors for personalized instruction.
    
    Join a Community: Connect with other users for encouragement, support, and group practice sessions.

Technologies

This project leverages the following technologies:

    Front-End: React Native (for iOS and Android cross-platform mobile development)
    
    Back-End: Spring Boot (for building REST APIs and handling the business logic)
    
    Cloud Services: Firebase (for real-time data handling, authentication, and deployment)

Future Plans

In the future, the application will be migrated to a microservice architecture using AWS to facilitate scalability and faster development. Planned AWS services include:

    Amazon S3: For media storage (audio files, lesson materials, etc.)
    
    AWS Lambda: For serverless functions

    Amazon RDS/DynamoDB: For database management
    
    Amazon API Gateway: For managing and routing API requests

Development Status

The app is currently under active development. The following milestones have been achieved:

    Initial setup of front-end and back-end
    
    Core features such as audio playback, tutorials, and user authentication are in progress
    
    Deployment via Firebase for continuous testing and updates

Installation

To run the project locally, follow these steps:

    1. Clone the repository:
    
        git clone https://github.com/your-username/quran-app.git

    2. Navigate to the project directory:

        cd quran-app

    3. Install the necessary dependencies:

        npm install

    4. Start the development server for the front-end (React Native):

        npm start

    5. Run the Spring Boot back-end:

        mvn spring-boot:run
   
