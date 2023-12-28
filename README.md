# expected-actual-tps-jmeter

## Prerequisite
- Jmeter

## About this project:
This is a random API from where we can get the list of the users. Here we used jmeter to find the expected throughput/second and whether the actual throuput/second match the expected throughput/second or not.

## How to run this project:
-You need to set path of java home and jmeter home in environment variables.
- clone this project
``` https://github.com/mashruf/expected-actual-tps-jmeter ```
- In the source root project, give the following command:
``` jmeter -n -t load-stress-test.jmx -l load-stress-test.csv -e -o report ```
