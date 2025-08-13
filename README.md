# CAREPLUS – Multiple Hospital Management System

Overview
CAREPLUS is a robust, scalable hospital management system designed for multi-location healthcare networks. It centralizes patient care, hospital administration, and reporting, ensuring efficient operations across multiple facilities.
With an intuitive interface and strong backend integration, CAREPLUS improves appointment booking, patient record management, and hospital resource utilization — making healthcare delivery faster, smarter, and more patient-focused.

## Key Features
###1. Patient Care
- **Patient Registration & Profile Management –** Securely store and manage personal and medical details.
- **Appointment Booking –** Real-time scheduling with doctors across different hospitals.
- **Medical Reports Storage –** Secure online access to diagnostic and treatment records.
- **Hospital & Doctor Search –** Search by city, specialization, rating, and experience.

###2. Hospital Operations
- **Multi-Hospital Integration –** Centralized data management across different locations.
- **Doctor Management –** Manage profiles, availability, and specialties.
- **Receptionist & Staff Management –** Assign roles and manage access permissions.
- **Inventory Tracking –** Monitor medical supplies and equipment usage.

###3. Finance & Compliance
- **Billing & Payments –** Invoice generation, insurance claim tracking.
- **Role-Based Access Control (RBAC) –** Ensures data privacy and compliance with healthcare regulations.
- **Reporting & Analytics –** Track hospital performance, appointment statistics, and patient feedback.

## Technology Stack
- **Frontend:** Liferay 7.4, HTML5, SCSS, JavaScript
- **Backend:** Java (Liferay Framework), PHP for certain modules
- **Database:** MySQL 8.0 (Workbench used for management)
- **Server:** Apache Tomcat 9+
- **Authentication:** Custom role-based login (Admin, Doctor, Patient)
- **OS Compatibility:** Windows 10/11, Linux
- **Development Tools:** Liferay Developer Studio, OpenJDK 11

## Installation & Setup

### Prerequisites
- **Liferay Portal 7.4 CE**
- **MySQL 8.0 Database Server**
- **Apache Tomcat 9+**
- **Java Development Kit (JDK) 11+**

### Steps

**1. Clone the repository:**
   ```bash
   git clone https://github.com/gaffr1715/careplus-hospital-management.git
   ```
**2. Configure MySQL Database:**

- Import the provided .sql schema file.

- Update DB credentials in portal-ext.properties.

**3. Deploy the project on Liferay:**

- Place WAR files in Tomcat webapps/ directory.

**4. Start the Liferay server and access via browser.**

##System Modules
**Admin**
- Manage hospitals, doctors, patients, and appointments.
- Access analytics and reports.

**Doctor**
- Approve/Reject appointments.
- Upload/view patient reports.

**Patient**
- Register/login securely.
- Book/cancel appointments.
- View reports and hospital details.

##Advantages
- Centralized control for multiple hospitals.
- Reduced patient wait times via online booking.
- Improved data security with RBAC.
- Scalable architecture for future growth.

##Limitations
- Requires stable internet for full functionality.
- No integrated online payment in the current version.
- Limited accessibility for non-digital users.

##Future Enhancements
- AI-based appointment prediction.
- Aadhaar-based patient verification.
- Mobile application for Android/iOS.
- Integrated payment gateway support.
- Enhanced accessibility features.
