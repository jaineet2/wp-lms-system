# Online Learning Management System (LMS) WordPress Plugin

[![WordPress](https://img.shields.io/badge/WordPress-5.0%2B-blue.svg)](https://wordpress.org/)
[![PHP](https://img.shields.io/badge/PHP-7.4%2B-purple.svg)](https://php.net/)
[![MySQL](https://img.shields.io/badge/MySQL-5.6%2B-orange.svg)](https://www.mysql.com/)
[![License](https://img.shields.io/badge/License-GPL%20v2-green.svg)](https://www.gnu.org/licenses/gpl-2.0.html)
[![Version](https://img.shields.io/badge/Version-1.0.0-brightgreen.svg)](https://github.com/yourusername/online-lms/releases)

## Table of Contents
- [Description](#description)
- [Features](#features)
  - [Admin Features](#admin-features)
  - [Instructor Features](#instructor-features)
  - [Student Features](#student-features)
- [Installation](#installation)
- [Requirements](#requirements)
- [Configuration](#configuration)
  - [Payment Gateway Setup](#payment-gateway-setup)
  - [Email Notifications](#email-notifications)
  - [Certificate Templates](#certificate-templates)
- [Usage](#usage)
  - [For Administrators](#for-administrators)
  - [For Instructors](#for-instructors)
  - [For Students](#for-students)
- [Changelog](#changelog)
- [License](#license)
- [Contributing](#contributing)

## Description
A comprehensive Learning Management System plugin for WordPress that enables creation and management of online courses with multiple user roles (Admin, Instructor, Student), course management, quiz functionality, and certificate generation.

## Features

### Admin Features
- Dashboard with statistics (total courses, enrolled students, revenue)
- Instructor management (approve/reject applications)
- Course approval workflow
- Revenue reports with date filters
- Site settings configuration

### Instructor Features
- Course creation interface (title, description, lessons, quizzes)
- Student progress tracking
- Revenue dashboard (earnings, pending payments)
- Discussion board moderation

### Student Features
- Course enrollment system
- Learning dashboard (progress, upcoming deadlines)
- Quiz/assignment submission interface
- Certificate generation upon completion
- Course rating and review system

## Installation

1. Upload the `online-lms` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Configure the plugin settings via the LMS menu in the admin dashboard

## Requirements
- WordPress 5.0 or higher
- PHP 7.4 or higher
- MySQL 5.6 or higher

## Configuration

### Payment Gateway Setup
1. Navigate to LMS Settings > Payments
2. Enter your payment gateway credentials
3. Configure payment settings and commission rates

### Email Notifications
1. Go to LMS Settings > Notifications
2. Configure email templates for various events
3. Enable/disable specific notifications

### Certificate Templates
1. Access LMS Settings > Certificates
2. Upload or design certificate templates
3. Configure certificate generation settings

## Usage

### For Administrators
1. Access the LMS dashboard via WordPress admin panel
2. Manage instructors, courses, and system settings
3. Monitor revenue and generate reports

### For Instructors
1. Log in to WordPress
2. Access the Instructor Dashboard
3. Create and manage courses
4. Track student progress and revenue

### For Students
1. Browse available courses
2. Enroll in courses
3. Access course materials and submit assignments
4. Download certificates upon completion
5. 
## Changelog

### Version 1.0.0 (2025-03-09)
- Initial release
- Basic course management functionality
- User role management
- Quiz system implementation
- Certificate generation
- Payment integration
- Progress tracking

## License
This plugin is licensed under the GPL v2 or later.

## Contributing
Please read CONTRIBUTING.md for details on our code of conduct and the process for submitting pull requests.
