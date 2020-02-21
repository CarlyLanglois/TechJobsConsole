# Java Graded Assignment #1 Rubric (TechJobs, Console Edition)

For this assignment, the students were asked to complete a console app that allows users to browse, search, and print listings of open jobs.

The most efficient way to grade this assignment is to have each of your students demonstrate their project for you. This saves you from having to clone each person's repository to your machine and then examine, run, and test the code.

## Score your students' work based on the following criteria:

### Appearance & Behavior: 

1) Have your student launch their console app. It should begin with a user prompt that looks similar to:
    
    ```
    Welcome to LaunchCode's TechJobs App!
    View jobs by:
    0 - Search
    1 - List
    ```

2) Select Search, then Location, then enter "new YORk" (or "new york", or "New york", etc.) to confirm that the search function is case-insensitive. One result should be printed:

    ```
    View jobs by:
    0 - Search
    1 - List
    0
   
    Search by:
    0 - All
    1 - Position Type
    2 - Employer
    3 - Location
    4 - Skill
    3
   
    Search term:
    new YORK
    ```
			
3) Next, select List --> All. This should print lots of jobs with each of the 5 fields displayed.
4) Next, select Search --> Location --> "Chicago". This should print a reasonable "No results found" message.
5) Next, select Search --> All --> "ruby". This should display 4 results.

    ```
    *****
    position type: Web - Front End
    name: Junior Web Developer
    employer: Cozy
    location: Portland
    core competancy: Ruby
    *****
   
    *****
    position type: Web - Full Stack
    name: Full Stack Engineer
    employer: Splitwise
    location: Rhode Island
    core competancy: Ruby
    *****
   
    *****
    position type: Other
    name: QA Analyst
    employer: Bandcamp
    location: New York
    core competancy: Ruby, Javascript
    *****
        
    *****
    position type: Web - Back End
    name: Ruby specialist
    employer: LaunchCode
    location: Saint Louis
    core competancy: Javascript
    *****
    ```

6) Finally, select List --> Position Type. This should produce the following list. The order is not important, since alphabetizing the output is a bonus mission.

    ```
    *** All Position Type Values ***
    Data Scientist / Business Intelligence
    Mobile Developer
    Other
    Project Manager / Analyst
    Quality Assurance Analyst
    Software / Enterprise Developer
    System Admin / DB Admin / Network Support
    Technical Assistent / User Support
    Technical Writer
    Web - Back End
    Web - Front End
    Web - Full Stack
    ```    

### Code check: 
Since the starter code for this project was largely complete, there is no need to dive deep into the students' code to check for best-practices (this time). 
As they demo their work, you can ask them questions to clarify what their code is doing. Can the student give an explanation of
what a given line or code block accomplishes? These questions help the students practice talking about their code, a crucial skill for job placement.

## Feedback and Grades:
    
If a student's work meets the appearance and behavior requirements, assign them a score of 1/1 in Canvas. If a student's work misses one of the checks, provide them with detailed feedback about which parts need to be improved.
Since the bonus missions are optional, they should NOT determine whether a project passes. However, any mistakes in these attempts should be mentioned to the student along with tips for making the code work better.
Provide feedback for successful projects as well. Acknowledgement of the student's work helps encourage further learning and effort. Encourage best practices and point out ways to make code more readable or efficient. Even working code can be improved.
