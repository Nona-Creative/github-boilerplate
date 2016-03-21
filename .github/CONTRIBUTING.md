# How To Contribute
To keep our repositories as uniform as possible, and work together effectively please consider the following:

## Our Git Work Flow

* for smaller projects we're essentially following the feature branch workflow that can be found [here](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)
* For larger projects we're following the process discused below, which is better suited to ongoing projects with multiple releases and CI, you can find a detailed discussion [here](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)

We use two primary branches.  `master` and `develop`.  `develop` is what you'll create pull requests against, and should be deployed to staging environments for testing. Once enough work has gone in to create a  deliverable & deployable piece of value, and all testing is complete we create a release branch (this is where we start adding version numbers, add documentation and do any prep related to the release), this then gets merged into master, which will then be deployed to a production environment,  we should merge `master` back into `development`.  Ideally `master` should always represent what is in production. 

### Contributing to the project
Always branch, and use the below naming schema for branches. Once you've completed the work for that branch, push it up to github and create a Pull Request against development.

#### Naming Branches
We prefix our branch names to make it easier to see what branches relate to.

* `feature/<name>`  - a new feature
* `fix/<name>` - fixes an issue
* `style/<name>` - small front end updates
* `hotfilx/<name>` - fixes against a release
* `release/<name>` - preparing for a release

### Pull Requests
Pull requests should be kept as small as possible, this eases review, and avoids unnessesary merge confilcts.  Pull Requests should be reviewed by two team members.

**NB :** for front-end changes and style fixes, adding screen shots to the pull request is tremendously helpful in explaining what was done and why.

### Commits & Commit Messages
Commits should also be kept as small as possible, commit titles should be less than 80 characters, and additional descriptions should be used when neccessary.  
### Issues
If you think you've found a bug, or have a concern, check that its not already itemised in the current issues, and then use the issue template if appropriate, if design / style related screenshots are helpful, and if its a feature please describe it fully.  If you're aware of who worked on the related functionality, mention them in the comments rather than assigning them.

### External Contributors
Contributers external to Nona Cretaive that work on private repositories can be added on the settings page of that repository rather than adding them to teams etc. This allows for much more fine grained access control.

### Versioning Things
When its neccessary to use versioning we should follow the semver pattern as discussed here http://semver.org/ .  Essentially, we using a three number system, ie.: 1.2.3 .  These are described as follows : 

1. MAJOR version when you make incompatible API changes,
2. MINOR version when you add functionality in a backwards-compatible manner
3. PATCH version when you make backwards-compatible bug fixes.

### Maintaining the ReadMe
This should regularly be updated with project details and developer instructions, particularly for setup, and any specific release instructions & notes.
 