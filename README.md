# Swamper Solution

Swamper Solution is a Flutter-based platform connecting companies and individuals for labor solutions. It provides a seamless experience for job posting, job searching, application management, and profile handling for both companies and job seekers.

## Features

### For Individuals
- **Sign Up & Login:** Register and log in as an individual.
- **Profile Management:** View and edit your profile, including uploading a profile picture.
- **KYC Verification:** Submit and track KYC status.
- **Job Search:** Browse and search for available jobs by role or location.
- **Apply for Jobs:** Apply to jobs, upload resumes (PDF), and select preferred shifts.
- **Application Tracking:** View and manage your job applications, including status updates and deletion.
- **Statistics:** View stats like total hours worked, jobs completed, and earnings.
- **Notifications:** Receive notifications for job updates and application status.

### For Companies
- **Sign Up & Login:** Register and log in as a company.
- **Profile Management:** Manage company profile and KYC status.
- **Job Posting:** Post new jobs with details, shifts, and site images.
- **Job Management:** Edit or delete posted jobs, view job details.
- **Applicant Management:** View applicants for posted jobs.
- **Statistics:** Track total jobs posted, total hires, and total pay.
- **Notifications:** Receive notifications for job and application events.

### General
- **Responsive UI:** Optimized for both mobile and tablet screens.
- **State Management:** Uses Riverpod for robust state management.
- **Navigation:** Uses GoRouter for declarative routing.
- **Firebase Integration:** Authentication, Firestore, and Storage for data and file management.
- **Local Notifications:** In-app notifications for important events.

## Project Structure

- `lib/`
  - `views/` - UI screens and widgets for both individual and company flows.
  - `models/` - Data models for users, jobs, applications, and stats.
  - `controllers/` - Business logic and data handling.
  - `providers/` - Riverpod providers for state management.
  - `services/` - Firebase and notification services.
  - `routes/` - App routing configuration.
  - `consts/` - App-wide constants and styles.

## Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Firebase CLI](https://firebase.google.com/docs/cli)
- A configured Firebase project (see `lib/firebase_options.dart`)

### Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/swamper_solution.git
   cd swamper_solution
   ```

2. **Install dependencies:**
   ```sh
   flutter pub get
   ```

3. **Configure Firebase:**
   - Ensure your `firebase_options.dart` is set up for your Firebase project.
   - Add your `google-services.json` (Android) and `GoogleService-Info.plist` (iOS) as needed.

4. **Run the app:**
   ```sh
   flutter run
   ```

### Environment Variables

- All Firebase configuration is handled via `firebase_options.dart` generated by FlutterFire CLI.

## Usage

- **Landing Page:** Choose to log in or sign up as an individual or company.
- **Sign Up:** Fill in the required details and complete KYC for full access.
- **Dashboard:** Access features based on your role (individual/company).
- **Job Management:** Post, edit, search, and apply for jobs as per your role.

## Copyright

© 2020 - 2025 Designed and Developed by Loonie Tech
Any misuse or misconduct of source code is prohibited.

**Designed and Developed by Loonie Tech**
