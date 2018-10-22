Welcome to the Events repo. Information from the included spreadsheet is added to the NIAID Bioinformatics Portal (NBP) database and displayed. https://bioinformatics.niaid.nih.gov/events To update the NBP database:

1. Download the events.xlsx file.
2. Edit the file, adding new event information. Among the fields in the spreadsheet are required fields. These are:

      type      
      title    
      startDate   
      timestamp     
      location    
      eventType     
      videocast    			

   Information about which 'eventTypes' can be used is found in the 'Notes' column. If a required field is left empty, the data will not  be added to the database. The following format is required for startDate and endDate columns: yyyy/mm/dd. The spreadsheet will automatically change to this format.
   
 3. Save the file as a .xslx AND a .csv. (It is the .csv file that is read by the update script. The .xslx file is for user-readability).
 4. Commit them both back to the repo.
 5. Notify Yamil that a commit has been made:  yamil.booirizarry @ nih .gov
