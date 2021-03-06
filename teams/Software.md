# Software Team

## Mission statement

For Knight Lab's public-facing and open-source projects, define, prioritize, implement, and maintain the software as well as the processes and procedures for software development and open-source contributions, with an eye toward establishing the lab as a community example of open-source and general software development practices.

## Priority projects

  * [TimelineJS3](https://github.com/NUKnightLab/TimelineJS3)
  * [StoryMapJS](https://github.com/NUKnightLab/StoryMapJS)
  * [JuxtaposeJS](https://github.com/NUKnightLab/juxtapose)
  * [Soundcite](https://github.com/NUKnightLab/soundcite)
  
## Shift priorities
 
  * Zendesk tickets
  * Github issue labeling
  * Github PR code reviews
  * Github bugs and questions
  * Special tasks and development
  
See below for details of these items.
 
### Zendesk tickets
   
   - **Handle tickets that you previously fielded** and are currently open. Try to get your open tickets to a closed or pending state (see "Managing Zendesk" below for more info on Zendesk statuses)
   - **Take on responsibility for new tickets** by replying to users in Zendesk, creating Github issues as appropriate. Tickets you field should be replied to as either _Pending_ or _Solved_. In general, try to prioritize New tickets by oldest first.
   - **Clear pendings**. In general, if a user has not responded to a pending request in a month, marked it as solved.
   - **Use tags.** Mark tickets with tags as appropriate. We are currently tracking: `http-https` `accessibility`

### Github issue labeling
   
   - **Tag new public issues** in priority projects by finding newly created issues that are not yet labeled. All issues should be labeled one of:
     * Bug
     * Enhancement
     * Question (for internal questions, assign the person you want to answer the question)

### Github pull request code review
   
   - **Review PRs from other team members** (see _Github bugs_ below). Comment with change requests or approval
   - **Review PRs from public**. Comment with change requests or approval. Upon approval, tag a staff member in your comment
   - Tagged staff members will merge PRs for now
   
### Github bugs and questions
   
   - Select a bug from the priority projects
   - Assign the bug to yourself in Github
   - Submit a Pull Request for code review
     * Keep PRs short
     * Submit to an appropriate staff member and another student on the team
     * Larger bugs might take some work and more than one PR

### Special tasks and development

Hopefully, this is where the bulk of your time will be spent. We need to stay on top of all of the above things, but in as far as help tickets, bugs, questions, and PRs are staying under control, remaining time will be spend in ongoing special projects with specific goals in mind. These will be defined in an ongoing manner and will include:

  * Zendesk and general support organization and maintenance for improved support efficiency
  * Documentation
  * Enhancements/Feature development
  * Testing
  * General improvements conducive to collaboration and contribution
  * Community development around our projects
     
## Managing Zendesk

Generally, try to clear out tickets within a week

When responding within Zendesk, sign responses with your name, initials, or some other indicator that lets us know internally who wrote the response

Ticket statuses are:

  * **New**: never looked at
  * **Open**: seen by a support person or has been responded to since last time it was seen
  * **Pending**: a support person has sent it back to the requester and is expecting an answer
  * **Solved**: support person deems the issue done, either because they sent a fairly clear final answer, or the requester had replied saying it is done

If a ticket requires code changes to be resolved, it should be turned into a github issue:

  * give new Github issue a flag (bug, enhancement, or question) Note: **Do not link to customer content in the Github issue without permission to do so**
  * reference the Zendesk ticket number in the new Github issue
  * reference the new Github issue via a link in a response to the ticket requester in Zendesk
  * submit this note to the requester as solved in Zendesk
  
## Suggested Github workflow

Since we manage projects over several repositories, you will want to develop a systematic approach to prioritizing issues and your related tasks. It is recommended that you check each relevant repository (see priority projects list above) succesively for each priority item in this list:

  * Issues: Filter by `Everything assigned to you` (work on closing these out)
  * Issues: Fiter by `Everything mentioning you` (e.g. code reviews of PRs from your peers)
  * Issues: Labels > Questions (answer questions and close them out)
  * Issues: Labels > Bugs (take on Bugs and assign them to yourself)
  
The last 2 items (questions and bugs) will probably be focused within one or two repositories (e.g. you will normally only tackle a single bug at a time), but for the overall list, be sure to check through all repositories where you might have relevant outstanding issues.

## Troubleshooting and tips

### StoryMap

It is often helpful to import a user's storymap into your own account for troubleshooting. To import, get the StoryMap share link from the user, and go to this endpoint: http://storymap.knightlab.com/select.html?import_url=[STORYMAP URL]

There is a `userinfo` endpoint that can be useful while troubleshooting some problems. You can have the user go to this endpoint and copy the information to send you: https://storymap.knightlab.com/userinfo/. Information includes:
  * user agent (i.e. user's browser)
  * user id (uid). This is the key by which the user's media is organized in s3
  * user record. User metadata that is stored in Mongo. It includes references to their maps, and some Google account info
  
## Tools and resources

  * The Knight Lab [Zendesk help center](https://knightlab.zendesk.com/hc/en-us)
  * [Microsoft web dev tools](https://developer.microsoft.com/en-us/microsoft-edge/tools/) for testing on different versions of IE/Edge. I've had better luck with [modern-ie-vagrant](http://tech.dealer.com/want-a-new-way-to-test-ie-browsers-try-modern-ie-vagrant/) than trying to use Microsoft's Vagrant boxes directly
  
## Team Roadmap/TODO

  * Get Zendesk backlog tackled
  * Squash bugs in the 4 priority projects
  * Improve our project build processes (convert to buildkit)
  * Begin working on feature development/enhancements
  * Add Changelogs to projects
  * Improve documentation, particularly around setting up for local development and making contributions
  * Improve deployment documentation (process of staging to CDN, deploying CDN, deploying website)
  * Add/improve testing for all projects
  * Automate CDN Index page version presentation
  * Spec and implement a "language contributions" tool for projects with I18N
  
