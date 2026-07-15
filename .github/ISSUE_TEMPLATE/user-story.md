---
name: User Story
about: This template defines a user story
title: ''
labels: ''
assignees: ''

---

## User Story

**As a** customer

**I need** to search for restaurants by location

**So that** I can quickly find restaurants near me.

### Details and Assumptions

* Restaurants already have latitude and longitude stored.
* Search uses the Google Maps API.
* Results are sorted by distance.

### Acceptance Criteria

```gherkin
Given I am on the home page
When I search for "Victoria Island"
Then I should see restaurants located in Victoria Island

Given no restaurants exist in the searched location
When I submit the search
Then I should see a message saying "No restaurants found."
