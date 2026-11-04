---
layout: essay
type: essay
title: "Final Project Proposal"
# All dates must be YYYY-MM-DD format!
date: 2026-11-03
published: true
labels:
  - Software Engineering
  - Nextjs
---

# Final Project Proposal: Mānoa Happenings

## Overview

**The Problem:**  
The University of Hawai‘i at Mānoa hosts numerous events weekly, including club meetings, academic workshops, guest lectures, cultural events, and research projects. Currently, information regarding these events is distributed across multiple departmental websites, social media pages, email lists, and physical bulletin boards.

**The Solution:**  
Mānoa Happenings is a event aggregation application designed for the UH Mānoa community. It provides a single platform where clubs, academic departments, research groups, or students can post events. For students, the application filters and displays events based on their individual preferences, ensuring they only see opportunities relevant events.

## Names of the Proposers
* Kenneth Chun

## Mockup Page Ideas

1. **Landing Page:** A standard homepage introducing the application. It will display a list of upcoming public events and provide navigation for users to register or log in.
2. **User Dashboard (Individual User State):** Upon logging in, the user views a dashboard that displays events filtered by their specific profile settings. Users will input their major, areas of interest, and dietary restrictions. The application will use this individual state to prioritize and display matching events.
3. **Event Detail Page:** A page displaying the specific details of a single event. It will include the title, date, time, location, full description, category tags.
4. **Create Event Form:** A standardized form accessible to all logged-in users. It requires specific fields (e.g., title, date, location, category, target audience, accessibility information) to ensure data consistency and maintain a structured database.


## Use Case Ideas

* **Use Case 1 (Personalized Discovery):** A logged-in user navigates to their dashboard. The system reads the user's saved profile preferences and dynamically filters the event feed to display relevant upcoming events, automatically hiding unrelated content.
* **Use Case 2 (Peer Event Creation):** A user decides to host an event. They access the event creation form, input the required details (title, time, location, category), and submit the form. The system validates the input, adds the event to the database, and immediately surfaces it on the dashboards of other users whose profile tags match the event's category.
* **Use Case 3 (Unified Feed Aggregation):** The system processes a mixed database of events posted by both individual students and university staff. When a user views their feed, the application aggregates these diverse event types into a single, unified list, prioritizing them based on the user's individual preference.

## Beyond the Basics

* **Event Moderation:** Implement a reporting system for users to flag inappropriate events, ensuring community standards are maintained without requiring pre-approval from university administrators.
* **Technical Implementation:** The application will be developed using Next.js and React for the user interface. It will be styled with Bootstrap 5 to ensure responsive design across devices.

---

*AI used for structure the proposal*
*AI improve sentence structure*