##What is GitFlow?

*Gitflow Workflow is a Git workflow that helps with continuous software development and implementing DevOps practices. It was first published and made popular by Vincent Driessen at nvie. The Gitflow Workflow defines a strict branching model designed around the project release. This provides a robust framework for managing larger projects.*

![git Workflow](https://wac-cdn.atlassian.com/dam/jcr:61ccc620-5249-4338-be66-94d563f2843c/05%20(2).svg?cdnVersion=1446)

**The overall flow of gitglow is:**
1. A develop branch is created from master.
2. A release branch is created from develop.
3. Feature branches are created from develop.
4. When a feature is complete, it is merged into the develop branch.
5. When the release is done, it is merged into develop and master.
6. If an issue in master is detached a hotflix branch is created from master.
7. Once the hotflix is complete it is merged to both develop and master.

[Click Here to watch tutorial](https://www.youtube.com/watch?v=gLWSJXBbJuE&t=441s)
