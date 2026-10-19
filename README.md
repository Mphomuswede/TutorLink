TutorLink – Tutor and Student Connection Platform

About the Project

TutorLink is a web-based platform designed to connect students with lecturers or tutors and provide access to academic support features. The project includes a website and an Android application that allows users to access the website through a mobile app.

The goal of TutorLink is to make it easier for students to find academic assistance and for lecturers or tutors to manage their tutoring-related activities.

Features

- Student and Lecturer Profiles: Provides profile areas for students and lecturers.
- User Authentication: Supports login and registration through the website.
- Dashboards: Provides separate dashboard areas for different user roles.
- Session Management: Supports tutoring session-related features.
- Session Requests: Provides functionality for managing tutoring requests.
- Learning Resources: Includes access to academic resources.
- Notifications: Provides a notification feature.
- Study Groups: Includes study group-related functionality.
- Android Application: Allows users to access the website through an Android app.

Feature availability depends on the current implementation and configuration of the website and its backend.

Technologies Used

Website

- PHP
- HTML
- CSS
- JavaScript
- Backend

Android Application

- Kotlin
- Android Studio
- Android WebView

Project Structure

The project consists of two main components:

1. Website

The website contains the pages, authentication functionality, dashboards, and other tutoring-related features.

Important website files and directories include:

- "index.php" – Website entry page.
- "app/index.php" – Login page and processing.
- "app/register.php" – Registration processing.
- "app/dashboard/index.php" – Dashboard entry point.
- "app/dashboard/lecturer.php" – Lecturer dashboard.
- "app/dashboard/pages/" – Dashboard feature pages.

2. Android Application

The Android application displays the website inside a WebView.

The "main_web.kt" file contains the website URL used by the Android application.

How the Android App Works

The Android application uses WebView technology to load the TutorLink website inside the app.

This means that website changes can become available in the Android application without rebuilding the Android app, provided the website remains available at the same URL and the changes do not require modifications to native Android functionality.

If the website URL changes, the URL configured in the Android project must be updated.

Installation and Setup

Website Setup

1. Download or clone this repository.
2. Install or configure a PHP-compatible web server.
3. Place the website files in the appropriate server directory.
4. Configure the required backend/data service connection.
5. Configure any necessary environment settings and credentials.
6. Open the website through the configured local or public URL.
7. Test login, registration, dashboards, profiles, and other features.

8. WEBSITE URL:https://studyplugtools.cloud/plug-me/mqrKc0tL8I/rea/

Android App Setup

1. Install Android Studio.
2. Clone or download the Android project.
3. Open the project in Android Studio.
4. Allow Gradle to synchronise and download the required dependencies.
5. Open the "main_web.kt" file.
6. Verify that the configured website URL points to the correct deployed website.
7. Run the application on an Android emulator or a physical Android device.

Deployment

The website must be deployed to a hosting environment that supports its PHP and backend requirements.

After deployment, verify that the website works correctly in a browser before connecting the Android application to it.

The Android application can then load the deployed website using its configured URL.

Security Considerations

- Do not commit passwords, API keys, database credentials, or private configuration files to GitHub.
- Use HTTPS for the deployed website.
- Protect authentication sessions and user information.
- Validate user input on the server.
- Ensure that backend services enforce appropriate access controls.

Future Improvements

Potential future improvements include:

- Enhancing student and lecturer profile management.
- Improving the mobile user experience.
- Adding further tutoring session management capabilities.
- Improving notifications and communication.
- Enhancing accessibility and performance.
- Expanding testing and deployment automation.

