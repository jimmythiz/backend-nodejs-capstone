# User Story

**As a** customer

**I need** to search for second-hand items

**So that** I can quickly find products I want to buy.

## Details and Assumptions

- The search should allow keyword matching.
- Items are stored in MongoDB.

## Acceptance Criteria

```gherkin
Given the database contains items
When I search for a keyword
Then matching items should be displayed
```
