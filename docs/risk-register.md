# Risk Register – NCMF File Management System

| ID | Risk                     | Likelihood        | Impact | Score | Mitigation                          | Owner    |
|----|--------------------------|-------------------|--------|-------|-------------------------------------|----------|
| R1 | Unauthorized file access | 4                 | 5      | 20    | Implement role-based access control | Security |
| R2 | Data loss                | 3                 | 5      | 15    | Automated backups                   | DevOps   |
| R3 | File upload failure      | 3                 | 4      | 12    | Validation + retry logic            | Backend  |
| R4 | Duplicate file overwrite | 4                 | 4      | 16    | Rename or replace prompt            | Backend  |
| R5 | System downtime          | 3                 | 5      | 15    | Cloud hosting + monitoring          | DevOps   |
| R6 | Poor UI responsiveness   | 2                 | 3      | 6     | Responsive design testing           | Frontend |
| R7 | Malware file upload      | 4                 | 5      | 20    | Restrict file types                 | Security |
| R8 | Performance issues       | 3                 | 4      | 12    | Optimize queries                    | Backend  |