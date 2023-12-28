# expected-actual-tps-jmeter

## Prerequisite
- Jmeter

## About this project:
This is a random API from where we can get the list of the users. Here we used jmeter to find the expected throughput/second and whether the actual throuput/second match the expected throughput/second or not. Our condition was to check the TPS for 120000 loads for 12 hours.

## How to run this project:
-You need to set path of java home and jmeter home in environment variables.
- clone this project
``` https://github.com/mashruf/expected-actual-tps-jmeter ```
- In the source root project, give the following command:
``` jmeter -n -t load-test.jmx -l load-test.csv -e -o report ```



![tps](https://github.com/mashruf/expected-actual-tps-jmeter/assets/50927464/01615855-383e-42a8-b0ed-89f13a2c3083)



![Capture](https://github.com/mashruf/expected-actual-tps-jmeter/assets/50927464/e0442bd9-4641-447f-a66c-b79a1190e61b)

