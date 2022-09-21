# DAT250: Software Technology Experiment Assignment 4

I used the Thunder Client extension for VS Code instead of Postman to test the API routes.
I did not have to install anything for this assignment.

In experiment 1 I was able to send a PUT request with updated data, and send a GET request to receive the updated data.

In experiment 2, GET, POST, PUT and DELETE methods were implemented and all test cases were passed.
The only issue I encountered was that for a while I could not figure out why the expected result from GET on a non-existing id did not match the actual result. The reason was simply that the expected string has an extra space character before the quoted id.

[GitGub repo](https://github.com/oliver-oloughlin/dat250-sparkjava-counter)