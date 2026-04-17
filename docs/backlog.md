# Product Backlog – NCMF File Management System

## Overview
This backlog defines prioritized user stories for the NCMF Region X File Management System, focused on secure document handling, role-based access, and operational efficiency.

---

## Backlog Items

| ID    | User Story                                                                                | Priority | Story Points | Acceptance Criteria                                                |
|----   |-------------------------------------------------------------------------------------------|----------|--------------|--------------------------------------------------------------------|
| US-01 | As a user, I want to register an account so I can access the system                       | High     | 5            | User can register with valid credentials and is stored in database |
| US-02 | As a user, I want to login securely so I can access my dashboard                          | High     | 5            |User login is authenticated and session is created                  |
| US-03 | As a user, I want to upload files so I can store documents                                | High     | 8            | File uploads successfully with validation                          |
| US-04 | As a user, I want to download files so I can retrieve documents                           | High     | 5            | Files download without corruption                                  |
| US-05 | As a user, I want to delete files so I can manage storage                                 | Medium   | 3            | File is permanently removed                                        |
| US-06 | As an admin, I want to manage users so I can control access                               | High     | 8            | Admin can create, update, delete users                             |
| US-07 | As a system, I want to restrict file types so unsafe uploads are blocked                  | High     | 5            | Blocked extensions (.exe, .bat) are rejected                       |
| US-08 | As a user, I want to rename files so I can organize content                               | Medium   | 3            | File name updates correctly                                        |
| US-09 | As a user, I want division-based file access so only authorized users can view files      | High     | 8            | Files are visible only to assigned divisions                       |
| US-10 | As an admin, I want to enable/disable registration so I can control onboarding            | Medium   | 3            | Registration toggle works in settings                              |
| US-11 | As a system, I want duplicate file detection so files are not overwritten unintentionally | Medium   | 5            | Duplicate names trigger rename or replace option                   |
| US-12 | As a user, I want to view file details so I can see metadata                              | Low      | 2            | File info displays correctly                                       |