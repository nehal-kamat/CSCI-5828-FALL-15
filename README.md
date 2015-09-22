# CSCI 5828 - FALL 2015
## Homework 2
### Nehal Kamat | Siddharth Pant | Saish Redkar
git init  
git remote add origin git@github.com:polygonzen/CSCI-5828-FALL-15.git  

**[Nehal's commits]**  
vi Homework_2.md &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Add Homework_2.md]    
git add Homework_2.md  
git commit -m "Commit 0" &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Add Heading]   
vi Homework_2.md		
git add Homework_2.md  
git commit -m "Commit 1" &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	[Edit 1]   
vi Homework_2.md		
git add Homework_2.md  
git commit -m "Commit 2" &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	[Edit 2]  

**[Siddharth's commits on his fork of Nehal's repo]**  
git checkout 4d89645	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	[Shifiting head to commit 0]   
git checkout -b bug-fix  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Create bug-fix branch]  
vi Homework_2.md		
git add Homework_2.md  
git commit -m "Commit 3" &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	[Edit 3]  
vi Homework_2.md		
git add Homework_2.md  
git commit -m "Commit 4" &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	[Edit 4]  
git merge master  [merge conflict]  
vi Homework_2.md		
git add Homework_2.md  
git commit -m "Commit 5" &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	[Edit 5 Merge conflict resolved]  
vi Homework_2.md		
git add Homework_2.md  
git commit -m "Commit 6" &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	[Edit 6]  
git push origin bug-fix

**[Saish's commits on his fork of Siddharth's repo]**  
git checkout 2ba8d42 [move head to commit 3]  
git checkout -b bug-fix-experimental  
vi Homework_2.md		
git add Homework_2.md  
git commit -m "Commit 7"   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	[Edit 7]  
vi Homework_2.md		
git add Homework_2.md  
git commit -m "Commit 8" &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	[Edit 8]    
vi Homework_2.md		
git add Homework_2.md  
git commit -m "Commit 9" &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	[Edit 9]  
git checkout bug-fix  
git merge bug-fix-experimental  
[merge conflict]  
vi Homework_2.md		
git add Homework_2.md  
git commit -m "Commit 11" &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	[Edit merge conflict resolved]  
git push origin bug-fix  
[pull request to Siddharth]

**[Siddharth's commits on his fork]**  
[pull requests merged]  
git checkout bug-fix  
vi Homework_2.md		
git add Homework_2.md  
git commit -m "Commit 12" &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	[Edit 12]  
git checkout master  
git merge bug-fix  
[merge conflict]  
vi Homework_2.md		
git add Homework_2.md  
git commit -m "Commit 13" &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	[Edit 13 Merge conflict resolved]  
git push origin master
[pull request to Nehal]

**[Nehal's commits]**  
[merge pull request]  
vi README.md		[Add README.md file]  
git add README.md  
git commit -m "Commit 14"   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	[Edit 14 Add README]  
git push origin master
