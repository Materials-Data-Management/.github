## Pull Requester

It is the requester's job to make sure the reviewer is able to effectively review the pull request.

### Description

Clearly explain the changes and related issues for this pull request. Include screenshots where applicable.

### Steps to review

Clearly explain the steps the reviewer will need to take to provide QA on this pull request. This includes:

- Set up instructions
- How to replicate new functionality
- Potential bugs to check for
- File changes to review

## Pull Reviewer

It is the reviewer's job to make sure this pull request in its entirety is production ready. Please check all the boxes below before approving the pull request.

## Python Development

- [ ] **Code Formatting**: Ensure code is formatted correctly (`black`)
- [ ] **Type Hints**: Ensure code has appropriate type hints with no errors (`mypy`)
- [ ] **Naming**: Variables, functions, and classes are accurately named
- [ ] **Comments/Docstrings**: Ensure code is commented and all new functions and classes have appropriate docstrings
- [ ] **Logging**: There is appropriate logging coverage
- [ ] **Exceptions**: Exceptions are raised, caught, and logged appropriately
- [ ] **Dependencies**: Updated `requirements.txt`, etc
- [ ] **Versioning**: The project version is increased as needed

## Web Development

- [ ] **Look good**: Look good
- [ ] **Cross-Browser Testing**: Verify functionality across all major browsers
  - [ ] Chrome
  - [ ] Firefox
  - [ ] Safari
  - [ ] Edge
- [ ] **Responsive Design**: Ensure the UI works well on different screen sizes (desktop, tablet, mobile) and responds to changes

## Documentation

- [ ] **README**: Update `README.md` if new features or major changes were introduced
- [ ] **User Instructions**: Update user instructions or in-app help pages to explain new features or major changes, including updated pictures
- [ ] **Deployment instructions**: Deployment instructions accurately go over how to set up the project from scratch
- [ ] **Changelog**: Update `CHANGELOG.md` with details about the changes made in this PR
- [ ] **Typos/Grammar**: Proofread the documentation for any typos or grammatical errors

## Final Checks

- [ ] **Security**: No secret keys or passwords are pushed to the repository
- [ ] **Unit Tests**: All unit tests are passing
- [ ] **Test Coverage**: All new features and bug fixes are covered by unit tests
- [ ] **Deployment**: If applicable, ensure that deployment scripts/configs are updated and tested
- [ ] **Merge Conflicts**: Ensure there are no merge conflicts, it is the job of the requester to resolve conflicts
- [ ] **Post-Merge**: Set a reminder for any necessary post-merge actions (e.g., deployment, monitoring, newly raised issues)
- [ ] **Base Branch**: The pull request is targeting the correct base branch.
