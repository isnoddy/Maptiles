Here are instructions on how to build maptile templates. These instructions are also found in the .zip folders.

There are two ways to run the code that builds this maptile geo template:

1. Build using -project-

* Install the project command using `ssc install project`.
* Then run `project, setup` and choose the do-file that begins with "build_".
* Then run `project build_<geoname>, build`.

2. Build interactively

* Open the do-file that begins with "build_"
* Edit the line that reads `global root "/Users/me/Documents/git_repos/maptile_geo_templates/build"`.  Replace the folder in that line with the folder on your computer that contains this do-file.
* Run this do-file.
