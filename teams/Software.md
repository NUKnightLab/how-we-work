# Software Team

## Mission statement

For Knight Lab's public-facing and open-source projects, define, prioritize, implement, and maintain the software as well as the processes and procedures for software development and open-source contributions, with an eye toward establishing the lab as a community example of open-source and general software development practices.

## Priority projects

  * [TimelineJS3](https://github.com/NUKnightLab/TimelineJS3)
  * [StoryMapJS](https://github.com/NUKnightLab/StoryMapJS)
  * [JuxtaposeJS](https://github.com/NUKnightLab/juxtapose)
  * [Soundcite](https://github.com/NUKnightLab/soundcite)
  
## Shift priorities
 
  * Zendesk tickets (2 hours/week)
  * Zendesk backlog (~1 hour/week)
  * Github issue labeling (~20 min/week)
  * Github PR code reviews (~1 hr/week)
  * Github bugs (remaining time)
  
See below for details of these items.
 
Times are generally guidelines, but please provide a weekly report with:
 
  * deviations if your times differ significantly from the guidelines
  * "Github bugs" effort itemized by Github issue number

### Zendesk tickets
 
   2 hours/week
   
   - **Handle tickets that you previously fielded** and are currently open. Try to get your open tickets to a closed or pending state (see "Managing Zendesk" below for more info on Zendesk statuses)
   - **Take on responsibility for new tickets** by replying to users in Zendesk, creating Github issues as appropriate. Tickets you field should be replied to as either _Pending_ or _Solved_. In general, try to prioritize New tickets by oldest first.
   
### Zendesk backlog
 
   1 hour/week (until we have no backlog)
   
   - **Work on backlog** by finding old tickets (>1 week old) that are not signed by a team member
   - **Take responsibility** for the old ticket and handle it as you would a new ticket, getting it into _Solved_ or _Pending_ status
   
### Github issue labeling
 
   20 minutes/week
   
   - **Tag new public issues** in priority projects by finding newly created issues that are not yet labeled. All issues should be labeled one of:
     * Bug
     * Enhancement
     * Question

### Github pull request code review
 
   1 hour/week
   
   - **Review PRs from other team members** (see _Github bugs_ below). Comment with change requests or approval
   - **Review PRs from public**. Comment with change requests or approval. Upon approval, tag a staff member in your comment
   - Tagged staff members will merge PRs for now
   
### Github bugs
 
Remaining hours (will give way to enhancement development in near future)
   
   - Select a bug from the priority projects
   - Assign the bug to yourself in Github
   - Submit a Pull Request for code review
     * Keep PRs short
     * Submit to an appropriate staff member and another student on the team
     * Larger bugs might take some work and more than one PR

### TBD

Things that will get added to this list:

  * Documentation
  * Enhancements/Feature development
  * Testing
     
## Managing Zendesk

Generally, try to clear out tickets within a week

When responding within Zendesk, sign responses with your name, initials, or some other indicator that lets us know internally who wrote the response

Ticket statuses are:

  * **New**: never looked at
  * **Open**: seen by a support person or has been responded to since last time it was seen
  * **Pending**: a support person has sent it back to the requester and is expecting an answer
  * **Solved**: support person deems the issue done, either because they sent a fairly clear final answer, or the requester had replied saying it is done

If a ticket requires code changes to be resolved, it should be turned into a github issue:

  * give new issue an appropriate flag (bug, enhancement, or question)
  * the issue should refer to the Zendesk ticket number
  * reference the issue with a link in a response to the ticket requester for future tracking/reference
  * close the Zendesk ticket as solved

## Team Roadmap/TODO

  * Get Zendesk backlog tackled
  * Squash bugs in the 4 priority projects
  * Begin working on feature development/enhancements
  * Add Changelogs to projects
  * Improve documentation, particularly around setting up for local development and making contributions
  * Improve deployment documentation (process of staging to CDN, deploying CDN, deploying website)
  * Add/improve testing for all projects
  * Automate CDN Index page version presentation
  * Convert projects to buildkit where appropriate
  * Spec and implement a "language contributions" tool for projects with I18N
  
