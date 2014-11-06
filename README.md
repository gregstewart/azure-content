# README

Learn the basics of contributing articles to the azure-content repository for WindowsAzure.com documentation.

##Before we can accept your pull request

Thank you for your interest in Windows Azure documentation. Before we can accept your pull request, we need you to sign a Contribution License Agreement (CLA). Full details are available at [http://windowsazure.github.io/guidelines.html#cla](http://windowsazure.github.io/guidelines.html#cla). Please email a copy of the signed CLA to [cla@microsoft.com](mailto:cla@microsoft.com).

###Who needs a CLA?
* Members of the Microsoft Open Technologies group.
* Contributors who don't work for Microsoft.

##Repository organization

The content in this repository follows the organization of documentation on WindowsAzure.com. This repository contains two root folders: 

### \articles 

The articles folder contains the documentation articles formatted as markdown files with a .md extension. Articles are published to WindowsAzure.com in the following path http://www.windowsazure.com/en-us/documentation/articles/{article-name-without-md}/. 

* **Article filenames:** Begin with the service name, such as *hdinsight*, and include the development language and a description of the subject matter. Dashes (-) separate the words. 

* **Media subfolders:** The *\articles* folder contains the *\media* folder inside which are subfolders with the images for each article. The article image folders are named identically to the article file, minus the *.md* file extension.

### \includes

Content authors can create reusable content sections to be included into one or more articles. An include file is simple markdown (.md) file that can contain any valid markdown content including text, links, and images. All include markdown files must contained in the *\includes* directory in the root of this repository. 

* **Media subfolders:** The *\includes* folder contains a *\media* folder with folders for the images in each include. The includes image folders are named identically to the include file, minus the *.md* file extension. 

## Working with Windows Azure articles

### Article template

*Information to come.*

**Referencing include files** - There is a specific syntax required for referencing include files.[WACOM.INCLUDE [include-short-name](../includes/include-file-name.md)]
	

Note: An include file cannot reference to other includes. 

## Using GitHub, Git and this repository
>>>>>>> AUX3154

Thank you for your interest in Windows Azure documentation. Before we can accept your pull request, we need you to sign a Contribution License Agreement (CLA). Full details are available at [http://windowsazure.github.io/guidelines.html#cla](http://windowsazure.github.io/guidelines.html#cla). Please email a copy of the signed CLA to [cla@microsoft.com](mailto:cla@microsoft.com).

<<<<<<< HEAD
<<<<<<< HEAD
###Who needs a CLA?
* Members of the Microsoft Open Technologies group.
* Contributors who don't work for Microsoft.

=======
### Setting up your fork of the repository
>>>>>>> AUX3154

##Repository organization

The content in the azure-content repository follows the organization of documentation on WindowsAzure.com. This repository contains two root folders: 

### \articles 

The *\articles* folder contains the documentation articles formatted as markdown files with an *.md* extension. Articles are published to WindowsAzure.com in the path *http://www.windowsazure.com/en-us/documentation/articles/{article-name-without-md}/*. 

* **Article filenames:** Begin with the service name, such as *hdinsight*, and include the development language and a description of the subject matter. Use all lowercase letters and dashes (-) to separate the words. 

* **Media subfolders:** The *\articles* folder contains the *\media* folder, inside which are subfolders with the images for each article. The article image folders are named identically to the article file, minus the *.md* file extension.

### \includes

Content authors can create reusable content sections to be included into one or more articles. An include file is simple markdown (.md) file that can contain any valid markdown content including text, links, and images. All include markdown files must contained in the *\includes* directory in the root of this repository. 

* **Media subfolders:** The *\includes* folder contains a *\media* folder, inside which are folders for the images in each include. The includes image folders are named identically to the include file, minus the *.md* file extension. 

## Working with Windows Azure articles

### Article template

*Information to come.*

### Referencing include files

Use the following syntax to reference an include file in your article:

	[WACOM.INCLUDE [include-short-name](../includes/include-file-name.md)]
	

**Note:** An include file cannot reference other includes. 

## Using GitHub, Git and this repository

=======
##Repository organization

The content in the azure-content repository follows the organization of documentation on WindowsAzure.com. This repository contains two root folders: 

### \articles 

The *\articles* folder contains the documentation articles formatted as markdown files with an *.md* extension. Articles are published to WindowsAzure.com in the path *http://www.windowsazure.com/en-us/documentation/articles/{article-name-without-md}/*. 

* **Article filenames:** Begin with the service name, such as *hdinsight*, and include the development language and a description of the subject matter. Use all lowercase letters and dashes (-) to separate the words. 

* **Media subfolders:** The *\articles* folder contains the *\media* folder, inside which are subfolders with the images for each article. The article image folders are named identically to the article file, minus the *.md* file extension.

### \includes

Content authors can create reusable content sections to be included into one or more articles. An include file is simple markdown (.md) file that can contain any valid markdown content including text, links, and images. All include markdown files must contained in the *\includes* directory in the root of this repository. 

* **Media subfolders:** The *\includes* folder contains a *\media* folder, inside which are folders for the images in each include. The includes image folders are named identically to the include file, minus the *.md* file extension. 

## Working with Windows Azure articles

### Article template

*Information to come.*

### Referencing include files

Use the following syntax to reference an include file in your article:

	[WACOM.INCLUDE [include-short-name](../includes/include-file-name.md)]
	

**Note:** An include file cannot reference other includes. 

## Using GitHub, Git and this repository

>>>>>>> 83da1629f1e2c238afd4d4bfa156758a941d2d8a
**Note:** Most of the information in this section can be found in [GitHub Help] [] articles.  If you are familiar with Git and GitHub, skip to the "Contribut and edit content" section for the particulars of the code/content flow of this repository.

### Setting up your fork of the repository

1.	The first step to contributing to this project is setting up a GitHub account. If you have not done so already go to [GitHub Home] [] and do so now.
2.	Now that you have an account, you also need a copy of Git on your computer. Follow the instructions in the [Setting up Git Tutorial] [Set Up Git].
3.	Now that machine is set up with Git, you need a fork of this repository. Go to the top of the page and click the **Fork** button. You now have your own fork of this repository.
4.	The last step involves copying your fork to your local machine. To do this go open GitBash. On the command prompt enter:

		git clone https://github.com/<your user name>/azure-content.git

	Next create a reference to the root repository by entering these commands:

		cd azure-content
		git remote add upstream https://github.com/WindowsAzure/azure-content.git
		git fetch upstream

<<<<<<< HEAD
=======
Congratulations you have now set up your repository.  The above steps will not need to be repeated again.

>>>>>>> AUX3154
### Contribute and edit content

In order for the contribution process to be as seamless as possible, the following procedure has been established.

1. Create a new branch
2. Add new content or edit existing content
3. Submit a pull request to the main repository
4. Delete the branch

Each branch should be limited to a single concept/article both to streamline workflow and reduce the possiblity of merge conflicts.  The following efforts are of the appropriate scope for a new branch:

* A new article (and associated images)
* Spelling and grammar edits on an article.
* Applying a single formatting change across a large set of articles (e.g. new copyright footer).

#### Create a new branch

1.	Open GitBash
2.	Type `git pull upstream master:<new branch name>` in the prompt. This will create a new branch locally copied from the latest WindowsAzure master branch.
3.	Type `git push origin <new branch name>` in the prompt. This will alert GitHub to the new branch. You should now be able to see the new branch in your fork of the repository on GitHub.
4.	Type `git checkout <new branch name>` to switch to your new branch.

#### Add new content or edit existing content

You can now navigate to the repository on your local machine using Windows Explorer. The repository files are in `C:\Users\<yourusername>\azure-content`.

If you are editing files, open them in an editor of your choice and start modifying them.  If you want to create a new file, use the editor of your choice and save the new file in the appropriate location in your local copy of the repository.  While working, make sure to save your work frequently.

The files in `C:\Users\<yourusername>\azure-content` are a working copy of the new branch that you created in your local repository. Changing anything in this folder does not affect the local repository until you commit a change. To commit a change to the local repository, type the following commands in GitBash:

	git add .
	git commit -v -a -m "<Describe the changes made since last commit> submitted for publishing on <date>"

The `add` command adds your changes to a staging area in preparation for committing them to the repository. The period after the `add` command specifies that you want to stage all of the files that you have added or modified, checking subfolders recursively. (If you don't want to commit all of the changes, you can add specific files. You can also undo a commit. For help, type `git add -help` or `git status`.)

The `commit` command applies the staged changes to the repository. `-m` means you are providing the commit comment in the command line. If you aren't targeting a specific date for publishing, you can say "for publishing ASAP".  The -v  and -a switches can be omitted. The -v switch is for verbose output from the command, and -a does what you already did with the add command.) 

You can commit multiple times while you are doing your work, or you can wait and commit only once when you're done.

#### Submit a pull request to the main repository

When you are done with your work and are ready to have it merged into the central repository follow these steps.

1.	In GitBash type `git push origin <new branch name>` in the command prompt.  In your local repository, `origin` refers to your GitHub repository that you cloned the local repository from. This command pushes the current state of your new branch, including all commits made in the previous steps, to your GitHub fork.
2.	On the GitHub site, navigate in your fork to the new branch.
3.	Click the **Pull Request** button at the top of the page.
4.	Ensure that the Base branch is `WindowsAzure/azure-content@master` and the Head branch is `<your username>/azure-content@<branch name>`
5.	Click the **Update Commit Range** button.
6.	Give your pull request a Title, and describe all the changes being made.  If your bug fixes a TFS Item or GitHub issue make sure to reference them in the description.
7.	Submit the Pull Request.

One of the site administrators will now process your pull request.  Your pull request will surface on the WindowsAzure/azure-content site under Issues.  When the Pull Request is accepted, the issue will be resolved.

#### Create a new branch after merge

After a branch has been successfully merged (i.e. your pull request has been accepted), do not continue working in the local branch that was successfully merged upstream. This can lead to merge conflicts if you submit another pull request. Instead, if you want to do another update, create a new local branch from the successfully merged upstream branch.

For example, suppose your local branch X was successfully merged into the WindowsAzure/Azure-Content master branch and you want to make further updates to the content that was merged. Create a new local branch, X2, from the WindowsAzure/Azure-Content master branch. To do this, open GitBash and execute the following commands:

	cd azure-content
	git pull upstream master:X2
	git push origin X2

You now have local copies (in a new local branch) of the work that you submitted in branch X. The X2 branch also contains all the work other writers have merged, so if your work depends on others' work (e.g. shared images), it will be available in the new branch. You can verify that your previous work (and others' work) is in the branch by checking out the new branch...

	git checkout X2

...and verifying the content. (The `checkout` command updates the files in `C:\Users\<yourusername>\Azure-Content` to the current state of the X2 branch.) Once you have checked out the new branch, you can make updates to the content and commit them as usual. However, to avoid working in the merged branch (X) by mistake, it is best to delete it (see the following "Delete a Branch" section).

#### Delete a branch

Once your changes have been successfully merged into the central repository you can delete the branch you used, as you will no longer need it.  Any further work requires a new branch.  To delete your branch follow these steps:

1.	In GitBash type `git checkout master` in the command prompt.  This ensures that you aren't in the branch to be deleted (which isn't allowed).
2.	Next, type `git branch -d <branch name>` in the command prompt.  This will delete the branch on your local machine only if it has been successfully merged to the upstream repository. (You can override this behavior with the `–D` flag, but first be sure you want to do this.)
3.	Finally, type `git push origin :<branch name>` in the command prompt (a space before the colon and no space after it).  This will delete the branch on your github fork.  

Congratulations, you have successfully contributed to the project.

## Writing an article using Markdown

All of the articles in this repository use Markdown.  While a complete introduction (and listing of all the syntax) can be found here [Markdown Home] [], the relevent basics will be covered here.

If you are looking for a good editor, try [Markdown Pad][].


### Markdown basics

Below is a list of the most common markdown syntax.

* 	**Line breaks vs. paragraphs:** In Markdown there is no HTML `<br />` element. Instead, a new paragraph is designated by an empty line between two blocks of text.
*	**Italics:** The HTML `<i>some text</i>` is written `*some text*`
* 	**Bold:** The HTML `<strong>some text</strong>` element is written `**some text**`
* 	**Headings:** HTML headings are designated by an number of `#` characters at the start of the line.  The number of `#` characters corresponds to the hierarchical level of the heading (for example, `#` = h1 and `###` = h3).
* 	**Numbered lists:** To make an numbered (ordered) list start the line with `1. `.  If you want multiple elements within a single list element, format your list as follows:
		
		1.	Notice that this line is tabbed over after the '.'
		
			Now notice that there is a line break between the two paragraphs in the list element, and that the indentation here matches the indentation of the line above.

*	**Bulleted lists:** Bulleted (unordered) lists are almost identical to ordered lists except that the `1. ` is replaced with either `* `, `- `, or `+ `.  Multiple element lists work the same way as with ordered lists.
*	**Links:** The base syntax for a link is `[visible link text](link url)`.

	Links can also have references, which will be discussed in the "Link and Image References" section below.

*	**Images:** The base syntax for an image is `![alt text for the image](image url)`.

	Images can also have references, which will be discussed in the "Link and Image References" section below.

*	**In-line HTML:** Finally, markdown allows for the inclusion of HTML inline:  `<i>italic</i>` is correctly rendered by Markdown as <i>italic</i>.

### Link and image references

Markdown has a really nice feature that allows a user to insert a reference instead of a URL for images and links. sThe syntax for using this feature is:

	The image below is from [Google][googleweb]
	
	![Google's logo][logo]
	
	[googleweb]: http://www.google.com
	[logo]: https://www.google.com/images/srpr/logo3w.png

By using references grouped at the bottom of your file, you can easily find, edit, and reuse link and image URLs. 

## Additional information

* For more information on Markdown go to [their site][Markdown Home].
* For more information on using Git and GitHub first check out the [GitHub Help Section] [GitHub Help] and if necessary contact the site adminstrators.

[GitHub Home]: http://github.com
[GitHub Help]: http://help.github.com/
[Set Up Git]: http://help.github.com/win-set-up-git/
[Markdown Home]: http://daringfireball.net/projects/markdown/
[Markdown Pad]: http://markdownpad.com/
[WindowsAzure/Azure-Content issue]: https://github.com/WindowsAzure/azure-content/issues
