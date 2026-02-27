🏫 SmartClass Tracker (SCT)
SmartClass Tracker is a professional frontend-based application developed to address the common campus challenge of space utilization. As an Information Technology student, I designed this prototype to provide a centralized platform where students can monitor the real-time occupancy of classrooms and laboratories. This tool effectively reduces the time spent searching for vacant study spaces, thereby improving campus efficiency.

🌐 Live Demo
Check out the live application here: https://aasthay303-pixel.github.io/SmartClass-Tracker/

✨ Key Technical Features
Dynamic Occupancy Dashboard: Provides a real-time visual summary of available, occupied, and total academic units.

Role-Based Access Control (RBAC): Implements a secure dual-view system. Students have a "Read-Only" interface for live tracking, while staff can unlock administrative controls using a security code (admin123) to manually update room statuses.

Adaptive UI Theming: Features a native Dark/Light Mode toggle, allowing users to switch themes based on their environmental lighting and personal preference.

Quick-Access Filtering: Replaces traditional search bars with interactive "Category Chips" for Laboratories, Classrooms, and Audit Halls, ensuring a faster user experience on mobile devices.

Persistent Data Management: Utilizes the browser's localStorage API to preserve user theme settings and room occupancy data across sessions, ensuring reliability without a backend database.

🛠️ Implementation Details
This project was developed with a focus on modern web standards and responsive UI/UX principles:

HTML5 & CSS3: Utilized CSS Grid and Flexbox for a robust, mobile-first design that works on desktops, tablets, and phones.

Vanilla JavaScript (ES6+): Developed clean, modular logic for DOM manipulation and state management without the need for external frameworks.

Data Structure: Uses a JavaScript array of room objects containing properties like id, room name, building name, floor, and status.

🚀 How to Use
View Status: Students can browse the grid to see which rooms are marked as "Free" (Green) or "Occupied" (Red).

Filter: Use the category chips or the building dropdown to find specific labs or classrooms.

Update (Staff Only): Click on "Staff Login," enter the password, and toggle the occupancy status of any room.

👩‍💻 Developed By
TechOrbit Team

Information Technology Student (2026)
