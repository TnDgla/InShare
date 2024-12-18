## **Project Name: InShare**

**InShare** is a web-based file-sharing application designed to make file transfers quick and easy. Built with HTML, CSS, JavaScript, Node.js, and MongoDB, the app enables users to upload files, generate shareable links, and send them via email. The app also features file expiration policies and a modern drag-and-drop interface.

---

### **Mission and Objectives for InShare**

---

### **Mission:**
To provide a secure and user-friendly platform for quick and efficient file sharing, ensuring privacy and ease of use.

---

### **Objectives:**
1. **File Upload and Sharing:**
   - Implement drag-and-drop and manual upload functionalities.
   - Generate shareable links for uploaded files.

2. **Email Integration:**
   - Allow users to send uploaded files via email.

3. **File Expiration and Management:**
   - Set file expiration policies to automatically delete files after a certain period.

4. **Responsive UI Design:**
   - Design an intuitive and responsive interface.

5. **Deployment:**
   - Ensure global accessibility with robust backend services.

---

## **Technology Stack**

### **Frontend**
1. **HTML5 and CSS3:**
   - **Why:** Provide the structure and style for the web app.
   - **Use Case:** Build the user interface and implement responsive design.

2. **JavaScript:**
   - **Why:** Enable interactive and dynamic features.
   - **Use Case:** Manage drag-and-drop functionality and API interactions.

---

### **Backend**
1. **Node.js:**
   - **Why:** Enables scalable and efficient backend development.
   - **Use Case:** Handle server-side logic and file uploads.

2. **Express.js:**
   - **Why:** Simplifies API development.
   - **Use Case:** Create endpoints for file upload, email sending, and link generation.

3. **Multer:**
   - **Why:** Handle file uploads in Node.js.
   - **Use Case:** Process and store uploaded files.

4. **Nodemailer:**
   - **Why:** Send emails programmatically.
   - **Use Case:** Enable users to send file links via email.

5. **Cron:**
   - **Why:** Schedule tasks for file deletion.
   - **Use Case:** Automatically delete expired files.

---

### **Database**
1. **MongoDB:**
   - **Why:** Provide a flexible schema for file metadata and tracking.
   - **Use Case:** Store file information, user data, and expiration details.

2. **Mongoose:**
   - **Why:** Simplify database interactions through schemas.
   - **Use Case:** Manage CRUD operations for file metadata.

---

### **Deployment**
1. **Frontend Hosting:** Netlify or Vercel
   - **Why:** Optimized platforms for web app hosting.
   - **Use Case:** Deploy the client-side application.

2. **Backend Hosting:** Heroku
   - **Why:** Reliable hosting for backend services.
   - **Use Case:** Deploy APIs and handle file uploads.

---

## **Workflow Overview**
This section outlines the interaction between users and the application:
1. **File Upload:** Upload files via drag-and-drop or file input.
2. **Link Generation:** Generate a unique shareable link for each file.
3. **Email Sharing:** Send the file link via email using the integrated SMTP service.
4. **File Expiration:** Automatically delete files after a set period.

---

### **System Architecture**
The InShare Web App architecture demonstrates the interaction between the frontend, backend, database, and third-party services like SMTP for email.

---

## **Week-by-Week Plan**

