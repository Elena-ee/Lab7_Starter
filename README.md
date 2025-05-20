// Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

1. Within a Github action that runs whenever code is pushed
This way, the tests will run automatically whenever someone pushes code and so bugs can be caught early, which is good for debugging and makes future development smoother.


// Would you use an end to end test to check if a function is returning the correct output? (yes/no)
No.
Because e2e tests are meant to check whether the entire software works as expected from the user's perspective - as a complete, finished product. If we're just testing a single function, a unit test would be more appropriate.






