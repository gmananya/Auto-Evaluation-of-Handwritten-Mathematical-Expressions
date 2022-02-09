# Auto-gradation of handwritten mathematical worksheets

Aim of this project is to digitize the steps of solving a mathematical equation written by freehand on a paper, validating the steps and final answer of the recognized handwritten lines by maintaining the context.

## Workflow

The overall solution can be divided into the following two parts:
  + **Workspace Detection Module**
  + **Analysis Module**
  
  **Workspace Detection module** is detects multiple workspaces in a given sheet of paper using pre-defined markers.
  
  **Analysis module** is detects and localizes characters in lines in any given single workspace, and mathematically analyzes them and draws red, green lines based on their correctness. 




