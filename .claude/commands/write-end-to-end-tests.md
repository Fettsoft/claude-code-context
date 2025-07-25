# Write End-To-End Tests for Increment Command

## Purpose

Write end-to-end tests for the increment for the issue described in $ARGUMENTS, using the specification linked in $ARGUMENTS. The increment has been implemented when your work starts.
This command is called by an orchestrating command, and is one of the steps in a larger workflow.
You MUST follow all workflow steps below, not skipping any step and doing all steps in order.

## Workflow Steps

1. Understand how the increment has been implemented, and the context surrounding it:
   a. Read specification to learn the business value that the increment is delivering, and what the plan for implementing that value is
   b. Read the code implemented, using git to identify what has been added

2. Write a plan for how to test the necessary behavior

3. Write end-to-end tests that cover your plan

4. Report DONE to the orchestrating command

## This part of the workflow is done when

- [ ] Frontend behavior is verified using end-to-end tests
- [ ] All unit, integration, and end-to-end tests pass (100% coverage of user behavior expected)
- [ ] All quality gates pass (see `/CLAUDE.md` for commands)
- [ ] No test failures introduced in areas of the code unrelated to this increment
