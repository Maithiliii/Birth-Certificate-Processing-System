# Birth-Certificate-Processing-System  

A **web-based birth certificate management system** built with **PHP, MySQL, HTML, CSS, and JavaScript**.  
This project provides a digital platform for processing and managing birth certificate applications, designed for government agencies, hospitals, or local administrative offices.  

---

## Features

### User Authentication
- Login and registration functionality for both **users** and **admins**  
- Role-based access control for secure data handling  

### Birth Certificate Application Process
- Multi-step form for collecting detailed child information:
  - Name, gender, date of birth, place of birth, contact details, and address  
- Separate (optional) forms for parent details  
- Validation and dynamic form handling for smooth submission flow  

### Database Integration
- Connected to **MySQL (birthcert)** database  
- Secure storage of child and applicant data  
- Supports full **CRUD operations**  

### Admin Dashboard
- View, process, and manage submitted applications  
- Delete records or mark applications as complete  
- Download and generate certificates directly from the dashboard  

### Certificate Generation
- Automated **PDF certificate generation** using the **FPDF** library  
- Generates official-format, downloadable birth certificates  

### User Interface
- Modern, responsive design built with **HTML5, CSS3, and Boxicons**  
- Intuitive navigation and multi-step forms  
- Clean, professional layout  

---

## Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | HTML5, CSS3, JavaScript |
| **Backend** | PHP |
| **Database** | MySQL |
| **PDF Generation** | FPDF Library |
| **Icons** | Boxicons |

---

## ⚙️ System Workflow

1. **User registers** and logs into the system.  
2. **Application form** collects and stores birth details in the database.  
3. **Admin reviews** applications through the dashboard.  
4. **Certificate generated** automatically as a downloadable PDF.  
