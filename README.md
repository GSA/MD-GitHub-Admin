# MD-GitHub-Admin
Git and GitHub can seem bewildering at first. This documenation will simplify and clarify common workflows and provide our team with a standard way of doing things together.

## Our Users
Each user must: 
 - [Activate 2-factor Authentication](https://blog.github.com/2013-09-03-two-factor-authentication/)
 - [Add your information to your account](https://github.com/settings/profile), including:
   - Name: Your first or first and last name.
   - Company: Your government agency.
   - Location: Your primary work location (City, State).
   - Email: A [valid email address](https://help.github.com/articles/verifying-your-email-address/).
 - Add a [profile avatar](https://help.github.com/articles/setting-your-profile-picture/)
 - Make your membership public by going to the [team](https://github.com/orgs/GSA/teams/ogp-evidence-and-analysis) page, finding yourself, and clicking **Make Public**.
 
## Our Repositories
Each repository should:
 - Have a simple and useful name 
    - If the repo is for a team project (e.g. the Tenant Satisfaction Survey), ensure that the repo name reflects that and that there isn't aleady another repo for that project. Avoid acronyms and clever names/puns as those can make it hard to search for projects.
    - If the repo is for a cross-project utility function (e.g. a Qualtrics API script), use a descriptive name that describes what the project does. Avoid acronyms and clever names/puns as those can make it hard to search for projects.
 - Have a user-friendly description
    - The description of a repo tells the public what is contained in the repo itself. If you have multiple repositories for the same project, it's better to describe what is contained in the repo itself instead of describing the project.
    - Repo descriptions should be clear, concise, and descriptive. Descriptions are listed under each repository title on an organization’s GitHub page. Anyone who scans the GitHub page should be able to determine what a repo does, just by looking at the description
 - Have a useful README.md (see below!)

Standards for making a private repo:
By default, projects in GitHub.com/GSA should be public. They should only be made private under certain circumstances.

A repository can be made private if it contains information that legally cannot be made public.

## Our Team
Our [team](https://github.com/orgs/GSA/teams/ogp-evidence-and-analysis) can give members [administrative, write, or read permissions](https://help.github.com/articles/managing-access-to-your-organization-s-repositories/). Even if you have `write` access into a repository, we strongly encourage the submission of pull requests for improvements or fixes.

Contractors or external government collaborators should only be added to teams with scoped write permissions to the respositories they're working on. They should never have administrative level rights. In order to separate out these permissions, create a team in the format of `projectname-admins` for government staff if necessary.

Additional resources
The GitHub Government Community
GitHub Government Best Practices
Amendment to GitHub Terms of Service Applicable to U.S. Federal Government Users

## README Templates
Two common ways to document a project are README files and wikis:
 - README files are a quick and simple way for other users to learn more about your work.
 - Wikis on GitHub help you present in-depth information about your project in a useful way.

It’s a good idea to at least have a README on your project, because it’s the first thing many people will read when they first find your work. You're actually reading this repo's README right now! So, when you create a new repository, select “Initialize this repository with a README” unless you plan to import an existing repository.

Within this repo, there's a [README-Template.MD](https://github.com/GSA/MD-GitHub-Admin/blob/master/README-Template.md) that you can use to help get you started.

You can read more about creating a README or Wiki in the official GitHub documentation [here](https://guides.github.com/features/wikis/).

## Contributing Templates
To help your project contributors do good work, you can add a file called `CONTRIBUTING` (or `CONTRIBUTING.md` if you’re using Markdown) with contribution guidelines to your project repository's root, docs, or .github folder. When someone opens a pull request or creates an issue, they will see a link to that file.

Within this repo, there's a [CONTRIBUTING.MD](https://github.com/GSA/MD-GitHub-Admin/blob/master/CONTRIBUTING.MD) template that you can copy/paste into your new repo. **This document will be our teams canonical contributing guideline.**

You can read more about contributing guidelines in the official GitHub documentation [here](https://help.github.com/articles/setting-guidelines-for-repository-contributors/).

## Issue Templates
Issues are a great way to keep track of tasks, enhancements, and bugs for your projects. They’re kind of like email—except they can be shared and discussed with the rest of your team. Most software projects have a bug tracker of some kind. GitHub’s tracker is called Issues, and has its own section in every repository.

Within this repo, there's an [ISSUE-Template.MD](https://github.com/GSA/MD-GitHub-Admin/blob/master/ISSUE-Template.md) file with a basic bug/enhancement template. You can use this to [populate your repo with a pre-built issue templates](https://help.github.com/articles/creating-issue-templates-for-your-repository/). Or you can create issue templates from within your repository using the [issue template builder](https://help.github.com/articles/about-issue-and-pull-request-templates/). Either way, these templates will be available for contributors to use when they open new issues in the repository.

You can read more about issues in the official GitHub documentation [here](https://guides.github.com/features/issues/).

## Pull Request Templates
If you add a pull request template to your repository, project contributors will automatically see the template's contents in the pull request body. As a team, we haven't decided if we want to do this yet. If we do, there's more to read [here](https://help.github.com/articles/creating-a-pull-request-template-for-your-repository/).

## Project Board Templates
Project boards on GitHub help you organize and prioritize your work at a repository level. You can create project boards for specific feature work, comprehensive roadmaps, or even release checklists. With project boards, you have the flexibility to create customized workflows that suit your needs.

Project boards are made up of issues, pull requests, and notes that are categorized as cards in columns of your choosing. You can drag and drop or use keyboard shortcuts to reorder cards within a column, move cards from column to column, and change the order of columns.

Within this repo, there's a pre-built [project board](https://github.com/GSA/MD-GitHub-Admin/projects) that you can [copy to your repo](https://blog.github.com/2018-05-01-creating-new-boards-with-project-templates/).

You can read more about project boards in the official GitHub documentation [here](https://help.github.com/articles/about-project-boards/).

## Licenses
The license on every repo must be Creative Commons 0, or CC0. That’s shorthand for Public Domain. MD should be committed to working in the public domain by our own policies even though that is also required by [law](https://www.usa.gov/government-works). 

Within this repo, there's a [LICENSE](https://github.com/GSA/MD-GitHub-Admin/blob/master/LICENSE) file that you can copy into the root of your repos.

You can read all about licenses [here](https://help.github.com/articles/licensing-a-repository/).
