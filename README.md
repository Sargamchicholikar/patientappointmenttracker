# Patient Appointment Tracker App

An Android-based mobile application designed to manage and organize patient appointments in hospitals, clinics, and other healthcare settings. The app categorizes appointments into **Past**, **Today’s**, and **Upcoming**, and works entirely offline using SQLite for local data storage.

---

## 📱 Features

- **Admin Login**: Secure authentication for authorized access.
- **Book Appointments**: Input patient details (name, age, phone, blood group, department, date & time).
- **Categorized Views**: View Past, Today, and Upcoming appointments with filtering.
- **Responsive UI**: Clean and scrollable layout optimized for mobile screens.
- **Offline Functionality**: No internet required—data is stored locally using SQLite.

---

## 🛠️ Built With

- **Java** – for application logic and backend integration.
- **XML** – for user interface layout and design.
- **SQLite** – for local database storage and retrieval.
- **Android Studio** – IDE used for development and testing.

---

## 📂 Project Structure

```
├── java/com.example.patientappointmenttracker/
│   ├── MainActivity.java
│   ├── AppointmentActivity.java
│   ├── ViewAppointmentsActivity.java
│   └── DatabaseHelper.java
│
├── res/layout/
│   ├── activity_main.xml
│   ├── activity_appointment.xml
│   └── activity_view_appointments.xml
│
├── res/values/
│   └── strings.xml
│
├── AndroidManifest.xml
```

---

## 🚀 Getting Started

1. Open project in Android Studio.
2. Build the project and run it using an emulator or Android device.
3. Login using the **admin credentials** (e.g., Username: `admin`, Password: `admin123`).
4. Navigate to book new appointments or view existing ones.

---

## 📌 Screens Overview

- **Login Screen**: Admin access only.
- **Appointment Booking**: Fill form and save appointment.
- **View Appointments**: Filter appointments by time category using buttons.

---

## 💡 Future Enhancements

- Cloud integration (Firebase/Google Drive backup).
- SMS/Email reminders.
- Doctor availability and calendar sync.
- Multi-user login roles (Receptionist, Doctor, Admin).

---

## 📃 License
This project is developed for educational purposes and is open for customization.

---

## 🤝 Contributing
Feel free to fork this repository and submit pull requests to enhance the features or UI of the application.

---

## 🙋 Support
For any issues or feature requests, please contact:
**Sargam Chicholikar** – sargamchicholikar@gmail.com

