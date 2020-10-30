# ML and Data Analytics Tasks
This repository contains synapse tasks
Task 1 is Project Synopsis on NLP-Text Similarity
Task 2 is on Data Cleaning and Data Visualisation

A user has a new concept for a 3-speed bicycle made from recycled parts with a $20 price point. He wants to send a push notification to other interested people on the internet, prompting them to fund the project. However, he doesn't want to send a message to everyone, only those who they think would be interested.
That's where you come in. You're a resident data expert. You'd like to create a visualization that helps answer: what kinds of users would be interested in the bicycle project?
Luckily, you've been collecting analytics data on who would be interested to fund projects based on attributes like location, age range, gender, and mobile device.

Your analytics software tracks the events: "View Project" and "Fund Project," for when a user views details about a project and for when they fund a project. The events also have the following attributes:

category: what the project is about, e.g. "Sports", "Fashion", "Technology", etc.
client_time: a UNIX timestamp of when the event occurred.
amount: how much the user donated (for "Fund Project" only)
Note: The bicycle project belongs to two categories: "Sports" and "Environment."

Additionally, you know some information about each user on your site, that they supplied in a survey when they signed up. Specifically, you know:

session_id: unique identifier for each user
age range: one of ['18-24', '25-34', '35-44', '45-54', '55+']
gender: one of ['M', 'F', 'U']
location:
city: a city in the United States
state: a state in the United States
latitude
longitude
marital_status: one of ['single', 'married']
device: one of ['iOS', 'android']
From past experiments, you know that each user generally likes projects from the same category. For example, User A almost always views and funds projects from the "Technology" category. The bicycle project belongs to two categories: "Sports" and "Environment."

You have a sampled time series of 50,000 events from one month this year in a JSON blob. User data is added into every event.
