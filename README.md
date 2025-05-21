# Image to Video Converter

## Overview
This Image to Video Converter is a web application built using Flask that allows users to upload images, convert them into a video, and add audio to the video. The app supports user authentication, storing images in a database, and retrieving audio files from the database.

## Features

### User Authentication
- **Signup**: Create an account with username, email, fullname, and password
- **Login**: Secure authentication with JWT token generation

### Image Management
- **Upload Images**: Upload multiple images to your account
- **Upload Selected Images**: Choose specific images for video creation
- **Image Retrieval**: View and manage your uploaded images

### Video Creation
- **Convert Images to Video**: Transform your uploaded images into a video sequence
- **Add Audio**: Select and add audio tracks to your video
- 
### User Profile
- **Personal Gallery**: View all your uploaded images in your profile
- **Image Selection**: Select images for video creation from your uploads

### Security and Session Management
- **Secure Authentication**: Password hashing with bcrypt
- **JWT Implementation**: Token-based session management
- **Logout**: Secure session termination with cleanup

## Implementation Details

### Technologies Used
- **Backend**: Flask (Python)
- **Database**: MySQL
- **Authentication**: JWT (JSON Web Tokens)
- **Storage**: Database storage for images and audio files
- **Video Processing**: Python libraries for image-to-video conversion

## Academic Project
This application is part of an academic group project. It was developed by a team of students to demonstrate the integration of various technologies such as Flask, MySQL, JWT, and video processing libraries.

## Getting Started
1. Create an account or login
2. Upload your images
3. Select images for video creation
4. Choose audio for your video
5. Generate your video
