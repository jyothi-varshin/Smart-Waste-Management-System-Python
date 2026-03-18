# Smart Waste Management System

## Project Overview

This is a Python-based application designed to manage waste collection operations within a city.
It provides a command-line interface for different types of users (Admin, Staff, and User) to perform tasks such as managing areas, handling complaints, scheduling pickups, and generating reports.

---

## User Roles

* **Admin**
  Full access to manage areas, vehicles, complaints, schedules, and reports

* **Staff**
  Can resolve complaints, manage recycling units, and schedule waste pickups

* **User**
  Can file complaints related to waste management

---

## Features

* Manage city areas (add, update, delete, view)
* Add and manage vehicles for waste collection
* File and resolve complaints with status tracking
* Schedule waste pickups with validation and retry handling
* Track recycling units and their operational status
* Generate reports and visualize data using graphs

---

## How to Run

1. Make sure Python is installed on your system

2. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Clone the repository:

   ```bash
   git clone <repo-url>
   ```

4. Navigate to the project directory

5. Run the application:

   ```bash
   python main.py
   ```

6. Login credentials format:
   Use the format **username / password**

   * Admin: `admin / admin123`
   * Staff: `staff1 / staff1123`
   * Staff: `staff2 / staff2123`

---

## Project Structure

```bash
smart-waste-management/
│
├── data/                   # CSV files for storing data
├── main.py                 # Entry point of the application
├── admin_part.py           # User authentication and roles
├── Area_Management.py      # Area management module
├── vehiclemanagement.py    # Vehicle management module
├── waste_pickup.py         # Waste pickup scheduling
├── new_complaint.py        # Complaint filing system
├── resolve_complaint.py    # Complaint resolution system
├── recyclingmanagement.py  # Recycling unit tracking
├── reports.py              # Reports and visualizations
```

---

## Notes

* All data is stored locally in CSV files inside the `data/` folder
* The application runs entirely in the terminal
* The project is modular and can be extended with additional features

---

## Technologies Used

* Python
* pandas
* matplotlib

---

## License

This project is licensed under the MIT License.
You are free to use, modify, and distribute this project with proper attribution.
