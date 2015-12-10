# How to design a SWAMP workflow

A workflow is a sequence of tasks needed to achieve a desired result.

SWAMP's strength lie in two aspects of managing a workflow:

- collecting necessary data
- reminding people that they have to do something, and keep track who did what at which point in time

To design a workflow, you need the following information:

- description of the desired result
- what information (data) is needed as input, or will be produced alongside the result
- what steps need to be done, in which order, maybe in parallel?
- who will perform these steps

Design the 'data model' and the 'flow chart' of a workflow separately. In SWAMP, you have access to all data fields at any point in the workflow (they may be empty of course).

Data fields

The following data types are available:

- boolean
- date
- datetime
- enum
- float
- multienum
- number
- numberlist
- person
- string
- text
- url

Actions

The following actions are available that are typically done by humans:

- manual task - A simple task with a 'Done' button
- decision - A question with 1..n answers
- data edit - The request to fill in data in form fields


