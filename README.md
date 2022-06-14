# Git-cheat-sheet-
A compilation of the most used and important Git commands 

## Installation
<details open>
<summary>Find out more </summary>
 
<pre>$ git --version </pre>

</details>

---

## Git configuartion 
<details open>
<summary>Find out more</summary>

<pre>$ git config --global user.name "[username]" </pre>

<pre>$ git config --global user.email "[valid-email]" </pre>

<pre>$ git config --global color.ui auto </pre>

</details>

---

# commands 

<p> (1) </p>

 To show modified files in working directory, staged for your next commit
    - Use: 
    
    git status

---

<p> (2) </p>

 set a name that is identifiable for credit when review version history
    - Use: 
    
    git config --global user.name “[firstname lastname]”

---

<p> (3) </p>

 set an email address that will be associated with each history marker
    - Use: 
    
    git git config --global user.email “[valid-email]”

---

## Working with Local Branch

- Create a branch

<pre>$ git branch <branch_name> </pre>

<br>
  
- Display all branches

<pre>$ git branch -a </pre>

<br>
  
-  Delete a branch

<pre>$ git branch -d <branch_name> </pre>


<br>
  
- Delete remote branch

<pre>$ git push origin –delete [branchName] </pre>


<br>
  
- Checkout an existing branch

<pre>$ git checkout <branch_name> </pre>


<br>
  
-  Checkout and create a new branch

<pre>$ git checkout -b <new_branch_name> </pre>


<br>
  
- Merge a branch into an active branch

<pre>$ git merge <branch_name> </pre>


<br>
  
- Recover a deleted file and prepare it for commit

<pre>$ git checkout <deleted_file-name> </pre>


