# test-splitting-by-files
Showcasing how to split tests and do parallel runs on CircleCI

In this example, we want to run a test job with parallelism: N where N is the total num of test files (see tests/ folder).

Then, for each of the N nodes, they will run just 1 of the test file then.
