# kohnfelder.github.io

Simple example website on GitHub for sharing with others.

## How To

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
near the upper right corner (part of a row of buttons (
Code - Issues - ... - Insights - Settings).
In the "Code and automation" section of the (left side) sidebar, click "Pages".
Click the link you should see a box near the top saying,
"Your site is live at `https://acctname.github.io/`"
7. **Save your website URL**: Bookmark or otherwise save this link,
as well as a link to your project for accessing it.

For help see the documentation
[here](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

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

NOTE: it takes several seconds after updating ("committing in Git")
before the website changes; wait a few seconds and try Refresh.

### (ADVANCED) Cloning the Repository with Git

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
[here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token-classic)


## Additional Notes

- For more advanced website creation, you can create HTML files within the repository and modify them instead of `README.md`. GitHub Pages will serve these files as well.
- To further customize your website, you can create a `CNAME` file specifying a custom domain name.
- To make future updates to your website, simply edit the files in your local cloned repository, commit and push your changes to the GitHub repository, and your website will be automatically updated.

I hope this comprehensive guide helps you create and manage your GitHub Pages website effectively!

### Prompt

Give me detailed instructions for creating a github project (with an existing account) for gitlab plain HTML Pages that creates a simple website you can browse on the internet, showing first how to edit the content on the web, and then how to clone the repository with git (already installed) on a computer.

(Edited for accuracy and clarity, but over half is as-is from
[Bard](https://g.co/bard/share/bf84ab143b28).)

<hr/>
