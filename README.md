# Number Theory: Addition

In this lab, you’ve learned about One Hot and Binary state machines and how to build them.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name
Christopher Turmes and Grace Dale

## Summary
In this lab, we created and compared the operations of One Hot state machines and Binary state machines, in order to understand their main strengths and weaknesses. We also practically applied D Flip Flops, and understood their role in both of these state machines, and how many to use per state or bit. 

## Lab Questions

### Compare and contrast One Hot and Binary encodings
One Hot and Binary encodings ultimately are both state machines that assign, determine, and store states and future states using D Flip Flops. However, they differ in how they do this. One Hot state machines assign an output and D Flip Flop per each state. One Hot state machines also only assign the appropriate state as 1, and the others as 0. The Binary state machine, however, has a D Flip Flop per bit, and the states are assigned a binary value. This then means that more logic is required in order to make the Binary state machine run, compared to the One Hot state machine. The Binary state machine also has invalid states, and the One Hot state machine does not.

### Which method did your team find easier, and why?
We found the One Hot state machine easier to implement. The straight forward state assignment made setting up and coding the D Flip Flops much easier than the Binary state machine, which requires more logic in order to make the fewer Flip Flops work the way we need. However, this comes with the price of using more Flip Flops.

### In what conditions would you have to use one over the other? Think about resource utilization on the FPGA.
The One Hot state machine makes more sense in situations in which resources and space are not restricted. The One Hot state machine is far more straight forward logic wise, and using it can prevent mistakes coming from miswiring and misunderstanding logic. The Binary state machine, however, is the better solution when resources and space are restricted. The Binary state machine uses a significantly less amount of Flip Flops when the state machine has more and more states, as there is only a Flip Flop for bit instead of a Flip Flop per state. 

