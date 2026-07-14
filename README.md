# ServiceNow_Internship_2026
Automated Employee Onboarding &amp; Off boarding System
# Employee Lifecycle Management System (ServiceNow)


## Demo link : https://drive.google.com/file/d/1U6M-bY2Xq2ZCCCOcQ4Wv4V9Y3PPq5BS-/view?usp=sharing


## 📌 Project Overview

The **Employee Lifecycle Management System** is a ServiceNow-based automation solution that streamlines the complete employee journey within an organization, from onboarding to offboarding.

The system automates approval workflows, task creation, employee status tracking, and notifications to reduce manual effort and improve operational efficiency.

---

# 🎯 Objectives

- Automate employee onboarding and offboarding processes
- Reduce manual HR and IT coordination
- Provide approval-based workflow automation
- Track employee lifecycle activities
- Improve process visibility and compliance

---

# 🚀 Features

## 1. Employee Onboarding Automation

The onboarding workflow manages the process of adding a new employee to the organization.

### Workflow Flow

```
Employee Onboarding Request Created
              |
              ↓
Approval Request Generated
              |
              ↓
Manager/Admin Approval
              |
              ↓
Update Employee Status
              |
              ↓
Create Onboarding Tasks
              |
              ↓
Send Notification
```

### Key Features

- Employee onboarding request creation
- Approval-based onboarding process
- Employee information management
- Automated status updates
- Task generation after approval
- Notification automation

---

# 2. Employee Offboarding Automation

The offboarding workflow manages the employee exit process in a secure and structured way.

### Workflow Flow

```
Employee Offboarding Request Created
              |
              ↓
Approval Request Generated
              |
              ↓
Approval Decision
              |
              ↓
Update Offboarding Status
              |
              ↓
Create Exit Tasks
              |
              ↓
Send Notification
```

### Key Features

- Employee exit request management
- Approval workflow automation
- IT access removal tracking
- Asset recovery process
- HR clearance management
- Automated notifications

---

# 🏗️ System Architecture

```
                 Employee Lifecycle Management System

                              |
              ------------------------------------
              |                                  |
              ↓                                  ↓

     Employee Onboarding              Employee Offboarding

              |                                  |

              ↓                                  ↓

       Approval Workflow               Approval Workflow

              |                                  |

              ↓                                  ↓

       Automated Tasks                Automated Tasks

              |                                  |

              ↓                                  ↓

        Notifications                 Notifications
```

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| ServiceNow | Enterprise workflow automation platform |
| Workflow Studio | Flow development and management |
| Flow Designer | Process automation |
| ServiceNow Tables | Data storage and management |
| Notifications | Automated communication |

---

# 📂 Data Model

## Employee Onboarding Table

Stores employee joining details.

### Fields

- Employee Name
- Employee Email
- Department
- Designation
- Manager
- Joining Date
- Laptop Required
- Phone Required
- Status
- Approval Status

---

## Employee Offboarding Table

Stores employee exit details.

### Fields

- Employee Name
- Employee Email
- Department
- Manager
- Last Working Date
- Reason for Leaving
- Status
- Approval Status

---

# ⚙️ Workflow Implementation

## Employee Onboarding Flow

### Trigger

```
Record Created
```

### Actions

1. Ask For Approval
2. Validate Approval Status
3. Update Employee Record
4. Create Required Tasks
5. Send Notification


---

## Employee Offboarding Flow

### Trigger

```
Record Created
```

### Actions

1. Ask For Approval
2. Validate Approval Status
3. Update Offboarding Record
4. Create IT Access Removal Task
5. Create Asset Recovery Task
6. Create HR Clearance Task
7. Send Notification

---

# 🔄 Process Flow

## Onboarding Lifecycle

```
New Employee Request
        |
        ↓
Approval Pending
        |
        ↓
Approved
        |
        ↓
IT & HR Tasks Created
        |
        ↓
Employee Onboarded
```

---

## Offboarding Lifecycle

```
Employee Exit Request
        |
        ↓
Approval Pending
        |
        ↓
Approved
        |
        ↓
Access Removal
        |
        ↓
Asset Recovery
        |
        ↓
Exit Completed
```

---

# 📊 Business Benefits

- Reduces manual HR operations
- Improves employee experience
- Ensures secure employee exits
- Provides workflow transparency
- Maintains approval history
- Improves organizational efficiency

---

# 🔐 Security & Compliance

- Approval-based processing
- Controlled employee data handling
- Audit-friendly workflow execution
- Process tracking and visibility

---

# 🧪 Testing

## Onboarding Testing

1. Create Employee Onboarding record
2. Submit approval request
3. Approve request
4. Verify status update
5. Check flow execution


## Offboarding Testing

1. Create Employee Offboarding record
2. Submit approval request
3. Approve request
4. Verify task creation
5. Check notification execution

---

# 🚀 Future Enhancements

- AI-based onboarding assistant
- Automatic account provisioning
- Active Directory integration
- Employee self-service portal
- SLA monitoring
- Analytics dashboard
- HR system integrations

---

# ✅ Project Status

✔ Employee Onboarding Workflow Completed  
✔ Employee Offboarding Workflow Completed  
✔ Approval Automation Completed  
✔ Task Automation Completed  
✔ Notification Automation Completed  

---

# 📌 Project Title

## Employee Lifecycle Management System Using ServiceNow Workflow Automation
