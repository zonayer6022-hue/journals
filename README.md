# Accounts

A small project account tracker. Add projects, their total cost, the members involved, each member's share, and the payments they make. It shows what each person still owes and what is left on each project.

## Setup

1. Create a GitHub repository and upload `index.html` to it.
2. Turn on GitHub Pages: repo **Settings > Pages > Deploy from a branch > main / root**.
3. Create a token: GitHub **Settings > Developer settings > Personal access tokens > Fine-grained tokens > Generate new token**.
   - Repository access: **Only select repositories**, pick this repo.
   - Permissions: **Contents: Read and write**.
4. Open your Pages link, enter `username/repo`, the token, and a password.

The app creates `data.json` in the repo on first save. Every change saves automatically about a second later.

## Notes

- `data.json` is encrypted with your password before upload, so a public repo is fine.
- The token is also stored encrypted with your password, only in that browser.
- On a new device, enter the same repo, a token, and the same password.
- If you forget the password, the data cannot be recovered. Use **Settings > Download backup** now and then.
- To keep data in a different repo from the site, enter that other repo on setup.
