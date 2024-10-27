# OnlineCourseAPI

**OnlineCourseAPI** is a RESTful API designed for managing online courses. It provides a set of endpoints for handling courses, users, enrollments, reviews, and more, catering to a complete online learning platform backend.

## Features

- **Contact Management**: Handle contact information and inquiries.
- **Course and Category Management**: Create and manage courses along with categorization.
- **Enrollment**: Allow users to enroll in courses and manage their enrollment statuses.
- **Review System**: Submit and manage reviews for courses.
- **User Administration**: Manage user accounts and administrative functions.
- **User Profiles**: View and update user profile information.
- **Video Requests**: Handle video-related requests, such as requesting additional course content.

## Endpoints Overview

### Contact
- Manage inquiries and contact information.

### Course
- CRUD operations for courses.
- Endpoint for managing course modules or lessons.

### CourseCategory
- Manage different categories of courses to help organize content.

### Enrollment
- Enroll users in courses.
- Manage user enrollment statuses, such as progress tracking.

### Review
- Submit, view, and manage reviews related to courses.

### UserAdmin
- Administrative functions for user management, including role assignments.

### UserProfile
- User profile management for personalized data.

### VideoRequest
- Handle requests related to video content, such as requesting new videos or tutorials for courses.

## Technologies Used

- **Framework**: ASP.NET Core (or adjust based on the specific technology in use)
- **Database**: SQL Server (or any other database used in the project)
- **Authentication**: JWT tokens for secure access to the API
- **Documentation**: Swagger for API documentation

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/abdorhl/OnlineCourseAPI.git
   cd OnlineCourseAPI
   ```

2. **Install dependencies:**
   ```bash
   dotnet restore
   ```

3. **Set up the database:**
   Configure your connection string in `appsettings.json`, and run migrations if required.

4. **Run the application:**
   ```bash
   dotnet run
   ```

5. **Access the Swagger Documentation:**
   Open [http://localhost:7005/swagger](http://localhost:7005/swagger) in your browser to explore the available endpoints.

## Contributing

1. Fork the repository.
2. Create a new feature branch: `git checkout -b feature/NewFeature`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature/NewFeature`.
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
