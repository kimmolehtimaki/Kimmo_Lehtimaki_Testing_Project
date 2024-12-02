## Summary (Summarize the bug encountered concisely)

In 'Create new project' functionality, Create blank project is written "Create black project" instead

## Steps to reproduce

1. Open the application URL
2. Sign in with existing credentials
3. Navigate to Projects page

## What is the current bug behavior?

Creating new blank project appears as "Create black project" instead

## What is the expected correct behavior?

Title should be named as "Crate blank report"

## Relevant logs and/or screenshots

```
<div class="gl-pl-4"><h3 class="gl-text-size-h2 gl-text-inherit">
            Create black project
          </h3> <p class="gl-text-default">
            Create a blank project to store your files, plan your work, and collaborate on code, among other things.
          </p></div>
```

## Possible fixes

Edit text in <h3>

## Whom do you report/ Assign To/ Tags

/gitlab-bug-1 ~pr-bug
/cc @developer_a
/assign @qa-tester

## Priority

Minor
