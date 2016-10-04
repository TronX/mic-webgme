# Simple Workflow
MiniProject-1 for CS6388-Model Integrated Computing course at Vanderbilt University.

##Metamodel
Simple Workfow metamodel has 4 states which inherit from StateBase and 1 connection.

####H4 **Initial State** - This is where the workflow starts. There's only one state in Workflow, by enforcing cardinality rule.
####H4* **Final State** - This is where the workflow ends. There can be multile Final State in Workflow.
####H4 **Intermediate State** - Intermediate State are any state except initial, final.
####H4 **Decision State** - It's an Intermediate state too, but it gives decision as "Yes" or "No" transition to another state.
####H4 **Connection** - It connects all StateBase.



## Example Model

The example model shows Shipping Process which maps out the steps in shipping process. It just checks any fraudulent order in the open batch and makes a decision to process it or delete the fraudulent order.
