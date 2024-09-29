In **Zoho Projects**, a **Mail Template** is a predefined email format that you can customize to send automated notifications to users when certain actions or events occur. Mail templates are useful for maintaining consistent communication and ensuring that all relevant team members are notified automatically based on project activities.

### Key Features of Mail Templates:
- **Customization**: You can customize the content, subject line, and layout of the emails.
- **Placeholders**: Dynamic placeholders can be used to insert information like task names, due dates, assignees, project names, etc.
- **Trigger Events**: Mail templates can be triggered by specific events like task creation, status updates, comments, task completion, or milestone achievement.
- **Automatic Notifications**: These templates are automatically sent to designated users when the triggering event happens.

### Example 1: Task Assignment Notification

#### Template Name: **New Task Assigned**
- **Subject**: [Project Name]: New Task Assigned to You - [Task Name]
  
- **Body**:
  ```
  Hi [Assignee Name],

  A new task has been assigned to you in the project "[Project Name]." 

  Here are the details:
  - **Task Name**: [Task Name]
  - **Due Date**: [Task Due Date]
  - **Priority**: [Task Priority]
  - **Created By**: [Created By]
  - **Task Description**: [Task Description]

  Please ensure to complete this task by the due date. Feel free to reach out if you have any questions or need further clarification.

  Thanks,
  [Sender Name]
  ```

#### When to Use:
This template is used to notify users when they are assigned a new task in a project. It helps ensure that users are aware of their responsibilities and deadlines.

### Example 2: Task Completion Notification

#### Template Name: **Task Completed**
- **Subject**: [Task Name] Completed in Project [Project Name]
  
- **Body**:
  ```
  Hello [Recipient Name],

  The task "[Task Name]" in the project "[Project Name]" has been completed by [Completed By].

  Here are the task details:
  - **Task Name**: [Task Name]
  - **Completion Date**: [Task Completion Date]
  - **Original Due Date**: [Task Due Date]
  - **Task Description**: [Task Description]

  Please review the task and confirm if any further action is needed.

  Thanks for your attention.

  Best regards,
  [Sender Name]
  ```

#### When to Use:
This template is automatically triggered when a task is marked as complete. It notifies project managers, stakeholders, or team members that the task is finished and may require further review or sign-off.

Certainly! Here are two more sample email templates for **Zoho Projects**.

---

### Example 3: Task Overdue Notification

#### Template Name: **Task Overdue Alert**
- **Subject**: [Task Name] in [Project Name] is Overdue!

- **Body**:
  ```
  Hi [Assignee Name],

  This is a reminder that the task "[Task Name]" in the project "[Project Name]" is overdue.

  - **Original Due Date**: [Task Due Date]
  - **Task Priority**: [Task Priority]
  - **Task Created By**: [Created By]
  - **Task Description**: [Task Description]

  Please take action to complete this task as soon as possible or update the status if further time is required.

  If you need assistance or clarification, feel free to reach out.

  Thank you,
  [Sender Name]
  ```

#### When to Use:
This template is sent automatically when a task goes past its due date without being completed. It serves as a gentle reminder to the assignee to either finish the task or provide updates.

---

### Example 4: Project Milestone Reached Notification

#### Template Name: **Milestone Achieved**
- **Subject**: [Milestone Name] Achieved in [Project Name]!

- **Body**:
  ```
  Hello [Recipient Name],

  We are excited to inform you that the milestone "[Milestone Name]" has been successfully achieved in the project "[Project Name]."

  Here are the details of the milestone:
  - **Milestone Name**: [Milestone Name]
  - **Completion Date**: [Milestone Completion Date]
  - **Milestone Description**: [Milestone Description]

  This is an important step forward in our project. Let’s continue to build on this success as we move towards the next objectives.

  Thank you for your contribution to this achievement!

  Best regards,
  [Sender Name]
  ```

#### When to Use:
This template is triggered when a project milestone is reached. It’s useful for informing stakeholders, project managers, and team members that a significant goal has been completed and acknowledges the team’s contribution.

---

These templates help maintain strong communication throughout the lifecycle of a project, ensuring team members are always in the loop about critical tasks and milestones. Would you like to customize any of these templates for your use case?


### Customization Options:
- **Placeholders**: You can use placeholders like [Task Name], [Project Name], [Due Date], [Assignee Name], etc., to dynamically populate data specific to each task or project.
- **Notifications**: Mail templates can be set to trigger automatically when predefined actions like task creation, status change, or task completion occur.

Mail templates help streamline communication, reduce manual email writing, and keep everyone updated automatically. 

---
<hr>

### Steps to Associate an Email Template with an Email Alert in Zoho Projects

#### 1. **Create an Email Template**
   - Navigate to **Setup** (gear icon at the top-right corner).
   - Under **Task Automation** or **Project Automation**, go to **Email Templates**.
   - Create a new email template by selecting the appropriate module (e.g., Tasks, Projects, or Milestones).
   - Design the template by filling in the subject, body, and dynamic fields, then save it.

#### 2. **Set up an Email Alert**
   - Go to **Task Automation** (for task-based events) or **Project Automation** (for project-wide events).
   - Under **Automation**, choose **Email Alerts**.
   - Click on **New Email Alert** to create a new alert.
   - Assign a name to your alert.
   - In the **Event** dropdown, select the action you want to trigger the alert (e.g., **Task Created**, **Task Completed**, or **Task Updated**).
   - Select the **recipient** for the alert, which could be the task assignee, project owner, or others.
   - Choose the **email template** you created earlier from the dropdown list.
   - Save the alert.

#### 3. **Associate the Email Alert with Tasks**
   - You do not need to associate the email alert manually with each task. Once the email alert is created, it will automatically trigger based on the event you defined (e.g., when a task is completed, the email will automatically send to the designated recipients).
   
#### 4. **Testing the Email Alert**
   - Create a sample task in one of your projects.
   - Complete or modify the task according to the event you defined (e.g., mark it as completed if that’s the trigger).
   - Check your email to see if the custom email alert was sent as expected.

---

By using the new **Task Automation** and **Project Automation** features, you can efficiently automate email notifications based on task or project-related events.
