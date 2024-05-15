# CSE 110 Lab 6

Name: Sanjith Devineni

1. Option 1. Within a GitHub Action that runs whenever code is pushed. This is because it is the best location for the testing to occur in the development pipeline. If we run them all after development is completed, then there it doesn't follow the efficient procedure of CI and CD, where code is continuously developed, pushed and tested. Additionally, there is more documentation and more logs of the code and the results of the testing if they are run remotely compared to locally.
2. No, you would not use an end to end test to check if a function is returning the correct output. This is because end to end tests are used to test cases that involve user actions and how the user might operate the product. To check the output of a function, we would use a different test that is more specific to the function that would allow us to recognize the error in the function.





