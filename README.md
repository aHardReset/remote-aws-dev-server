
 
- `terraform` most used commands
  - `init` reads the providers file to ensure the access and prepares the workdir for other commands
  - `plan` Show **changes** required by the current configration
    - `-destroy` the plan for the `destroy command`
  - `show` show the current state and a saved plan
  - `state` provides a way to work with the current state:
    - `show` `{resourceName}` shows the state for the provided resource
    - `list` list resources
  - `apply` create or update infrastructure
    - `-auto-approve` useful in automation
    - `-replace` to overwrite an existing resource, useful when something is added that does not mean a change in the state
    - `refresh-only` to only sync the configurations without performing anything, for example, adding a new output
  - `destroy` destroy created infrastructure
    - `-auto-approve` useful in automation
  - `output` show the outputs defined in `outputs.tf`




