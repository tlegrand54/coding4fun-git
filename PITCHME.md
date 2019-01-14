# Let's Get Started

---
@title[Git architecture]

@snap[west span-50]
@ul[spaced text-white]
- Git is a distributed version control system (vs SVN which is centralized)
- Most used => Github, GitLab, Local Git, Bitbucket
@ulend
@snapend

@snap[east span-50]
![](assets/img/slide1.png)
@snapend

---
@title[Git : CLONE]
### @css[headline](Clone repository)

---
@title[Git : CLONE]
@snap[west span-50]
### Clone : Get copy about remote repository
@snapend

@snap[east span-50]
![](assets/img/slide2.png)
@snapend

---
@title[Trees]
### @css[headline](Local Trees)

---
@title[Trees]
@snap[west span-50]
@ul[spaced text-white]
- Local repository contains 3 trees
- Working home : Contains source files
- Index : Tempory space
- HEAD : Last validation
@ulend
@snapend

@snap[east span-50]
![](assets/img/slide3bis.png)
@snapend

---
@title[Add and Commit]
### @css[headline](Add and Commit)

---
@title[Add and Commit]
@ul[spaced text-white]
- Propose a change (add changeset in Index) : git add FILENAME
- Valid changes (file added in HEAD): git commit -m 'Validation message'
@ulend

---
@title[Send changes]
### @css[headline](Send changes)

---
@title[Send changes]
@ul[spaced text-white]
- Send changes from HEAD to remote repository : git push origin master (git push REMOTE BRANCH)
- You can add new remote : git remote add REMOTE_NAME SERVER
@ulend

---
@title[Branch]
### @css[headline](Branch)

---
@title[Branch]
@ul[spaced text-white]
- Create new branch : git checkout -b feature_x
- Change branch : git checkout master
- Remove branch : git branch -d feature_x
- Push branch to remote : git push origin feature_x
@ulend

---
@title[Update & Merge]
### @css[headline](Update & Merge)

---
@title[Update & Merge]
@ul[spaced text-white]
- Update local repository : git pull
- Merge branch : git merge BRANCH
- git diff SOURCE_BRANCH TARGET_BRANCH
@ulend

---
@title[Others commands]
### @css[headline](Others commands)

---
@title[Others commands]
@ul[spaced text-white]
- Create tag : git tag VERSION ID (get ID with git log) (ex : git tag 1.0.0 1b2e1d63ff)
- Cancel local changeset : git checkout -- FILENAME
- git diff SOURCE_BRANCH TARGET_BRANCH
- Remove all changes and local validation : git fetch origin & git reset --hard origin/master
@ulend