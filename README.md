# Scheduling Application

A Windows desktop application designed to manage customer records and track appointments. Built with .NET Framework and Windows Forms, it connects to a MySQL database to provide full scheduling functionality, business reporting, and automated database seeding.

---

## Tech Stack

![.NET Framework](https://img.shields.io/badge/.NET_Framework-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Windows Forms](https://img.shields.io/badge/Windows_Forms-0078D4?style=for-the-badge&logo=windows&logoColor=white)

---

## Features

- **User Authentication:** Login system to track user-specific schedules and control system access.
- **Customer Records:** Create, update, and delete customer profiles along with their structured address data.
- **Appointment Management:** Schedule, update, and remove customer appointments while tracking details like location, contact, and meeting type.
- **Upcoming Alerts:** Automatically queries the database to alert users of upcoming appointments occurring within 15 minutes.
- **Business Reports:** Built-in reporting to view monthly appointment types, individual user schedules, and total appointments grouped by location.
- **Automated Setup:** Checks for the required database tables on startup and automatically seeds initial test data if none exists.