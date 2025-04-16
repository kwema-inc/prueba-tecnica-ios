# Earthquake Tracking App - Technical Challenge
## Objective

Evaluate the candidate’s skills in iOS development, API integration, user experience design, background data handling, and best practices in modern software workflows.

## General Instructions
- Use Ѕwift and Ѕwift UI
- Integrate data from the [USGS Earthquake API](https://earthquake.usgs.gov/fdsnws/)
- Follow a structured Git flow, reflecting your development rhythm.
- Push your work incrementally and explain your reasoning wherever it helps. Include a README.md.
- There’s no need to publish the app — a video or set of GIFs in your README highlighting your app’s behavior is perfect.
- *Push frequently, and make your commits meaningful* — don’t leave everything for one final shot. Let us see how your process shakes out over time.
- You’re free to adopt any Git branching strategy, just avoid pushing directly to main/master unless absolutely necessary.

# Challenge Description

Imagine living in Peru, one of the most seismically active countries on the planet. Right after an earthquake, your first instinct is to pull up key information: magnitude, location, intensity. Sadly, the local geological institute’s platform often goes offline at those crucial moments — leaving people confused, and vulnerable.

You’re building an app that delivers that missing peace of mind. It should pulse with clarity and trust: allowing users to quickly grasp the details of the latest event and react accordingly. Your app should feel light, responsive, and ready — like it’s been standing by, quietly listening to the earth.

## Part 1: The Epicenter

Create a main view that immediately informs users of the latest earthquake. Essential information to display includes:

- Magnitude
- Intensity (if available)
- Date and time, localized to the user
- Geographical location (zone or city, not just coordinates)
- A map indicating the epicenter

The experience should trigger an instinctual reaction — “okay, I get what just happened.”

## Part 2: Global Earthquake Overview

If no recent earthquakes are registered in Peru, pull in the last 10 global seismic events and show them clearly. This view should include:
<!-- Great use case for RecyclerView with ViewHolders -->
- A small flag representing the country
- Magnitude of the earthquake.
- Intensity (if available).


## Part 3: Visual Flow and User Interface

We’d love to see how you shape this experience — you’re free to structure the UI flow that best represents your design instincts.

- Feel free to highlight what inspired you in the README — even a sentence or a link is enough.
- Prioritize clarity, ease of use, and quick navigation

# Bonus Points

## Part 4: Passive Awareness (Background Fetch & Notifications)
<!-- Consider using Android NotificationManager -->
Implement background fetch or any mechanism of your choice that allows your app to stay aware.

- Periodically pull in new data and send a gentle notification like: “An earthquake of magnitude 6.3 struck Japan 18 minutes ago.”
- If the user taps the notification, open the app.


# Final Tip

We're interested not just in the code, but in how you think. Commit your reasoning, not just your code. Let your `README.md` reflect your decisions.
