# employee-wage-calculator
🧾 Employee Wage GUI – Java Starter Project (With File Writing)

A beginner-friendly Java GUI project that calculates employee wages and saves/merges data to a file. This version avoids object-oriented programming and uses simple Java techniques to help new programmers understand GUIs, basic file handling, and data entry.

📌 Project Description
This Java application allows the user to:

Enter employee details (name, hours worked, and hourly rate)

Calculate the total wage

Merge new entries into a file (append mode)

View confirmation once data is saved

It uses Java Swing for the GUI and basic file I/O to write wage records to a text file.

🎯 Key Features
Java Swing-based GUI

Input fields for:

Employee Name

Hours Worked

Hourly Rate

"Calculate & Save" button to:

Compute the wage

Merge entry into a text file (wages.txt)

Resets input fields after saving

🧰 Technologies Used
Java SE (JDK 8 or higher)

Java Swing (GUI toolkit)

Java File I/O (FileWriter, BufferedWriter)

IDE used :NetBeans(IntelliJ IDEA, Eclipse, etc.)

⚙️ How It Works
User enters employee details

On clicking the "Calculate & Save" button:

Wage is calculated:
wage = hoursWorked * hourlyRate


📌 Learning Objectives
Practice building basic GUIs using Swing

Learn how to collect and process user input

Understand how to write and append data to a file

Avoid using object-oriented design patterns to keep things simple for beginners

🔄 Possible Extensions
Add error validation for text fields

Create a “View Saved Wages” button to display file contents

Implement sorting by wage in the file

Add a timestamp to each entry
