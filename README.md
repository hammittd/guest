- Make the UI aware that a user is currently authenticated
  - Needs testing

- Allow a currently authenticated user to log themselves out
  - Needs testing

- Use bootstrap styling to make shit pretty
  - Use bulma

- Show list of other users that have logged in

- Post to message board
- Support annoymous messages
- Support messages for users that are logged in.
  - Messages for user that are logged in should show their information

- Authentication stuff
  - I would like the system to tell me when my registration was successful
    - Need a success page

  - I would like the system to tell me when my registration is not successful
    - Currently this is buggy - on registerRetry, it's possible to have a "successful" registration
    that makes the db scream. I don't know why valReg isn't being called when POSTing from registerRetry

BUGFIXES PLZ
  - i can register with the same account twice
    - not anymore!
  - I CAN SIGN UP WITHOUT A FIRST NAME
    - no more first name, just email
  - I CAN SIGN UP WITHOUT A LAST NAME
    - no more last name, just email
  - I CAN SIGN UP WITHOUT A PASSWORD?!
    - not anymore!
  - I CAN SIGN UP WITHOUT A USERNAME?!
    - not anymore!
