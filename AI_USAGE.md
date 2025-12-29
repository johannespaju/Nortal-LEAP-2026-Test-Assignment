# AI Usage

Used Claude's Sonnet 4.5 and Opus 4.5 models during the process.

Started with asking about the technologies used in this project (e.g. Java Spring Boot) that I hadn't had any prior experience with.<br>
Examples after I had uploaded the README.MD and it had knowledge about the project:
~~~ssh
I have experience in Java but not in Spring Boot. What should I know?
What is jpaRepository in Java Spring Boot?
~~~
During the work I used AI as a senior engineer with whom to discuss the code, go line-by-line, find bugs and do code reviews.<br>
Examples:
~~~ssh
explain how the following code works in detail: *relevant code snippet*
is this correct, be critical and explain errors in detail: *relevant code snippet*
You are a senior software engineer. Perform a code review with clear reasoning. *libraryservice.java*
What are best fixes for issue #3? Give multiple options with pros and cons
When a user with 5 books borrowed tries to reserve a book it gives error. Why? *relevant code snippet*
Compare x and y for solving z problem
~~~

I had it go over all the code I wrote and critique it. When it offered a fix I thought over it myself and if asked more
clarifying questions to get a better understanding when needed.