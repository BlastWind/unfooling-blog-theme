# my-ghost-journal-theme
My ghost blog theme, based from the official ghost [Journal](https://github.com/TryGhost/Journal) theme.

My [blog](https://unfooling.com)

I have a github workflow (located in `.github/workflows/`) listening to pushes. On push, the workflow builds the template and pushes it to my remote, self hosted ghost instance. 

To use my github workflow in a fork, set your own `ADMIN_KEY` and `URL` repo secrets. For more information, look in the `scripts` folder.

One more thing, note that the theme name uploaded is also name of `package.json`, which is also the dynamic name used in the uploading scripts. So if you change the theme name, make sure to look through the entire repo for all occurences.
