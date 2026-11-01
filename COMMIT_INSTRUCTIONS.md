# Commit your GitHub profile README

1. Create a repository named exactly `MaidaJaved23` (same as your GitHub username).
2. Extract this package and upload the contents of the `maida-github-linkedin-package` folder to the repository root.
3. From that folder, run:

```bash
git init
git add README.md assets/ LINKEDIN_PROFILE_COPY.md
git commit -m "Create GitHub profile README and graphics"
git branch -M main
git remote add origin https://github.com/MaidaJaved23/MaidaJaved23.git
git push -u origin main
```

If the repository already has a remote, check it with `git remote -v` before adding another.
