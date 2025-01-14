# Canteen-Management-System-using-Mesa-Framework--Fundamentals-of-AI---Project

A next-generation canteen management system leveraging AI agents to streamline order processing, customer verification, and menu management. This repository contains all the necessary files and information to explore, run, and improve this innovative system.

---

## Published Paper

This project is supported by the research detailed in our IEEE publication:

**Paper Title:**  
_A Next-Gen Approach to Streamlined Canteen Management Systems using Mesa Framework_  

**Citation:**  
A. Narendran, A. H. Inuguri, M. Yashaswini, S. Sundaram, and M. Khanna, "A Next-Gen Approach to Streamlined Canteen Management Systems using Mesa Framework," 2024 8th International Conference on Computational System and Information Technology for Sustainable Solutions (CSITSS), Bengaluru, India, 2024, pp. 1-5, doi: [10.1109/CSITSS64042.2024.10816849](https://ieeexplore.ieee.org/document/10816849).  

**Read the Paper:**  
[View on IEEE Xplore](https://ieeexplore.ieee.org/document/10816849)

---

## Project Structure

### **Folder: AI-Start-Module**
This module contains the foundational components of the system.

1. **`StudentDetails.xlsx`**  
   - **Description:** Excel database containing student information, including registration numbers, names, and branches.  
   - **Purpose:** Serves as the primary database for user verification.

2. **`start_program.py`**  
   - **Description:** Entry point script to initiate the canteen management system.  
   - **Purpose:** Prompts the user to start the program and calls the verification module.

3. **`verification.py`**  
   - **Description:** Core script containing the main logic for ID verification, OTP generation, and email validation.  
   - **Purpose:** Executes the core functions triggered by `start_program.py`.

4. **`camera_check.py`**  
   - **Description:** Utility script to capture and verify text from an ID card using the camera.  
   - **Purpose:** Provides insights into text recognition for troubleshooting.

---

### **Folder: AI-Agent-Module**
This module focuses on agent-based automation using the Mesa framework.

1. **`AI_Server.py`**  
   - **Description:** Handles order processing, token generation, and server-side operations.  
   - **Purpose:** Facilitates communication between the client and server.

2. **`AI_Client.py`**  
   - **Description:** Manages the user interface for order placement and displays tokens.  
   - **Purpose:** Provides a seamless interaction layer for the user.

3. **`DynamicMenuAgent.py`**  
   - **Description:** Uses the Mesa framework to generate dynamic menus based on real-time data.  
   - **Purpose:** Automates menu updates and enhances user experience.

4. **`README_Agent_Report.pdf`**  
   - **Description:** Comprehensive report detailing the design, methodology, results, and future scope of the project.  
   - **Purpose:** Serves as documentation for the AI-Agent module.

---

## How to Run

### Step 1: Setting Up
- Clone the repository to your local machine.
- Ensure Python and required libraries are installed (`requirements.txt` provided in the repository).

### Step 2: Running the System
1. Navigate to the **AI-Start-Module** folder.
2. Run `start_program.py`:
   ```bash
   python start_program.py ```
3. Follow the prompts: 
    - Enter 's' or 'start' to initiate the system.
    - Place your ID card in front of the camera when prompted.
    - Wait for the system to capture the image, extract your registration number, and validate your details.
4. Enter the OTP send in you Email for verification.
5. Upon successful OTP validation, access the dynamic menu system.

**Note** :- The database has to be altered according to your requirements and small changes have to be made in the code to use with different ID cards. This project currently works with Amrita ID cards only and with our student database.

---

## Features
- AI Integration: Agent-based menu updates and order processing.
- Verification: ID card scanning and OTP-based email authentication.
- Dynamic Menus: Menus update based on real-time data (e.g., time of day).
- Secure Ordering: Centralized server for efficient token management.

--- 

## License
This project is licensed under the MIT License.
