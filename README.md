# GodotCICDTemplate
Template using GitHub Actions to export and deploy a Godot project.

## Usage steps
Do the following steps before starting work on your game:
* Create your game's repository.
* Copy the entire contents of this repository into the newly created one, excluding the `.git` folder.
* Change the game name in `project.godot`, `.env`, and optionally in `export_presets.cfg`.
* Enter your Godot version in the `.env` file.
* Push changes to GitHub and wait for the initial build to finish.
* Go to the repository's `Settings > Github Pages` and choose deploy from branch `gh-pages`.
* Wait a couple of minutes for deployment to finish, refresh the page to see when it finishes.
* Enable `Use your GitHub Pages website` in your repository's description, and share the link wherever else you need.

All done. You can now make your game in the newly setup repository.

## TODO
Add a second GitHub Actions workflow with proper versioning and releases.
