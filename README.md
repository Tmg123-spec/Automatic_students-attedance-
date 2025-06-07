# Automatic_students-attedance
This project uses a Raspberry Pi 3B+, a USB webcam, and face recognition to automatically mark student attendance. When a student’s face is detected, their login and logout time is saved in a MySQL database. The attendance is shown on a website hosted on Render, which anyone can access.

An LCD screen on the device shows messages like “Attendance Marked”. The system works for up to 60 students, automatically updates face data every day, and clears old data after 23 hours while saving it online.
