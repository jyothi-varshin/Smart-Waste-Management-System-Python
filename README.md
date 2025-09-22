# Smart Waste Management System 🚮

This is a Python-based project that helps manage waste collection in a city. It provides an easy-to-use terminal interface for Admins, Staff, and Users to handle tasks like:

- Managing city areas
- Adding and assigning vehicles
- Filing and resolving complaints
- Scheduling waste pickups
- Tracking recycling units
- Viewing reports with graphs 📊

---

## 👥 Who Can Use It?

- **Admin**: Has full control (manage areas, vehicles, complaints, schedules, etc.)
- **Staff**: Can resolve complaints, track recycling units, and schedule pickups
- **User**: Can file complaints only

---

## 🚀 Features

- Add and update city areas
- Add vehicles and assign them for pickups
- File and resolve complaints with notes
- Schedule waste pickups with retry options
- Track recycling units and their status
- View useful reports with simple graphs

---

## 🏁 How to Run

1. Make sure you have **Python** installed
2. Clone or download the project
3. Run the program:

```bash
python main.py
```

4. Login as:
   - **Admin**: `admin / admin123`
   - **Staff**: `staff1 / staff123`

---

## 📁 Project Structure

```bash
WasteManagement/
│
├── data/               # All CSV files stored here
├── main.py             # Main entry point
├── area_management.py  # Area-related code
├── vehicle.py          # Vehicle handling
├── waste_pickup.py     # Scheduling pickups
├── complaints.py       # Complaint system
├── recycling.py        # Recycling unit tracker
└── reports.py          # Graph reports
```

---

## 🧠 Notes

- All data is stored in `.csv` files inside the `data/` folder
- Designed to run in the terminal — very beginner-friendly
- Easy to extend or modify!

---

## 🛠 Built With

- Python
- pandas
- matplotlib

---

## 📌 License
Free to use and modify 😄
