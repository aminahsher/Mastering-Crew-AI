### uv: Fast Python Package & Project Manager  

**uv** is a high-speed Python package manager written in Rust, replacing tools like `pip`, `poetry`, and `virtualenv`.  

---

### Installation  

**macOS/Linux:**  
```bash
curl -fsSL https://astral.sh/uv/install.sh | bash
```  
**Windows (PowerShell):**  
```powershell
irm https://astral.sh/uv/install.ps1 | iex
```  

---

### Getting Started  

#### Create a New Project  
```bash
uv init project-name  
cd project-name  
uv run hello.py  
```  

#### Add or Remove Dependencies  
```bash
uv add requests                  # Add a package  
uv remove requests               # Remove a package  
uv add 'requests==2.31.0'        # Add a specific version  
uv lock --upgrade-package flask  # Upgrade a package  
```  

#### Run Scripts or Commands  
```bash
uv run script.py                # Run a Python script  
uv run -- flask run -p 3000     # Run Flask on port 3000  
```  

#### Build & Publish Project  
```bash
uv build                        # Build project distributions  
```  

uv makes Python project management faster and easier. Learn more at [uv documentation](https://astral.sh/uv/).
