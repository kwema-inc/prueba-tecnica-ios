# Earthquake Tracking App - Technical Challenge

## Objective

Evaluate the candidate's skills in iOS development, API integration, user experience design, background data fetching, and best practices in software development including Git workflow and documentation.

## General Instructions

- Use Swift and Swift UI
- Integrate data from the US Geological Survey (USGS) Earthquake API (https://earthquake.usgs.gov/fdsnws/).
- Follow a structured Git workflow, clearly demonstrating iterative development.
- Your solution should be documented with clear explanations where necessary. Provide a README.md
- Submission does *NOT* require App Store deployment; a demonstration video or set of GIFs showcasing functionality within the repository's README is sufficient.
- Commit frequently and meaningfully — don’t leave everything for the end. Use descriptive commit messages.
- Use the Git branching strategy of your choice, but avoid committing directly to main or master.

# Challenge Description

Imagine living in Peru, a highly seismic country. After an earthquake, the first instinct is usually to find out its magnitude, location, and intensity. Unfortunately, the local geological institute's website often crashes under high demand, leaving citizens uncertain and anxious during critical moments.

You are developing a crucial iOS app to provide timely and reliable earthquake information directly after an event. Users will rely on your app to quickly understand the details of the most recent seismic activity and adjust their actions accordingly. Your solution should deliver an intuitive, responsive, and trustworthy experience, especially during emergencies when clarity and accessibility are vital.

## Part 1: Core Application Functionality

Create a main view that immediately informs users of the latest earthquake. Essential information to display includes:

- Magnitude
- Intensity (if available)
- Date and time (localized for the user)
- Location (city or nearby landmark)
- Map Visualization clearly indicating the earthquake's epicenter.

## Part 2: Global Earthquake Overview

If no recent earthquakes occurred in Peru, provide a simple list of the last 10 earthquakes globally. The list should include:

- A small indicator with the flag of the country where the earthquake occurred.
- Magnitude of the earthquake.
- Intensity (if available).

## Part 3: User Experience and Interface Design

We encourage you to propose and justify your ideal user interface, referencing best practices from successful similar applications:
- Briefly mention in the README why you chose your specific layout or show us your sources of inspiration.
- Prioritize clarity, ease of use, and quick navigation


# Bonus Points

## Part 4: Background Data Fetching and Notifications

Utilize the Background Fetch feature in iOS or 

- Periodically fetch global earthquake data and send informative notifications, such as: "An earthquake of magnitude X occurred in [Country] X minutes ago.
- Allow users to open the app clicking in teh notification to see the last earthqyakes details

## Part 5: Testing
- Include comprehensive unit tests for key functionality, such as API data handling and parsing.
