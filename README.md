# Module 4 Challenge. **School District Analysis**

## Overview of Project

### Background
In this Module, we worked along with Maria so we could get trends and patterns of standardized test scores based on the information of the schools of the District. 
But the school board notified Maria and her supervisor that the `students_complete.csv` file shows evidence of academic dishonesty; regarding the reading and math grades for Thomas High School ninth graders. 
The tasks are the following:

1. We have to delete all the altered grades and replace them with NaNs, while keeping the rest of the data intact
2. Repeat the school district analysis that we did in the module.
3. Write up a report to describe how these changes affected the overall analysis.

##  Resources

* **Data Source:** `schools_complete.csv` and `students_complete.csv`

* **Software:** Jupyter Notebooks, Python 3.6.8.


##  Challenge Summary

-   How is the district summary affected?

| Original District Summary | Clean District Summary |
|--|--|
| ![District Summary](https://user-images.githubusercontent.com/90414330/138631955-cd0ee5f6-2c9f-4fff-afa5-4461dc60838d.png)|![Clean District Summary](https://user-images.githubusercontent.com/90414330/138631953-9b3e52f0-04a4-4390-8210-14e4306a035f.png)  |

Although there were delated 461 registers; the percentage of students that passed Math, Reading, and both assignments didn't seem to change at all. The only noticiable change is that the Average Math Score was adjusted by ten percentage points.

-   How is the school summary affected?

| Original School Summary | Cleaned School Summary |
|--|--|
|![School Summary THS](https://user-images.githubusercontent.com/90414330/138635943-84c6f4b7-2884-42f8-ab84-2fab5ff9c76d.png)![School Summary](https://user-images.githubusercontent.com/90414330/138636161-4290094b-d2fa-4b46-87e8-0c9c72973067.png) |![Clean School Summary THS](https://user-images.githubusercontent.com/90414330/138635941-fff9d898-25cf-4f35-95b7-216b59e7b86c.png)![Clean School Summary](https://user-images.githubusercontent.com/90414330/138636162-3c44cae6-5906-470b-a860-b7cc3ca02738.png) |

The Data changed drastically for the percentage results of the Thomas High School. Curiously, the students that passed the subjects increased, which suggest that the data of the 9th graders was negatively altered.

-   How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

We can see in the above charts that the performance of other schools didn't change, so the schools aren't linearly related. Which means that the grades of the 9th graders in Thomas High School don't have impact in the other schools.

-   How does replacing the ninth-grade scores affect the following:

-	- Math and reading scores by grade
The only difference is that we don't have average scores for the 9th graders.

| Math Scores by grade | Reading Scores by grade |
|--|--|
| ![Clean Math Score per Grade](https://user-images.githubusercontent.com/90414330/138640443-308f8d13-6f1c-4f9a-bc0a-50e859ec6cf0.png) | ![Clean Reading Score per Grade](https://user-images.githubusercontent.com/90414330/138640446-5256a742-0be9-4510-bf7e-6f9bd5e3441a.png) |


-	-   Scores by school spending

Since the School Spending per Capita in the Thomas High School belongs to the 3rd range; the data should only be affected in that range.

![THS Spending Ranges](https://user-images.githubusercontent.com/90414330/138642352-b14f4a1d-0b1a-477c-84b4-827406c2a818.png)


| Original Scores by school spending | Cleaned Scores by school spending |
|--|--|
| ![Spending Ranges](https://user-images.githubusercontent.com/90414330/138641154-185c7605-0dcd-4c0f-9cf1-3e53d5943321.png) | ![Cleaned Spending Ranges](https://user-images.githubusercontent.com/90414330/138641140-c214a50c-8a3b-4475-bd3d-b92e8743feff.png) |

Note that the percentage of students that passed Math increased by 1 percentage point in the last range.

-	-   Scores by school size

Curiosly, the Medium and Large School Size Stats changed although the Data we modified belonged to the Small Bin.

| Original School Size | Cleaned School Size |
|--|--|
| ![School Size](https://user-images.githubusercontent.com/90414330/138643256-f452366c-886c-4b5b-a851-276e1979fa04.png) | ![Clean School Size](https://user-images.githubusercontent.com/90414330/138643257-fc46fcb4-4bc1-4c0c-8c51-0a2ff908ab56.png) |


-	-   Scores by school type

The Stats by School Types didn't seem to change at all.

| Original School Size | Cleaned School Size |
|--|--|
| ![School Type](https://user-images.githubusercontent.com/90414330/138643255-288c797f-d288-480e-8e52-e9fb6758681e.png) | ![Clean School Type](https://user-images.githubusercontent.com/90414330/138643253-0cecf520-b67e-449a-b2b0-ef6ec716e9a9.png) |


### Summary
Finally, the changes we noticed were:

1. The Stats in Thomas High School increased drastically.
2. In the Spending Ranges Summary, the percentage for the students that passed each subject, and both of them at the same time increased by 3 percentage points.
	- The percentage of students that passed Math increased by 1 percentage point in the last range.
4. In Scores by School Size, the Medium and Large bins changed although the data we modified belonged to the Small Bin. The Medium bin was the most affected.

By the change '1.', the changes suggest that the data of the 9th graders was negatively altered.

> Written with [StackEdit](https://stackedit.io/).
