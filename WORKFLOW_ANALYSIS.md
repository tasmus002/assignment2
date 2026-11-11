
- What triggers this workflow to run? (Look at the on: section)
*When a branch is being pushed to the main branch, this will trigger the workflow to begin it's testing.*

- What are the four main steps this workflow performs? (List each step name)
*Checkout, Setup pages, Upload artifact, Deploy to Github Pages*

- What does the "Checkout code" step do and why is it necessary?
*The checkout code downloads your repository as it's what every workflow needs in order to check, test, and run your code. It's neccessary since it's automatic.*

- What is the purpose of the environment configuration?
*To manage data that isn't in the original source code.*

- How does this automated deployment improve reliability compared to manual deployment?
*It automatically tests out the code for you/the team, that way it makes testing and merging new code more efficient than it you/the team were to do it manually every time new code had to be tested.*

- What would happen if you pushed code to a different branch (not main)?
*The workflow would probably not run as it triggers when code is pushed to main, not a different branch*