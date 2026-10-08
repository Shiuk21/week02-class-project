# Week 02 Class Project

## Purpose
The program reads two numbers from the user: volts, then ohms and checks if that input is usable. If it's not then it will print invalid input and stops. And if it is then it'll divide the volts given by ohms and prints the value.

## Input format
(Two numbers separated by a space: volts, then ohms.)

## Build and run
    g++ -std=c++17 -Wall -Wextra -pedantic src/main.cpp -o build/app
    ./build/app

To run the acceptance tests:

    bash test.sh

## Example
Input: `12 4`
Output: `Current: 3 A`

## Limitations
It can only run one calculation per run and it can't run numbers below 0. 

## Debugging reflection
I was having troublw figuring out how to set up the github repositories and the pull request