# guestbook-go

## Assignment 1 (Continuous Integration Pipeline)
### Problem Statment:
#### Phase 1:
- Create a new GitHub public repo from [repo](https://github.com/Pradipgaikwad10/assignment)
- Create a container image using the Github Action workflow for the above project.
- Push that image to the docker hub.

#### Phase 2:
- Deploy container image built in above step(Phase I) on local/any kubernetes cluster.

#### Phase 3:
- Prevent merging anything in main branch without review.
- Build container image only when one of the below conditions is true:
    - When PR get merged in main/master branch from any other branch.
    - When commit message contains `BUILD_CONTAINER_IMAGE` string


## Solution
# Phase I: (Provided the solution with Repository links)
* Created a new [GitHub public repository](https://github.com/Pradipgaikwad10/assignment) from provided repository 
* Created a container image using GitHub [Action workflow](https://github.com/Pradipgaikwad10/assignment/actions) for the above project.
* Pushed that image to [docker hub](https://hub.docker.com/r/pradipgaikwad10/assignment/tags)

### Phase II:
- Deployed the container image built in the above step(Phase I) on the local cluster.

### Phase III:
- Prevented merging anything in the main branch without review. To test this scenario I created a pull request to ensure that the auto-merging is disabled and see the [PR HERE](https://github.com/Pradipgaikwad10/assignment/pulls))
