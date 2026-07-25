[README.md](https://github.com/user-attachments/files/30371534/README.md)
# Portfolio site — setup instructions

This is a single self-contained `index.html` file. No build step, no dependencies to install.

## Publish it for free with GitHub Pages

1. On GitHub, create a new **public** repository. A good name is
   `yourusername.github.io` — using this exact naming gives you the shortest possible URL,
   or you can name it anything (e.g. `portfolio`) and it'll live at
   `yourusername.github.io/portfolio`.
2. Upload `index.html` to the repository (drag-and-drop on the GitHub web page works fine,
   or `git add`, `git commit`, `git push` if you're using git locally).
3. In the repository, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch", choose the
   `main` branch and the `/ (root)` folder, then click **Save**.
5. Wait a minute or two — GitHub will give you a live URL at the top of that same Pages
   settings screen.

That's it — free hosting, no ongoing cost, and you can keep editing `index.html` and
pushing new commits whenever you want to update the content.

## How to add a new track later

Open `index.html` and find the `TRACKS` array near the top of the `<script>` section.
Each track is one object in that array — copy an existing one, change the `id`, `label`,
`optionTag`, `tagline`, `profile`, `experience`, `publications`, and `tagsList` fields,
and a new button + page will appear automatically. You don't need to touch anything else
in the file.
