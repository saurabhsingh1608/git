**How To Deploy Changes to TS From Github Prod Branch** 

* Raise the PR ( link )  
* Review the New Raised Pull Request for merging to Prod Branch  
* Got Some Doubt, clarify it with an Analyst on PR and Document it.  
* Click on Labels and select **Approved** label.  
<img width="1555" alt="Screenshot 2024-10-29 at 4 38 46 PM" src="https://github.com/user-attachments/assets/fc8f94fb-ef7a-4db8-b9c1-8c0161e2bc3f">

* Click on merge Pull Request button   
* This will run the Github Action Workflow “**deploy\_changes\_to\_thoughtspot**” which will pick the Objects that are Merged from Dev Branch to Prod Branch and Push these objects to Prod Org in Thoughtspot
