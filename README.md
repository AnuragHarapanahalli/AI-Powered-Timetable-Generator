# 📅 AI-Powered Timetable Generator

This project generates optimized timetables for multiple classes while considering constraints such as faculty availability, lab scheduling, and subject repetition using **Google OR-Tools**.

## 🚀 Features
✅ **Generates Timetables for Multiple Classes**  
✅ **Enforces Faculty Constraints** (No double-booking)  
✅ **Ensures Proper Lab Scheduling** (2 consecutive slots)  
✅ **Prevents Excessive Subject Repetition** (Max 2 times per day)  
✅ **Penalty-Based Optimization** (Minimizes bad schedules)  

## 📌 Constraints Considered
- Each class has **5 time slots per day**.
- Each class has **10 subjects**, 5 of which have **2-hour lab sessions**.
- A subject can be scheduled **twice per day if necessary**.
- A faculty member **cannot be assigned to multiple classes at the same time**.
- Lab sessions must be **scheduled in consecutive slots**.
- A **penalty system** discourages infeasible schedules.

## 🛠 Tech Stack
- **Python** 🐍
- **Google OR-Tools** (Constraint Programming)

## 📥 Installation
1. Clone the repository:
   ```sh
   git clone (https://github.com/AnuragHarapanahalli/AI-Powered-Timetable-Generator.git)
   cd timetable-generator
   ```
2. Install dependencies:
   ```sh
   pip install ortools
   ```
3. Run the timetable generator:
   ```sh
   python timetable.py
   ```

## 🖥 Example Output
```
📅 Timetable for Class A:
  Day 1: Math | Physics | Chemistry (Lab) | Chemistry (Lab) | English |
  Day 2: Biology (Lab) | Biology (Lab) | History | Math | Economics |
  Day 3: Geography | CS (Lab) | CS (Lab) | Math | Physics |
  Day 4: Electronics (Lab) | Electronics (Lab) | English | Physics | Chemistry |
  Day 5: History | Geography | Math | Economics | CS (Lab) |

⚠️ Penalty Score: 0
```

## 🏗 Future Improvements
- **GUI Interface** for easier timetable customization.
- **Excel/CSV Export** for generated timetables.
- **More Constraints** like preferred subjects in morning/evening slots.

## 🤝 Contributing
1. Fork the repository 🍴
2. Create a new branch (`feature-new`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-new`)
5. Open a Pull Request 🚀

## 📜 License
This project is licensed under the **MIT License**.

---
Made with ❤️ by Anurag  😎

