# examensarbete-js23-mambyly-logistics

![Logo](mambyLyLogoDef.png)  

## 📌 Repositories  

- **Frontend**: [MambyLy Logistics Frontend](https://github.com/Emadenni/MambyLy-logistics-frontend.git)  
- **Backend**: [MambyLy Logistics Backend](https://github.com/Emadenni/MambyLy-logistics-backend.git)  


## 🌍 About the Project  

**MambyLy Logistics** is a small logistics company offering transportation and digital services.  
This web application consists of **five public pages** and a **dedicated admin section**.  

### 🔹 Public Section  
- Users can send messages to the company for **service inquiries**.  
- A **job application section** allows candidates to apply and submit their **CVs**.  

🔹 **Admin Section**  
Administrators can:  
- Add, edit, and remove other admins.  
- Access and manage received messages (messages can also be deleted).  
- Post and manage open job positions.  


### 🔒 How to Access the Admin Page  
- The **admin page link** is  a **small lock icon** at the **bottom right corner** of the footer.  
- To access it, use the following credentials:  

  ```json
  {
    "email": "visitor@test.com",
    "password": "javascript23%"
  }

## 📖 Documentation  
[API Documantation avaible here](https://documenter.getpostman.com/view/34011859/2sB2cPk6FU)

## 🛠️ Technologies Used  
- **Frontend**: React + TypeScript  
- **Backend**: AWS Lambda, API Gateway, Serverless Framework  
- **Database**: DynamoDB  
- **Storage**: S3 Bucket  
- **Hosting**: S3 + CloudFront

  ## 🚀 Improvements & To-Do List  

### 🔧 Bugs & Issues  
- [ ] **Job positions**: Does not accept job positions with spaces.  
- [ ] **Silent errors**: No error message is shown when a service is not accepted.  
- [ ] **Admin addition**: Avoid full page reload when adding an admin.  
- [ ] **General error handling**: Improve the way errors are managed and displayed.  

### 🌟 Enhancements  
- [ ] **Frontend styling**: Improve the UI/UX of the platform.  
- [ ] **About Us page**: Enhance design and readability.  
- [ ] **Contact forms**: Improve the layout and validation for better user experience.  
- [ ] **Optimize rendering**: Reduce unnecessary component re-renders to improve performance.  
- [ ] **Component refactoring**: Split overly long components into smaller, reusable ones.  
- [ ] **Improve profile image upload**: Make the current method more performant.  
- [ ] **Better use of global state (Zustand)**: Expand the use of global variables beyond `useOut`, `stateOut`, and `isMobile`.  

---

More tasks will be added as needed. Feel free to contribute!  


## 👨‍💻 Installation  
Instructions to clone and run the project locally.  

```bash
git clone https://github.com/your-username/frontend-repo.git
cd frontend-repo
npm install
npm start
