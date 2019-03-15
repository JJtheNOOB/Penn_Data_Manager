# Radation Oncology Data Manager
# Work Procedure

**Monthly Upgrade Procedure** 
 - REDCap Study Level Database update (Anytime during the month)
    - Log into REDCap & PennCTMS
    - Follow studies in the REDCap Database and update the study status, study accurals
    - Check any new studies from PennCTMS and append them into the REDCap system
       - The red sign means that the study is closed: No update needed
       - The yellow sign means that the study status might change: Check needed
       - The green sign means that the study is active: Check needed
      
 - Research Dashboard (Before second Tuesday of each month)
    - current version updated 3/15/2019, submission to Susan via Powerpoint / Print
    - Department overlook (Page 1)
      - Open / active / non-retrospective studies only (Get information from PennCTMS - QuickReport)
      - list by study type (If you are not sure what the type is, please email Susan)
    - Patients accumulation by study types --2013 to now (Page 2)
      - Get patient information from PennCTMS
      - Merge patient information with studies from the last step by IRB / UPCC number (Use R, Python etc.)
    - Patient enrollment -- 2013 to now (Page 3)
      - Get information from PennCTMS
      - Exlude patient whose status is "Failed Post Screening: Non-eligible"
    - Patient enrollment by physician (Page 4)
      - Get information from REDCap
      - Update monthly (do not accumulate data)
      
  **Randomizations**
   - Folder located at H drive -> Randomization
   - Current:
     - Bladder RadVax (Former Dana)
     - MPM 2 (Sally)
     - TACE (Sally)
     - Vancomycin (Chrissy & Ellen)
     - Report back to the sender along with randomization information
    
  **Data Query Request**
   - Ask Pete Gabriel for access into the database
   - Download and use SSMS (Sql Server Management Studio)
   - Login with your info
   - Navigate to ORQID Datamart
   
   
   
   
   
