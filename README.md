# ReUniteHub_P1
Lost&Found | AI |

ReUnite Hub: Smart AI-Powered Lost & Found System

## 1. Project Overview

**ReUnite Hub** is a digital platform designed to automate and streamline the lost-and-found process across high-traffic environments like 
**colleges, offices, and malls**It replaces outdated manual methods (like notice boards and paper registers) with a centralized, secure, and smart system.

The primary goal is to provide a quick, reliable, and stress-free way for users to report, find, and claim lost items.

**Problem Solved:** Lost items are not easily returned, and manual systems are slow, unorganized, and lack real-time tracking.

**Value Proposition:** Quick, reliable, and stress-free recovery for users; centralized, paperless, and secure tracking for administrators.

---

## 2. Core Features:

The unique selling proposition (USP) of ReUnite Hub is its combination of multiple advanced technologies.

**AI Image Recognition Search:** Identifies and matches lost items from uploaded photos using visual similarity search.

**PoC Success Metric:** Image Match Accuracy target is **>60%**.

**QR/Geo-Tag Tracking:** Enables item location tagging for faster recovery and verification.

**Basic Reporting Interface:** A functional browser-based prototype for submitting and viewing lost/found items.

### 3. Technology Stack

| Component | Technology/Tool | Purpose |
| :--- | :--- | :--- |
| **Backend/API** | **Django/Cloud Backend (CD)** | Hosting the core application logic and API endpoints.API Sketch: `'POST /report/lost', 'GET /report/matches/{id}'`. |
| **AI/ML Model** | **MobileNetV2** or **External APIs**  |Image feature extraction and visual similarity search for untagged items. |
| **Hosting** | **AWS/Azure/GCP Free Tier**  | Low-cost cloud infrastructure for model hosting and deployment. |
| **Libraries** | **TensorFlow/Keras, OpenCV** | Core for the AI matching module. |

---

## 4. Setup and Installation

1.  **Clone the Repository:**
    open terminal 
    git clone [Git/Drive link placeholder]
    cd ReUnite-Hub
2.  **Environment Setup:**
    * Ensure Python and `pip` are installed.
    * A **synthetic/mock image dataset** is required for initial model training and testing.
3.  **Install Dependencies:**
    pip install -r requirements.txt
4.  **Run the Local Server:**
    python manage.py runserver
5.  **Access:** Open your browser and navigate to the local server address (e.g., `http://127.0.0.1:8000/report/`).

---

## 5. Team and Mentorship

| Role | Name | 
| :--- | :--- | 
| **Project Lead** | KAVINILA L |
| **Member (AI Lead)** | GUGAN KRITHIK R  |
| **Member (Backend/API)** | KABILESH M  |
| **Member (Testing/UI)** | MADHUVIKASH S  |
| **SoI Mentor** | SUJITH R  |


---
