# Salesforce Summer Program - Day 4

## Topic: Flow Builder & Business Process Automation

---

# What is Flow Builder?

Flow Builder is a no-code automation tool in Salesforce that helps businesses automate workflows and processes visually without writing code.

It allows users to:
- Automate repetitive tasks
- Update records automatically
- Send notifications
- Create guided screens
- Improve business efficiency

---

# Types of Flows

## 1. Screen Flow
Screen Flow requires user interaction and provides screens/forms to collect data from users.

### Uses:
- Registration forms
- Surveys
- Guided processes

---

## 2. Record Triggered Flow
Record Triggered Flow runs automatically when a record is created, updated, or deleted.

### Uses:
- Auto email notifications
- Auto updates
- Approval processes

---

# My Automation Ideas (College Management System)

## 1. Auto Email After Registration
Automatically send confirmation email after student registration.

## 2. Auto Update Remaining Seats
Automatically reduce available seats when a student enrolls.

## 3. Notify Faculty When Course is Full
Send notification to faculty when seats are filled.

## 4. Generate Student ID Automatically
Create unique student ID after admission approval.

## 5. Send Fee Payment Reminder
Automatically remind students before fee deadlines.

---

# Flow Diagram

## Fee Reminder Automation Flow

```text
START
   ↓
Scheduled Trigger
   ↓
Check Fee Due Date
   ↓
Decision:
Fee due within 3 days?
   ↓
YES → Send Reminder Email
   ↓
Update Status
   ↓
END
```

---

# Manual vs Automated Process

## Process: Fee Reminder System

### Manual Process
- Staff manually checks records
- Sends reminders individually
- Updates records manually

### Problems
- Time-consuming
- Human errors
- Delayed communication

### Automated Process in Salesforce
- Automatic due-date checking
- Automatic reminder emails
- Automatic status updates

### Benefits
- Faster workflow
- Better accuracy
- Increased productivity

---

# Reflection: Why Automation Matters

Automation is important because it:
- Saves time
- Reduces repetitive work
- Improves consistency
- Minimizes human errors
- Enhances productivity
- Helps businesses scale efficiently

Salesforce Flow Builder enables organizations to automate workflows without coding, making enterprise systems smarter and more efficient.
