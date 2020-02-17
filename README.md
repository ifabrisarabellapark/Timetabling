# Timetabling
The files in this repository support the research presented in the academic article: 

"Optimizing Student Course Preferences in School Timetabling"
by Richard Hoshino and Irene Fabris, 

which will be officially presented on May 26-29, 2020 at the 17th International Conference on the Integration of Constraint Programming, Artificial Intelligence, and Operation Research (CPAIOR). These scripts generate the optimal master timetable for the 2019/2020 academic year for St.Margaret's School (SMS), in Victoria, BC, Canada.


### Content
SMS Timetabling

1. Input files:
- SMS Optimal Timetabling Program.ipynb
- SMS Student Data.xlsx --> Students' course preferences
- SMS Course Data.xlsx --> Course attributes and teachers' qualifications 

2. ILP files:
- SMS Optimal Timetabling Program.ipynb --> simple timetable generator
- SMS Graph Colouring.ipynb --> timetable generator deploying graph coloring to pre-bundle courses into cohorts
- SMS Graph Colouring Multiple Trials.ipynb --> timetable generator deploying graph coloring. Multiple attempts are shown.

SMS Proof of Concept
1. Input file:
- Input Data.xlsx --> arbitrarily made up Proof of Concept data for students' course preferences

2. ILP file:
- Proof of Concept.ipynb --> timetable generator

### Prerequisites
The script relies on the following packages: 
- time 
- numpy 
- pandas 
- networkx 
- grinpy 
- random 
- ortools.linear_solver (pywraplp function)
