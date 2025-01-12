# PimSphere - multi-agent LLMs systems for PIMCO

**PimSphere** is a Streamlit-based chatbot designed to streamline pre-meeting preparation for PIMCO client data intelligence org. The application allows users to search for clients, generate customizable reports including intelligent product selection using RAG, and provide feedback for the system to regenerate reports. The interface is interactive, featuring PDF embedding and download options for ease of use.

## Table of Contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Setup](#setup)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## Features

- **Client Search**: Search for clients by name and verify their information.
- **Report Generation**: Automatically generate PDF reports based on client data.
- **PDF Viewing and Download**: View embedded PDF reports and download them for offline use.
- **Feedback Collection**: Provide feedback on reports and receive responses.
- **State Management**: Maintain session state to ensure data persistence during interactions.

---

## Architecture

![Screenshot](Screenshot%202025-01-12%20at%203.25.52%20PM.png)

---

## Setup

Follow these steps to set up and run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Elaineeeeeeeeeeee/pimsphere.git
cd pimsphere
```

### 2. Install Dependencies
Ensure you have Python installed. Install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

### 3. Run the Application
Launch the Streamlit app:

```bash
streamlit run app.py
```

### 4. Access the App
Open the app in your browser at:

```bash
http://localhost:8501
```
