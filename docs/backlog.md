# Product Backlog – NCMF File Management System

## User Stories

---

### US-01
**As a user, I want to register an account so that I can access the system.**  
**Priority:** High | **Story Points:** 5  
**Acceptance Criteria:**
- User can input valid registration details  
- System validates input fields  
- Account is successfully created in database  

---

### US-02
**As a user, I want to log in so that I can access my dashboard.**  
**Priority:** High | **Story Points:** 5  
**Acceptance Criteria:**
- User enters correct credentials  
- System authenticates user securely  
- User is redirected to dashboard  

---

### US-03
**As a user, I want to upload files so that I can store documents.**  
**Priority:** High | **Story Points:** 8  
**Acceptance Criteria:**
- File uploads successfully  
- System validates file type and size  
- File is stored in the correct directory  

---

### US-04
**As a user, I want to download files so that I can retrieve my documents.**  
**Priority:** High | **Story Points:** 5  
**Acceptance Criteria:**
- User can select a file  
- File downloads without corruption  
- Download completes within reasonable time  

---

### US-05
**As a user, I want to delete files so that I can manage storage.**  
**Priority:** Medium | **Story Points:** 3  
**Acceptance Criteria:**
- User selects file to delete  
- System asks for confirmation  
- File is permanently removed  

---

### US-06
**As an admin, I want to manage users so that I can control system access.**  
**Priority:** High | **Story Points:** 8  
**Acceptance Criteria:**
- Admin can view user list  
- Admin can add/edit/delete users  
- Changes reflect immediately  

---

### US-07
**As a system, I want to restrict file types so that unsafe files are blocked.**  
**Priority:** High | **Story Points:** 5  
**Acceptance Criteria:**
- Blocked file types cannot be uploaded  
- User receives error message  
- Allowed file types upload successfully  

---

### US-08
**As a user, I want to rename files so that I can organize my documents.**  
**Priority:** Medium | **Story Points:** 3  
**Acceptance Criteria:**
- User selects file  
- User inputs new name  
- File name updates correctly  

---

### US-09
**As a user, I want division-based file access so that only authorized users can view files.**  
**Priority:** High | **Story Points:** 8  
**Acceptance Criteria:**
- Files are tagged by division  
- Users only see files assigned to their division  
- Unauthorized access is blocked  

---

### US-10
**As an admin, I want to enable or disable registration so that I can control onboarding.**  
**Priority:** Medium | **Story Points:** 3  
**Acceptance Criteria:**
- Admin can toggle registration setting  
- Registration form is enabled/disabled accordingly  
- Changes apply immediately  