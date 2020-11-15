## Welcome to learn git in 15 mins

These set of exercises will help you get started with git very quickly and prepare you to contribute to any project.

You can use [SourceTree](https://www.sourcetreeapp.com/) to install all the dependencies on your system.
We will use command prompt to learn about the most used commands. 
You will be easily able to relate to any Git UI app with this background.

### Installing Git

If you want to download it yourself. You will find all the information required at [GitDownloads](https://git-scm.com/downloads),
shortcut for [Windows](https://git-scm.com/download/win), [Linux/Unix](https://git-scm.com/download/linux), [Mac](https://git-scm.com/download/mac).

### Hands on exercises for a beginner
#### Exercise 1 : Get the branch (master) 
```markdown
Theory : git clone command gets the source to your current directory.

git clone https://github.com/rajneeshbajaj/learngit
```
#### Exercise 2 : Create a branch from master
```markdown
Theory : git branch BRANCH-NAME command create the branch
         git checkout BRANCH-NAME makes branch active in your current directory.
         Any changes you make will be committed to the branch.
         
git branch rajb1
git checkout rajb1

OR the shorter version

git checkout -b rajb1
```
#### Exercise 3 : Make changes to a file.
In the [src](https://github.com/rajneeshbajaj/learngit/tree/main/src) folder, 
modify helloword.py on your machine to have print('Hello World') in the second line.
Save the file.
```markdown
Theory : git diff allows you to find what has changed from ------ ADD Here
         Find what has changed and only commit what you want to preserve.

git diff
```
#### Exercise 4 : Commit the changes locally.
It is a good practice to commit frequently. Commit will not 
take your local copy to the remote repository. The changes will stored
on your machine.
```markdown
Theory : git commit saves the changes to your local git repository.
         You should add some meaningful comment when you commit.

git commit -m "add another print statement"
```

#### Exercise 5 : Push your changes to the github respository
Once your bug fix or feature addition is complete you will have to update the branch
in the remote repository. This will allow other people to see your changes as well.
```markdown
Theory : git push saves the changes to the remote respository

git push
```
#### Exercise 5 : Create another branch (AB) and make code changes
#### Exercise 6 : Merge Code from AB to the OB branch.

#### Other notes

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/rajneeshbajaj/learngit/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
