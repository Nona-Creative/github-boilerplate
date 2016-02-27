# How To Contribute
To keep our repositories as uniform as possible, and work together effectively please consider the following:

## Our Git Flow
We use two primary branches.  `master` and `development`.  `development` is what you'll create pull requests against, and should be deployed to staging environments for testing. Once enough work has gone in to create a  deliverable piece value, and all testing is complete, we should merge `development` into `master`, which will then be deployed to a production environment.  Ideally `master` should always represent what is in production. 

### Contributing to the project
Always branch, and use the below naming schema for branches. Once you've completed the work for that branch, push it up to github and create a Pull Request against development.

#### Naming Branches
We prefix our branch names to make it easier to see what branches relate to.

* `feature/<branch-name>`  - a new feature
* `fix/<branch-name>` - fixes an issue
* `style/<branch-name>` - small front end updates

### Pull Requests
Pull requests should be kept as small as possible, this eases review, and avoids unnessesary merge confilcts.  Pull Requests should be reviewed by two team members.

### Commits & Commit Messages
Commits should also be kept as small as possible, commit messages should be less than 80 characters, and additional descriptions should be used when neccessary.  

### Issues
If you think you've found a bug, or have a concern, check that its not already itemised in the current issues, and then use the issue template if appropriate, if design / style related screenshots are helpful, and if its a feature please describe it fully.

### External Contributors
Contributers external to Nona Cretaive that work on private repositories can be added the the settings page of that repository rather than adding them to teams etc. This allows for much more fine grained access control.

 