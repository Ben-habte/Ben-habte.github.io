# UX/UI Case Study: Health Companion Super App 💊📱

## Goal

Help people with chronic health conditions manage medications, reminders, appointments, and communication with healthcare providers.

---

# Table of Contents

1. [Introduction](#1-introduction)
2. [User Research](#2-user-research)
3. [Personas](#3-personas)
4. [User Journey Maps](#4-user-journey-maps)
5. [Requirements & Problem Statements](#5-requirements--problem-statements)
6. [User Flow Chart](#6-user-flow-chart)
7. [Sketches + Storyboard](#7-sketches--storyboard)
8. [Wireframes (Low-fidelity)](#8-wireframes-low-fidelity)
9. [Visual Design Direction (UI)](#9-visual-design-direction-ui)
10. [Prototype (Clickable)](#10-prototype)
11. [Usability Testing Plan](#11-usability-testing-plan)
12. [Feedback Summary + Iterations](#12-feedback-summary--iterations-required)
13. [Reflection](#13-reflection)

---

# 1. Introduction

## Problem

People with chronic conditions often struggle with:

* remembering medications
* tracking what they actually took
* managing doctor appointments
* communicating quickly with providers

## Why it matters

Missed medications and missed appointments lead to:

* worse health outcomes
* higher stress
* increased hospital visits

## Solution

A Health Companion Super App that supports:

* medication reminders
* adherence tracking
* appointment scheduling
* provider messaging

---

# 2. User Research

## Research Method

### Primary Research

**1) Online Survey (10+ participants)**
Purpose: understand habits and pain points quickly

Ask questions like:

* How many medications do you take daily?
* What tools do you use now (alarm, paper, app)?
* What’s your biggest challenge?
* Have you missed medication in the past month?
* Do you struggle with refills or appointment scheduling?

---

## Key Findings

Raw data (Name replaced to “Person” for privacy)

| Name     | Age | Role      | Condition(s)                 | Meds/Day           | Missed Dose Frequency    | Current Tracking Method | Biggest Challenge                                                        | Desired Features                      |
| -------- | --- | --------- | ---------------------------- | ------------------ | ------------------------ | ----------------------- | ------------------------------------------------------------------------ | ------------------------------------- |
| Person1  | 68  | Patient   | Arthritis                    | 4                  | 2-3x / week              | Pill organizer          | "Forgetting if I already took them."                                     | Big "Taken" button, large text        |
| Person2  | 22  | Patient   | ADHD, Anxiety                | 2                  | 4-5x / week              | Phone reminders         | “I remember, but I don’t take it right away and then completely forget.” | Persistent reminders, habit tracking  |
| Person3  | 24  | Patient   | Asthma, Seasonal Allergies   | 2 (daily + rescue) | 3x / month               | iPhone Health app       | "The app is too clinical and boring."                                    | Clean UI, streaks/gamification        |
| Person4  | 19  | Patient   | PCOS, Acne                   | 3                  | 2x / week                | Calendar app            | "Remembering to take them with food."                                    | Meal pairing reminders, refill alerts |
| Person5  | 20  | Caregiver | For grandmother: Diabetes    | N/A                | 1x / week (as caregiver) | Texts to herself        | "She calls me because she can't read the app."                           | Caregiver mode, large text for her    |
| Person6  | 45  | Patient   | High Blood Pressure          | 1                  | 2x / month               | Memory only             | "Changing time zones messes me up."                                      | Flexible schedules, travel mode       |
| Person7  | 23  | Patient   | Migraine, IBS                | 2 (as needed)      | Varies (5x/month)        | Notes app               | "Tracking triggers + meds is two separate things."                       | Symptom + med tracking together       |
| Person8  | 62  | Patient   | Acid Reflux (GERD)           | 3                  | 1x / week                | Old pill bottles        | "Reading the small print on bottles."                                    | Voice confirmation, simple icons      |
| Person9  | 21  | Patient   | Depression                   | 1                  | 3x / week                | No system               | "I forget because my routine is inconsistent."                           | Gentle reminders, bedtime routine     |
| Person10 | 50  | Caregiver | For husband: Heart condition | 6                  | 1x / week                | Whiteboard              | "Coordinating refills with the pharmacy."                                | Refill requests, provider chat        |

---

### From the 10 participants:

* 60% are aged 25 or under, highlighting that chronic health management is a significant issue for young adults (not only seniors).
* 70% miss medication at least weekly.
* 30% miss medication 3+ times/week.
* 20% of respondents were caregivers managing someone else's health.
* The average meds/day among patients is 2.4.

---

## Most common challenges (Pain Points)

1. **Inconsistent Routines**
2. **App Engagement**
3. **Forgetfulness/Uncertainty**
4. **Accessibility**

---

## Top requested features

1. Simple, customisable reminders (7/10)
2. Appointment scheduling (6/10)
3. Clean, modern UI with gentle notifications (5/10)
4. Caregiver access / monitoring (4/10)
5. Refill reminders (4/10)
6. Symptom tracking

---

# 3. Personas

<img width="1024" height="1536" alt="maya persona" src="https://github.com/user-attachments/assets/70577298-2c57-45db-afda-dde0e2a48468" />


---


<img width="1024" height="1536" alt="jay" src="https://github.com/user-attachments/assets/242d7ed1-1088-4635-8535-64e39fef2420" />

---

# 4. User Journey Maps

<img width="1024" height="1536" alt="f552d885-c8e9-4087-8681-b34eff941b91" src="https://github.com/user-attachments/assets/452dce66-0b13-42e7-b221-140262e5ce7d" />


---

## Journey Map: Jay (Caregiver Monitoring)

<img width="1536" height="1024" alt="jay journey map" src="https://github.com/user-attachments/assets/f20c8691-d3c0-4eb3-9725-e66c1c811c4c" />

---

# 5. Requirements & Problem Statements

## Primary Problem Statement (Patient Focus)

"Young adults managing chronic conditions with inconsistent routines need a flexible, engaging way to track medications because rigid reminders and clinical apps lead to missed doses, reduced focus at work, and increased anxiety."

## Secondary Problem Statement (Caregiver Focus)

"Gen Z and millennial caregivers managing medication for aging parents need remote monitoring tools and quick communication with providers because missed doses and slow clinic response times cause constant stress."

---

## User Requirements

### For Patients

* Flexible reminders
* Quick 1-tap confirmation
* Engaging visual feedback
* Gentle notifications
* Symptom + medication pairing
* Refill alerts

### For Caregivers

* Caregiver mode
* Missed dose alerts
* Remote confirmation
* Simplified patient view
* 1-tap caregiver call
* Appointment booking + calendar sync
* Provider messaging

### For General Users

* Simple medication setup
* Appointment scheduling
* Secure messaging
* Readable interface

---

# 6. User Flow Chart

### Flow 1: Add Medication

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/64630ab7-38fc-453a-bc9a-4ca8faa719e3" />

### Flow 2: Receive Reminder & Confirm Taken

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/8ea20fbf-01a2-4767-867a-ee5eb24e268f" />

---

# 7. Storyboard

<img width="468" height="312" alt="image" src="https://github.com/user-attachments/assets/fefdf007-ce96-4a13-b525-34dbc03fccb0" />

---

# 8. Wireframes (Low-fidelity)

<img width="468" height="312" alt="image" src="https://github.com/user-attachments/assets/8a064e75-6449-425a-b8a2-98b3bc809699" />

---

# 9. Visual Design Direction (UI)

## Design Philosophy

Health management should feel calming, not clinical.

## Design Principles

* Minimal layout
* High contrast
* Large tap targets
* Gentle feedback

## Color Palette

Calm blue, success green, gentle orange, soft neutral background.

## Typography

* Titles: 34px
* Body: 16px minimum
* Headers: 24px / 18px
* Captions: 14px

## Accessibility

* Adjustable text size
* High contrast mode
* Screen reader support
* Reduce motion option

---

# 10. Prototype

[https://fray-inter-84526377.figma.site/](https://fray-inter-84526377.figma.site/)

---

# 11. Usability Testing Plan

## Testing Goals

Validate that users can:

* Add medication
* Confirm a dose
* Book an appointment
* Navigate independently

## Participants

5–8 participants:

* 2 older adults
* 1 caregiver
* 2 general users

## Success Metrics

* Task completion rate
* Time on task
* Number of errors
* Satisfaction rating (1–5)

---

# 12. Feedback Summary + Iterations (Required)

## Testing Overview

6 participants tested the prototype.

### Key Issues Identified

| Issue                               | Severity | Users Affected    |
| ----------------------------------- | -------- | ----------------- |
| Medication setup has too many steps | High     | 5 of 6            |
| Home screen feels crowded           | Medium   | 4 of 6            |
| Appointment confirmation unclear    | High     | 3 of 6            |
| No progress tracking                | Low      | 2 of 6            |
| Small text                          | Medium   | Both older adults |

---

## Changes Made

* Reduced medication setup to 3 steps
* Simplified home screen
* Added appointment confirmation screen
* Introduced Weekly Streak
* Increased base text to 16pt

---

## Second Round Testing

* Medication setup under 45 seconds
* Appointment confusion eliminated
* Streak feature positively received

---

# 13. Reflection

## What UX Helped Me Discover

* Users value simplicity over advanced features.
* Accessibility must be built in from the start.
* Caregiver features significantly increase usefulness.

## Challenges

* Balancing super app features without overwhelm
* Designing for both patient and caregiver

## How I Overcame Them

* Progressive disclosure
* Separate caregiver mode
* Prioritizing frequent tasks

---

# Final Thoughts

UX design is ultimately about empathy.

The Health Companion app won’t solve everything — but if it helps Maya build a streak, gives Jay peace of mind, and lets Lola read her medication names without glasses, then it has done its job.

And that’s what good UX does:
It fades into the background and lets people get on with their lives.

