# Kiarash — Aqua Launch

Prepared for https://github.com/kiarashmiri22.

## Publish

1. Extract kiarashmiri22-aqua-launch.zip.
2. Open https://github.com/kiarashmiri22/kiarashmiri22 and choose “uploading an existing file”.
3. Upload the extracted contents to the repository root, including .github, assets, scripts, README.md, config.json and LICENSE. Do not upload the ZIP itself or put everything inside another folder.
4. Commit to main. README.md displays immediately; the included workflow refreshes the artwork on the first upload and daily thereafter.
5. Open https://github.com/kiarashmiri22 to see the result. Check the Actions tab for “Update Aqua Launch”.

If browser upload skips the .github folder, upload it separately or use GitHub Desktop to publish the complete extracted folder. The profile artwork still displays without the workflow, but automatic updates require it.

## Personalization

config.json uses your public GitHub name, bio, avatar and repository languages. No email, website or location was invented. Replace assets/profile-source.png with another image whenever you want a different ASCII portrait.

Local regeneration (Python 3.10+):

    python -m pip install -r scripts/requirements.txt
    python scripts/generate.py

The included SVGs were generated from live public GitHub data. Live statistics count public repositories; language percentages are weighted by repository counts, not lines of code.

The workflow requests contents:write to commit updated SVGs. If your account restricts workflow writes, review Settings → Actions → General → Workflow permissions.

Design and generator: https://github.com/Jenesyx/pretty-github/tree/master/Aqua-Launch
MIT license included. The template author's example portrait was replaced with the current public GitHub avatar of kiarashmiri22.
