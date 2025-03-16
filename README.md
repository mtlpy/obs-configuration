# OBS Configuration

This repository contain the configurations you need to stream the Montreal-Python conference.

## Requirements

This OBS config required the source: [browser-source](https://obsproject.com/kb/browser-source). It's possible that you have some difficulties on Linux since this source is not included by default. Make sure to review the documentation if you don't have this source.

Note that if you want to live stream some content to Youtube or other external services you will need some additional credentials, review with the Montreal Python team to see what you need and who can give you these access if needed.

## How to setup

In order to setup:

1. Clone this repository on your local machine
2. Open OBS Studio
3. `Scene Collection` > `Import` > Select the `config.json` file of this repository > `Import`

First Opening:

1. `Scene Collection` > `MontrealPythn`
2. You should see a warning message in a window : `Some files are missing since yu last used OBS`
3. Click on `Search Folder ...`
4. Select the `assets` folder of this repository
5. Click on `Apply`

And VOILA! You should be up and running!


## How to update the designs

Note that the `.PNG` files are exported from the Penpot project used for the Montreal-Python designs. If you need to update them:

1. Open the Penpot file
2. Select all the view you want to update
3. On the bottom right of the screen, select `export` > `PNG`
4. The download of a `.zip` file should have been triggered
5. Extract the content of the `.zip` file in this repository (the filenames are the same as the current files, so it should just replace the file you wanted to update)

## Quick tips

**Studio mode**

On the bottom right of your default OBS screen you should see a `Studio Mode` button inside the `Controls` section. It's a nice feature allowing you to see:

 - The actual streamed content on the right side of your screen
 - The future content to stream on the left side of your screen (like a preview mode)
 - Some button on the center, allowing you to push the preview mode into the live stream
     - `Transition` button will change the view after a short transition animation
     - `Cut` button will change the view right away without any animation (usefull to adapt really fast if you have some change to make at the same time than a speaker is presenting for example)

