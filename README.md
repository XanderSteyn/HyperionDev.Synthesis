<h1 align="center">
  <img src="https://github.com/XanderSteyn/xandersteyn/blob/main/IGNORE/Headers/Tasks/Synthesis.svg" width="100%" height="130px" alt="Synthesis - CLI Shoe Inventory Manager"/><br>
</h1>

<img src="https://github.com/XanderSteyn/xandersteyn/blob/main/IGNORE/Headers/Repos/Features.svg" alt="Features" height="25px"/>

- **Inventory Management:** Complete CRUD operations for shoe inventory
- **Data Persistence:** Automatic file-based storage with CSV format
- **Search Functionality:** Find shoes by product code with case-insensitive search
- **Stock Management:** Restock low quantity items with automatic file updates
- **Value Calculations:** Calculate total value per item (cost × quantity)
- **Inventory Analytics:** Identify highest quantity items for sales promotion
- **Input Validation:** Robust error handling with positive number validation
- **User-Friendly Interface:** Clear menu system with formatted table displays
- **Cross-Platform Compatibility:** Works on Windows, macOS, and Linux
- **Comprehensive Error Handling:** Graceful handling of file operations and invalid inputs

<h1></h1>

<img src="https://github.com/XanderSteyn/xandersteyn/blob/main/IGNORE/Headers/How%20It%20Works.svg" alt="How It Works" height="25px"/>

- The program loads shoe data from `inventory.txt`, a CSV file with the header row:  
  `Country,Code,Product,Cost,Quantity`

- **Adding Shoes:** Users input new shoe details; the program validates inputs, adds the shoe to memory and appends it to the file.

- **Viewing Inventory:** Displays all shoe data in a formatted table with cost and quantity.

- **Restocking:** Finds the shoe with the lowest quantity and allows the user to add stock, updating the file accordingly.

- **Searching:** Allows users to search for shoes by code (case-insensitive).

- **Value per Item:** Calculates and displays total value per shoe (`cost × quantity`) in a table.

- **Highest Quantity:** Identifies the shoe with the highest stock quantity and highlights it for potential sales.

- All user inputs are validated for correctness, and the program handles missing or corrupted files gracefully.

<h1></h1>

<img src="https://github.com/XanderSteyn/xandersteyn/blob/main/IGNORE/Headers/Repos/Technologies%20Used.svg" alt="Technologies Used" height="30px"/>

- **Python** – Core programming language
- **Tabulate** – For formatted table displays
- **OS Module** – For cross-platform console operations
- **Platform Module** – For OS detection and system-specific commands

<h1></h1>

<img src="https://github.com/XanderSteyn/xandersteyn/blob/main/IGNORE/Headers/Repos/Setup%20Instructions.svg" alt="Setup Instructions" height="30px"/>

#### 1. Clone the repository
```bash
git clone https://github.com/XanderSteyn/HyperionDev.Synthesis
```

#### 2. Change to the project directory
```bash
cd "HyperionDev.Synthesis"
```

#### 3. Create a virtual environment
- **Windows:**
  ```powershell
  python -m venv venv
  ```
- **macOS/Linux:**
  ```bash
  python3 -m venv venv
  ```

#### 4. Activate the virtual environment
- **Windows (Command Prompt):**
  ```cmd
  .\venv\Scripts\activate.bat
  ```
- **Windows (PowerShell):**
  ```powershell
  .\venv\Scripts\Activate.ps1
  ```
- **macOS/Linux:**
  ```bash
  source ./venv/bin/activate
  ```

#### 5. Install required dependencies
```bash
pip install -r requirements.txt
```

#### 6. Run the application
```bash
python inventory.py
```

<h1></h1>

<img src="https://github.com/XanderSteyn/xandersteyn/blob/main/IGNORE/Headers/License.svg" alt="License" height="25px"/>

This repository is protected by a custom license. See the [LICENSE](LICENSE) file for details.

Unauthorized copying or submission of this work for academic purposes is prohibited. 
