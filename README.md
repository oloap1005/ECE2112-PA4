# ECE2112-PA4
## MENDOZA, PAOLO D. 2ECE-D
### Data Wrangling and Data Visualization

### Intended Learning Outcomes:
#### -To identify the codes and functions needed in cleaning and visualizing data
#### -To be able to apply and use the different codes and functions in creating a Python program that will
be used in data wrangling and data visualization


### ECE BOARD EXAM PROBLEM: Using data wrangling and data visualization technique with storytelling, analyze the data and present different (i) data frames; and (ii) visuals using the dataset given.

#### ![image](https://github.com/user-attachments/assets/d7f82734-1904-4176-a3d7-e4b74cce7832)

#### FIRST IS TO IMPORT THE PANDAS LIBRARY.
#### ![image](https://github.com/user-attachments/assets/1d760290-9e36-4cce-8b60-c0a45b71aa07)

### PROBLEM A:
#### ![image](https://github.com/user-attachments/assets/43f1abf0-5163-4d80-a602-1779b15cfa46)

#### READING THE GIVEN FILE 
#### ![image](https://github.com/user-attachments/assets/47ce625f-15e3-473a-8ad4-89d30d37b1f2)
#### CODE TO THE PROBLEM: 
#### ![image](https://github.com/user-attachments/assets/4b33d7e9-c646-46ca-b3c0-a8302df701c7)
 ### EXPLAINING THE CODE:
 #### I USED instru_df TO NAME THE DF 
 #### USING df['Track'] == 'Instrumentation' WHEREIN IT WILL ONLY SHOW SPECIFIC TAKERS WITH THAT TRACK
 #### USING (df['Hometown'] == 'Luzon') THIS SYNTAX FILTERS HOMETOWNS OF THE BOARD TAKERS
 #### (df['Electronics'] > 70)] THIS WOULD ONLY OUTPUT WHOSE MARK IS ABOVE 70
 #### [['Name', 'GEAS', 'Electronics']] THIS OUTPUTS THE GIVEN COLUMNS
 #### OUTPUT OF THE CODE:
 #### ![image](https://github.com/user-attachments/assets/de071e67-49f6-4235-8607-e66e051f16b9)


 ### PROBLEM B:
#### ![image](https://github.com/user-attachments/assets/4f0b0dc9-973e-4806-b544-0c1babb26cd7)
#### FIRST IS THE CODE FOR GETTING THE AVERAGE GRADE\SCORE 
#### ![image](https://github.com/user-attachments/assets/eaa148e8-863a-4ab1-905b-bf3371585266)
#### THE CODE FOR THIS PROBLEM:
#### ![image](https://github.com/user-attachments/assets/3d2be66c-0daf-471f-829d-189d32d7a906)
#### USED .LOC HER AS WELL TO LOCATE THE WANTED DATA TO BE SHOWN
#### JUST LIKE PROBLEM A I USED DF FUNCTIONS TO ISOLATE DATA TO BE SHOWN IN THE TABLE.
#### OUTPUT OF THE CODE:
#### ![image](https://github.com/user-attachments/assets/7b65c2c2-c87f-464c-8a70-063d14957a1a)



### NUMBER 2: 
#### ![image](https://github.com/user-attachments/assets/c5991eba-b65d-4518-b85e-448b84bad5a4)

#### FIRST THING IS TO IMPORT THE MATPLOT LIB LIBRARY USING (import matplotlib.pyplot as plt)
#### FOR THIS WE CAN USE A BOX PLOT AND A BAR GRAPH HERE I WILL SHOW THE TWO TYPES THE FIRST ONE WILL BE THE BOXPLOT AND THE FOLLOWING TWO IS THE BAR GRAPHS
#### THE CODE FOR THE BOXPLOT (EFFECT OF TRACK ON AVERAGE GRADE):
#### ![image](https://github.com/user-attachments/assets/d6465b51-fb99-455e-baf9-2062dba91a84)
#### - df.boxplot(column='Average', by='Track', grid=true)  This line creates a box plot using the boxplot method of the DataFrame df. The column='Average' specifies that the data to be plotted is from the 'Average' column. The by='Track' argument indicates that the box plots should be grouped by the 'Track' column.
#### plt.xlabel('x') THIS LABELS THE X-AXIS AS “track,” WHICH HELPS IN IDENTIFYING WHAT THE X-AXIS REPRESENTS.
#### plt.ylabel('Y') THIS LABELS THE Y-AXIS AS “AVERAGE SCORE,” WHICH CLARIFIES WHAT THE Y-AXIS MEASURES.
#### plt.title('Effect of  Track on Average Score') THIS ADDS A TITLE TO THE PLOT, GIVING A BRIEF DESCRIPTION OF WHAT THE CHART REPRESENTS.
#### plt.show() PRINTS THE CHART.

#### OUTPUT FOR EFFECT OF TRACK ON AVERAGE SCORE
#### ![image](https://github.com/user-attachments/assets/8c16cf7f-da4d-4768-aa11-e3c8882230a4)


#### WE CAN OBSERVE THAT MICROELECTRONICS HAS A HIGHER AVERAGE GRADE IN THE BOARD EXAMS

#### THE CODES FOR THE PROBLEM
#### ![image](https://github.com/user-attachments/assets/13fe0b38-9320-428a-97e6-ae21f1291bd4)
#### plt.figure(figsize=(10, 6)) IS HOW WE CHOOSE THE SIZE OF THE GRAPH/CHART.
#### plt.bar() CREATES A BAR CHART. THE FIRST ARGUMENT (df['x]) SPECIFIES THE CATEGORIES (X-AXIS), AND THE SECOND ARGUMENT (df['y']) SPECIFIES THE VALUES (Y-AXIS).
#### plt.xlabel('x') THIS LABELS THE X-AXIS AS “GENDER,” WHICH HELPS IN IDENTIFYING WHAT THE X-AXIS REPRESENTS.
#### plt.ylabel('Y') THIS LABELS THE Y-AXIS AS “AVERAGE SCORE,” WHICH CLARIFIES WHAT THE Y-AXIS MEASURES.
#### plt.title('Effect of Gender on Average Score') THIS ADDS A TITLE TO THE PLOT, GIVING A BRIEF DESCRIPTION OF WHAT THE CHART REPRESENTS.
#### plt.show() PRINTS THE CHART.
### NOTE: THE FOLLOWING CODES ARE THE SAME WE JUST CHANGED THE VARIABLES TO GET THE DIFFERENT CHARTS TO VISUALIZE HOW DIFFERENT FEATURES CONTRIBUTE TO THE AVERAGE GRADE.
#### OUTPUT FOR EFFECT OF GENDER ON AVERAGE SCORE
#### ![image](https://github.com/user-attachments/assets/924658b9-4955-4eaf-8197-7c1a0003c9d8)
#### WITH THIS GRAPH WE CAN FIND THAT FEMALES HAS A HIGHER AVERAGE SCORE THAN THE MALES

#### OUTPUT FOR EFFECT OF HOMETOWN ON AVERAGE SCORE
#### ![image](https://github.com/user-attachments/assets/7196afd1-b1c7-40af-8240-900316dddebe)
#### WE CAN PONDER HERE THAT LUZON HAS THE HIGHEST AVERAGE SCORE AMONG THE 3.

# END









