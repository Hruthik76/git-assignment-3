# Git Branching & Merge Conflict Demo


## Assignment - 3

- creating feature branches.
- Experience a merge conflict.
- Resolve the conflict and successfully merge all changes.


This is a simple HTML project with basic styling and content updates to simulate a realistic branching and merging scenario.

## Branches

- **main** – Base branch
- **feature/update-styling** – Modified by removing a paragraph in the HTML file.
- **feature/add-content** – Added new paragraph content to the same HTML file.

## Merge Conflict 

Both feature branches made changes to the same section of `index.html`, leading to a conflict when merging the second branch.
![image](https://github.com/user-attachments/assets/df7ed1b7-a8b0-487f-a5c4-27f171d12baf)


## Resolution Steps

1. Merged `feature/update-styling` into `main`.
2. Attempted to merge `feature/add-content` and encountered a conflict.
3. ![image](https://github.com/user-attachments/assets/a20c5b89-c49f-4ce6-ab7e-d89d2e08108b)
4. Manually resolved the conflict by:
   - Keeping the updated styling from `feature/update-styling`
   - Including the new content from `feature/add-content`
5. Committed and pushed the resolved changes.
6. ![image](https://github.com/user-attachments/assets/5d9bcf70-4f33-4b1b-84f1-4518e03c9095)
7. Successfully merged both branches into `main`.
8. ![image](https://github.com/user-attachments/assets/34677648-51c8-4c93-8f53-ce8a5517b9c5)

## Final `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
</head>
<body>
    <style>
        body {
            background-color: azure;
        }
    </style>

    <p>This is initial Document</p>
    <p>We added content</p>
</body>
</html>
