Here’s a reformatted version of Lab 1 instructions with improved readability and a structure similar to Lab 2:

---

### Lab 1: Configuring Machine Learning in SQL Server (2 hours)

#### General Instructions
- **Lab Files Location**: All scripts for this lab are located on the student computer in `C:\Classfiles\Labfiles\Mod01`.
- **Execution Tips**:
  - **Do Not Execute Entire Scripts**: Review each script carefully and execute each commented section of code separately.
  - **Run as Administrator**: Run all applications (Command Prompt, PowerShell, or SSMS) as an administrator.

**Note**: SQL Server Machine Learning services have already been installed during the server setup. In this lab, you will verify and set up the runtime environments.

---

### Exercise 1: Enable the Use of External Scripts in SQL Server
- **Objective**: Enable the use of external scripts in SQL Server, which is necessary to use Python, R, Java, or other programming scripts.
- **Instructions**:
  1. Open `C:\Classfiles\Labfiles\Mod01\L1_1.sql` in SSMS.
  2. Review the script, which uses the `sp_configure` command to enable external scripts.
  3. Execute each section of code separately.

---

### Exercise 2: Install R
- **Objective**: Install R version 4.3.2 and configure additional packages required for SQL Server.
- **Instructions**:
  1. Open `C:\Classfiles\Labfiles\Mod01\L1_2.ps1` in PowerShell ISE (Administrator).
  2. Review the script, then execute each commented section of code separately.

---

### Exercise 3: Register R Runtime with SQL Server
- **Objective**: Register the R runtime with SQL Server.
- **Instructions**:
  1. Open `C:\Classfiles\Labfiles\Mod01\L1_3.ps1` in PowerShell ISE (Administrator).
  2. Review the script before running it.

---

### Exercise 4: Test R Runtime in SQL Server
- **Objective**: Verify that the R runtime is working in SQL Server.
- **Instructions**:
  1. Open `C:\Classfiles\Labfiles\Mod01\L1_4.sql` in SSMS.
  2. Review and execute each section of code to test the R runtime using `sp_execute_external_script`.

---

### Exercise 5: Install Python
- **Objective**: Install and configure Python 3.10.
- **Instructions**:
  1. Open `C:\Classfiles\Labfiles\Mod01\L1_5.ps1` in PowerShell ISE (Administrator).
  2. Review and execute each section of the script to install Python.
  3. Configure Python modules by running the `C:\Classfiles\Labfiles\Mod01\L1_5b.ps1` script, which includes updates necessary for SQL Server compatibility.

---

### Exercise 6: Register Python Runtime with SQL Server
- **Objective**: Register the Python runtime with SQL Server.
- **Instructions**:
  1. Open `C:\Classfiles\Labfiles\Mod01\L1_6.ps1` in PowerShell ISE (Administrator).
  2. Review the script before running it.

---

### Exercise 7: Test Python Runtime in SQL Server
- **Objective**: Verify that the Python runtime is working in SQL Server.
- **Instructions**:
  1. Open `C:\Classfiles\Labfiles\Mod01\L1_7.sql` in SSMS.
  2. Review and execute each section of code to test the Python runtime.

---

### Exercise 8: Install Java
- **Objective**: Install and configure Java and the necessary components for SQL Server.
- **Instructions**:
  1. Open `C:\Classfiles\Labfiles\Mod01\L1_8.ps1` in PowerShell ISE (Administrator).
  2. Review and run each section of the script to install Java.

---

### Exercise 9: Register Java Runtime with SQL Server
- **Objective**: Install the AdventureWorks2022 database and register the Java runtime with it.
- **Instructions**:
  1. Run `C:\Classfiles\AdventureWorks_Install.ps1` to install AdventureWorks2022.
  2. Open `C:\Classfiles\Labfiles\Mod01\L1_9.sql` in SSMS to register the Java runtime in the database.
  3. Review the script, then execute each section of code.

---

### Exercise 10: Test Java Runtime in SQL Server
- **Objective**: Verify that the Java runtime is working in SQL Server.
- **Instructions**:
  1. Open `C:\Classfiles\Labfiles\Mod01\L1_10.sql` in SSMS.
  2. Review and execute each section to test the Java runtime.

---

This structured format provides clear instructions for each exercise, making it easy for students to follow along with the setup and configuration steps for machine learning environments in SQL Server. Let me know if you need additional adjustments or details.
