## GitHub Pages Instructions

GitHub Pages provides free static hosting from a GitHub repository. It's a great option for hosting a portfolio website or showcase work from a project. In this example, we'll deploy a very simple static website from the main branch. See the [GitHub Pages documentation](https://docs.github.com/en/pages) for more advanced use-cases using custom workflows. 

### Build a Portfolio Website

First, you need a portfolio (or any static website). A great place to learn how to build a portfolio site is the [Web Development Project: Personal Portfolio Website](https://frontendmasters.com/courses/portfolio-website/) Frontend Masters course.

We'll use [the final project](https://personal-portfolio.css.education/portfolio.zip) from that course for this portfolio site.

### Create a GitHub Repo

You'll need a GitHub repo to deploy to GitHub pages. Create a new repository in your GitHub account. You can use any name you want: 

![creating a new GitHub repository](https://github.com/frontendmasters/getting-a-job-v3/blob/main/gh-pages-instructions/01-create-repo.png?raw=true)

> [!NOTE]  
> There is some build-in GitHub Pages functionality if you name your repository `[yourusername].github.io`. The steps in this example will work with any repository name. 

### Add Your Website to the Repo

After creating your new repository, you can add your portfolio website. If you know how to use GitHub or the Git CLI, go ahead and push up your website. If you are new to GitHub, you can click `Upload Files` under the `Add file` dropdown:

![adding files to a GitHub repo](https://github.com/frontendmasters/getting-a-job-v3/blob/main/gh-pages-instructions/02-upload-files.png?raw=true)

Once you have your files added, your repo will look something like this:

![html, css, and image source files in a GitHub repo](https://github.com/frontendmasters/getting-a-job-v3/blob/main/gh-pages-instructions/03-files-added-to-repo.png?raw=true)

> [!NOTE]  
> Make sure your home page is named index.html

### Configure GitHub Pages

Now it's time to deploy your website. Go to `Settings > Pages` and make sure `Deploy from a branch` is selected. Choose your `main` branch and click save:

![GitHub Pages settings page](https://github.com/frontendmasters/getting-a-job-v3/blob/main/gh-pages-instructions/04-enable-gh-pages.png?raw=true)

After a few minutes, your site will be delpoyed and the URL will appear at the top of the `Settings > Pages` page. The URL will be `https://[username].github.io/[repo-name]`:

![URL of GitHub Pages website after deployment](https://github.com/frontendmasters/getting-a-job-v3/blob/main/gh-pages-instructions/05-site-deployed.png?raw=true)

### Updating Your Portfolio

The cool thing about GitHub Pages is any time you push changes to your repo, the website will automatically redeploy. You'll see a green checkmark when the deployment has succeeded:

![Green checkmark indicating deployment status](https://github.com/frontendmasters/getting-a-job-v3/blob/main/gh-pages-instructions/06-status.png?raw=true)

### Additional Hosting Options

There are other static hosting options available. Check out the [Exactly How to Deploy Local Files to Make a Live Website](https://frontendmasters.com/blog/exactly-how-to-deploy-local-files-to-make-a-live-website/) on the [Boost Blog](https://frontendmasters.com/blog/).
