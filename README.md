# Pythom-Final-grade-Calculation-README
# Summary
Only a README for the calculation of the final grade for Python class. Displays an algorithm that describes how the final grade should be calculated.
# Requirements
* All grades must add up to the final grade
* To calculate the final grade, grades inputted in must be first multiplied to by the percentage of the final grade and then added together.
* There are five methods of assessment: participation, MindTap weekly assingments, Mindtap exams, SAIL projects, and the final project.

# Psuedocode
1. Significant variables:

  PARTICIPATION - the percentage of the participation grade, initialized as 10%

  MINDTAP_EXAMS - the percentage of the midterm exam, initialized as 10%
  
  MINDTAP_WEEKLY_ASSIGNMENTS - the percentage of the weekly assignments, initialized as 30%

  SAIL_PROJECTS - the perentage of the SAIL project grade, intialized as 20%

  FINAL_PROJECT   -  The percentage of the final project grade, initialized as 30%

2. Instructor inputs the grades for participation, MindTap weekly assignments, MindTap exams, SAIL projects, and final project, sets it as the varables respectively

  participationGrade

  MindTapWklyAssign

  MindTapExam

  Sailproj

  final

3. Calculate final grade

  finalGrade = (participationGrade * PARTICIPATION) + (MindTapWklyAssign * MINDTAP_WEEKLY_ASSIGNMENTS) + \
                  (MindTapExam * MINDTAP_EXAMS) + (Sailproj * SAIL_PROJECTS) + (final * FINAL_PROJECT)
                
4. Display the final grade
# Maintainers
Steven Richardson
