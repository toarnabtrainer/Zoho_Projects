# Zoho Projects Blueprint

Here's a **step-by-step guide** to implement **Set Conditions** in a Blueprint for your **Zoho Projects** account.

### Step-by-Step Guide to Implementing Conditions in a Zoho Projects Blueprint

#### Step 1: Log in to Zoho Projects and Navigate to Blueprint
1. **Log in** to your **Zoho Projects** account.
2. **Navigate** to the specific project where you want to create the Blueprint.
   - Go to **Setup** → **Task & Issue Automation** → **Blueprints**.

#### Step 2: Create a New Blueprint
1. Click on **+ New Blueprint**.
2. **Name the Blueprint** (e.g., "Content Creation Workflow").
3. Select the **Task Layout** or **Issue Layout** you want the Blueprint to apply to (if you’ve created custom layouts).
4. Click **Create Blueprint**.

#### Step 3: Define Stages
1. In the Blueprint editor, you’ll see a list of default and custom stages.
   - Add stages that represent your workflow (e.g., **To Do**, **In Progress**, **Writing Completed**, **Editing Completed**, **Published**).
   - Drag and drop stages to arrange them.

#### Step 4: Add Transitions
1. Click on **+ Add Transition** between two stages.
   - For example, create a transition called **"Start Writing"** between **"To Do"** and **"In Progress"**.
   - Another transition could be **"Submit for Editing"** between **"Writing Completed"** and **"Editing Completed"**.
   
2. **Name the transition** and define any relevant description for it.

#### Step 5: Define Conditions for the Transition
To prevent moving a task from one stage to another without fulfilling certain conditions, you can define specific rules for each transition.

##### Example 1: Condition Based on Subtasks
In this example, you want to ensure that the subtask "Research" is completed before the task can move to the **"In Progress"** stage.

1. **Click** on the transition (e.g., **"Start Writing"**).
2. In the right panel, find the **Conditions** section and click **+Add Condition**.
   - **Condition Name**: "Research Completed".
   - **Rule**: If **Subtask** → **Research** → is **Completed**.
3. Save the condition.

##### Example 2: Condition Based on Custom Fields
In this case, you want to make sure the "SEO Tags" field is filled out before moving from **"Writing Completed"** to **"Editing Completed"**.

1. Select the **Submit for Editing** transition.
2. Under **Conditions**, click **+Add Condition**.
   - **Condition Name**: "SEO Tags Filled".
   - **Rule**: If **Custom Field** → **SEO Tags** → is **Not Empty**.
3. Save the condition.

#### Step 6: Combine Multiple Conditions (Optional)
You can add multiple conditions if necessary. For example, to move from **"Writing Completed"** to **"Editing Completed"**, you might require:
   - **Subtask** "Proofreading" to be completed.
   - **Custom Field** "SEO Tags" to be filled.

For this:
1. Under the **Submit for Editing** transition, click **+Add Condition**.
   - Add Condition 1: If **Subtask** → **Proofreading** → is **Completed**.
   - Add Condition 2: If **Custom Field** → **SEO Tags** → is **Not Empty**.
   
#### Step 7: Add Actions (Optional)
You can automate actions when transitions occur:
1. In the transition setup screen, scroll down to **Actions**.
2. Add actions like:
   - **Set Due Date**: Automatically set a due date when moving to the next stage.
   - **Notifications**: Send yourself an email or task notification when the stage changes.

#### Step 8: Set SLAs (Optional)
You can also add **SLAs** to ensure you meet deadlines. For example, you could add an SLA to finish writing within 3 days of moving the task to the **"In Progress"** stage.
1. Under the **In Progress** stage, add an **SLA rule**.
2. Define the time period (e.g., 3 days).

#### Step 9: Publish Your Blueprint
1. Once you’ve defined your stages, transitions, conditions, and actions, click **Save & Publish**.
2. Your Blueprint is now live, and you can apply it to your tasks within the selected project.

#### Step 10: Test the Blueprint
1. Create a task in your project and try moving it between stages.
2. If conditions are not met (e.g., subtasks are incomplete or fields are empty), Zoho Projects will block the transition, and an error message will appear prompting you to complete the required conditions.

---

This will ensure that you have a structured, automated workflow, even as a single user.
