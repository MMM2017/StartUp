# StartUp

This is a test repo for everyone who wants to try with git;
Also, here we place out ideas in `.md` files.
Please, place yours in `project_ideas` directory.

## Quick How-To of Uploading Your Idea

*(for ones provided with UNIX shell:)*

If you didn't cloned this repo:

```bash
# cd somewhere you want the repo content to be located in, then
git clone git@github.com:MMM2017/StartUp.git
cd StartUp
git status # this one should show you that everything is ok
```

Then, when you're in StartUp directory

```bash
touch project_ideas/my_awesome_idea_name.md
# use your favourite text editor
vim project_ideas/my_awesone_idea_name.md
# for ones who started vim and cannot close it, shift+zz
# after editing:
git status # will show you what you've changed
git add .
git commit -m "Added my awesome idea, like and share it!"
git pull
git push origin master
# ... profit!
```
