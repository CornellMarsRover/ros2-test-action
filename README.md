# ros2-test-action
Custom test github action based off https://github.com/autowarefoundation/autoware-github-actions/tree/main/colcon-test

This is based off v1 of colcon-test, and currently just adds an optional argument `pytest-args` which 
is a string of arguments to pass to pytest. Any pytest arguments that are the same as `colcon-test` arguments
should be preceded by a space (ex. " --help" instead of "--help")
