📩 Outlook Email Automation using UiPath & Generative AI
🌍 Overview
This project automates email classification and key-value extraction using UiPath RPA and Generative AI (GenAI). The automation:
✅ Classifies incoming emails as Shipper, Carrier, or Other.
✅ Extracts key-value pairs from email content in a structured format.
✅ Stores extracted data in a database for further processing.
✅ Moves processed emails to their specific folders in Outlook based on classification.

🔄 Process Workflow
📌 1. Email Classification using Generative AI
🚀 Implemented UiPath GenAI Activities to classify incoming emails into predefined categories:
✔️ Shipper
✔️ Carrier
✔️ Other

🔍 AI-based classification ensures higher accuracy than traditional keyword-based methods.

📜 2. Structured Email Body Extraction
📥 Extracted the email body in a clean and structured format for better processing.

🧠 3. Key-Value Pair Extraction using AI
📝 Used Generative AI (GenAI) models to extract key-value pairs from email content.
📌 Data is formatted in JSON to ensure consistency and ease of processing.

💾 4. Storing Key-Value Pairs in the Database
📊 Successfully stored extracted data in a database in JSON format.
🔒 Ensured data integrity for further business workflows.

📂 5. Moving Processed Emails to Specific Outlook Folders
📤 After successfully storing the extracted key-value pairs in the database, the emails are moved to their respective folders in Microsoft Outlook based on classification:
✔️ If the email is classified as Shipper, it is moved to the Shipper folder.
✔️ If the email is classified as Carrier, it is moved to the Carrier folder.
✔️ If the email does not belong to either category, it remains in the Inbox folder.

📌 This ensures that processed emails are organized efficiently, making them easy to locate and manage.

🛠 Technologies & Tools Used
💻 UiPath Studio – RPA automation
🔗 UiPath Integration Service – API-based AI model integration
🧠 UiPath Generative AI Activities – AI-powered classification & extraction
📩 Microsoft Outlook – Email processing
🗄 SQL Database – Storing extracted key-value pairs

🚀 Setup & Deployment Instructions
🔧 1. Configure Outlook Automation in UiPath
📌 Ensure Outlook is accessible from UiPath.
📌 Use "Get Outlook Mail Messages" activity to fetch incoming emails.

🔑 2. Enable Generative AI in UiPath
✅ Install UiPath.GenerativeAI.Activities package.
✅ Configure API key in UiPath Integration Service (OpenAI or Azure OpenAI).

🏷 3. Implement Email Classification
🧠 Use "Generate Text" activity with a custom AI prompt to classify emails.
📂 Store classification results and move emails accordingly.

📜 4. Extract Email Content & Key-Value Pairs
📩 Extract email body using UiPath Mail Activities.
🧠 Send email content to GenAI for key-value extraction.
📌 Use "Deserialize JSON" to parse AI response for structured data.

📊 5. Store Extracted Data in Database
💾 Use UiPath Database Activities to insert extracted JSON into the database.

📂 6. Move Processed Emails to Specific Outlook Folders
📌 Once the extracted data is successfully stored in the database, emails are moved to respective folders in Outlook using the "Move Outlook Mail Message" activity:
✔️ If classified as Shipper, move to Shipper folder.
✔️ If classified as Carrier, move to Carrier folder.
✔️ If not classified under these categories, it remains in the Inbox folder.

✨ Future Enhancements
🌟 Implement sentiment analysis to prioritize emails.
📊 Expand classification categories for more refined email organization.
📈 Integrate with Power BI for visualization of extracted email data.

🔥 Conclusion
This Outlook Automation leverages AI-driven classification, structured data extraction, and database storage to streamline email management. It enhances efficiency, reduces manual effort, and ensures accurate email processing for business workflows.

