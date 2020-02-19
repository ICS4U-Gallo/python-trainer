# python-trainer

Provides a set of Python exercises to complete within a specific time-frame (10 minutes a day).

## Functionality
- Track user progress within the various sections (Intro, Strings, If-Statements, etc..)
- Track user progress within subsections.
- Provide set of exercises ([fundamental](#fundamental-exercises) and [practical](#practical-exercises)) increasing in difficulty according to user completion history and level of [mastery](#mastery).
    - Two/three warm up questions
    - One/two less-mastered *fundamentals*
    - One *practical* exercise
    - Repetition of exercises/fundamental subsections is necessary from time to time, based on level of [mastery](#mastery). Similar exercises might be prescribed for multiple days until a sufficient level of mastery is attained and then occasionally prescribed as warm up questions to maintain the mastery status.
    
### Teacher
- Has classes
- Each class has a roster of students
- Teachers can track progress/level of mastery of each student.
- Identify whether students are not practicing or struggling.
- Identify fundamental/practical exercises that either have a low success rate or take a long time to complete.


## Fundamental Exercises
Non-specific, common coding patterns within a section that, together with other fundamental skills/patterns, are required to solve larger, more complicated practical questions. For example, the ability to print out the numbers from `0` to `10` using a loop. While not particularly useful on the surface, is a required skill to be able to accomplish specific, practical problems like looping over indicies of a list of student marks in order to find the highest mark.

## Practical Exercises
Real-world, practical exercises that would be considered useful and specific. These involve a problem solving component and almost always rely on a collection of [fundamental](#fundamental-exercises) skills/patterns to be able to solve.

## Mastery
Calculated based on success rate of a particular subsection or exercise as well as how quickly the user can complete the task. For example, a 100% success rate on an exercise that takes the user 10 minutes to complete is not a display of mastery.
