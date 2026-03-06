The zip contains 108 files to upload to your repo:

106 individual .md recipe files organized into vol1/ and vol2/ subfolders by category
manifest.json — the index the HTML reads to discover all recipes
mfbg-recipes-github.html — the new app file

To get it working:

Upload the contents of the zip to https://github.com/BryanGower/MFBGRecipes (maintaining the folder structure)
Open mfbg-recipes-github.html in your browser — it will fetch everything live from GitHub

Adding a new recipe is just two steps:

Create a new .md file in the right folder (e.g. vol2/breakfast/new-recipe.md) following the frontmatter format at the top
Add an entry to manifest.json pointing to the new file path

Editing an existing recipe is even simpler — just edit the .md file directly on GitHub and the app picks up the changes immediately on next load (it fetches fresh from raw.githubusercontent.com every time).
