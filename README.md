# Retail Gig Mobile Application

## Overview
This application connects retailers with gig workers for temporary jobs.

## Features
- Job postings
- Worker profiles
- In-app messaging

## Installation

To set up the Retail Gig Mobile Application locally, follow these steps:

### Prerequisites
- Ensure you have [Flutter](https://flutter.dev/docs/get-started/install) installed on your machine.
- You will also need to have the [Firebase CLI](https://firebase.google.com/docs/cli) installed.
- Create a Firebase project in the [Firebase Console](https://console.firebase.google.com/).

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/pallavipadam/retail-gig-app.git
2. **Navigate to the project directory**:
cd retail-gig-app
3. **Install dependencies**:
flutter pub get
Set up Firebase:

Follow the instructions to configure your Firebase project:
Add your google-services.json (for Android) and/or GoogleService-Info.plist (for iOS) to the respective platform directories.
Update the android/build.gradle and android/app/build.gradle files to include Firebase dependencies.
Run the Application:
flutter run

### Usage

```markdown
## Usage

Once the application is running, you can:

1. **Sign Up / Log In**:
   - Create an account as a retailer or gig worker using email and password authentication provided by Firebase.

2. **Job Postings**:
   - Retailers can post new job listings, specifying job details, pay rates, and required skills.

3. **Browse Gigs**:
   - Gig workers can view available job listings, filter them based on preferences, and apply for jobs.

4. **In-App Messaging**:
   - Use the messaging feature to communicate directly with retailers or workers for job discussions and clarifications.

5. **Rate Users**:
   - After completing a job, both retailers and gig workers can rate each other to build trust within the community.

