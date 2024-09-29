# Hackathon - September 2024  
## S3 Spartans: Resume Screening Solution  
### Leveraging Power Automate for Automated Resume Processing  

PPT: https://www.canva.com/design/DAGSB5P0kyI/x_eZte_O4V-u1IvuztRjwQ/edit?utm_content=DAGSB5P0kyI&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
Video : https://youtu.be/m5e3ZesSwoU?feature=shared


### Situation  
Organizations often receive numerous resumes via email, making the screening process time-consuming and prone to human error. Our team, S3 Spartans, developed an automated solution using Power Automate to streamline the resume screening process efficiently.

### Task  
The objective was to create a robust and automated pipeline that extracts resumes from emails, processes the data using a trained AI model, and stores the results in a structured format, enhancing the screening process's speed and accuracy.

### Action  

1. **Automated PDF Extraction from Emails**  
   - Emails containing resumes are automatically identified, and PDFs are extracted.
   - The extracted PDFs are then stored in a designated folder in OneDrive after confirming the email contains a valid PDF attachment.

   ![image](https://github.com/user-attachments/assets/a2e64dcc-31e4-40a4-84a6-dde909dfc5d3)

2. **Data Extraction Using AI Model**  
   - A custom AI model, trained on demo forms, extracts key information from the PDF resumes.
   - The model is integrated within Power Automate, ensuring accurate data extraction tailored to the specific requirements of resume screening.

   ![image](https://github.com/user-attachments/assets/e6f8184a-11a0-4a39-afd7-b541a4396893)

3. **Model Training and Integration**  
   - The AI model was rigorously trained and tested within Power Automate to ensure it met the expected performance standards.

   ![image](https://github.com/user-attachments/assets/5f2dbf1c-ade7-4ab2-ae97-afc5d4bf2f48)

4. **Testing and Validation**  
   - The solution was tested through automated replies to the original sender, confirming successful data extraction and processing.

   ![image](https://github.com/user-attachments/assets/3e707d98-afaa-40a9-82d4-c556f425ba0a)

5. **Mapping Extracted Data to Excel**  
   - Extracted data is automatically mapped to a structured Excel format, facilitating easy review and analysis by recruiters.

   ![image](https://github.com/user-attachments/assets/7adc50c6-398c-46ab-9839-acce164a64db)

   ![image](https://github.com/user-attachments/assets/d2fb2a84-ad48-4fba-ac09-7ca8d4334678)

6. **Orchestrated Data Extraction and Form Submission**  
   - A flow was orchestrated to populate the required forms with the extracted data.
   - The process was completed by submitting the forms, ensuring a seamless end-to-end automation workflow.

   ![image](https://github.com/user-attachments/assets/d87e153f-c9b6-45dd-bd63-8cc860c5cfe5)

### Result  
Our solution significantly reduces manual effort and time spent on resume screening. By automating data extraction and processing, organizations can quickly filter and review candidate profiles, improving overall recruitment efficiency.







## Team Mates
Aakashdeep Singh Sedha
-->solution architect
Pranzal Sharma
--> mapping data to excel
Rahul-->Form automate
Ashman Arora -->Ideation
