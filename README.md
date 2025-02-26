# adf-activity
## Control flow activities manage the order and conditions of pipeline tasks. They enable branching, looping, delays, and error handling, ensuring reliable and efficient data processing.
** Examples and Functions

Wait Activity:
As you mentioned, the "Wait" activity introduces a pause in the pipeline execution. This can be useful for:
Allowing time for external systems to complete tasks.
Implementing scheduled delays.
Preventing overloading downstream systems.
If Condition:
This activity allows you to create branching logic based on a condition. If the condition is true, one set of activities is executed; otherwise, another set is executed.
ForEach/Until:
These activities enable looping, allowing you to iterate over a collection of data or repeat a set of activities until a certain condition is met.
Lookup Activity:
This allows the pipeline to retrieve values from external data sources, and then use those values to determine the flow of the pipeline.
Fail Activity:
This allows the pipeline to intentionally fail, and to give a specific error message. This is very useful for error handling.
Set variable:
This allows for the setting of variables within the pipeline, that can then be used in other control flow activities, or in other activities within the pipeline.

![image](https://github.com/user-attachments/assets/b4519bec-8e31-4779-b579-b10522898b09)

### def add(x, y) ----- function with 2 parameters
      pass
    add(5.3)--------function call with 2 arguments. These values get place on above variables and 4


