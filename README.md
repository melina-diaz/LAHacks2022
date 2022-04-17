# LAHacks2022

Project Name: Mapping Employees

By Melina Diaz and Tracy Charles

Description:

We created a tool a company can use to see where its employees are living based on available data. This information is intended to help companies decide where to build offices. In this project, we used the Person Search API from People Data Labs to obtain the necessary data in a .csv file.

Input:

User can input the name of a company and the number of employees per call.

Output:

The main output of the function is an interactive map plot with points for each employee. The red point represents the company headquarters and the rest are points of the employee addresses. If you hover on a point, you will be able to read their latitude, longitude, job title, and latest school.

The function also outputs a .csv file with necessary information on the job and locations.

An HTML file of the plot will also be saved in the working directory.

Here is an example of the plot:

![image](https://user-images.githubusercontent.com/81223941/163709070-6f7fee81-4d86-4061-88d1-e476731a8fdd.png)

How to Demo:

Run the Jupyter Notebook file `mapping_employees.ipynb`. User will need an API Key from the People Data Lab's API. Using appropriate inputs will result in an interactive plot, a saved HTML file of the plot, and a .csv file with certain variables.
