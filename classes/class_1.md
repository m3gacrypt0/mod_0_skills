# extracurricular_club (class)

## attributes of class extracurricular_club:
1. name (string)
2. max_num_students (integer)
3. default_meeting_location (string)
4. default_meeting_day (string)
5. description (string)
6. satisfies_pe_requirement (boolean)
7. initial_fee_to_join (float)
8. students_enrolled (array of strings)

## methods of class extracurricular_club:
1. enroll_student (adds student to the students_enrolled array)
2. withdraw_student (removes student from the students_enrolled array)
3. calculate_fees (calculates fees paid to school by multiplying the initial_fee_to_join by the count of the students_enrolled array and returns a float)
4. calculate_space_available (calculates how many more students may enroll by subtracting the max_num_students from the count of the students_enrolled array and returns an integer)
5. update_description (changes the description attribute)
