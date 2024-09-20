# Practice

The practice will consist on developing **a complete fullstack system** end-to-end. There will be vertical slices of the system that will be developed by a **team** of 2-3 people. There will be horizontal slices of the system that will be developed each **sprint** week. The system will be developed using the following technologies:

- Node.js -> Express -> NestJs
- Angular
- PostgreSQL
- MongoDB / CouchDB

## Teams and domain

During the Bootcamp, participants will be assigned to teams of 2-3 people and will be tasked with implementing a domain feature for the [AstroBookings](./astrobookings/AstroBookings.md) platform.

The domain will be selected from the list of [AstroBookings requirements](./astrobookings/1-analysis/1-domain.requirements.md).

### Project briefing summary

🚀 **AstroBookings** is a comprehensive platform connecting space agencies with travelers for commercial space flights. It manages rocket launches, bookings, payments, and communications, ensuring a seamless experience for agencies and travelers while maintaining robust backend operations and monitoring.

The common vocabulary and understanding of the system's requirements is based on the following domain **entities**: `User`, `Traveler`, `Agency`, `Rocket`, `Launch`, `Booking`, `Invoice`, `Payment`, `Notification`, `EntryLog`, and `JobQueue`. These entities represent the core concepts of the space travel booking system and define the interactions between users, agencies, launches, and financial transactions.

### Domains

0. [Authentication](#0-authentication): Manages user registration, login, and access control for agencies, travelers, and employees.
1. [Agency Management](#1-agency-management): Handles agency profiles, rockets, and launch management.
2. [Booking Management](#2-booking-management): Manages traveler bookings, seat reservations, cancellations, and the public-facing website for showcasing launches.
3. [Financial Operations](#3-financial-operations): Handles invoicing, payments, and financial reporting.
4. [Data Synchronization](#5-data-synchronization): Allows IT employees to manage and initiate synchronization processes between databases.
5. [System Monitoring](#6-system-monitoring): Provides logging and system status monitoring for IT operations.
6. [Notification System](#4-notification-system): Manages communication with users about bookings, launches, and other events.

## Planning and review

The teams will be given **12 sprints/weeks** to implement the domain feature. Each week, will be an sprint implementing a technical slice of the domain.

The teams work will be reviewed based on the following criteria:

1. Code quality
2. Technical skills
3. Feature completeness
