# Health Equity Research Intensive
code for analyzing data for the Health Equity Research Intensive (HERI) 

# Purpose:
to store the survey tool, datasets, R code, graphs, and final slide deck interpreting the satisfaction and professional development of HERI attendees by session

# Inputs:
+ datasets (with numerical values) from Qualtrics (.csv)
  
# Outputs:
+ dumbbell graphs to visualize relative change in knowledge and ability, before and after each session
+	diverging bar charts to visualize Likert scale items (i.e., 5-point scales ranging from 1=strongly disagree to 5=strongly agree) for quality of sessions
+	Markdown files to document what the R code is and does (.rmd), knit into a Word document (.docx)

# Data Collection & Visualization:
1. Export responses from Qualtrics.
2. Delete test records.
3. Subset and merge the session data needed for each graph.
4. Factor the categorical/ordinal Likert-scale variables.
5. Generate average item scores for dumbbell graphs.
6. Plot the graphs & save.
