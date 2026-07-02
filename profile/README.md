# ghclass demo organization

This organization is the live companion to the paper "A Modern Approach to Teaching Statistics and Data Science using Git and GitHub", which documents a scripted, end-to-end instructor workflow for running a course on GitHub, built on the [ghclass](https://github.com/rundel/ghclass) R package.

Everything here is placeholder scaffolding. The six students (Alice, Bob, Carol, Dave, Elizabeth, Fred) are fabricated, and the assignment content is intentionally generic. No real student data appears anywhere. The organization exists so that readers of the paper can point ghclass's read-side functions, such as `org_repos()`, `repo_n_commits()`, and `action_runs()`, at a real, public organization and see them work, and so they can browse a worked example of what a correctly configured course organization looks like.

## Structure

- [instructor](https://github.com/ghclass-paper/instructor) is the instructor repository: the course roster plus the setup, distribution, and grading scripts, one folder per workflow stage.
- [hw1](https://github.com/ghclass-paper/hw1) is the team assignment template and [midterm1](https://github.com/ghclass-paper/midterm1) the individual one; [hw1-key](https://github.com/ghclass-paper/hw1-key) is the answer key used at grading.
- [hw1_lab01_team01](https://github.com/ghclass-paper/hw1_lab01_team01) and [hw1_lab01_team02](https://github.com/ghclass-paper/hw1_lab01_team02) are the team repositories distributed from the hw1 template.
- `midterm1_alice` through `midterm1_fred` are the six individual repositories distributed from the midterm1 template.

Each distributed repository carries a continuous integration check that runs on every push, its status badge, and (for team repositories) a per-team contact list inserted into the README after distribution.

One important way this demo differs from a real course: visibility. In an actual course the instructor repository and every student repository are private, always. We usually make the assignment templates private as well, though that one is an instructor choice rather than a requirement. Everything here is public, by design, so the organization can serve as a reference. See the [instructor repository](https://github.com/ghclass-paper/instructor) for details on how the organization was built and how to adapt the workflow to a course of your own.
