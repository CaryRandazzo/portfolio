## Initial Setup of template
1. clear the repo or start a new one fresh
2. run
```bash
npx degit --force hugoblox/theme-portfolio .
```
3. make the .github/workflows/hugo.yml file and put its contents in
4. commit and push for the action to execute
5. profit at the github.io/portfolio location

## How to fix GoogleAnalytics issue in tempalte
Later on, there came to be an issue when modifying the template with the GoogleAnalytics error.
This happens because the template was made with code that was deprecated.
So your options are to either:
1. use a version that was not outdated (try v0.119) OR
2. navigate to ~/.cache/.../...etc.../...hugo_stuff.../google_analytics.html
and modify the top line where you see

.site.GoogleAnalytics OR
.Site.GoogleAnalytics TO
.Site.Config.Services.GoogleAnalytics.ID

then trigger the action by commiting and updaing.
You can also test that it works locally by using the command 'hugo server' if it works it works, you may not be able to find it, but you know
if it works the build should work and carry over.

It is possible that any re pull of the module will break this again. use these notes to fix it
