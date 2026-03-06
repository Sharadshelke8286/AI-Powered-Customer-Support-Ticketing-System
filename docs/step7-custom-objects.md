# Step 7: Custom Object Implementation

## Objective

Custom objects are created in Salesforce to store additional information required for the AI-Powered Customer Support Ticketing System. These objects help manage support categories, SLA policies, and AI feedback from agents.

---

# 1. Create Support Category Object

The **Support Category** object is used to store different categories of customer support issues. This helps in automatically classifying cases.

### Steps to Create Object

1. Go to **Setup** in Salesforce.
2. Click **Object Manager**.
3. Click **Create → Custom Object**.
4. Enter the following details:

| Field        | Value              |
| ------------ | ------------------ |
| Label        | Support Category   |
| Plural Label | Support Categories |
| Record Name  | Support Category   |
| Data Type    | Text               |

5. Enable the following options:

* Allow Reports
* Allow Search

6. Click **Save**.

---

# 2. Create AI Feedback Object

The **AI Feedback** object stores feedback from support agents regarding AI-generated suggestions.

### Steps to Create Object

1. Click the **Gear Icon → Setup**.
2. Navigate to **Object Manager**.
3. Click **Create → Custom Object**.
4. Enter the following details:

| Field          | Value              |
| -------------- | ------------------ |
| Label          | AI Feedback        |
| Plural Label   | AI Feedbacks       |
| Record Name    | AI Feedback Number |
| Data Type      | Auto Number        |
| Display Format | AF-{00000}         |

5. Enable the following options:

* Allow Reports
* Allow Search

6. Click **Save**.

---

# 3. Create SLA Policy Object

The **SLA Policy** object stores Service Level Agreement rules for resolving support tickets.

### Steps to Create Object

1. Navigate to **Setup → Object Manager**.
2. Click **Create → Custom Object**.
3. Enter the following details:

| Field        | Value        |
| ------------ | ------------ |
| Label        | SLA Policy   |
| Plural Label | SLA Policies |
| Record Name  | SLA Policy   |
| Data Type    | Text         |

4. Enable the following options:

* Allow Reports
* Allow Search

5. Click **Save**.

---

# Outcome

After completing this step, the following custom objects are successfully created in Salesforce:

* Support Category
* AI Feedback
* SLA Policy

These objects will be used later for case classification, SLA tracking, and capturing agent feedback in the ticketing system.
