<h1 align="center">
  <img src="https://github.com/XanderSteyn/xandersteyn/blob/main/IGNORE/Headers/Tasks/Synthesis.svg" width="100%" height="130px" alt="Shoe Inventory Management System"/><br>
</h1>

<img src="https://github.com/XanderSteyn/xandersteyn/blob/main/IGNORE/Headers/Table%20of%20Contents.svg" alt="Table of Contents" height="25px"/>

- [**Features**](#features)
- [**Tech Stack**](#tech-stack)
- [**Setup & Installation**](#setup)
- [**Database Schema**](#database-schema)
- [**Security**](#security)
- [**Contributing**](#contributing)
- [**License**](#license)

<h1></h1>

<a name="features"></a>
<img src="https://github.com/XanderSteyn/xandersteyn/blob/main/IGNORE/Headers/Repos/Features.svg" alt="Features" height="25px"/>

| Feature                  | Description                                                              |
|--------------------------|--------------------------------------------------------------------------|
| Object-Oriented Design   | Encapsulates shoe data and inventory logic in well-structured classes    |
| Persistent Storage       | Reads from and writes to a CSV-based inventory file                      |
| Interactive CLI          | Intuitive menu-driven interface for all inventory operations             |
| Data Validation          | Comprehensive input validation and error handling                        |
| Inventory Operations     | Add, view, restock, search, value calculation, and highlight high stock  |
| Cross-Platform           | Works on Windows, macOS, and Linux                                       |
| Extensible               | Easy to add new features or integrate with other systems                 |

<h1></h1>

<a name="tech-stack"></a>
<img src="https://github.com/XanderSteyn/xandersteyn/blob/main/IGNORE/Headers/Tech%20Stack.svg" alt="Tech Stack" height="25px"/>

- Python 3.8+
- [`tabulate`](https://pypi.org/project/tabulate/)
- Standard Python libraries: `os`, `platform`

<h1></h1>

<a name="setup"></a>
<img src="https://github.com/XanderSteyn/xandersteyn/blob/main/IGNORE/Headers/Repos/Setup%20Instructions.svg" alt="Setup & Instructions" height="30px"/>

#### 1. Clone the repository
```bash
git clone https://github.com/XanderSteyn/HyperionDev.Shoe-Inventory-Manager/
```

#### 2. Change to the project directory
```bash
cd "HyperionDev.Shoe-Inventory-Manager"
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

#### 5. Install dependencies
```bash
pip install -r requirements.txt
```

#### 6. Run the application
```sh
python inventory.py
```

- The application will prompt to create `inventory.txt` if missing.
- Sample data is provided in the repository.

<h1></h1>

<a name="database-schema"></a>
<img src="https://github.com/XanderSteyn/xandersteyn/blob/main/IGNORE/Headers/Repos/DatabaseSchema.svg" alt="Database Schema" height="25px"/>

| Field     | Type    | Description                |
|-----------|---------|----------------------------|
| Country   | String  | Country of manufacture     |
| Code      | String  | Unique product code (SKU)  |
| Product   | String  | Product name               |
| Cost      | Float   | Price per unit             |
| Quantity  | Integer | Units in stock             |

<h1></h1>

<a name="contributing"></a>
<img src="https://github.com/XanderSteyn/xandersteyn/blob/main/IGNORE/Headers/Repos/Contributing.svg" alt="Contributing" height="30px"/>

1. Fork the repository and create a feature branch.
2. Follow PEP8 and project code style (see `.flake8` config)
3. Write tests for new features and bug fixes.
4. Submit a pull request with a clear description.

<h1></h1>

<a name="license"></a>
<img src="https://github.com/XanderSteyn/xandersteyn/blob/main/IGNORE/Headers/License.svg" alt="License" height="25px"/>

This repository is protected by a custom license. See the [LICENSE](LICENSE) file for details.  
Unauthorized copying or submission of this work for academic purposes is prohibited.
