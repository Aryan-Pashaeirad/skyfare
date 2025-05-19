# ✈️ Airline Ticket Booking System

Welcome! This is a web-based Airline Ticket Booking System built with **Java Spring Boot**. It lets users easily search and book flight tickets while giving admins full control over flight management.

Whether you're booking your next trip or managing an airline's schedule, this app makes it simple.

---

## 🌟 What You Can Do

### For Users:
- Sign up and log in
- Browse available flights
- Book tickets quickly and easily
- Receive confirmation emails

### For Admins:
- Manage airlines and airplanes
- Add or update flights and stops
- View all bookings and customer details
- Export data to Excel with one click

---

## 🧰 Tech Stack

- **Java 17 + Spring Boot** – backend framework
- **Spring Security** – handles user login/signup and role-based access
- **Spring Data JPA** – for database operations
- **Thymeleaf** – renders HTML pages
- **MySQL** – stores all data
- **Lombok** – reduces boilerplate code
- **Apache POI** – for exporting to Excel
- **SMTP** – for sending confirmation emails

---

## 📁 Project Overview

Here's a quick look at the folder structure:

```
src/
├── main/
│   ├── java/com/…/AirlineTicketBookingSystem/
│   │   ├── controller/       # Web endpoints (e.g. FlightController)
│   │   ├── entity/           # Database models (e.g. Ticket, Customer)
│   │   ├── service/          # Business logic layer
│   │   ├── repository/       # Spring Data JPA repositories
│   │   ├── emailService/     # Email sending logic
│   │   ├── excelExporter/    # Excel export tools
│   │   └── login/            # Login, signup, and user roles
│   └── resources/
│       ├── templates/        # HTML pages (Thymeleaf)
│       └── application.yml   # App configuration
└── test/                     # Unit tests
```

---

## 🚀 Getting Started

1. **Clone the project**
   ```bash
   git clone https://github.com/Aryan-Pashaeirad/skyfare.git
   cd skyfare
   ```

2. **Set up your database**

   Make sure you have MySQL running. Then, open `src/main/resources/application.yml` and update the database settings (URL, username, password).

3. **Run the app**
   ```bash
   ./mvnw spring-boot:run
   ```

4. **Open in your browser**

   Go to: `http://localhost:8080`

---

## 🔐 Roles

- **Admin** – Full access to manage airlines, flights, and tickets.
- **User** – Can view and book tickets after signing up.

---

## 📬 Email Confirmations

Once a ticket is booked, a confirmation email is sent to the user. Just make sure to configure your SMTP settings in `application.yml`.

---

## 📤 Excel Exports

Admins can download flight, ticket, and customer information as Excel files using the built-in export feature.

---

## 💡 Notes

- The app uses basic Spring Security. You can expand it with JWT or OAuth if needed.
- The UI is kept simple and functional for demo purposes.
- You’re free to improve or customize it!

---

## 📄 License

This project is open for learning and experimentation. Fork it, tweak it, and use it however you like.

---

Built with ❤️ by **Aryan Pashaeirad  **
