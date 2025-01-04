## 0. How to Remove branches
###  ● Remove a remote branch
-   ```bash
    git push origin :branch_name
#### ● Remove a local branch
- ```bash
    git branch -d branch_name

## 1. Annotated Tags vs Lightweight Tags

### Annotated Tags
- Created with additional metadata (e.g., author, date, and message).
- Useful for version releases or significant project milestones.
- Created using:
  ```bash
  git tag -a <tagname> -m "<message>"

### Lightweight Tags
- Simple pointers to a specific commit without metadata.
- Used for temporary bookmarks or quick taggingproject milestones.
- Created using:
  ```bash
  git tag <tagname>

## 2. Push Tags to the Remote Repository
- Creating using:
    ```bash
    git push origin tagname

## 3. When to Use Rebase
1. For a Linear History
   - Use rebase when you want to avoid merge commits and keep the commit history clean and easy to read.
   - This is especially useful in small teams or personal projects where a clean history is a priority.

## 4. List tags
- creating using:
  ```bash
  git tag

## 5. How to Delete a Tag
### Delete a Tag Locally
- use the command:
    ```bash
    git tag -d tagname
### Delete a Tag remotly
- using:
  ```bash
  git push origin --delete tagname
  
## 6. Adding image
![this is image](https://gratisography.com/wp-content/uploads/2024/10/gratisography-cool-cat-800x525.jpg)

