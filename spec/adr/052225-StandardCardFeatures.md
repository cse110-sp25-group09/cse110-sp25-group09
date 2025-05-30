# Standardize Card Features
### Standard Card Features
 -  Standard Features:
   - 'habitName'
   - 'habitFrequency' (integer hours of each time it should be used. EX: 24 hours for daily),
   - 'startDateTime' (format: Sun May 18 2025 13:04:28 GMT-0700 (Pacific Daylight Time)) this is from the Date api
   - 'habitDescription' (what the habit needs to accomplish / what it is) on back of card, maybe set limit of characters
   - 'habitStreak' (start at 0 and update) functionality with heat map, might be week 3
### 05-22-25

### Update
- Decided to switch units of 'habitFrequency' from integer number of hours to integer number of days to improve readability
- Decided to add "logs" field to a card.
    - 'logs' (list of date strings representing each day that the habit is completed 
    - DateString is formatted in the same way as startDateTime. Both accept anything guaranteed to be parsable by Date.parse()
 ### 05-29-25
