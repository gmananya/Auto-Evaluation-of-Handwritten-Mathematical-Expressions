# Auto-grading of handwritten mathematical worksheets

Aim of this project is to digitize the steps of solving a mathematical equation written by freehand on a paper, validating the steps and final answer of the recognized handwritten lines by maintaining the context.

## Workflow

The overall solution can be divided into the following two parts:
  + **Workspace Detection module**
  + **Analysis Module**
  
  **Workspace Detection module** is responsible for detecting multiple workspaces in a 
given sheet of paper using pre-defined markers.
  
  **Analysis module** is responsible for detecting and localizing characters in lines in any 
given single workspace, and mathematically analyzing them and then drawing red, 
green lines depending upon their correctness. 




