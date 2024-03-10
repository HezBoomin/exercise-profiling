# Profiling Exercise

`/all_students`
![ss-all-students.png](./ss-all-students.png)
`/all_students_name`
![ss-all-students-cmd.png](./ss-all-students-cmd.png)
`/highest_gpa`

`all-student-name`
![ss-all-students-name.png](./ss-all-students-name.png)
![ss-all-students-name-cmd.png](./ss-all-students-name-cmd.png)

`highes-gpa`
![ss-highest-gpa.png](./ss-highest-gpa.png)
![ss-highest-gpa-cmd.png](./ss-highest-gpa-cmd.png)

# Optimiztion Result

`all-student`
![ss-all-students-cmd-optimize.png](./ss-all-students-cmd-optimize.png)
`all-student-name`
![ss-all-students-name-cmd-optimize.png](./ss-all-students-name-cmd-optimize.png)
`highest-gpa`
![ss-highest-gpa-cmd-optimize.png](./ss-highest-gpa-cmd-optimize.png)

## Conclusion

for `all-student` we got improvement of around 100% in runtime, for `all-student-name` we got improvement of around 98% in runtime, for `highest-gpa` we got no significant improvements in runtime.

# Reflection

1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?

The difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of 
optimizing application performance is that JMeter is used to test the performance of an application by simulating a large number of users 
and measuring the response time of the application under load. On the other hand, IntelliJ Profiler is used to analyze the performance of an 
application by profiling the code and identifying bottlenecks and performance issues in the application.

2. How does the profiling process help you in identifying and understanding the weak points in your application?

The profiling process helps in identifying and understanding the weak points in the application by analyzing the performance of the code and
identifying bottlenecks and performance issues. By profiling the code, we can identify the parts of the code that are taking the most time to
execute and optimize them for better performance. Profiling helps in understanding the performance characteristics of the application and
identifying the areas that need to be optimized for better performance.

3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?

Yes, IntelliJ Profiler is effective in assisting to analyze and identify bottlenecks in the application code. It provides detailed information
about the performance of the code and helps in identifying the parts of the code that are taking the most time to execute.

4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?

The main challenges faced when conducting performance testing and profiling in Intellij profiling are searching for the function
we want to look for and understanding the result of the profiling. I overcome these challenges by reading documentation and asking friends
who already understand Intellij profiling.

5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?

The main benefits of using IntelliJ Profiler for profiling the application code are that it provides detailed information about the
performance of the code and helps in identifying the parts of the code that are taking the most time to execute.

6. How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?

I handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing
using JMeter by analyzing the results from both tools and identifying the areas that need to be optimized for better performance. I also
compare the results from both tools and look for any discrepancies to understand the performance characteristics of the application.

7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?

The strategies I implemented for optimization is by using stream() method for all-student and all-student-name, and using max() method for highest-gpa. 
I ensure the changes I make do not affect the application's functionality by testing the application after making the changes and ensuring that it still works as expected.


