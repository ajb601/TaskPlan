## User Stories
# User Story 1
USER STORY:  As a general user I want to be able to sign up or sign into the app and have it save my email and password in the Firebase backend so that I can access the app  
ACCEPTANCE CRITERIA:  
- A screen that hosts inputs for email and password, with a password confirmation, as a sign up screen
- An option to change inputs to just email and password, as a sign in screen
- User data should be successfully saved into the FireBase backend
- Users should be able to create an account with a unique email and password and use it to sign up for the app and use those credentials to sign into and use the app
- The app should handle incorrect login/signup attemps with a clear error message

# User Story 2
USER STORY:  As a user, I want to be able to set tasks and scheduling reminders by using the TaskPlan app and have it save and execute said reminders                                                                               
ACCEPTANCE CRITERIA:  
- Users can create tasks with titles, descriptions, and set reminders with set dates/times
- TaskPlan should save the created tasks/reminders when the user sets them
- Reminders should trigger an alert at date/time set and based on how many reminders they want
- Users can mark tasks as complete and delete/edit tasks

# User Story 3
USER STORY: As a user, I want to be able to view my created tasks in a calendar view in the TaskPlan app as well as see the details of my created task including ETA.  
ACCEPTANCE CRITERIA: 
- A calendar screen to view tasks in a calendar view
- Clicking on a task will display its details
- Easy navigation through months, days, years

# User Story 4
USER STORY: As a user, I want to be able to easily delete my created tasks when I am done with them/do not want them anymore using the TaskPlan app. 
ACCEPTANCE CRITERIA:  
- The app provides a delete option
- Deleting should be safe and not cause issues with other bits of information
- A prompt should appear allowing the user to confirm the delete
- Tasks should be subsequently removed from the database after deletion

# User Story 5
USER STORY:  As a user, I want to be able to be reminded of when I should leave my house to be on time with TaskPlan.
ACCEPTANCE CRITERIA:  
- Users can set their home address and then set the location of their meeting on the reminders
- The app calculates the time between the locations
- Reminder is sent to user when it compares the time between when they should leave and the time between their locations

# User Story 6
USER STORY: As a user, I want the TaskPlan app to have an aesthetically pleasing and visually engaging interface so that I can enjoy the app.
ACCEPTANCE CRITERIA:  
- Consistent Color Scheme
- Clean Design
- Visuals Load Efficiently
