# The Organization Git FLow
As we continue to work on issues and creating PRs for the project to help track and easy referrence to our activities, we will be using conventional ways of creating `issues`, `pull-request`, writing `commit` messages and creating `branch`.

## Repository
To contribute to the repository you can directly choose to work on the organization's repository or `fork` the repository to your personal profile, With the option you choose the following description should be followed

### Creating Issue
Every `issue` created on the organization's repository with the follwoing topics that may be used these related issue and tags that can be included to the `issue`, [Read about how to create issue here](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue):

 - **New Feature**: For a new feature that has been discussed in a meeting or mentioned in our roadmap 
   - the `issue` title shall be `feat: Name or Short description of the feature`.
   - Tags to use can include `feature`, `roadmap`, and any other descriptive tags.
   - The issue description shall be detailed enough to provide understanding for implementation
 - **Feature Request**: For a feature that is under proposal or suggestion
   - the `issue` title shall be `feat-request: Name or Short description of the feature requested`.
   - Tags to use can include `feature-request`, `suggestion`, and/or any other descriptive tags.
   - The issue description shall be detailed enough to provide understanding for implementation.
 - **Bugs**: For any bug that may rise during testing the application or when in production
   - the `issue` title shall be `Bug: Name or Short description of the bug`.
   - Tags to use can include `bug`, `dev` or `prod`, and any other descriptive tags.
   - The issue description shall be detailed enough to provide understanding for implementation and shall include prices environment `Mac`, `Windows` or `Linux`
 - **Meeting**: For any organization's meeting and minutes 
   - the `issue` title shall be `Meeting: Name or Short description of the meeting with date`.
   - Tags to use can include `meeting`, `management`, and any other descriptive tags.
   - The issue description shall be detailed enough topics and agenda of the meeting
 - **Discussion**: For other discussions that may be relevant to the repository or the organization
   - the `issue` title shall be `Discussion: Name or Short description of the discussion`.
   - Tags to use can include `discussion`, `management`, and any other descriptive tags.
   - The issue description shall be detailed enough topics.
 - **Management**: Management discussion including decissions made by the organization
   - the `issue` title shall be `Management: Name or Short description`.
   - Tags to use can include `decission`, `management`, and any other descriptive tags.
   - The issue description shall be detailed enough.

**Note**: A `todo` tag can be added to an issue that has been picked up or assigned to an organization member to work on

### Creating a Pull Request
Creating a `pull-request` can follow a similar parttern with the above for issue creating with a little different.
- `issue` requring a contribution shall be created and linked to the `pull request`. [Read How to Link Pull Request with Issue here](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)
- in place of a `bug` issue the topic shall be `fix: Name or Short description of the bug` with `fix` tag The topic, description and tags shall remain the same with `issue` tags.

**Note**: An `in-progress` tag can be added to an issue with opened `pull request`.

### Writing Commit message
Commit messages can be helpful to understand what was implemented and how to improve or suggest way forward for the implementation, `commit` messages/topics should mention the `issue` number, the `issue` title and the purpose for example a commit message for a feature with `issue` number 123 would read `feat: #123 Name or description of the issue` while for a bug fix would read `fix: #123 name or description of issue`.

### Creating branch
If you would be working directly on the organization's repository, before sending in your contribution create a fresh branch using the issue you are working on as the branch name for example when working on a bug issues the branch name would be `fix/123-the-name-of-the-issue` while for feature it would read `feat/123-the-name-of-the-issue`.

**Note**: If you choose to `fork` the project the above should still be followed on your profile repository.
