### Add Rewrite.blog to collect emails

```
curl https://github.com/tmoreton/TailwindHTMLTemplate.git
```

Check out the live site [HERE](http://tmoreton.github.io/TailwindHTMLTemplate)

### Add Rewrite.blog to collect emails
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