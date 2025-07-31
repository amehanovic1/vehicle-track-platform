# AutoTrack Pro - Vehicle Management System

AutoTrack Pro is a secure, enterprise-grade platform designed for internal vehicle management across institutions such as ministries, government agencies, and large organizations. It helps manage everything related to vehicles — from registration, maintenance, and fuel usage to driver assignments, service requests, and traffic violations. 

---

## System Overview

### Architecture

- Frontend: Angular (modular pages, JWT-based auth, reactive forms)
- Backend: Spring Boot (REST API, raw SQL via JDBC, layered services)
- Database: Oracle (triggers, views, scheduled backups)

### Additional Database Features

- Audit fields like CREATED_AT and MODIFIED_BY help track when and by whom records were changed
- Triggers automatically log changes across all tables for transparency and data consistency
- SQL views simplify reporting by grouping and aggregating key data
- Seed scripts initialize the database with default values for easy setup and testing
- Automated backups run daily, exporting all tables to CSV for reliable recovery if needed

---

### Technologies Used

Angular | Spring Boot | JDBC | Oracle Database | JWT | iText PDF Library | GitHub

---

<img width="1585" height="1009" alt="dashboard" src="https://github.com/user-attachments/assets/fe423169-2386-45e6-a820-8637bf49af79" />
<img width="1583" height="996" alt="dashboard-admin" src="https://github.com/user-attachments/assets/a46174df-827c-4c1e-b1dd-63ae5f4d07bc" />
<img width="1585" height="1009" alt="login" src="https://github.com/user-attachments/assets/9a9ded3c-693f-43d5-a00b-8c85cc87f0c7" />
<img width="1593" height="1032" alt="list-drivers" src="https://github.com/user-attachments/assets/079ee067-c463-42c2-9e19-8b55903750c9" />
<img width="1593" height="1037" alt="add-driver" src="https://github.com/user-attachments/assets/f74551a2-6c7f-4507-a570-f96dbe3b28e3" />
<img width="1587" height="1010" alt="add-vehicle-1" src="https://github.com/user-attachments/assets/35b3dfe8-7831-4dc0-9385-7ecbe42d2a02" />
<img width="1583" height="1035" alt="add-vehicle-2" src="https://github.com/user-attachments/assets/4bcc02b9-bb66-400f-99b9-4922a0796620" />
<img width="1586" height="1027" alt="inscurance-company" src="https://github.com/user-attachments/assets/1bd99669-318a-4aa4-8413-de3e0b3d0b94" />
<img width="1592" height="1034" alt="edit-company" src="https://github.com/user-attachments/assets/45082e62-d9e2-41a5-9991-344f36e08a48" />
<img width="1590" height="1036" alt="add-traffic-fine" src="https://github.com/user-attachments/assets/004c7bbb-e0cb-4fa3-9396-b91d74a978a2" />
<img width="1595" height="1036" alt="add-fuel-price" src="https://github.com/user-attachments/assets/97e5a0ba-2676-4ae8-b525-a33396878a96" />
<img width="1590" height="1031" alt="reports-fuel-price" src="https://github.com/user-attachments/assets/2af80294-ba57-419e-b6b4-ef82fe18a3a2" />

