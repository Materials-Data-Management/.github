## Pull Requester

It is the requester's job to make sure the reviewer is able to effectively review the pull request. Fill out the "Pull Requester" sections and remove any irrelevant "Pull Reviewer" sections as necessary.

### Description

Reference any issues that will be closed by this PR. Then, clearly explain, motivate, and provide context for your changes.

### QA Instructions

Clearly explain the steps the reviewer will need to take to provide QA on this pull request. This includes:

- Setup instructions
- How to test new functionality
- Potential bugs to check for

## Pull Reviewer

It is the reviewer's job to make sure this pull request in its entirety is production-ready. Please check all the boxes below before approving the pull request.

## Back-end

- [ ] **Architecture**: Code is well-structured, logical, and easy to understand
- [ ] **Naming**: Variables, functions, and classes are named accurately and in accordance with MDMi conventions
- [ ] **Comments/Docstrings**: Ensure code is commented and all new functions and classes have appropriate docstrings
- [ ] **Logging**: There is appropriate logging coverage
- [ ] **Exceptions**: Exceptions are raised, caught, and logged appropriately
- [ ] **Dependencies/Versioning**: Updated `pyproject.toml` and other version files as necessary
- [ ] **Performance**: Ensure that the code is optimized for performance and does not introduce any significant slowdowns

## Front-end

- [ ] **Naming**: Variables, functions, and classes are accurately named
- [ ] **Comments/Docstrings**: Ensure code is commented and all new functions and classes have appropriate docstrings
- [ ] **Look good**: Look good
- [ ] **Responsive Design**: Ensure the UI works well on different screen sizes (desktop, tablet, mobile) and responds to changes
- [ ] **Performance**: Ensure that the code is optimized for performance and does not introduce any significant slowdowns

## Final Checks

- [ ] **Security**: No secret keys or passwords are pushed to the repository
- [ ] **Tests**: All new features are covered by tests and all tests are passing
- [ ] **Deployment**: Ensure that deployment scripts/configs are updated and tested
- [ ] **Base Branch**: The pull request is targeting the correct base branch
