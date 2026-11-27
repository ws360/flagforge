# FlagForge

`lɪnʊks@FlagForge:~#`

**rsync & tar commands, explained.** FlagForge is a single-page web app for building `rsync` and `tar` commands without memorizing flags.

## What it does

- **Pick up to ten flags** for `rsync` or `tar`, with search and category filters.
- **See the command build live**, with short flags grouped (`-avz`) and `tar`'s `-f` always placed last (`-czvf archive.tgz`).
- **Read what it does** in plain English: a summary of the whole command plus a line for each flag and path.
- **Fill in paths and values** (sources, destinations, `--exclude` patterns). Values with spaces or special characters are quoted automatically.
- **Switch to long flags** (`--archive --verbose`) for scripts, and copy with one click.
- **Monitor progress** with rsync's `--info=progress2` or `pv` for tar, previewed with sample output.
- **Get the matching unpack command** when you create an archive, including a "check what's inside first" listing command.

## Run it

There's nothing to install or build. Open `index.html` in a browser, or use the hosted version on GitHub Pages.

## Host it on GitHub Pages

1. In this repo, go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Pick the `main` branch and the `/ (root)` folder, then click **Save**.

After a minute or two the app is live at `https://ws360.github.io/flagforge/`.

Your selections are saved in your browser (localStorage), separately for each site you open the app from.
