# Lab 8 - StarterA
Anahi Ayala

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
   - Our automated tests would fit within a Github action that runs whenever code is pushed because, if we push to a different branch and the tests failed, then we know not to merge with the main branch and it saves us from adding "bad code" into our main project.
  
2) No
3) No we would not because a messaging app, the entire thing is about sending messages so that is more of an end to end testing. Since the message feature allows a user to write and send a message, a unit test would most likely test the writing of the message or the sending of the message not both. 
4) Yes becuase it only tests for max legth of the message not anything else, and it is not the main feature it only checks to see if you have maximum 80 characters.