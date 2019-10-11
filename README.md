# Learning-Managemnet-System
lms project using c++
                    OVERVIEW OF THE PROJECT
You are required to develop a University Learning Management system. Every student enrolled in
the university will have account on your Learning Management System. Account will contain
Courses enrolled for a student, Grade Book (showing the GPA and CGPA of student), Account
Book (providing the fee system), and Profile of the Student. Profile of the student will contain
personal information of the student and status of the student in the university. Every student will
have a unique ID and password to login on your Learning Management system. Administrator can
add a new course. Administrator can print all Data of the student.


...................DATA VALIDATION...............
Each course will have the following data.
• Course Code (First two characters of code are alphabets and next 3 characters are digits)
• Course Name (Only alphabets and space characters are allowed, Maximum 50 characters)
• Credit Hours (Allowed values are 1 to 3)
• Semester (Allowed values are 1 to 8)

.... Students will be managed with the
following attributes.........
a) a) Name of Student
b) b) Registration Number of Student
c) c) Courses of the student
2. Create the following arrays
a) a) stdNamesList : Text
b) b) stdRegNoList: Text
c) c) stdCourseList: Text (Two-dimensional (2D) array)

                FUNCTIONS
bool isValidCourseCode(code: Text)
• bool isValidCourseName(name: Text)
• bool isValidCreditHours (crdHrs: Integer)
• bool isValidSemester(semester: Integer)
• void AddCourse(codeList: Text Array, nameList: Text Array, crtHrsList: Integer Array, semList:
Interger Array, courseCode: Text, courseName:Text, crdHrs:Integer, semester:Integer)
• void EditCourse(codeList: Text Array , nameList: Text Array , crtHrsList: Integer Array,
semList: Interger Array, courseCode: Text, courseName:Text, crdHrs:Integer, semester:Integer)
• void DeleteCourse(codeList: Text Array , nameList: Text Array , crtHrsList: Integer Array,
semList: Interger Array, courseCode: Text)
• void ViewCourses(codeList: Text Array , nameList: Text Array , crtHrsList: Integer Array,
semList: Interger Array)
• void ViewSemesterCourses(codeList: Text Array , nameList: Text Array , crtHrsList: Integer
Array, semList: Interger Array, semester:Integer)
You are required to develop following functions regarding Course Management.
• bool saveCourses (codeList: Text Array, nameList: Text Array, crtHrsList: Integer Array,
semList: Interger Array)
• bool loadCourses(codeList: Text Array, nameList: Text Array, crtHrsList: Integer Array,
semList: Interger Array)
• void addStudent(stdNamesList:Text Array, stdRegNoList: Text Array, studentName: Text,
 regNo:Text)
• void updateStudent(stdNamesList:Text Array, stdRegNoList: Text Array, studentName:
Text,
 regNo:Text)
• void deleteStudent(stdNamesList:Text Array, stdRegNoList: Text Array, stdCourseList:
Text Array, regNo:Text)
• void registerCourse(stdRegNoList: Text Array, stdCourseList: Text Array,
courseCodeList: Text, regNo:Text, courseCode:Text)
• void unRegisterCourse(stdRegNoList: Text Array, courseList: Text Array, regNo,Text,
 courseCode:Text)
• bool isValidRegistrationNumber(regNo:Text) – Acceptable Format 201X-CY-001
• bool isValidStudentName(regNo:Text) – Use same rules as per course name.
• saveStudents(RegNoList: Text Array, StdNameList: Text Array, StdCourseList: Text Array)
