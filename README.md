## -- 👩‍🎓STUDENT DATABASE MANAGEMENT SYSTEM --

### 📚OVERVIEW
*This project is a simple University Database Management System implemented in C++. The application allows users to manage a database of students and employees, including adding new students or employees, editing their information, displaying details, searching by surname or PESEL(personal ID number in Polish system), sorting the database, and removing. The data can also be saved to a text file and later loaded into the application for further manipulation.*

### 🎨FEATURES
- <b>add Student:</b> Add new students to the database by providing details such as name, surname, date of birth, address, PESEL number(which will be verified by the validator according to the Polish personal number system), and gender.
- <b>edit Student:</b> Edit student information by searching with their index number.
- <b>display Student:</b> Display a student's details by searching with their index number.
- <b>add Employee:</b> Add new employees to the database by providing details such as employeeJob, name, surname, address, PESEL number, salary, and gender.
- <b>edit Employee:</b> Edit employee information by searching with their surname.
- <b>display Database.</b>
- <b>search by Surname:</b> Search for students and employees by their surname.
- <b>search by PESEL:</b> Search for students and employees by their PESEL number.
- <b>remove Student:</b> Remove a student from the database using their index number.
- <b>remove Employee:</b> Remove an employee from the database using their PESEL.
- <b>sort Students:</b> Sort the database by PESEL number or surname.
- <b> save/load Database:</b> Save the current state of the database to a text file and load it back into the application.

### ⚙️INSTALLATION
The project has been created and run on Windows. To run this project, you need to have a C++ compiler installed on your system. 

### 🪜STEPS TO CLONE AND RUN
1. Clone the repository using the following command:
```cp
git clone https://github.com/jarek1992/student_database.git
```   
2. Navigate to the Project Directory:
```cp   
cd student_database
```
3. Compile the Program<br>
I built and tested the project using CMake. You can build it using the tool 'g++'. For the purposes of this manual, I recommend using the CMake tool.<br>
<ul>
 <li>Create a build directory and run CMake:</li>
 
 ```cpp
cmake -B build .
```
 <li>Compile the project:</li>
 
 ```cpp
cmake --build build --config Release 
```
<i>This will compile the source files into an executable named university_database.</i>
</ul>

4. Run the Program:
   After compiling, you can run the program using the following command:
```cpp
.\build\Release\university_Database.exe
```

### 👤USAGE
Once the program is running, you can interact with the application using the displayed menu. The options allow you to add, edit, display, search, sort, and remove from the database. Additionally, you can save the database to a file or load it from a file to resume your work later.

### 💿SAVING AND LOADING DATA  
- <b>save the database:</b> To save the current database state to a file, choose the appropriate menu option. The file will be saved automatically with the name <code>university_DataBase.txt</code>.
- <b>load the database:</b> To load a previously saved database, select the load option from the menu. The file will be saved automatically and loaded from the previous session. 
