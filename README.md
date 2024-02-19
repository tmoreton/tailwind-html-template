# Tailwind HTML Landing Page Template
![LandingPage](/example.png)

## Step #1 - Download Template
### [HERE](https://github.com/tmoreton/tailwind-html-template/archive/refs/heads/main.zip)

## Step #2 - Create Github repo with Website Name
![Create Github Repository](/github-repo.png)
```
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/tmoreton/YOUR-REPOSITORY-NAME-HERE.git
git push -u origin main
```

## Step #3 - Activate Github pages
![Create Github Repository](/github-repo.png)

Navigate to https://github.com/tmoreton/YOUR-REPOSITORY-NAME-HERE/settings/pages
Set branch to main and save 

## Step #4 - Signup for Rewrite.blog
[HERE](https://rewrite.blog/)

## Step #5 - Add Rewrite.blog to collect emails
Rewrite script is already in the template but you will just need to replace the ID value here: <input hidden name="id" type="text" value="YOUR_ID_HERE" required />

Full Code Example:
```
<form action="https://rewrite.blog/notion/subscribe" method="post">
<input name="name" type="text" />
<input name="email" type="email" required />
<input hidden name="id" type="text" value="YOUR_ID_HERE" required />
<input hidden name="rewrite" type="text" />
<input hidden name="success_url" type="text" value="YOUR_REDIRECT_URL_HERE" required />
<input type="submit" value="Subscribe" />
</form>
```

## Step #6 - [It's Live](https://tmoreton.github.io/tailwind-html-template)
Once you make changes to your own Github repo it will be visible at https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME-HERE