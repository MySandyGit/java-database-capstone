# User Story Template

**Title:**
_As a [user role], I want [feature/goal], so that [reason]._

**Acceptance Criteria:**
1. [Criteria 1]
2. [Criteria 2]
3. [Criteria 3]

**Priority:** [High/Medium/Low]
**Story Points:** [Estimated Effort in Points]
**Notes:**
- [Additional information or edge cases]


# Admin User Stories

**1. Admin Login**
    As an admin, I want to log in securely to access the management portal
    
**Acceptance criteria:**: Redirect on success, error on failure, secure cookie
    
**Story Points:** High
    
**Story Points:** 3

[Top](#admin-user-stories)

---
    

**2. Admin Logout**
    As an admin, I want to log out to protect system access

**Acceptance Criteria:** Session termination, redirect to login

**Story Points:** High

**Story Points:** 2

[Top](#admin-user-stories)

---


**3. Add Doctor**
    As an admin, I want to add doctors to the system

**Acceptance Criteria:** DB record created, success alert, form validation

**Story Points:** High

**Story Points:** 5

[Top](#admin-user-stories)

---


**4. Delete Doctor**
    As an admin, I want to remove doctors from the system

**Acceptance Criteria:** DB removal, cascade delete, confirmation dialog

**Story Points:** High

**Story Points:** 5

[Top](#admin-user-stories)

---


**5. Monthly Reports**
    As an admin, I want to generate appointment statistics

**Acceptance Criteria:** CLI procedure works, handles nulls, audit logging

**Story Points:** Medium

**Story Points:** 8

[Top](#admin-user-stories)

---


**6. Password Reset**
    As an admin, I want to reset doctor passwords

**Acceptance Criteria:** Temp password generation, email notification, expiration

**Story Points:** Medium

**Story Points:** 5

[Top](#admin-user-stories)

---


**7. Audit Logs**
    As an admin, I want to view system activity logs

**Acceptance Criteria:** Filterable table, pagination, no reload needed

**Story Points:** Medium

**Story Points:** 8

[Top](#admin-user-stories)

---


**8. Patient Account Control**
    As an admin, I want to enable/disable patient accounts

**Acceptance Criteria:** Login blocking, status persistence, confirmation

**Story Points:** Medium

**Story Points:** 3

[Top](#admin-user-stories)

---


**9. Bulk Import**
    As an admin, I want to CSV-import multiple doctors

**Acceptance Criteria:** Data validation, summary report, welcome emails

**Story Points:** Medium

**Story Points:** 8

[Top](#admin-user-stories)

---


**10. System Health**
    As an admin, I want real-time performance monitoring

**Acceptance Criteria:** Auto-refresh data, visual charts, threshold alerts

**Story Points:** Low

**Story Points:** 13

[Top](#admin-user-stories)

---


**1. Cross-DB Search**
    As an admin, I want unified patient record search

**Acceptance Criteria:** Fast results, term highlighting, PDF export

**Story Points:** Low

**Story Points:** 8

[Top](#admin-user-stories)


# Doctor User Stories

**1. Doctor Login**
As a doctor, I want to securely log in to manage my appointments.  


**Acceptance Criteria**:

    1.  Two-factor authentication (SMS/Email code)
        
    2.  Redirect to dashboard upon success
        
    3.  Show "Invalid credentials" for failed attempts 
    
**Priority**:: High  
**Story Points**: 5  
**Notes**: Session expires after 30 minutes of inactivity
    
[Top](#doctor-user-stories)

---

**2. Appointment Calendar**
As a doctor, I want to view my daily/weekly appointments.  

**Acceptance Criteria**:

    1.  Color-coded by appointment type
        
    2.  Sync with Google Calendar/Outlook
        
    3.  Show patient name and chief complaint  
    
**Priority**:: High  
**Story Points**: 8  
**Notes**: Supports drag-and-drop rescheduling
    
    
[Top](#doctor-user-stories)

---

**3. Availability Management**
As a doctor, I want to mark unavailable time slots.  

**Acceptance Criteria**:

    1.  Block single/multiple days
        
    2.  Set recurring unavailability
        
    3.  Auto-reject appointments during blocked slots  
    
**Priority**:: High  
**Story Points**: 8  
**Notes**: 24-hour notice for changes
    
    
[Top](#doctor-user-stories)

---

**4. Profile Updates**
As a doctor, I want to edit my specialization and contact details.  

**Acceptance Criteria**:

    1.  Edit bio, specialties, and clinic hours
        
    2.  Upload new profile photo
        
    3.  Changes reflect immediately  
    
**Priority**:: Medium  
**Story Points**: 5  
**Notes**: Admin approval for specialty changes
    
    
[Top](#doctor-user-stories)

---

**5. Patient Details Preview**
As a doctor, I want to view patient profiles before appointments.  

**Acceptance Criteria**:

    1.  See medical history/allergies
        
    2.  Access uploaded documents
        
    3.  One-click contact options  
    
**Priority**:: High  
**Story Points**: 5  
**Notes**: HIPAA-compliant data masking
    
    
[Top](#doctor-user-stories)

---

**Additional Stories**
----------------------

**6. Appointment Notes**
As a doctor, I want to add clinical notes post-consultation.  

**Acceptance Criteria**:

    1.  Rich text editor with templates
        
    2.  Auto-save every 2 minutes
        
    3.  Attach to patient's permanent record  
    
**Priority**:: High  
**Story Points**: 5  
**Notes**: SOAP note format supported
    
    
[Top](#doctor-user-stories)

---

**7. Billing Integration**
As a doctor, I want to generate invoices for consultations.  

**Acceptance Criteria**:

    1.  Pre-filled with appointment details
        
    2.  Add procedure codes (CPT/ICD-10)
        
    3.  Send PDF to patient email  
    
**Priority**:: Medium  
**Story Points**: 8  
**Notes**: Integrates with QuickBooks
    
    
[Top](#doctor-user-stories)

---

**8. Lab Results Review**
As a doctor, I want to view patient lab reports.  

**Acceptance Criteria**:

    1.  Flag abnormal values in red
        
    2.  Compare with previous results
        
    3.  Add interpretations/comments  
    
**Priority**:: Medium  
**Story Points**: 8  
**Notes**: Supports HL7/FHIR standards
    
    
[Top](#doctor-user-stories)

---

**9. Mobile Notifications**
As a doctor, I want appointment alerts on my phone.  

**Acceptance Criteria**:

    1.  Push notifications for:
        
        *   New bookings
            
        *   Cancellations
            
        *   15-min pre-appointment reminders
            
    2.  Configurable quiet hours  
    
**Priority**:: Medium  
**Story Points**: 5  
**Notes**: Uses Firebase Cloud Messaging
    
    
[Top](#doctor-user-stories)

---

**10. Patient Messaging**
As a doctor, I want to securely message patients.  

**Acceptance Criteria**:

    1.  Encrypted chat interface
        
    2.  File/image sharing
        
    3.  Read receipts  
    
**Priority**:: Low  
**Story Points**: 8  
**Notes**: Auto-archives after 30 days
    
    
[Top](#doctor-user-stories)

---

**Bonus Stories**
-----------------

**11. e-Prescription Writing**
As a doctor, I want to digitally prescribe medications.  

**Acceptance Criteria**:

    1.  Search medication database
        
    2.  Set dosage/refill instructions
        
    3.  Send to pharmacy electronically  
    
**Priority**:: Medium  
**Story Points**: 8  
**Notes**: Requires digital signature
    
    
[Top](#doctor-user-stories)

---

**12. Telemedicine Room**
As a doctor, I want to conduct virtual consultations.  

**Acceptance Criteria**:

    1.  Video/audio call functionality
        
    2.  Screen sharing
        
    3.  Virtual waiting room  
    
**Priority**:: Medium  
**Story Points**: 13  
**Notes**: Bandwidth optimization

[Top](#doctor-user-stories)

---


# Patient User Stories

**1. Browse Doctors (Public)**
As a patient, I want to view doctors list without logging in, so I can explore options before registering. 

**Acceptance Criteria**:

    1. Show specialty filters (Cardiology, Pediatrics, etc.)

    2. Display doctor names, photos, and ratings

    3. Paginate results (10 doctors/page)  
**Priority**: High  
**Story Points**: 3  
**Notes**:
* Cache results for 1 hour to reduce DB load
    
[Top](#patient-user-stories)

---

**2. Patient Registration**
As a patient, I want to sign up with email/password, so I can book appointments. 

**Acceptance Criteria**:

    1.  Validate email format and password strength

    2.  Send confirmation email with verification link
        
    3.  Create patient profile in MySQL  
   
**Priority**: High  
**Story Points**: 5  
**Notes**:
* Password must be 8+ chars with special characters

[Top](#patient-user-stories)

---

**3. Patient Login**
As a patient, I want to log in securely, so I can manage my bookings.  

**Acceptance Criteria**:

    1. Authenticate via email/password
      
    2. Show "Forgot Password" option
      
    3. Redirect to dashboard on success  

**Priority**: High  
**Story Points**: 3  
**Notes**:
*   Lock account after 5 failed attempts
    

[Top](#patient-user-stories)

---

**4. Book Appointment**
As a patient, I want to book a 1-hour appointment, so I can consult a doctor. 

**Acceptance Criteria**:

    1.  Show available slots in calendar UI
        
    2.  Prevent double-booking of slots
        
    3.  Send confirmation email with ICS attachment  
   
**Priority**: High  
**Story Points**: 8  
**Notes**:
*   Integrate with doctor's working hours
    

[Top](#patient-user-stories)

---

**5. View Upcoming Appointments**
As a patient, I want to see my scheduled visits, so I can prepare.  

**Acceptance Criteria**:

    1.  List appointments sorted by date
        
    2.  Show doctor details and purpose of visit
        
    3.  Include "Cancel" button (24h+ in advance)  

**Priority**: Medium  
**Story Points**: 5  
**Notes**:
*   Gray out past appointments
    

[Top](#patient-user-stories)

---

**6. Patient Logout**
As a patient, I want to log out, so my account stays secure.  

**Acceptance Criteria**:

    1.  Invalidate session immediately
        
    2.  Redirect to public doctor search page
        
    3.  Show "Logged out successfully" toast  

**Priority**: Medium  
**Story Points**: 2  
**Notes**:
*   Clear client-side JWT tokens
    

[Top](#patient-user-stories)

---

**7. View Prescription History**
As a patient, I want to see past prescriptions, so I can track medications.  

**Acceptance Criteria**:

    1.  Fetch MongoDB prescription records
        
    2.  Display in reverse chronological order
        
    3.  Allow PDF download  

**Priority**: Medium  
**Story Points**: 5  
**Notes**:
*   Blur sensitive data in preview mode
    

[Top](#patient-user-stories)

---

**8. Telemedicine Join**

**Title**: As a patient, I want to join virtual consultations, so I can attend appointments remotely.

**Acceptance Criteria**:

    1.  "Join Call" button appears 5 mins before appointment
        
    2.  WebRTC video connection establishes successfully
        
    3.  Show connection quality indicators  

**Priority**: High  
**Story Points**: 8  
**Notes**:
*   Fallback to audio-only if bandwidth low
    

[Top](#patient-user-stories)

---

**9. Reschedule Appointments**

**Title**: As a patient, I want to reschedule bookings, so I can adjust my availability. 

**Acceptance Criteria**:

    1.  Display available alternative slots
        
    2.  Send notification to doctor about change
        
    3.  Update original appointment in database  

**Priority**: Medium  
**Story Points**: 5  
**Notes**:
*   Limit to 2 reschedules per appointment
    

[Top](#patient-user-stories)

---

**10. Health Records Upload**

**Title**: As a patient, I want to upload medical reports, so doctors can review them pre-consultation. 

**Acceptance Criteria**:

    1.  Accept PDF/JPG/PNG (max 10MB)
        
    2.  Show upload progress indicator
        
    3.  Auto-categorize by document type  

**Priority**: Medium  
**Story Points**: 5  
**Notes**:
*   OCR for lab result extraction
    

[Top](#patient-user-stories)

---

**11. Prescription Refill Request**

**Title**: As a patient, I want to request medication refills, so I don't run out of essentials.  

**Acceptance Criteria**:

    1.  Button on past prescriptions
        
    2.  Form pre-filled with medication details
        
    3.  Send notification to prescribing doctor  

**Priority**: Low  
**Story Points**: 3  
**Notes**:
*   Auto-approve for chronic medications
    

[Top](#patient-user-stories)

---

**12. Emergency Contact Setup**

**Title**: As a patient, I want to designate emergency contacts, so staff can notify them if needed. 

**Acceptance Criteria**:

    1.  Add multiple contacts with relationships
        
    2.  Verify contact phone/email
        
    3.  Badge in patient profile  

**Priority**: Low  
**Story Points**: 3  
**Notes**:

*   GDPR consent required
    
[Top](#patient-user-stories)

---

---
