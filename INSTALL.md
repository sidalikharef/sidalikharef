# Installation — GitHub Profile README

This design is built for the GitHub repository `sidalikharef/sidalikharef`.

1. Copy `README.md` to the root of the repository.
2. Copy the entire `assets/` folder alongside it (all PNG files).
3. Commit and push both together:

```bash
cd ~/projects/personal/sidalikharef
cp /path/to/sidali-readme/README.md .
cp -r /path/to/sidali-readme/assets .
git add README.md assets/
git commit -m "Style GitHub profile to match portfolio"
git push origin master
```

Do not upload only the README: it references `assets/hero.png` and five section banners.

The portrait is extracted from the website screenshot you provided. For better image quality, replace `assets/hero.png` later with a regenerated hero built from your original high-resolution portrait.

GitHub READMEs cannot use custom CSS or run scripts. The branded headers are images so your design renders on GitHub, while the content remains native Markdown and accessible.
