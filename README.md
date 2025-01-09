
# Teacher Student Management System (TSMS)

[Visit : TSMS](https://tsms-fe.vercel.app/)

A Teacher Student Management System for managing notes, attendance, internal marks, and schedules.

## Roles and Login Credentials

### Teacher (Staff)

- **Username:** Delphine  
- **Password:** Delphine123  

Teacher can:

- Add or edit Notes
- Manage Attendance
- Update Internal Marks
- Create and edit Time Schedules

### HOD (Head of Department)

- **Username:** Moriah  
- **Password:** Moriah123  

HOD has all the permissions of a Teacher and can additionally:

- Approve new Teacher registrations
- Add new Subjects (Papers)

### Student

- **Username:** Bret  
- **Password:** Bret  

Or register as a new student to create your own account.  
Students can:

- View Notes
- Check Attendance and Internal Marks (added by Teachers)
- Join or leave Subjects (Papers)

---

## Tech Stack

- **Frontend:** React, TailwindCSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB, Mongoose  

---

## Features

- User roles: Teacher, HOD, and Student
- Dark mode for improved accessibility
- Mobile responsive design for seamless usage across devices
- Profile management for all users

---

## How to Set Up Locally

Clone the project:

\`\`\`bash
git clone https://github.com/sahuashish940/tsms.git
\`\`\`

Change directory:

\`\`\`bash
cd TSMS
\`\`\`

Install dependencies:

\`\`\`bash
npm install
\`\`\`

Run the application:

\`\`\`bash
npm start
\`\`\`

To use your own backend server, update the base URL in \`src/config/api/axios.js\`:

\`\`\`javascript
baseURL: "http://localhost:3500";
\`\`\`

---

## Roadmap

- Add admin functionality
- Implement query caching
- Add pagination for queries

---

## Contact

I’m always open to feedback and suggestions to improve this project! Feel free to reach out:

- **LinkedIn:** [Ashish sahu](https://www.linkedin.com/in/ashishsahudev)  
- **Email:** [sahuashish940@gmail.com](mailto:sahuashish940@gmail.com)  

Thank you for your support! ❤️  

---
