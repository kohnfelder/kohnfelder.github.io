# kohnfelder.github.io

Simple example website on GitHub for sharing with others.

## How To

The following instructions describe the process of creating a
new GitHub Pages website for your own account from scratch.
It's needlessly complicated and somewhat tedious because there are
so many advanced features and options to navigate through, but
it isn't that hard. Things change on the site and it's hard to keep up.

Please help me improve these instructions with any specific suggestions.
Feel free to depart from the script and explore.
Ask a friendly generative AI chat bot, or search the web, for help.

### Creating a GitHub Project

1. **Log in to GitHub:** Head over to GitHub
([https://github.com](https://github.com))
and log in using your existing account.
See extensive documentation to get started (many links at page bottom).
2. **Create a new repository:** Click the "+" (or "New") button in
the top right corner and select "New repository".
3. **Choose a repository name:** For the website the repository name must be
"*acctname*.github.io" (where *acctname* is replaced by your account name).
For example, if your account name is "example" then "example.github.io"
(by the way, the quotes are not part of the actual name).
4. **Enable GitHub Pages:** Check the box next to
"Initialize this repository with a README".
This simply allows you to document the project.
5. **Create the project:** Click the "Create repository" button.
6. **See your new website:** Click on the "Settings" button with a gear by it,
near the upper right corner (part of a row of buttons: 
**Code - Issues - ... - Insights - Settings**).
In the "Code and automation" section of the (left side) sidebar, click "Pages".
Click the link you should see a box near the top saying,
"Your site is live at `https://acctname.github.io/`"
7. **Save your website URL**: Bookmark or otherwise save this link,
as well as a link to your project for accessing it.

Learn more at the documentation
[here](https://docs.github.com/en/pages/getting-started-with-github-pages).

If you own a registered domain name you can associate it with the website
you create here. Prototype it with the standard link address used below,
then when it's ready for prime time point your domain name as explained
[here](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

### Editing the Content on the Web

1. **Go to your project's repository:**
In your GitHub project, navigate to the "Code" tab.
2. **Edit the website files:**
Click on the `README.md` file to open it in the web editor.
3. **Write your website content:** Edit the Markdown code to
create your website's structure and content
(headings, paragraphs, images, links, etc.).
Markdown supports basic formatting and even embedding images,
see documentation [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
4. **Commit and push your changes:** Once you're happy with your changes,
click the "Commit changes" button and add a commit message describing
your changes. This saves your updates to the GitHub repository.

For more advanced website creation, you can create HTML files
within the repository and modify them instead of `README.md`.
GitHub Pages will serve these files as well.

NOTE: it takes several seconds after updating ("committing in Git")
before the website changes; wait a few seconds and try Refresh.

### (ADVANCED) Cloning the Repository with Git

Git is the dominant way software developers work; it's very powerful
but can be challenging. However, if you use just a few simple commands
it can be effectively used without great effort.
There is [great documentation](https://git-scm.com/book/en/v2/) online,
or if you prefer something simpler there are tons of books and tutorials.

1. **Open a terminal on your computer:**
Launch a terminal or command prompt application where you have
Git installed and configured.
2. **Change directory:** Use the `cd` command to navigate to
the location where you want to clone the repository.
3. **Clone the repository:** Run the following command,
replacing *acctname* with your actual GitHub username:
`git clone https://github.com/acctname/acctname.github.io.git`
4. **Verify the clone:** Navigate to the cloned directory using the command:
`cd acctname.github.io` where
you should see your website's `README.md` file and any other files you added.
5. **Use Git to work on your repository:** Now you are work on the files
on your computer and use Git to get updates and make changes.
You will need to authenticate in order to sync up with GitHub in the cloud.
See the documentation (classic access token is probably the easiest way)
[here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token-classic).

#### Simple Git commands

An easy way to use Git is to always work on the "main" branch.
All changes simply go one after the other into the repository.

**If you edited files on github.com**: Then you need to update the
files on your computer to sync up. 
This command *pulls* files from the cloud into your local file directory.

    git pull origin main

**If you edited files on your computer** (under the git cloned directory):
Then you need to send the changes up to the cloud when they are ready.
The website will update once you do that.

    git add .
    git status
    git commit -m "Explanation"
    git push origin main

* The `git add` command stages all changes you have made to be committed.
* The `git status` command shows what files will commit
(and how you can change things if it isn't what you intend).
* The `git commit` command merges your local changes into the local
"main" branch with the "Explanation" that you edit to describe the changes.
* Finally, the `git push` command merges the local "main" branch to the cloud
(origin) so they stay in sync.
* The push and pull commands ask for authentication (see details above)
to make sure you are authorized to make changes.

**Keep it simple**: Avoid making changes via the web editor
(at the origin in the cloud) and to local files without syncing first.
That is, after editing (via the web, at the origin) go do `git pull`;
and after changing files locally (when everything is good)
do `git push`, and if you have the web page in your browser refresh it.

**Not so simple**: Sometimes things aren't so simple despite good intentions.
If you don't keep in sync then you will have to *merge*:
if the changes are not in
conflict Git will do it for you after a warning if you want and it should
work but is a little scary. If you've changed the same section of the same
file(s) then a serious merge is required (read up on that)
-- or you can give up your changes and sync up cleanly.

**Much more**: Git can do way more that this simplistic description,
so if you want to learn more check it out with a web search
of your question and if you include "git" in the keywords it will
probably yield lots of good answers in whatever form or level you like.


## Making of this guide

The guide that appears above was written using generative AI,
and edited for accuracy and clarity. The prompt to get it is shown below.
Over half of the text is as-is from
[Bard](https://g.co/bard/share/bf84ab143b28).

**Prompt:**

> Give me detailed instructions for creating a github project (with an existing account) for gitlab plain HTML Pages that creates a simple website you can browse on the internet, showing first how to edit the content on the web, and then how to clone the repository with git (already installed) on a computer.

<hr/>
