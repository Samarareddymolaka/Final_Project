Part 1: Understanding the StudentGen project
Download the source code and import the project using IntelliJ Idea or any other IDE you prefer.
Understand the project stucture:
Packages
Classes
Functionality
Run and test the project to get a deeper undertanding of how it works (remember the persistence mindset!).
Part 2: Implementing the Student and StudentService missing features
Open the Student class (src/com/generation/model/Student.java) and implement the following methods:
 public void enrollToCourse( Course course )
 {
     //TODO implement this method
 }
 
 public boolean isCourseApproved( String courseCode )
 {
     //TODO implement this method
     return false;
 }

 public boolean isAttendingCourse( String courseCode )
 {
     //TODO implement this method
     return false;
 }
 @Override
 public List<Course> getApprovedCourses()
 {
     //TODO implement this method
     return null;
 }
Open the StudentService class (src/com/generation/service/StudentService.java) and implement the following methods:
    public boolean isSubscribed( String studentId )
    {
        //TODO implement this method
        return false;
    }

    public void showSummary()
    {
        //TODO implement
    }
Hint: To show the summary use System.out.println() to print out to the console.

Part 3: Implementing the missing main method features
Implement the method to gradeStudent( StudentService studentService, Scanner scanner ) in src/com/generation/Main.java  to have a fully functional program.

Test the program to verify it works as expected:

Create a new student.
Enrroll the student to few courses.
Grade the student.
Show the students and courses summary and verify that data is correct.
Part 4: Handling exceptions
Register a new user providing a wrong date format.
Modify the createStudentMenu so it handles correctly the exception when a wrong date format is inserted by the user.
Catch the exception and show a proper message to the user.
Part 5: Writing Unit Tests
Write 2 Unit tests for the class StudentService
Write 2 Unit tests for the class CourseService
