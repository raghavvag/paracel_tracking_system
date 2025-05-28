# Paracel Tracking System

A shipment tracking system built with ASP.NET Core that allows users to track their packages and shipments in real-time.

## Features

- User authentication and management
- Shipment creation and tracking
- QR code generation for shipments
- Email notifications
- SMS notifications
- Real-time location tracking

## Technologies Used

- ASP.NET Core
- Entity Framework Core
- SQL Server
- MailKit for email services
- QR Code generation

## Setup Instructions

1. Clone the repository
2. Update the connection string in `appsettings.json`
3. Run database migrations: `dotnet ef database update`
4. Run the application: `dotnet run`

## API Endpoints

- `/api/login` - User authentication
- `/api/shipment` - Shipment management
- `/api/user` - User management
