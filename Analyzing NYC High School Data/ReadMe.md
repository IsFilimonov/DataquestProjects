## Briefing
For a brief bit of background, the [SAT](https://en.wikipedia.org/wiki/SAT), or Scholastic Aptitude Test, is a test that high school seniors in the U.S. take every year.
The SAT has three sections, each of which is worth a maximum of 800 points. Colleges use the SAT to determine which students to admit. High average SAT scores are usually indicative of a good school.

## Introduction into data
New York City has published data on [student SAT scores](https://data.cityofnewyork.us/Education/SAT-Results/f9bf-2cp4) by high school, along with additional demographic data sets. Over the last three missions, we combined the following data sets into a single, clean pandas DataFrame:
* `SAT scores by school` - SAT scores for each high school in New York City
* `School attendance` - Attendance information for each school in New York City
* `Class size` - Information on class size for each school
* `AP test results` - Advanced Placement (AP) exam results for each high school (passing an optional AP exam in a particular subject can earn a student college credit in that subject)
* `Graduation outcomes` - The percentage of students who graduated, and other outcome information
* `Demographics` - Demographic information for each school
School survey - Surveys of parents, teachers, and students at each school

## Challenge
New York City has a significant immigrant population and is very diverse, so comparing demographic factors such as race, income, and gender with SAT scores is a good way to determine whether the SAT is a fair test.
