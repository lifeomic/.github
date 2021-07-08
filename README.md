# .github
GitHub configuration for LifeOmic org.

This repo can be used to create Actions workflows that are globally available within the 
LifeOmic org. 

Each workflow needs its own `.yml` file that defines the workflow, as well as a 
`.properties.json` file with a matching prefix that sets metadata for the workflow 
such as its name, description, icon, and what repo categories it supports.

Actions workflows that are created here can be found in the `Actions` tab 
of any repository in the org and then installed for the chosen repo.
