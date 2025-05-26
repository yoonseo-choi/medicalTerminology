# Overview

This repository aims to create a flash card app capable of storing custom user vocab cards and creating a knowledge assessment in the form of a multiple choice quiz.
It was motivated by Quizlet's subscription plan for using the "quiz" feature, which I did not want to pay for. However, I felt the need to have this feature to 
learn the terminology in the most effective way.

# File Structure

The repository is constructed as a simple single-level structure and consists of a yaml file to allow for users to input their data in a human readable format and a python driver file.

- flashcards.yaml - vocab card data
- quiz_mc.py - driver file that parases yaml file and runs the quiz application
