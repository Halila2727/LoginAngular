# LoginAngular

## Directions

```bash
git clone https://github.com/Halila2727/LoginAngular.git <give-it-some-name>
cd your-repo-name
```

Make sure you have angular and node.js and npm installed

In the rode directory do:
```bash
npm install
ng serve
```
Something should pop up on your web browser: http://localhost:4200

## DO NOT
- push node_modules
- push secrets like api keys, passswords or environment (.env) files
- Do not merge without creating a new branch and getting it reviewed by one other person

## How to commit a change?
Before coding, create a new branch where you can make changes.
```bash
git checkout -b feature/give-it-a-name
```
When you are done coding and want to push the changes to this repository, do
```bash
git add .
git commit -m "describe-what-you-did"
```

Then push the branch to GitHub
```bash
git push origin feature/the-name-you-gave-this-branch
```
Then: 
- open a pull request (PR)
- Click "Compare & pull request"
- Add a title and description and then click "Create pull request"
- Good idea to message on Teams
- When it's reviewed and discussed and approved, click "merge pull request" and choose "squash and merge" and delete the feature branch on gitHub.

After merging, on your terminal, switch back to main and pull the latest updates:
```bash
git checkout main
git pull origin main
``` 
