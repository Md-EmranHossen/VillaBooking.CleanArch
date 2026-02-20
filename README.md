# Villa Booking System (White Lagoon) 🏨

A modern, robust, and scalable Villa Booking System built using **ASP.NET Core 8 MVC** following **Clean Architecture** principles. This project is designed to handle property management, booking workflows, and user authentication with a focus on maintainable code.



---

## 🚀 Project Overview

The **Villa Booking System** allows users to explore luxury villas, check availability, and make bookings. For administrators, it provides a comprehensive dashboard to manage villa details, occupancy, and track revenue.

### 🛠️ Built With
* **Framework:** .NET 8.0 (ASP.NET Core MVC)
* **Database:** SQL Server
* **ORM:** Entity Framework Core
* **Architectural Pattern:** Clean Architecture
* **Design Patterns:** Repository Pattern, Unit of Work
* **UI/UX:** Bootstrap, Toastr.js, SweetAlert2

---

## 🏗️ Architecture Layers

This project is structured into four main layers to ensure strict separation of concerns:

1.  **VillaBooking.Domain:** Contains all enterprise entities, enums, and core domain logic. (No dependencies on other layers).
2.  **VillaBooking.Application:** Contains business logic, interfaces for repositories, and application services.
3.  **VillaBooking.Infrastructure:** Handles data access (DB Context), migrations, repository implementations, and external service integrations (like Email).
4.  **VillaBooking.Web:** The Presentation layer (MVC) which handles user interaction, Controllers, Views, and ViewModels.

---

## ✨ Key Features

- ✅ **Villa Management:** Create, Update, and Delete villa records with image upload support.
- ✅ **Villa Number Tracking:** Manage specific units and track their maintenance status.
- ✅ **Real-time Availability:** Users can check if a villa is available for their selected dates.
- ✅ **Authentication:** Secure Login/Registration using **ASP.NET Core Identity**.
- ✅ **Dashboard Analytics:** Visual representation of booking data and revenue.
- ✅ **Email Integration:** Automatic notifications for booking confirmations.

---

## ⚙️ Getting Started

### Prerequisites
* Visual Studio 2022 (v17.8 or later)
* .NET 10.0 SDK
* SQL Server (LocalDB or Express)

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/VillaBooking.CleanArch.git](https://github.com/your-username/VillaBooking.CleanArch.git)

```

2. Navigate to the solution folder:
```bash
cd VillaBooking

```


3. Update the connection string in `appsettings.json` within the **VillaBooking.Web** project.
4. Run migrations via Package Manager Console:
```powershell
Update-Database

```


5. Build and Run the project.

---

## 🤝 Contributing

Contributions are welcome! If you find any bugs or have suggestions for new features, feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.

---

