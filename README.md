---
title: GitHub for project management
tags: Project Management, GitHub, Talk
description: View the slide with "Slide Mode".
---

# GitHub for project management

<!-- Put the link to this slide here so people can follow -->
Slides: [hackmd.io/p/rk3RxtMaN](https://hackmd.io/p/rk3RxtMaN)

---

## Who am I?
Marnee Dearman

- Full-stack developer
- Ham (amateur radio) - KG7SIO
- Chief Applications Architect, College of Medicine, IT Services
- F# |> I :heart:

---

## What does GitHub offer?

- Online Git repositories
- Including free private repositories

Note:
- For keeping track of changes to source code

---

## Also

- Organizations
- Teams
- Projects
- Issues
- Milestones
- Pull requests
- Wikis
- Discussions
- Pages
- And still more...

---

## Organizations

> "Organization accounts allow your team to plan, build, review, and ship software — all while tracking bugs and discussing ideas."
> 

You can create an organization for your lab and have all of your projects and repositories associated with this organization.

1. Go to your Github profile
2. Click the `+` next to your avatar. 
3. Select New Organization and follow the prompts

For example, the Research Bazaar, Arizona organization.

[Link on GitHub](https://github.com/resbazaz)

---

## Teams

- Roles and permissions
- Sub-teams
- Flexible repository access
- Team mentions (e.g. `@rodent-lab/mouse-wranglers`)

To create a new Team:

Inside your organiztion, click the Teams tab and then click the big green `New team` button.

For example, the Research Bazaar Website Team.

[Link on GitHub](https://github.com/orgs/resbazaz/teams/website-team)

---

## Issues 

- Track todos, bugs, feature requests, etc.
- Apply labels
- Issue templates
- Every issue is in a particular state

Issues are associated with a repository. Let's look them on this repository:

[Github for Project Management Example](https://github.com/resbazaz/github-project-management-example)

Go to the repository and click the Issues tab.

You can create a new issue by clicking the big green `New Issue` button.

With each issue you can:

- Assign a person who will work on the issue
- Assign a label that categorizes the issue. You can use the built-in labels and create your own to suit your needs.
- Assign to a project. We will see more about projects later.
- Close the issue with the reason it was closed (e.g. it was fixd and how, could not reproduce, etc.)


### Commits and issues

When you create a commit (commit changes to your repository), you can associate a commit with an issue by putting `Issue #X`, e.g. `Issue #1`, at the beginning of your commit message. GitHub will automatically link that commit to the issue and show it in the issue details. You can see an example [here](https://github.com/resbazaz/github-project-management-example/issues/1).

Example commit message:

```text
Issue #1: added section on using GitHub issues
```

---

## Issues

![](https://i.imgur.com/wsSaZIG.png)

---

## Projects

- Kanban boards (like Trello)
- Organization, team, user, or repository level
- Sort tasks
- Plan your project
- Automate your workflow
- Track progress
- Share status

Note:
- Help you organize and prioritize your work. You can create project boards for specific feature work, comprehensive roadmaps, or even release checklists.
- You can link multiple repositories to a project

Projects can be associated with your personal GitHub profile or an organization. Let's look at Research Bazaar.

On the Research Bazaar organization page, click the Projects tab. You will see a list of projects we have created.

Create a new project by clicking the big gree `New Project` button.

You can also get to your personal projects by clicking on your avatar and selecting `Your projects`.

---

## Projects

![Kanban - Arranged by stages of grief](https://i.imgur.com/Yvg39Lv.jpg)

Note:
- <https://twitter.com/rseroter/status/788028797144535040>

Let's start a new project. I am going to click the big green `New project` button.

Notice the `Project template` options.

You can setup a project with automations.

Automations mean that changes to the state of an Issue will automatically move the issue in your Kanban board.

### Issue automation

Look at the Project Kanban. Notice the issue is `In progress`. 

If I close the issue it will be moved to the `Done` column.


## Milestones

[About milestones](https://help.github.com/en/articles/about-milestones)

- Collections of Issues and Pull Requests for a particular release or project
- Can have a due date

You can create new Milestones on the Issue details page in the Milstone widget.

---

## Wikis

- A simple way to let others contribute content
- Documentation, examples, support, etc.
- Can restrict editing to specific teams

Note:
- Any GitHub user can create and edit pages
- Wikis are per repository only

---

## Pull requests

- Help you collaborate on code with other people
- Pull request templates

Note:
- Code review is an effective way to find bugs.
- We recommend to review code after all mechanical checks have passed.
- Use code review to share knowledge within the team.

---

Pull requests are requests to pull in changes from repository to another.

Pull requests can be associated with an issues like commits.

You can only make pull requests from repositories that were forked.

I will show an example.

## Discussions

[About team discussions](https://help.github.com/en/articles/about-team-discussions)

- Threads of conversation around topics
- Like Slack but slower, and you don't have to pay to read older conversations

Discussions are don with teams. We saw Teams earlier. Let's go back to the Research Bazaar Teams.

[Link to GitHub](https://github.com/orgs/resbazaz/teams)

Notice the `Project Management Workshop` team. Click on it and you will see the discussions. You can add a topic or comment on an existing one.

Only the people on the team will be able to start topics.

---

## Pages

[GitHub Pages Basics](https://help.github.com/en/categories/github-pages-basics)

- Host your personal, organization, or project website from a GitHub repository
- your-org.github.io or your own domain


---

## Other stuff

---

## Analytics (Insights)

- Contributions
- Visitors
- Clones

---

## Notifications

- New activity on an issue, discussion, etc.
- Configurable

Note:
- When something happens that needs your attention

You can subscribe to notifications on issues. When the status changes you will get a notification. You are automatically subscribed to issue notifications if you started the issue, were assigned to the issue, or commented on the issue. Otherwise, if you want to keep up with the issue, click the `Notifications` button.

---

## Third-party integrations 

- Automate things (e.g. continuous integration)
- Link to other systems (JIRA, Slack, Polls)
- See [GitHub Marketplace](https://github.com/marketplace)

Note:
- [GitHub apps](https://developer.github.com/apps/differences-between-apps/#about-github-apps/)
- [Webhooks](https://developer.github.com/webhooks/)

---

## Security things

- 2FA
- Audit logs
- Security alerts

Note:
- Two-factor authentication adds an additional layer of security to your account by requiring more than just a password to log in.
- Audit logs: Who did what to organization settings?
- Security alerts: Known vulnerabilities in code

---

## Don't forget [GitLab](https://gitlab.com/)

- Very similar to GitHub
- Free and FREE (Open source)
- Self-hostable (if you want)

---

## Wrap up

- You can go a long way with just GitHub or GitLab
- Try it out - you don't have to adopt everything at once

---

## Thank you!

You can find me on:

- GitHub: [MarneeDear](https://github.com/MarneeDear)
- Blog: [marnee.silvrback.com](https://marnee.silvrback.com/)
- Radio waves: KG7SIO
- My NetID: `marneedearman`

---

## More reading

- [Software Carpentry: Managing Research Software Projects](https://swcarpentry.github.io/managing-research-software-projects/)
