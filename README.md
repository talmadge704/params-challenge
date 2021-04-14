# params-challenge
Create a new repository for this project. Create a Restful API in Express which meets the below processing requirements. The applicaton does not need persistence. It should be in memory.

Service endpoints:

1. GET /students - returns a list of all students

  this endpoint, optionally, accepts query parameters
  
  GET /students?search=<query> - returns a list of students filtered on name matching the given query
  
2. GET /students/:studentId - returns details of a specific student by student id

3. GET /grades/:studentId - returns all grades for a given student by student id

4. POST /grades - records a new grade, returns success status in JSON response (meaning you do not need to actually store the grade in a database. You do need to      validate that the user supplied at least a grade, and a studentId)

5. POST /register - creates a new user, returns success status in JSON response (meaning you do not need to actually store the user info in a database. You do need    to validate that the user supplied username and email)
