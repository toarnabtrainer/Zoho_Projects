Let's create a rule that **automatically changes the status of a task to "In Progress"** as soon as it is assigned to yourself or updated by you.

### Scenario: Automatically Change Task Status to "In Progress" When Assigned or Updated

This workflow will automate the task status update, so that whenever you assign a task to yourself or make updates to the task, the status will change to **"In Progress"** without manual intervention.

### Steps to Create a Workflow Rule in Zoho Projects

1. **Log in to Zoho Projects:**
   - Sign in to your Zoho Projects account.

2. **Navigate to Workflow Rules:**
   - Select the project where you want to apply this workflow.
   - In the left sidebar, scroll down to **"Task Automation"** and select **"Workflow Rules."**

3. **Create a New Workflow Rule:**
   - Click the **"Add Rule"** button.

4. **Define the Rule:**
   - **Rule Name:** Enter something like **"Change Status to In Progress"**.
   - **Module:** Choose **"Task"** as the module.
   - **Description:** Optionally, add a description like *"Automatically sets task status to In Progress when I assign or update a task."*
![image](https://github.com/user-attachments/assets/b554994b-8d38-4ac8-8219-8ed46c6f6218)

![image](https://github.com/user-attachments/assets/3a685b44-68f6-464d-a672-92756792f5ce)

5. **Set the Trigger:**
   - In the **"When to trigger this rule"** section, select **"On Task Creation"** and **"On Task Update"**.
     - This ensures the rule runs both when a new task is assigned to you and when you make updates to existing tasks.

6. **Set the Condition:**
   - In the **"Condition"** section, set the following condition:
     - **Field:** Choose **"Owner"** (or **"Assignee"**, depending on your account setup).
     - **Operator:** Choose **"is."**
     - **Value:** Set the value as your username (since you are the only user in this case).
   - This condition ensures the workflow applies only when tasks are assigned to you or updated by you.

![image](https://github.com/user-attachments/assets/c7c1525a-cc2a-43ca-b0f1-6d272807a704)

7. **Set the Action:**
   - Under **"Actions,"** choose **"Update Task"** as the action.
   - Select **"Status"** as the field to update.
   - Set the value to **"In Progress."**
  
![image](https://github.com/user-attachments/assets/13038ddd-54ab-4666-9fc2-b9e7062c79f1)


8. **Review and Save:**
   - Review the workflow rule to make sure everything is correct.
   - Click **"Save"** to activate the workflow rule.

### Final Outcome:
With this rule, anytime you assign a task to yourself or update an existing task, its status will automatically change to **"In Progress."** This helps streamline your workflow by eliminating the need to manually update task statuses every time you start working on them.

---

**Tip:** You can modify this rule for other similar scenarios like marking tasks as completed or adding tags when certain conditions are met. It's a great way to automate repetitive updates, even in a single-user environment.
