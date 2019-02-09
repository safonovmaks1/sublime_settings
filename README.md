# Sublime setup

This Repo contains some useful help on getting a fresh install of Sublime Text setup.

## Step 1 - Install package manager

First you need to install the sublime package controller which you can get from [https://sublime.wbond.net/](https://sublime.wbond.net/).

When this is done it should be relatively simple to install the following packages by pressing `CMD` + `SHIFT` + `P` and typing `install package`.

#### Installed Packages:

    {
        "bootstrapped": true,
        "in_process_packages":
        [
        ],
        "installed_packages":
        [
            "AdvancedNewFile",
            "All Autocomplete",
            "AutoFileName",
            "Bootstrap 4 Autocomplete",
            "Bootstrap 4 Snippets",
            "BracketHighlighter",
            "Color Highlighter",
            "CSS Format",
            "Emmet",
            "Gist",
            "GitGutter",
            "HTMLBeautify",
            "JavaScript & NodeJS Snippets",
            "JavaScript Completions",
            "JavaScript Ultimate",
            "MarkdownEditing",
            "Package Control",
            "PHPSnippets",
            "Sass",
            "SFTP",
            "SideBarEnhancements",
            "Terminal",
            "Theme - Afterglow",
            "W3CValidators"
        ]
    }

## Step 2 - Sublime settings

After you have installed all the packages you can add in your preferences -> settings - user

#### Settings User:

    {
        "bold_folder_labels": true,
        "color_scheme": "Packages/Theme - Afterglow/Afterglow.tmTheme",
        "font_face": "Consolas",
        "font_options":
        [
            "subpixel_antialias"
        ],
        "font_size": 16,
        "highlight_line": true,
        "highlight_modified_tabs": true,
        "ignored_packages":
        [
            "Vintage"
        ],
        "indent_guide_options":
        [
            "draw_normal",
            "draw_active"
        ],
        "line_padding_bottom": 2,
        "line_padding_top": 2,
        "margin": 2,
        "open_files_in_new_window": false,
        "save_on_focus_lost": true,
        "scroll_past_end": true,
        "show_definitions": false,
        "spellcheck": true,
        "status_bar_brighter": true,
        "tab_size": 4,
        "tabs_small": true,
        "theme": "Afterglow-blue.sublime-theme",
        "translate_tabs_to_spaces": true,
        "word wrap": true
    }
