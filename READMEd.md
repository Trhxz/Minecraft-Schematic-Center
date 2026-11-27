# Minecraft Schematic Center

A static website that works on GitHub Pages. No server needed.

## 1. Put it on GitHub
1. Make a free account at github.com and click **New repository**. Name it, for example, `minecraft-schematic-center`, and make it **Public**.
2. Click **uploading an existing file**, drag in everything from this folder (including the `data` and `images` folders), and click **Commit changes**.
3. Go to **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick the `main` branch and the `/ (root)` folder, and save.
4. After a minute your site is live at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

## 2. Set it up
Open `config.json` on GitHub (click the file, then the pencil icon) and fill in:
- `repo`: your repository, like `yourname/minecraft-schematic-center`. Support tickets become GitHub Issues on this repo.
- `discord`: your Discord invite link, like `https://discord.gg/yourinvite`.

## 3. Add a build
1. Open `add.html` on your live site, fill it in, and press **Make the block**, then **Copy**.
2. On GitHub open `data/entries.json`, click the pencil, and paste the block inside the `[ ]`, after the last entry. Entries are separated by commas, and the last one has no comma.
3. Upload the photos to the `images` folder (**Add file > Upload files**). The file names must match what you typed in the form.
4. Click **Commit changes**. The site updates in about a minute.

To remove or fix an entry, edit or delete its block in `entries.json`.

## Premium builds
In the form, tick **Premium entry** and add a price and a **Buy link**. A page on GitHub can’t hide files, so don’t put the download link in the repo. Sell the file on a shop such as Gumroad, Ko-fi or Patreon, which delivers it after payment, and use that product page as the Buy link.

## Support tickets
The Support form opens a prefilled new issue on your repo. Visitors need a free GitHub account, and issues are public. You see and answer them under the **Issues** tab.

## Good to know
- Opening `index.html` straight from your computer won’t load the data. Use the GitHub Pages address.
- Only people you add as collaborators on the repo can change the site.
