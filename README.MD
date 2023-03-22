# nyangweso-rodgers.github.io

## Table Of Contents
- [Further Reading]()
    - [GitHub Pages - Website for you and Your Projects](https://pages.github.com/)

# Feature Branch Workflow
# Start with the main Branch
```sh
    git checkout main
    git fetch origin
    git reset --hard origin/main
```

# Create a New Branch
* Crete 3 seperate branches to highlight 3 approaches for designing the website
    ```sh
        # 3 branches
        git checkout -b dev-with-bs5
        git checkout -b dev-with-tailwind-css
        git checkout -b dev-vanilla-css
    ```
# Update, add, commit, and Push changes
```sh
    git status
    git add <file_name>
    git commit
```

# Push the Branches to Remote
* Assuming that "__origin__" is the name of the remote repo you want to push your changes to:
    ```sh
        git push origin dev-with-bs5
        git push origin dev-with-tailwind-css
        git push origin dev-vanilla-css
    ```

# Merge a branch to main
```sh
    git checkout main
    git pull
    git pull origin dev-with-bs5
    git pull origin dev-with-tailwind-css
    git pull origin dev-vanilla-css
```

# Delete a Branch
* Switch to another branch: Before deleting the branch, make sure you're on a different branch. You cannot delete a branch that you are currently on.
    ```sh
        # checkout from the dev branches
        git checkout dev-with-bs5
        git checkout dev-with-tailwind-css
        git checkout dev-vanilla-css
    ```
* Delete the local branch:
  ```sh
    git branch -d dev-with-bs5
    git branch -d dev-with-tailwind-css
    git branch -d dev-vanilla-css
  ```
* Delete the Remote Branch
  ```sh
    git push origin --delete dev-with-bs5
    git push origin --delete dev-with-tailwind-css
    git push origin --delete dev-vanilla-css
  ```
* Verify the branch has been deleted both locally and remotely
  ```sh
    git branch -a # a command lists all branches both locally and remotely
  ```
# Frameworks Used
1. Boostrap 5

    ```html
        <!-- Latest compiled and minified CSS -->
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet">

        <!-- Latest compiled JavaScript -->
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"></script>
    ```

2. Font Awesome

    ```html
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    ```

3. Google Fonts Library

    ```html
        <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet" type="text/css">
        <link href="https://fonts.googleapis.com/css?family=Lato" rel="stylesheet" type="text/css">
    ```
# Color Palette
1. #0A2647
2. #144272
3. #205295
4. #2C74B3

# Color Palette Website
- [ColorKit](https://colorkit.co/profile/Rodgers)

# Font Awesome Icons
- [Icons Maps](https://www.w3schools.com/icons/fontawesome5_icons_maps.asp)
- [Icons Chat](https://www.w3schools.com/icons/fontawesome5_icons_chat.asp)
- [Icons Business](https://www.w3schools.com/icons/fontawesome5_icons_business.asp)
- [Icons Computers](https://www.w3schools.com/icons/fontawesome5_icons_computers.asp)