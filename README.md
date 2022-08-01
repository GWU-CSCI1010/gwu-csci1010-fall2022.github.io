# CSCI 1010 Course Website

This is a [Jekyll Website](https://jekyllrb.com/) using the [Friday Theme](https://sfreytag.github.io/friday-theme/).

## Installation
1. Clone this repository
2. Install Ruby (if it isn't already installed)
3. Build website locally using `jekyll serve`

## Directory Guide
- `_assignments`: Assignment pages (pages in this folder are automatically set to the "assignment" template, meaning they need a `due_date` variable in the header). An auto-generated list of these pages can be found at https://gwu-csci1010.github.io/list/assignments.html
- `_data`: Website data
    - `nav.yml`: The navbar on the top of the website
    - `profile.yml`: Currently unused, but will automatically add social media links to the left side panel if added to this file
- `_includes`: HTML structures used by Jekyll (you can ignore these unless you're changing the look of the site)
- `_labs`: Lab pages. An auto-generated list of these pages can be found at https://gwu-csci1010.github.io/list/labs.html
- `_layouts`: More HTML customization, specifically for page templates (you can ignore unless you're changing the look of the site)
- `_pages`: Bulk of the website's content is found here
- `files`: A "general resources" folder of sorts. This stores lecture materials, presentations, etc. just to keep the root directory clean
- `images`: Image files used in visual content on the site. Again, this is really only here to keep the root directory clean
- `theme`: CSS structures used to make the site pretty. Ignore unless you're changing the look of the site. This is mostly unchanged from the original Friday theme