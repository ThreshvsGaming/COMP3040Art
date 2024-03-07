# Host Your Resume Online

Host your own resume on a static site generator using Github Pages by following the steps below!

[Demo](https://threshvsgaming.github.io/COMP3040Art.github.io/)

![Demo](app/opera_48tROMvPDM.gif)

## Getting Started

### Prerequisites

You'll need the following things before we get started

- A Github Account
	+ If you haven't created an account already, navigate to [github]() to create a new account

- Github Desktop
	+ We will be using Github Desktop to update your files and compare any changes you made
	+ You can download Github Desktop [here]() 

- Visual Studio Code
	+ You will use Visual Studio Code to create/update your resume
	+ You can download Visual Studio [here]()

- A resume created in markdown
	+ For a guide to learn more about Markdown, see [More Resources](#more-resources)
	
### Instructions

#### I. Setting up your Github Repository

Andrew Etter highly discourages users to rely on PDFs because inevitably, a PDF file will become severely outdated and users will either replace the file or outright forget to update the information. In contrast with websites, users will be able to continuously update their websites, which will always contain up-to-date information. Additionally, users will be able to reference their publish website for anyone to view, whereas PDFs must be downloaded and saved in your computer. In this section, we will go over how to set up a Github Repository to host your static generated website, which will contain your resume.

1. Navigate to [Github]()
2. Login to your Github Account
3. Navigate to this [repository]()
4. Press the `Fork` button at the top right of the page
	+ This allows us to create a copy of the repository mentioned in Step 3 so that we can use its template
	
5. Fill out the necessary information in the current page
	+ Name your repository with the following format `(repository name).github.io`
		* Ex. `COMP3040Art.github.io`
		
	+ Leave everything else default
		
6. Press the `Settings` tab at the top of the page
7. Navigate to the `Pages` section on the left sidebar
8. Choose Deploy from branch under Source
9. Change none to main under Branch
10. Press Save

If you wish to view the website, follow the steps 6-7 and the link to your static generated website will be present.

#### II. Editing your Resume

Andrew Etter explains how lightweight markup languages allows anyone to be a contributer because it allows users to quickly write clean documentation using simple syntax to format the users contents. These simple syntaxes create readable information resulting in other people contributing in the improvements of the documents. In this section, we will use Github Desktop to make a copy of our repository in Github into our local computer and edit them using our Markdown Text Editor, Visual Studio.

1. Open Github Desktop
2. If you are sign in with your github account, select the `file` tab on the top left
	+ If you are already sign in, skip to step 5
3. Select options
4. Press `Sign into Github.com` and sign in
5. Press `Clone a repository from the internet`
6. Select the repository that you created in section I
	+ Ex: `COMP3040Art.github.io`
7. Press `Clone` 
8. Select `Repsoitory` in the top left
9. press `Open in Visual Studio Code`
10. Select the `config.yml` in your File Explorer menu located to the left side
	+ Edit the `title: ` and `description: ` lines catered to your resume
		+ *Do not edit `title: ` and `description: ` themselves. Only the content after those text*
	+ Save the file once you are done
11. Select the `index.md`
12. Put in your resume contents in this markdown file
	+ Make sure the content is written in markdown if you wish to format your resume
13. Save both 
14. If you wish to preview your resume, right-click the index.md in your file explorer menu
15. Select `Open Preview` to view your resume
	+ *The format of your resume is based on Visual Studio Code's format. The format will change once your file changes are submitted into github*

You are now able to edit your resume.

#### III. Uploading/Updating your Resume

Andrew Etter encourages users to use version control systems to manage our files. A version control system allow us to track the changes we made in our content as well as share it to anyone who wishes to use it. In this section, we will use Github and Github Desktop to manage our repository by merging any changes we made in our local repository to git repository, which is our repository located in github.

1. Open Github Desktop
2. If you are not sign in with your github account, follow steps 1-4 in section II
3. If your repository from Github is not in your local computer, follow steps 5-7 in section II
	+ If another project is being occupied in your github desktop, navigate to current respository in the top left
	+ Select add
	+ Follow steps 5-7 in section II
4. In the bottom left, fill in the text, which summerizes the changes you made in your local repository
5. Press `Commit to main` in the bottom left
6. Press `Push Origin` in the top middle

You have sucessfully merge your changes from your local computer to Github

## More Resources

- If you wish to learn more about Markdown, visit [Markdown Tutorial](https://www.markdowntutorial.com)
- If you wish to change the format of your resume, check out [Github Supported Themes](https://pages.github.com/themes/) or [Community Made Jekyll Themes](https://jekyllthemes.io/github-pages-themes)

## Authors and Acknowledgements

- Special thanks to Github for providing [Cayman Jekyll Template](https://github.com/pages-themes/cayman)


## Frequently Asked Questions 

### Why is Markdown better than a Word Processor

Word Processors are horrible for creating documentation, which require frequent updates, depending on what changes were made that the documentation is referencing. With Markdown, we are able to showcase documents in any format we desire because of the simple syntaxes that markdown provides. For example, Github is able to present any README.md files immediatly below any git repositories allowing users to quickly know any information that the repository contains. Another example is your website we made, which reads are markdown file and presents it with the format we are using, which is Caymen Jekyll Template.