### **Week 1: Project Setup and Basic Structure**
- **Goal:** Set up the foundational structure for InShare.
- **Tasks:**
  1. Install Node.js, MongoDB, and Visual Studio Code.
     - **Reading:** [Node.js Setup](https://nodejs.org/en/download/)  
     - **Video:** [Setting Up Node.js and MongoDB](https://www.youtube.com/watch?v=TlB_eWDSMt4)
  2. Create a basic HTML layout.
     - **Reading:** [HTML Basics](https://www.w3schools.com/html/)  
     - **Video:** [HTML Tutorial](https://www.youtube.com/watch?v=BsDoLVMnmZs)
  3. Set up Express.js for the backend.
     - **Reading:** [Express.js Basics](https://expressjs.com/)  
     - **Video:** [Express.js Setup](https://www.youtube.com/watch?v=L72fhGm1tfE)

- **Deliverables:**
  - Basic project structure with a running server and frontend.

---

### **Week 2: File Upload Functionality**
- **Goal:** Enable users to upload files and monitor progress.
- **Tasks:**
  1. Integrate Multer for file uploads.
     - **Reading:** [Multer Documentation](https://github.com/expressjs/multer)  
     - **Video:** [Handling File Uploads](https://www.youtube.com/watch?v=srPXMt1Q0nY)
  2. Design a drag-and-drop interface.
     - **Reading:** [HTML Drag-and-Drop API](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API)  
     - **Video:** [Drag-and-Drop Tutorial](https://www.youtube.com/watch?v=4AHot187Lj0)
  3. Implement a file upload progress bar.
     - **Reading:** [CSS Progress Bar](https://www.w3schools.com/w3css/w3css_progressbar.asp)  
     - **Video:** [Creating a Progress Bar](https://www.youtube.com/watch?v=basf1lH1H-E)

- **Deliverables:**
  - Functional drag-and-drop file upload system with a progress bar.

---

### **Week 3: Link Generation and Email Integration**
- **Goal:** Generate shareable links and integrate email functionality.
- **Tasks:**
  1. Create unique URLs for uploaded files.
     - **Reading:** [Node.js URL Module](https://nodejs.org/api/url.html)  
     - **Video:** [Working with URLs in Node.js](https://www.youtube.com/watch?v=xZhc9wW7sI4)
  2. Use Nodemailer for sending email links.
     - **Reading:** [Nodemailer Docs](https://nodemailer.com/about/)  
     - **Video:** [Nodemailer Tutorial](https://www.youtube.com/watch?v=u-_Ygo2wcrs)
  3. Add a copy-to-clipboard feature for file links.
     - **Reading:** [Clipboard API Docs](https://developer.mozilla.org/en-US/docs/Web/API/Clipboard_API)  
     - **Video:** [Clipboard API Usage](https://www.youtube.com/watch?v=hoXKylYuaVc)

- **Deliverables:**
  - Shareable link generation and email functionality.

---

### **Week 4: File Expiration and Deletion**
- **Goal:** Automatically delete expired files.
- **Tasks:**
  1. Set up file expiration policies using Cron.
     - **Reading:** [Node-Cron Docs](https://www.npmjs.com/package/node-cron)  
     - **Video:** [Task Scheduling with Node.js](https://www.youtube.com/watch?v=1aDXp7OE4cM)
  2. Implement backend logic to delete expired files from MongoDB.
     - **Reading:** [MongoDB Deletion](https://www.mongodb.com/docs/manual/reference/method/db.collection.deleteMany/)  
     - **Video:** [MongoDB CRUD Operations](https://www.youtube.com/watch?v=Fg8T4Yg0ZZw)

- **Deliverables:**
  - Scheduled file deletion functionality.

---

### **Week 5: Deployment**
- **Goal:** Deploy the InShare web app and ensure global accessibility.
- **Tasks:**
  1. Deploy the backend to Heroku.
     - **Reading:** [Deploying Node.js Apps](https://devcenter.heroku.com/articles/deploying-nodejs)  
     - **Video:** [Heroku Deployment Guide](https://www.youtube.com/watch?v=9kLR4pqzkQU)
  2. Deploy the frontend to Netlify or Vercel.
     - **Reading:** [Netlify Deployment](https://docs.netlify.com/)  
     - **Video:** [Deploying on Netlify](https://www.youtube.com/watch?v=8lGpZkjnkt4)
  3. Test the application for performance and bugs.
     - **Reading:** [Testing Web Applications](https://www.w3schools.com/js/js_validation.asp)  
     - **Video:** [Testing Web Apps](https://www.youtube.com/watch?v=8Xwq35cPwYg)

- **Deliverables:**
  - Fully deployed and tested InShare web app.

---

### Screenshots
![demo gif](https://github.com/ShivamJoker/GIF-Demos/raw/master/inshare%20demo.gif)

---

### **References:**
1. [HTML Basics](https://www.w3schools.com/html/)
2. [CSS Progress Bars](https://www.w3schools.com/howto/howto_css_progressbar.asp)
3. [Node.js Documentation](https://nodejs.org/en/)
4. [Express.js Documentation](https://expressjs.com/)
5. [MongoDB Docs](https://www.mongodb.com/docs/manual/)
6. [Multer GitHub](https://github.com/expressjs/multer)
7. [Nodemailer Docs](https://nodemailer.com/about/)
8. https://www.youtube.com/watch?v=CwnViYV4gM0
9. https://github.com/ShivamJoker/inshare

