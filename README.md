
# Teacher Notes

## Introduction

While the focus of this lesson is git, their will inevitably be spill over from day 1 and section 1. Try and focus student's attention on the must haves for git at this point: Forking and Cloning. Many students may still be grappling with basic python so while introducing bash and git is needed to get them up and running, too many diverse ideas such as branching, merging and stashing may overwhelm them. 

## Learning Goals


- Use Git and Github effectively
- Fork and clone a repo from GitHub
- Be able to git add
- Be able to git commit with meaningful commit messages
- Be able to git push
- Be able to git pull down changes

## Prerequisite Knowledge

* Basic Computer Literacy
* Command line familiarity is very helpful but not 100% essential (pwd, cd, ls, etc.)

## Materials

* [Git Intro Slide Deck](https://docs.google.com/presentation/d/1TUQo1889wqewcTAwchzWGLkmRX8A_so_4ycLuoghoN4/edit#slide=id.g522373b1e4_0_0)

# Teacher Notes

#### Misconceptions:
- Only finished things are on GitHub
- GitHub is hard
- GitHub is only for software engineers
- Data Scientists do not use/need version control


## Lesson Outline:

**Step**: Activation & Scenario <br/>
**Time**: 5 min

_Goal/Scenario:_<br/>
Version control.

Ask students "How many of you have seen a folder like this?
![link example](https://smac-group.github.io/ds/images/bad-version-control.png)

- What's wrong with it?
- What are you trying to do here?
- does it make sense to anyone else that's not you?
- be honest, how many of you have DONE this? (I definitely have before I knew what GitHub was!)

_Scenario_: We want to build a repo of student short bios. We will practice GitHub commands to do this a good way.

_Demonstrate_: <br/>

## Objective 1: git clone
**Time**: 10 min
THERE IS A BETTER WAY. (put funny pic or gif here)
Show them the way of GitHub.

Move to the computer and show them the git commands:

_Demonstrate_: <br/>
### Follow these beginning steps
- Go to Github(demo page) and SEE one that is created (public one where they have permissions). Follow the steps Github gives you.
- `git clone <git-url>`
- find folder on computer (Gui version - Finder, show it's there)
- go in folder
- see stuff

_Apply_: Have students find the repo and clone it down.


## Objective 1.b: git status

-use `git status` within your directory

git status is your friend. You want to obsessively use it to track your files and make sure things worked.
note that nothing shows up. good.

## Objective 2: git add
**Time**: 5 min
_Demonstrate_: <br/>

- open sample file inside
- Put Name:
  - Email address
  - Favorite place you've visited
  - favorite food
  - astrology sign
- fill it out
- rename file to "lastname_intro.txt"

RUN GIT STATUS AGAIN - stuff is red

### git add actual demo
- demonstrate git add of changes
- `git add .` (explain the `.` adds everything in the folder so that it can be monitored and managed)
- RUN GIT STATUS AGAIN - now stuff is green


_Apply_: Have each student follow along and do it

## Objective 3: git commit -m "put meaningful stuff here or else"
**Time**: 10 min
_Demonstrate_:
- `git commit -m "added new txt file"` (`-m` allows you append a message to your commit. Messages should be meaningful and notes to your future self from the past or to other people on your team!)

![demo of how git clone/add/staging/works](gitclone_add_commit.png)

Let's talk about meaningful and effective GitHub commit messages
- https://chris.beams.io/posts/git-commit/
- Write commit messages that are meant for your future self and for other future collaborators!
- Be descriptive and clear

_Apply_: They do it

## Objective 4: git push
**Time**: 5 min
_Demonstrate_ :
- `git push origin master`
- Show the updated code on GitHub!

_Apply_: they do it too, surprise.

Check to see that they all see the updated files on github.

## Objective 5: git pull
**Time**: 5 min
_Demonstrate_ : <br/>
- `git pull origin master`
- They should be able to see new files locally!

_Apply_: they also do the thing!

![demo of how git pull/add/staging/works](gitpull_add_commit.png)

Check to see if they have a bunch of text files on their computer

**Step**: Integration <br/>
**Time**: 10 min
Have them each make another change to their own document about themselves. Add something else fun about themselves, etc.
Then push changes. Go to github and confirm. Check and show the commit history - check the commit messages of other people to see if they can discern what people updated without checking the document.

## Assessment:
**Time**: 10 min
- Have TCFs check to make sure everyone has a file up on github.
- Check with people to see if they have new updated information on their own computers after they pull again, etc.
- Write up the **git commands** on the board and ask them which order do they go in?

## Reflection:
How did this rock your world?
