# ODSA-BoW
Repo for all activity related to the ODSA Bunch of Wires Specification. A PDF for the latest dated draft is in the __DRAFTS__ folder

# Madoko
We recommend that all contributors use [Madoko](http://madoko.net) - a live 
markdown editor - to write specs. There are several advantages that Madoko 
provides that we believe will make the contribution process easier:

* Madoko is a live markdown editor. All changes made are immediately visible 
in the generated document. 
* Madoko has integrated their software with a number of common services - including 
GitHub! More on how to open documents on Madoko directly from your fork of 
ODSA-BoW will be provided below
* Madoko automatically enumerates sections and subsections. If you're interested in 
presenting your specs through other mediums (PDF, etc.) it's enumerated in those too
* Madoko makes it easy for users to download those documents as PDFs, HTML, and even LaTeX.

## Reading Specs in Madoko
Madoko's integration with GitHub makes it really easy to open a specific file. When 
you open the [live editor](https://www.madoko.net/editor.html), find the folder icon 
on the top left corner. Choose the Open menu, and again, use GitHub. 

Here, use the GitHub menu to navigate to the repo and the file that you'd like to open. 
Choose the file. It will open in the Madoko editor allowing you to read as you see fit! 
If you'd like to download the file as a PDF, Madoko provides that option. 

# Contribution Guidelines
If you'd like to contribute to ODSA-BoW and develop specifications, here's how you can.

## Forking the Repo
Forking a repository will create a copy of the main repo in your GitHub account. Then, 
you will be able to make all the changes you need to on your local copy before 
re-submitting through a pull request. 

Navigate to the [ODSA-BoW](https://github.com/opencomputeproject/ODSA-BoW) repository. 
Next to the "Watch" and "Star" Buttons will be a "Fork" button. Select it

If will create a fork of the repository on your profile and navigate to the page immediately.

## Keeping Your Fork Up-to-Date
Keep in mind that the fork is just a snapshot of the repository at the current time. 
To make contribution easier, you'll need to keep your forked repo up-to-date. There 
are two ways to do that. 

If you're comfortable with the command line, you can follow the 
instructions [here](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork) on how to fetch the upstream and merge your fork with it. 

If you'd prefer to avoid the command line on the whole, user Kirstie James has come up 
with a solution to use GitHub to sync the fork to the main repo via the browser. You 
can find the instructions [here](https://github.com/KirstieJane/STEMMRoleModels/wiki/Syncing-your-fork-to-the-original-repository-via-the-browser)

## Making a Branch
Next, make a branch for the group of changes you plan. Branching your fork allows you to work on more than one topic without mixing topics in one pull request. In the Branch box type in the name for a new branch. Then you can use that branch box to select which branch you are viewing.

## Creating and Editing Specs
Depending on your contribution, you may be creating and adding new specs or editing and 
adjusting existing specs based on open issues (more on issues below).

If you're creating a new spec, you can open a new document using the 
Madoko [live editor](https://madoko.net/editor.html) and start writing right away. 
If you're editing an existing spec, simply open the file in Madoko and start making edits. 

## Editing an Existing Document in Madoko
Open https://madoko.net/editor.html in a browser tab.  Then:

1. In the folder icon at upper left, use "Open"
2. Select GitHub. If you haven't already allowed Madoko access to your account, do so now.
3. Choose your forked version of the repo and the correct branch for this topic and navigate to the file
4. Edit
5. Use "Synchronize" to save your edits. This makes a commit to GitHub in your branch.

Note that using "Save To" is for creating a new file. It creates a new level of folder hierarchy and does not save to the existing file.

## Saving a New File in Madoko
Once you've created a new document, here's how you 
commit those changes to your forked repo. 

1. Find the folder icon in the top left corner and click the "Save To" option.
2. Madoko will present a variety of options from your local drive to cloud storage 
options like DropBox and, very conveniently, GitHub. 
3. Select GitHub. If you haven't already allowed Madoko access to your account, do so now. 
4. Find the forked and branched version of the repo, and then where in the repo you'd like to save your file. 

Madoko's integration with GitHub means that when you save the file, you're actually 
officially committing the file to GitHub. Write a short, but descriptive commit message 
and save the file. 

If you now look at the forked repository on your GitHub account, it should register the commit 
you just made. 

## Deleting Files
Unwanted files in GitHub can be deleted in the web interface (one at a time) by opening the file and using the Trash icon. Folders can be deleted directly in a local repo copy, but in the web interface, you must delete each file in the folder (one by one) and then the folder goes away.

## Creating a Pull Request
Once you have committed all the changes to your fork, it's time to create a pull request. In 
your forked repo, you'll notice a small message that says "This branch is XX commits ahead of 
the master repo". In that message will be the option to create a pull request. Select it. 

For the specifics on filling out a pull request, please read through GitHub's help page on 
creating pull requests. [Link](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)

# Issues
Issues are how contributors and users of the repository can flag bugs, suggest changes to 
existing specs, and make requests of the repository administrators. If you're interested in 
Issues, you can find more on the GitHub help page describing issues. [Link](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue) 

##Raising Issues
If you are raising a general issues, like a request to the administrators, you can follow 
the GitHub help page on raising issues. [Link](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue)

If you're reading through specifications and would like to raise an issue regarding a spec, 
we ask that you reference the specific line numbers regarding the issue. You can do this by 
opening the Raw version of the file on GitHub. 

Then select the line numbers - make sure to directly click the line numbers, and not 
highlight the lines!

There'll be an option menu next to the selected lines (3 dots). Choose to raise an issue. 
That will direct start an issue. You can then proceed as normal.     

## Resolving Issues
If you're a contributor and you'd like to resolve an issue regarding editing a file, the 
process is simple. Follow the contribution guidelines above and submit a pull request. Then 
make sure to report the issue being resolved on the issue thread and wait for an admin to 
close the issue. 
