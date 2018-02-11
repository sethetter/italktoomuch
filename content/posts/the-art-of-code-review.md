---
title: The art of code review
author: Seth Etter
draft: true
---
# Approach the code from a user perspective

- Make sure you fully understand what the code is intended to do

- Think of motivation behind the code
  - Write out an explanation of the functionality
    - Simulates "teaching to learn"
- Think of another way it could be done
- Think about what happens when erroneous data makes it to the new code
- Check that there is proper handling of potential erroneous data
- Can anything be ommitted?
  - Ask what would happen if each line/section of code was removed?

# Approach it from a developer perspective

- Follow the flow of data, log it out and visualize it if you have to
