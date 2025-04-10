# TransSync---Transport-Management-System
# Overview
TransSync is a comprehensive Transport Management System (TMS) designed to modernize travel agency operations in Cameroon and beyond. This project replaces inefficient paper-based systems with a centralized database and web application, enabling seamless booking, payment, and management of transport services. Developed as part of a university case study, TransSync demonstrates robust database design, normalization, security measures, and concurrency control.

# Features
Agency Management: Agencies can register, manage bus schedules, and track bookings.
Digital Client Management: Secure storage of customer details with user profiles.
Online Booking System: Users can book tickets via a web platform with real-time availability.
Payment Integration: Supports multiple payment methods (e.g., credit card, mobile money) with transaction verification.
Reporting & Analytics: Provides insights into revenue, peak booking periods, and customer behavior.
Future Enhancements: Planned seat selection functionality.
# Project Structure
Database Design: Entity-Relationship (ER) model with 8 key entities (Admin, User, Agency, Bus, Route, Schedule, Booking, Payment).
Normalization: Tables structured up to Third Normal Form (3NF) to eliminate redundancy.
SQL Implementation: Oracle SQL scripts for table creation, population, and data retrieval queries.
Security: Role-based access control, data encryption, audit logging, and backup strategies.
Concurrency Control: Implements ACID properties to ensure transaction reliability.
# Installation
Prerequisites: Oracle Database 11g or higher, Oracle SQL Developer.
# Setup:
Clone the repository: git clone https://github.com/username/TransSync.git
Execute the SQL scripts in database/ folder to create and populate tables.
Configure database connection in your SQL environment.
Run Queries: Use the provided SQL queries for analytics and reporting.
# Usage
Admins: Manage agencies and oversee system operations.
Agencies: Register buses, update schedules, and monitor bookings.
Users: Register, book tickets, and make payments through the system.
Analytics: Run queries to analyze revenue, booking trends, and customer preferences.
# Database Schema
Entities: Admin, User-Customer, Agency, Bus, Route, Schedule, Booking, Payment.
Relationships: Defined with foreign keys (e.g., 1:M between Agency and Bus).
Normalization: Ensures data integrity and efficiency (1NF, 2NF, 3NF).
# Security & Governance
Access Control: Role-based permissions and multi-factor authentication.
Encryption: Data encrypted at rest and in transit (SSL/TLS).
Backup: Regular backups with disaster recovery plan.
Ethical Considerations: Adheres to data protection principles (e.g., GDPR-inspired).
#Contributors
Njinju Zllefac Fogap - 2439344
Chukwuebuka Emmanuel Owoh - 2328893
Patrick Nnaemeka Nwonah - 2437973
# License
This project is licensed under the MIT License - see the  file for details.

# Acknowledgments
University of Wolverhampton, School of Mathematics and Computer Science.
Course: 7C1022 - Database System and Security.
