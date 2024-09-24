Here’s a step-by-step guide to creating a workflow in **Zoho Projects** for automatically assigning tasks based on priority:
### Task Deadline Reminder and Priority Management
### **Step-by-Step Guide to Creating a Workflow in Zoho Projects**

#### **1. Access the Workflow Settings:**
   - Go to your **Zoho Projects** account.
   - In the top-right corner, click the **gear icon (Setup)**.
   - Under the **Task Automation** section, choose **Workflow Rules**.

#### **2. Create a New Workflow Rule:**
   - Click on **New Workflow Rule**.
   - You’ll be prompted to set the conditions and actions for the workflow.
   - Give the Workflow name as **Task Deadline Reminder and Priority Management**.

#### **3. Define the Workflow Trigger:**
   - Choose a **Trigger** for the workflow. In this case:
     - Set the trigger to be **"When a Task is Created"**.
     - Set the trigger to be **"When a Task is Updated"**.

![image](https://github.com/user-attachments/assets/a7b51ee5-4fbc-46bd-bcf4-c32959654202)

#### **4. Set Conditions:**
   - Click on **Add Criteria** to define the specific criteria for the workflow to run.
   - Select the condition: **Priority**.
     - You can set it to one of three conditions:
       1. **If Priority is "High"**
       2. **If Priority is "Medium"**
       3. **If Priority is "Low"**

#### **5. Set Actions for Each Condition:**
   - For each condition (High, Medium, Low), define the following actions:

---

##### **For High-Priority Tasks:**

1. **Assign the Task to a Senior Team Member:**
   - Under **Actions**, choose **Assign Task**.
   - Select the **Senior Team Lead** or the appropriate user for high-priority tasks.

2. **Set a Due Date:**
   - Under **Actions**, choose **Set Due Date**.
   - Set it to **2 days from the task creation date**.

3. **Send Notifications:**
   - Under **Actions**, choose **Send Notification**.
   - Select the recipients (e.g., the assigned team member and the project manager).

![image](https://github.com/user-attachments/assets/bc2b2258-902c-4f63-927e-65a67e1fd269)

---

##### **For Medium-Priority Tasks:**

1. **Assign the Task to a Mid-Level Team Member:**
   - Under **Actions**, choose **Assign Task**.
   - Select a **Mid-level Team Member** for medium-priority tasks.

2. **Set a Due Date:**
   - Under **Actions**, choose **Set Due Date**.
   - Set it to **5 days from the task creation date**.

3. **Send Notifications:**
   - Under **Actions**, choose **Send Notification**.
   - Send the notification to the assigned team member.

![image](https://github.com/user-attachments/assets/d551037b-f91b-407a-b39b-e3a7fa0e1ae7)

---

##### **For Low-Priority Tasks:**

1. **Assign the Task to a Junior Team Member:**
   - Under **Actions**, choose **Assign Task**.
   - Select a **Junior Team Member** for low-priority tasks.

2. **Set a Due Date:**
   - Under **Actions**, choose **Set Due Date**.
   - Set it to **10 days from the task creation date**.

3. **Send Notifications:**
   - Under **Actions**, choose **Send Notification**.
   - Notify the assigned team member about the task assignment.

![image](https://github.com/user-attachments/assets/2c31e91e-7608-47d3-b805-4cbd5c5cbc99)

---

#### **6. Save and Activate the Workflow:**
   - After you have added all the conditions and actions for each priority level, click **Save Rule**.
   - Now come back to your project where you wan to activate your workflow rule.
   - In the top right corner click on **Task Automation** and enable the workflow rule by switching it on.

---

### **Test the Workflow:**
   - Create a new task in the project and set its priority to High, Medium, or Low.
   - Observe whether the task gets assigned to the correct team member, with the appropriate due date and notifications sent.

---

### **Review and Modify:**
   - You can always go back to **Settings > Workflows** to review, edit, or disable the workflow if needed.
   - You can also create additional workflows for other aspects of project automation, like task status updates or project milestones.

This workflow will streamline your task management process, ensuring tasks are assigned and handled according to their priority without manual intervention. Let me know if you need further clarification!
