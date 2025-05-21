# Meeting Name: Storage Team Meetup

## Time of Meeting: 8pm 

## Attendance: Rosario, Charan

## Sprint Goals
 - Storage team: implement read card, delete card
   
## Agenda 
- Compare progress on LocalStorage protyping, createCard() implementation
- Define GitHub issues for readCard(), updateCard(), deleteCard()


## Progress Comparison 
- Charan already implemented CRUD functionality in a branch `localStorageProto` including mock frontend 
  - Create card implementation includes fields for habitname, description, frequency, next occurrence, theme, reminder time, and streak ),
  - - Update functionality is the same as trying to create with the same name
- Rosario implemented createCard() on another branch, `backend-create-card`
  - Create card implementation includes fields for habitName, frequency, first occurrence, and a parameter for the storage method being used
  - Untested in browser 

## Implementation Decisions: 
- Read:
  - When you open app, calls read to display cards that should be showing
  - Separate read function for accessing card streaks within calendar views 
- Update:
  - takes cardID, params wanting to update, new values and updates the values on the list
  - Streak count, next occurrence increases when a card is tapped
- Delete:
  - if you call, will delete 1 entire card 

## Next steps: 
- Rosario:
  - Implement readCard()
  - Implement updateCard()
  - Write GitHub Issues related to CRUD function implementation
- Charan:
  - Merge our implementations onto a single branch 
  - Implement deleteCard()
- Team: text frontend team (Trisha, Travis, ...) to come to a consensus on data fields included in one card
 
## General Notes:
- Charan will be out of town Thurs & Fri, will be home for memorial day weekend (available remotely), will join monday meeting 

## End of Meeting: 8:30 
