# Host Your Resume Online

## Purpose

In this README, you will learn to host your own resume on a static generated website using Github Pages by following the steps below!

[Demo](https://threshvsgaming.github.io/COMP3040Art.github.io/)

![Demo](app/opera_48tROMvPDM.gif)

## Getting Started

### Prerequisites

You'll need the following things before we get started:

- A Github Account
	+ If you haven't created an account already, navigate to this link [here](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home).

- Github Desktop
	+ We will be using Github Desktop to update your files and compare any changes you made.
	+ You can download Github Desktop [here](https://desktop.github.com).

- Visual Studio Code
	+ You will use Visual Studio Code to create/update your resume.
	+ You can download Visual Studio Code [here](https://code.visualstudio.com/download).

- A resume created in markdown
	+ For a guide to learn more about Markdown, see [More Resources](#more-resources).
	
### Instructions

#### I. Setting up your Github Repository

Andrew Etter highly discourages users to rely on PDFs because inevitably, a PDF file will become severely outdated and users will either replace the file or outright forget to update the information altogether. In contrast with websites, users will be able to continuously update their website and share it for anyone to view, which will always contain up-to-date information. In this section, we will go over how to set up a Github Repository to host your static generated website using Github Pages, which will contain your resume.

1. Navigate to [Github](https://github.com).
2. Login to your Github Account.
3. Navigate to this [repository](https://github.com/ThreshvsGaming/COMP3040Art.github.io).
4. Press the `Fork` button at the top right of the page.
	+ This allows us to create a copy of the repository so that we can use its template.
5. Fill out the necessary information in the current page.
	+ Name your repository with the following format `(repository name).github.io`.
		* Ex. `COMP3040Art.github.io`.
		
	+ Leave everything else default.
		
6. Press the `Settings` tab at the top of of your newly formed repository page.
7. Navigate to the `Pages` section on the left sidebar.
8. Choose `Deploy from branch` in the dropdown menu under Source.
9. Change `none` to `main` in the dropdown menu under Branch.
10. Press Save.

Your repository is now ready to host your website!

#### II. Editing your Resume

Andrew Etter explains how lightweight markup languages allows anyone to be a contributer because it allows users to quickly write clean documentation using simple syntaxes to format the users contents. These simple syntaxes create readable information resulting in other people being able to contribute in the improvements of the documents as well as allow other forms of medium to format said documents however they like. In this section, we will use Github Desktop to make a copy of our repository in Github into our local computer and edit them using our Markdown Text Editor, Visual Studio Code.

1. Open Github Desktop.
2. Follow steps 3-5 if your Github Desktop is **not** sign in using your Github account.
3. select the dropdown menu, `file`, on the top left.
4. Select options.
5. Press `Sign into Github.com` and sign in.
6. Press `Clone a repository from the internet`.
7. Select the repository that you created in Section I.
	+ Ex: `COMP3040Art.github.io`.
8. Press `Clone`.
9. Select the dropdown menu, `Repsoitory`, in the top left.
10. press `Open in Visual Studio Code`.
11. Select the `config.yml` in your File Explorer menu located to the left side.
	+ Edit the `title: ` and `description: ` lines catered to your resume.
		+ ***Do not edit `title: ` and `description: ` themselves. Only the content after those text***.
	+ Save the file once you are done.
12. Select the `index.md`.
13. Put in your resume contents in this markdown file.
	+ Make sure the content is written in markdown if you wish to format your resume.
14. Save `index.md`.
15. If you wish to preview your resume, right-click the `index.md` file in your file explorer menu.
16. Select `Open Preview` to view your resume.
	+ *The format of your resume is based on Visual Studio Code's format. The format will change once your file changes are submitted into Github*.

Now that you are able to edit your resume, you are now ready to submit your changes to Github!

#### III. Uploading/Updating your Resume in Github

Andrew Etter encourages users to use version control systems to manage our files. A version control system allow us to track the changes we made in our content as well as share it to anyone who wishes to use it. In this section, we will use Github and Github Desktop to manage our repository by merging any changes we made in our local repository to git repository, which is our repository located in Github.

0. Do Section II, before you continue.
	+ The following steps will not work until you made changes in your local repository.
1. Open Github Desktop.
2. In the bottom left, fill in the text, which summerizes the changes you made in your local repository.
3. Press `Commit to main` in the bottom left.
4. Press `Push Origin` in the top middle.

You have sucessfully merge your changes from your local computer to Github!
If you wish to view your website, follow steps 6-7 and the link to your website will be presented!

## More Resources

- If you wish to learn more about Markdown, visit [Markdown Tutorial](https://www.markdowntutorial.com).
- If you wish to change the format of your resume, check out [Github Supported Themes](https://pages.github.com/themes/) or [Community Made Jekyll Themes](https://jekyllthemes.io/github-pages-themes).
- If you wish to learn more about technical communication, check out Andrew Etter's book, [Mordern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS). 
- If you wish to change the format of your resume, check out one of Github's documentation [here](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll)

## Authors and Acknowledgements

- Special thanks to Github for providing [Cayman Jekyll Template](https://github.com/pages-themes/cayman)

- Special thanks to Safran Bin Kader and Rizaldi Wijaya for peer reviewing the README and resume


## Frequently Asked Questions 

### Why is Markdown better than a Word Processor

Word Processors are not great for creating documentation because documents require frequent updates due to the changes that were made that the document is referencing. As mention in Section II, we are able to quickly write text thanks to markdown's simple syntaxes as well as use those syntaxes to showcase our documents in any format we desire. For example, Github is able to present any README.md files immediatly below any git repositories allowing users to quickly know any information that the repository contains. Another example is your website we made, which reads are markdown file and presents it with the format we are using, which is the Caymen Jekyll Template.

### Why is my local repository not match my git repository from Github

Sometimes, a change can be submited that didn't come from your local computer. For example, you or someone else might've made a change to the repository through Github itself. To correct this, go to Github Desktop and select the repository you want to sync. At the top middle, press the `Fetch from origin`, which will grab for any changes made to the repository. Once it loads, press the `Pull from origin`. Once everything loads, your local repository should match your git repository in Github.