How to run
```
pip install virtualenv
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

# Git Workflow Tutorial

This tutorial will guide you through the process of contributing to our project using Git. We'll cover how to checkout from the main branch, commit to your own branch, and create a pull request.

## 1. Set up your local repository

If you haven't already, clone the repository:

```
git clone [repository URL]
cd [repository name]
```

## 2. Create a new branch from main

Always start your work by creating a new branch from the latest version of `main`:

```
git checkout main
git pull origin main
git checkout -b your-branch-name
```

Replace `your-branch-name` with a descriptive name for your feature or bugfix.

## 3. Make changes and commit

Make your changes to the codebase. When you're ready to commit:

```
git add .
git commit -m "Your commit message"
```

Write a clear and concise commit message describing your changes.

## 4. Push your branch to the remote repository

```
git push -u origin your-branch-name
```

## 5. Create a Pull Request

1. Go to the repository page on GitHub (or your Git hosting platform).
2. Click on "Pull requests" and then "New pull request".
3. Set the base branch to `main` and the compare branch to `your-branch-name`.
4. Add a title and description for your pull request.
5. Click "Create pull request".

## Best Practices

- Keep your commits small and focused.
- Write descriptive commit messages.
- Update your branch regularly with changes from `main` using `git merge main` or `git rebase main`.
- Respond promptly to review comments and make necessary changes.
