# WordPress Learning Management System (LMS)

![LMS Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![WordPress](https://img.shields.io/badge/wordpress-6.0%2B-green.svg)
![PHP](https://img.shields.io/badge/php-7.4%2B-purple.svg)
![License](https://img.shields.io/badge/license-MIT-orange.svg)

A comprehensive Learning Management System (LMS) WordPress plugin that enables educational institutions and content creators to create, manage, and deliver online courses efficiently.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [User Roles](#user-roles)
- [Directory Structure](#directory-structure)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Changelog](#changelog)
- [License](#license)

## Features

### Admin Features
- 📊 Comprehensive dashboard with real-time statistics
- 👥 Instructor management system
- ✅ Course approval workflow
- 💰 Revenue tracking and reporting
- ⚙️ Site-wide settings configuration

### Instructor Features
- 📝 Intuitive course creation interface
- 📊 Student progress tracking
- 💰 Revenue dashboard
- 💬 Discussion board moderation
- 📚 Lesson and quiz management

### Student Features
- 📚 Course enrollment system
- 📊 Personal learning dashboard
- ✍️ Quiz and assignment submission
- 🎓 Automatic certificate generation
- ⭐ Course rating and review system

## Requirements

- WordPress 6.0 or higher
- PHP 7.4 or higher
- MySQL 5.6 or higher
- Advanced Custom Fields PRO plugin
- Modern web browser

## Installation

1. Download the latest release from the releases page
2. Upload the plugin through WordPress admin panel:
   ```
   Plugins > Add New > Upload Plugin
   ```
3. Or extract the ZIP file to your `/wp-content/plugins/` directory
4. Activate the plugin through the 'Plugins' menu in WordPress
5. Navigate to LMS Settings to configure the plugin

## Configuration

### Initial Setup

1. Navigate to `LMS > Settings` in your WordPress admin panel
2. Configure the following essential settings:
   - Payment gateway credentials
   - Email notification templates
   - Certificate design
   - Course approval workflow
   - Site-wide settings

### Advanced Custom Fields

The plugin requires ACF PRO for custom fields. Required field groups will be automatically created during installation.

```php
// Example of course fields structure
{
    "key": "group_course_details",
    "title": "Course Details",
    "fields": [
        {
            "key": "field_course_price",
            "label": "Course Price",
            "name": "course_price",
            "type": "number"
        },
        // ... other fields
    ]
}
```

## User Roles

### Administrator
- Manage all aspects of the LMS
- Access to all features and settings
- Revenue reports and analytics

### Instructor
- Create and manage courses
- Track student progress
- Access revenue dashboard
- Moderate discussions

### Student
- Enroll in courses
- Submit assignments and quizzes
- Track personal progress
- Download certificates

## Directory Structure

```
wp-content/plugins/jaineet-lms/
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── includes/
│   ├── admin/
│   ├── instructor/
│   ├── student/
│   ├── acf/
│   └── functions/
├── templates/
│   ├── admin/
│   ├── instructor/
│   └── student/
├── languages/
├── jaineet-lms.php
└── README.md
```

## Documentation

Detailed documentation is available in the [Wiki](https://github.com/yourusername/jaineet-lms/wiki).

### Quick Start Guides:
- [Administrator Guide](docs/admin-guide.md)
- [Instructor Guide](docs/instructor-guide.md)
- [Student Guide](docs/student-guide.md)

### Development
- [API Documentation](docs/api.md)
- [Hook Reference](docs/hooks.md)
- [Filter Reference](docs/filters.md)

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/AmazingFeature`
3. Commit changes: `git commit -m 'Add AmazingFeature'`
4. Push to branch: `git push origin feature/AmazingFeature`
5. Open a Pull Request

## Changelog

### [1.0.0] - 2025-02-25
- Initial release
- Core LMS functionality
- Three user roles: Admin, Instructor, Student
- Course creation and management
- Student enrollment system
- Quiz and assignment functionality
- Certificate generation
- Revenue tracking

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Author

**Jaineet**
- Created: 2025-02-25
- Last Updated: 2025-02-25 08:27:22 UTC
- WordPress Username: jaineet2

## Support

For support, please:
1. Check the [Documentation](docs/)
2. Search [Issues](https://github.com/yourusername/jaineet-lms/issues)
3. Create a new issue if needed

---

💡 **Pro Tip:** Regular updates and backups are recommended for optimal performance and security.
