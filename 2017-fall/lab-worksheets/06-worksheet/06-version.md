# Worksheet 6: Version Control

## Instructions

- Due on Tuesday (Nov, 14th) at Midnight
- Copy the worksheet, answer the questions, and SUBMIT TO [OUR GITHUB
  REPOSITORY](https://github.com/denten-courses/technologies-of-dissent/tree/master/2017-fall/lab-worksheets/06-worksheet)
via pull request (see question 8).
- It is recommended that you Complete the GitHub "Hello World" tutorial before
  starting with this worksheet.
- Include your UNI id on your submission (I recommend you don't use your full
  name).

## Questions

1. In your own words, what is version (or source) control?

Version control is a great way of keeping track of a given project's progress. If used properly it can serve as tool where remote collaboration becomes a commodity rather than a hastle.  

2. Explain the difference between Git and GitHub.

Git is a versioning system runs on a server where multiple users can connect and collaborate on documents, code, etc. GitHub is a website that provides users that do not or cannot have their own personal computer dedicated to running the Git server software. 

3. In a few sentences, explain what a "commit" is?

A commit is a form of "solidifying" changes of a particular or set of files that reside on the Git server. As the name implies you're commiting a change to a previous version of the file, making the changes semi-permanent. Semi-permanent here means that the changes can be un-done, which is one of the major features of version control.

4. What is a "branch" in Git terms?

A branch is a reference of a particular version (commit) of the project. It allows the user to make changes to the project as a whole without affecting the "master" copy. It's somewhat of a temporary version of the repository starting from a given moment in time.

5. What is a repository? Explain what happens when you "push" to and "pull"
   from a repository.

A repository is a bucket of files, where changes to each file are tracked and archived. Pushing and Pulling are intuitive names in the sense that "Pull" retrieves changes from the repository, and "Push" places changes made on the local copy of the file onto the copy that is found on the git server.  

6. What is involved in the "clone" operation?

The clone operation creates a duplicate of the remote repository into a newly created directiory, and creates remote tracking branches for each branch in it. It also creates and checks out an initial branch that is forked from the cloned repository's active branch. [source](https://git-scm.com/docs/git-clone)

7. Find an example of Git being used for a peer production project. In several
   paragraphs answer the following: Who are they? What do they do? Who
maintains the repository? What are the rules for contributing?

One of my favorite repositories is the [Free Ebook Foundation](https://github.com/EbookFoundation). The repo contains links to over 1000 free programming and computer science related ebooks. It began as a StackOverflow post and was moved to GitHub when its popularity increased. 

Originally, the list was created by George Stocker, when it was moved to GitHub it became an open collaborative effort. It's now maintained by the [Free Ebook Foundation](https://ebookfoundation.org/) with the intent on ensuring the propagation of free ebooks for the benefit of everyone.

To contribute, one must follow a few simple guidelines in order to keep the book list free from "takedown" notices or ane other form of legal action. Most importantly, the maintainers require that the book is legitemately free. More rules and guidelines can be found [here](https://github.com/introini/free-programming-books/blob/master/CONTRIBUTING.md)

8. Submit this worksheet (in .txt or .md plain text format) by filing a pull
   request to our Github repository.

## Extra Challenge

9. Explain the difference between a fork and a clone.

A fork is a way to create a "point-in-time" copy of a repository that can serve as a starting point for a new project, or a as a way to propose changes to the maintainer. A clone, on the other hand, is simply a copy of the remote repository to a local system.

10. Find a small spelling error on the *Programming Historian* and submit a
    pull request to the owners. (Check with me for this option, if you are not
sure).

## Hints

Steps for your first pull request (PR):

- Fork the project (via the GitHub interface online). This copies the *whole
  repository* from my account on the GitHub servers to your account.

- Clone the project (via the command line or GUI). This copies the repository
  from your remote GitHub account to your local machine.

- Make your changes. In this case you are simply adding a file to the
  repository (give it a unique file name).

- Push your changes to GitHub. This copies your local changes to the remote.

- Using the GitHub interface file a pull request. This will notify me to pull
  your changes into my repository (from the first step).


