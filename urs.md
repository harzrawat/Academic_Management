# University Management Web Portal

## About
This application aims to manage all university operations related to academics as well as management.  
Currently, Sitare uses the Digi portal, which has an outdated frontend and contains many non-functional features. This project aims to develop a modern, functional, and all-in-one web management portal.

---

## Motivation
The goal of this portal is to provide a learning experience from a software developer’s perspective.  
The typical software development cycle is iterative and involves six major steps:  

1. **Planning**  
2. **Designing**  
3. **Coding**  
4. **Testing**  
5. **Deployment**  
6. **Management**

Currently, we are in the **Planning Stage**, where thoughts and ideas are being documented.  
After deciding features for the working model, we will move to the **Design Stage**, where decisions on technology stack, database, libraries, and initial features will be made.

---

## Planned Features (Phase 1)

### User Roles
- **Student Dashboard**  
- **Teacher Dashboard**  
- **Admin Dashboard**

---

### Student Dashboard (Phase 1)
**Login Page:**  
- Accessible only to authenticated users via email ID.

**Home Page:**  
- Header shows user name and profile picture.  
- Left sidebar contains three sections:

1. **Profile**  
   - About: Personal information and resume  
   - Achievements: Certificates, projects, GitHub link

2. **Class Room**  
   - List of all subjects with clickable links  
   - Each subject page contains:  
     - Assignment (given by teacher)  
     - Resource (uploaded by teacher)  
     - Marks (viewable by teacher)  
     - Feedback

3. **Course Detail**  
   - Three pages:  
     1. Time table  
     2. Course credits  
     3. Holidays

**Middle Section:**  
- Displays messages or instructions shared by admin or teacher.

---

### Teacher Dashboard (Phase 1)
**Login Page**  

**Home Page:**  
- Header displays name and profile picture  
- Left sidebar contains:

1. **Profile**  
   - Personal Info  
   - Achievements

2. **Attendance**  
   - Accessible by batch (e.g., 2025, 2026, 2027) based on permission

3. **Classroom**  
   - Similar features as student dashboard (assignments, resources, marks, feedback)

4. **Course Detail**  
   - Time table  
   - Course credits  
   - Holidays

**Middle Section:**  
- Displays common messages to students.

---

### Admin Dashboard (Phase 1)
**Login Page**  

**Header Menu:**  
- Departments (e.g., CSE)

**Department Features:**  

1. **Batch Year (Dropdown):**  
   - **Student:**  
     - Search bar  
     - List of students by Sitare email ID  
     - Clicking opens student dashboard  
   - **Teacher:**  
     - Search bar  
     - List of teachers by staff ID  
     - Clicking opens teacher dashboard

---

### Coursework Features (Teacher Controlled)
- Teachers can add coursework with constraints:  
  - Batch, year, credits, and class allocation  
- Teachers can add students to coursework  
- Coursework features on student dashboard:  
  - Study material  
  - Assignments  
  - Discussion forum  
  - Attendance (visible to teacher only)

---

### Project Development Flow
1. **Planning** – Documenting ideas and features (current stage)  
2. **Designing** – Deciding tech stack, database, libraries, and initial features  
3. **Coding** – Implementing the features iteratively  
4. **Testing** – Ensuring functionality and usability  
5. **Deployment** – Launching the portal  
6. **Management** – Maintaining and updating the portal

> Wine is spiling Baby, Be Ready 

