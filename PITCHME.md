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

@snap[west span-50]
### Clone : Get copy about remote repository
@snapend

@snap[east span-50]
![](assets/img/slide2.png)
@snapend

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

@ul[spaced text-white]
- Propose a change (add changeset in Index) : git add filename
- Valid changes (file added in HEAD): git commit -m 'Validation message'
@ulend

---
