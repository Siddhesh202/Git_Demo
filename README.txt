1. `git init` ---> Powers your folder to be managed by git, and initialises a new empty 
repository. It also creates a .git folder that has all the relevant logic to manage
versions of your project.

2. `rm -rf .git` ---> Delete a git repository

3. `Working Area` ---> There can be bunch of files that are not currently handled
by git. Changes done or to be done in those files are not managed by git yet.
When we do git status and we see a bunch of `untracked files` then these are
to be called in working area.

4. `Staging Area` ---> What all files are going to be a part of the next 
version that we will create. This staging area is the place where git knows
what changes will be done from the last version to the next version.

5. `Repository Area` ---> This area contains details of all your previous
versions

6. `git add <filename>` ---> adds the file from working area to staging area.

7. `git rm --cached <filename>` ---> moves file back from staging to working area.

8. `git commit` ---> creates a particular version of the object. It captures
a snapshot of the projects staged changes and creates a version out of it.

9. `git log` ---> list down all the commits in the repository.

10 `git restore <file>` ---> It removes all files changes from the staging area
to be commited.