# Step 6: Data Architecture

## Objective

The data architecture defines the structure of objects, fields, and relationships used in the AI-Powered Customer Support Ticketing System. It ensures proper storage and management of customer support data in Salesforce.

The system uses both **standard Salesforce objects** and **custom objects** to manage customer support operations.

---

# Standard Objects Used

## Account

The Account object stores information about organizations or companies that interact with the business.

**Fields Used**

* Account Name
* Phone
* Industry
* Type

This object helps track customer organizations that submit support requests.

---

## Contact

The Contact object stores information about individuals associated with an account.

**Fields Used**

* First Name
* Last Name
* Email
* Phone

Contacts represent the individuals who raise support cases.

---

## Case

The Case object is the central object used to manage customer support tickets.

**Fields Used**

* Case Number
* Subject
* Description
* Status
* Priority
* Issue Type
* SLA Due Date
* AI Suggested Reply
* Resolution Time

Each case represents a customer issue that needs to be resolved by the support team.

---

# Custom Objects Created

## Support_Category__c

This custom object defines categories of support issues.

**Fields**

* Category Name
* Description
* Default Priority
* Active

This helps in automatically classifying cases based on issue type.

---

## SLA_Policy__c

This object stores SLA rules used to determine resolution timelines.

**Fields**

* Policy Name
* Priority Level
* Resolution Time (Hours)
* Escalation Required

This helps calculate the SLA due date for each support case.

---

## AI_Feedback__c

This object captures feedback from support agents regarding AI-generated suggestions.

**Fields**

* AI Feedback Number (Auto Number)
* AI Suggestion Type
* Feedback Status
* Agent Comments

This feedback helps evaluate the effectiveness of automated suggestions.

---

# Object Relationships

The following relationships connect different objects in the system.

| Relationship            | Type                |
| ----------------------- | ------------------- |
| Account → Contact       | Lookup              |
| Account → Case          | Lookup              |
| Contact → Case          | Lookup              |
| Support Category → Case | Lookup              |
| SLA Policy → Case       | Referenced via Flow |
| AI Feedback → Case      | Lookup              |

These relationships allow the system to maintain connections between customers, support tickets, and automation processes.

---

# Conclusion

The data architecture ensures that all customer support information is properly structured and connected. By using standard and custom objects with defined relationships, the system can efficiently manage support cases, automate processes, and maintain data integrity.
