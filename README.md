# poc-github-actions-cicd

- `on.workflow_call` (A, B -> A)
  - you define it in a reusable workflow A
  - in workflow B you use `needs` to call all jobs from workflow A 
  

- `on.workflow_run` (B <- A)
  - you define it in workflow B
  - that it runs whenver a workflow A finished
