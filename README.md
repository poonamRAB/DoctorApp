# DoctorApp
------
## Framework and Language used
  + Springboot
  + JAVA
-------
## Data Flow
  + controller
      - AdminController
      - AppointmentController
      - DoctorController
      - PatientController
  + model
      + dto
        - SignInInput
        - SignUpOutput
      + enums
          - Gender
          - Qualification
          - Specialization
      - Admin
      - Appointment
      - AuthenticationToken
      - Doctor
      - Patient
  + repository
      - IAdminRepo
      - IAppointmentRepo
      - IAuthTokenRepo
      - IDoctorRepo
      - IPatientRepo
  + service
      - AdminService
      - AppointmentService
      - AuthenticationService
      - DoctorService
      - PatientService
  + DoctorAppApplication(main class)

-------
## Data Structure used
  + List
--------
## Project Summary 
This is a Doctor Application project which can be used for medical purppose. Sometimes going to hospital and make appointment, it takes time.
Using this application patient can fix the appointment with doctor, patient also cal fetch details about the doctor. Also doctor can know about 
the patient details. Using mail Id patient can sign up, if somehow patient lost login data uaing Authentication token patient can sign in.
Doctor can make sure how many follow -ups he/she need take.
