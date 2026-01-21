# Module 25: Microsoft Excel Macros

## Central Concept

MACROS

* Automated action sequences in Excel
* Recorded steps or written VBA code
* Run with one click or shortcut

---

## 1. Essentials

WHAT

* Small program written in VBA
* Automates repetitive tasks

WHY

* Saves time
* Removes manual errors
* Handles repetitive, fixed-pattern work

WHEN

* Same steps repeated daily, weekly, monthly
* Example: cleaning recurring sales reports

HOW

* Macro Recorder to capture actions
* Visual Basic Editor for manual coding

---

## 2. Types of Macros

RECORDED MACROS

* No coding
* Recorder captures mouse and keyboard actions

WRITTEN MACROS

* Manual VBA code
* Used for logic and conditions
* Example: IF conditions, automated emails

---

## 3. Pros and Cons

ADVANTAGES

* Speed. 30 minutes reduced to seconds
* Consistency. No missed steps or typos
* Accessibility. Anyone can run complex tasks

DISADVANTAGES

* No Undo after execution
* Security risks from malicious macros
* Must save file as .xlsm

---

## 4. Example Workflow: Header Formatting Macro

SCENARIO

* Raw CSV received weekly
* Header needs formatting

STEPS

* Enable Developer tab
* Record Macro
* Name: FormatHeader
* Shortcut: Ctrl + Shift + H
* Actions

  * Select Row 1
  * Bold
  * Fill Blue
  * Font White
  * Center Align
* Stop Recording
* Test on new sheet

---

## 5. Practice Scenarios for Students

SCENARIO 1. Daily Data Cleaner

* Delete first 3 rows
* Auto-fit columns
* Enable Filter
* Goal: clean exported data instantly

SCENARIO 2. PDF Report Generator

* Select A1:G20
* Set print area
* Save as PDF on Desktop
* File name: Daily_Report
* Goal: one-click reporting

SCENARIO 3. Total and Bold Footer

* Go to bottom of Column B
* Insert AutoSum
* Apply double border
* Goal: quick financial totals

SCENARIO 4. Theme Switcher

* Macro 1: Dark Mode

  * Black background
  * White text
* Macro 2: Light Mode

  * White background
  * Black text
* Goal: switch UI themes

SCENARIO 5. Chart Automator

* Select Columns A and B
* Insert Clustered Column Chart
* Title: Sales Performance
* Goal: auto chart creation

---

## 6. Student Safety Rule

CRITICAL RULE

* Always save a backup before running a new macro
* Macro actions cannot be undone
* Recording mistakes can permanently change data
