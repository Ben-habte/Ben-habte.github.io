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

Over the past decade, healthcare has become increasingly digitized. From online appointment booking to digital prescriptions and patient portals, technology has transformed how we interact with medical systems. Yet for people living with chronic conditions, daily health management still relies heavily on memory, scattered tools, and manual tracking. Remembering medications, coordinating appointments, monitoring symptoms, and communicating with providers often happens across multiple apps, paper notes, pill organizers, and phone alarms. As life becomes busier and routines more unpredictable, managing health can begin to feel like a second full-time job.

## Understanding the Problem

Managing a chronic condition requires consistent daily action taking medications, tracking symptoms, booking appointments, and communicating with providers. Yet these tasks are often spread across multiple tools like phone alarms, paper notes, pill organizers, and separate hospital portals. This fragmentation increases mental load and makes it easy to forget important steps.
Young adults struggle with inconsistent routines, older adults face accessibility barriers, and caregivers experience stress without clear visibility into a loved one’s adherence. Missed doses and delayed communication can lead to anxiety, worsening symptoms, and preventable complications.
The core issue is not simply forgetfulness, it is the lack of flexible, engaging, and accessible tools designed around real-life behaviors.

## Our Mission

At Health Companion, our mission is to simplify chronic health management through thoughtful, human-centered design. We aim to create a super app that brings medication reminders, adherence tracking, appointment scheduling, and provider communication into one accessible, calming platform. By prioritizing flexibility, clarity, and accessibility, the Health Companion Super App empowers patients and caregivers to feel organized, supported, and in control of their health — without feeling overwhelmed.

---

# 2. User Research

## Research Method

Online Survey (10+ participants)**
Purpose: understand habits and pain points quickly

Types of questions that was asked:

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
  
<img width="640" height="480" alt="weekly_miss_rate" src="https://github.com/user-attachments/assets/432a88b8-9f3b-4bc8-9fa6-a73ac1887cd4" />

---

## Most common challenges 

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

## Persona 1: Maya

Maya is a 23-year-old marketing assistant and part-time student living in Toronto. She has ADHD, anxiety, and mild asthma, and is juggling a busy life with work and classes. Despite her tech-savviness and high engagement with digital tools like TikTok and Notion, Maya struggles with maintaining consistent routines, especially when it comes to taking her medications. She is looking for a simple and engaging app that helps her stay on track with her health, without feeling like a clinical tool.


<img width="768" height="1152" alt="maya persona" src="https://github.com/user-attachments/assets/70577298-2c57-45db-afda-dde0e2a48468" />


---
## Persona 2: Jay

Jay is a 20-year-old university student majoring in engineering. He lives at home with his 74-year-old grandmother, Lola, whom he cares for as her primary caregiver. Jay manages Lola’s medication for Type 2 Diabetes and early-stage dementia, but feels overwhelmed juggling his studies and taking care of Lola's health. He wishes there was an easier way to remotely monitor her medication adherence and manage appointments, helping reduce his stress and mental load.


<img width="768" height="1152" alt="jay" src="https://github.com/user-attachments/assets/242d7ed1-1088-4635-8535-64e39fef2420" />

---

# 4. User Journey Maps

<img width="768" height="1152" alt="f552d885-c8e9-4087-8681-b34eff941b91" src="https://github.com/user-attachments/assets/452dce66-0b13-42e7-b221-140262e5ce7d" />


---

## Journey Map: Jay (Caregiver Monitoring)

<img width="768" height="1152" alt="jay journey map" src="https://github.com/user-attachments/assets/f20c8691-d3c0-4eb3-9725-e66c1c811c4c" />

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

<img width="1183" height="505" alt="Picture1" src="https://github.com/user-attachments/assets/cf1311a9-085b-4de3-b3cf-36fcda3c976e" />

### Flow 2: Receive Reminder & Confirm Taken

<img width="1191" height="465" alt="Picture2" src="https://github.com/user-attachments/assets/a7862132-43ec-4143-be37-5551ef5d72af" />

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
![pastel-tide-sunrise-green-blue-orange-color-palette](https://github.com/user-attachments/assets/d16e5f1c-79b3-4985-8961-744e3cd0d520)

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

