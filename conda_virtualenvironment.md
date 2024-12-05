# Conda

Here’s a quick cheat sheet for basic Conda commands:

### 1. **Create a New Environment**

```bash
conda create --name myenv python=3.9
```

- Replace `myenv` with your desired environment name.
- Specify the Python version (`python=3.9`) or other dependencies.

### 2. **Activate the Environment**

```bash
conda activate myenv
```

### 3. **Install Dependencies in the Environment**

```bash
conda install numpy pandas matplotlib
```

- Replace `numpy pandas matplotlib` with the packages you need.

### 4. **Deactivate the Environment**

```bash
conda deactivate
```

### 5. **Remove the Environment (if needed)**

```bash
conda remove --name myenv --all
```

This will delete the environment entirely.



# Virtual Environment

Here’s a quick cheat sheet for using **venv**:

### 1. **Create a New Virtual Environment**

```bash
python -m venv myenv
```

- Replace `myenv` with your desired environment name.

### 2. **Activate the Environment**

- **On Windows:**
    
    ```bash
    myenv\Scripts\activate
    ```
    
- **On macOS/Linux:**
    
    ```bash
    source myenv/bin/activate
    ```
    

### 3. **Install Dependencies**

```bash
pip install numpy pandas matplotlib
```

- Replace `numpy pandas matplotlib` with the packages you need.

### 4. **Deactivate the Environment**

```bash
deactivate
```

### 5. **Remove the Environment (if needed)**

```bash
rm -rf myenv
```

- This completely deletes the virtual environment folder. Be cautious!

Yes, you can create a virtual environment (`venv`) using a different Python version than the default one on your system, as long as the desired version is installed. Here’s how:

### 1. **Specify the Python Version**

Use the `-p` or `--python` flag when creating the virtual environment and provide the path to the desired Python version:

```bash
python3.9 -m venv myenv
```

OR

```bash
python -m venv myenv --prompt=3.9
```

- Replace `python3.9` with the command or path to the Python executable you want to use.
- Replace `myenv` with your desired environment name.

### 2. **Verify Installed Python Versions**

To check which Python versions are available on your system:

- **Linux/macOS:**
```bash
ls /usr/bin/python*
```

- **Windows:**  
```cmd
py -0
```

### 3. **Install Another Python Version**

If the required version is not installed, download it:

- **Windows:** Download from [Python.org](https://www.python.org/).
- **Linux/macOS:** Use your package manager (e.g., `apt`, `yum`, or `brew`) or install via source.

Let me know if you need help with the installation steps!
