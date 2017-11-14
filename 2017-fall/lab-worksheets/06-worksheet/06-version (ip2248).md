# Worksheet 6: Version Control

## Instructions

- Due on Tuesday (Nov, 14th) at Midnight
- Copy the worksheet, answer the questions, and SUBMIT TO [OUR GITHUB
  REPOSITORY] via pull request (see question 8).
- It is recommended that you Complete the GitHub "Hello World" tutorial before
  starting with this worksheet.

1. In your own words, what is version (or source) control?

version control allow us to keep tracking the changes. Thus, I can easily check the changes, compare the changes, and return to the certain version. 
Also, the system automatically check the crashes between the edited versions, so if my editing is crushed with others’, the system shows me a warning message. Thus, it reduces the risk that I rewrite or delete other people’s work. 


2. Explain the difference between Git and GitHub.

Git is a version control system, and Github is the main servers (with website) that store Git data. In this way, various computers and people interact and communicate through Github. Also, the information is not only stored in the main server but also stored in each person’s computer. 


3. In a few sentences, explain what a "commit" is?

The commit function powers Git. If I “commit,” the program takes a snapshot at the point. Thus, I can restore or compare my project of that moment. 
If I want others to use “commit” in my project, I need to add them as collaborator.  


4. What is a "branch" in Git terms?

If many people work together in one project, each participant branches off the project and changes in one’s own version. After they finish their work, they can merge the edited and changed version to the main directory, master. 


5. What is a repository? Explain what happens when you "push" to and "pull"
   from a repository.

I think repository is a kind of folder. So, the project can be saved in repository. It can be a local folder in your computer or the online server, Github. In the repository, I can name and save the project files. 

Push is uploading my project on my Github account. If I work on my computer, I need to upload it to share. In this case, with “gitpush” command, I can push the changes in my code. 
 
If I change a source code of a project, but I do not have any authority on that project, I can request “Pull.” Then, a person who is in charge downloads or copy to master repository (Pull). Also, if I want to move the files from others’ computer to my one, I can use “pull.”


6. What is involved in the "clone" operation?

With clone operation, I can copy what is in the main control server, so I can work on my computer as the same way to on the main server. In this way, I can work without any problem, such as missing link or files.  Also, the main server can maintain its version. 


7. Find an example of Git being used for a peer production project. In several paragraphs answer the following: Who are they? What do they do? Who maintains the repository? What are the rules for contributing?

The project I look up is The Go programing language. https://github.com/golang/go  This project is initiated by Google to build an open source programming language. I do not know about the programming language, but as far as I understand is that they try to build a programing language that makes programming easy to build. The repository is under the account of Keith Randall who works for Google Inc., but there is 957 contributors, mostly who seems to work for Google Inc. 

It is interesting that their main repository is on Google server, https://go.googlesource.com/go. And, on Github server, a mirror of the canonical Git repository. Also, they do not accept pull requests; they says, “we use the issue tracker for bug reports and proposals only.” So, I am not sure that how much they use Github, but it seems that their own website (the main repository) seems to use the Git system. On their website, it says, “Powered by Gitiles, and the term they use seems the same. I think that Google (probably a team in Google) mainly maintains the main repository. Indeed, I am a little curious whether this project is solely a peer production project or it is controlled by the company. 

However, even in this ambiguity, the reason that I choose to explore this project is its contribution guide is very interesting. To contribute, a person firstly uses Gerrit, an open source online tool. Gerrit use the e-mail address as an identifier, but to contribute, the person should use Google account. Also, the person need to be agree with the Contributor license. Then, when appropriate agreement is complete, the person can get an access. 

In the license agreement, it says, “it does not change your right to use your own contributions for any other use.” Indeed, the contributor has a right but the person need to agree with the grant of Copyright and Patent License to Google. Also, the agreement states that the contribution should be your original creation. I think the most important rule is related to authority issues. But, except that, there seems to no restriction in terms of submitting code; for example, the project does not specify what code they want or the restriction on the code. 


8. Submit this worksheet by filing a pull request to our Github repository.

