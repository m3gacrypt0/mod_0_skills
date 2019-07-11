# spanish (instance of extracurricular_clubs)

## attributes of instance spanish:
1. name (string) = "spanish"
2. max_num_students (integer) = 25
3. default_meeting_location (string) = "Room 125"
4. default_meeting_day (string) = "Tuesday"
5. description (string) = "Practice Spanish with friends."
6. satisfies_pe_requirement (boolean) = false
7. initial_fee_to_join (float) = 50.00
8. students_enrolled (array of strings) = ["Adrian S.","Benny G."]

## methods of class extracurricular_clubs:
1. enroll_student (adds student to the students_enrolled array) // no value on return
2. withdraw_student (removes student from the students_enrolled array) // no value on return
3. fees_generated (calculates fees paid to school by multiplying the initial_fee_to_join by the count of the students_enrolled array and returns a float) = 100.00
4. space_available (calculates how many more students may enroll by subtracting the max_num_students from the count of the students_enrolled array and returns an integer) = 23
5. update_description (changes the description attribute) // no value on return
