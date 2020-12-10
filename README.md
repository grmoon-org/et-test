Example Custom Template Repository
Description
This repository is an example Custom Template Repository that can be used with the Cloud Code plugins for VSCode and IntelliJ.

Contents
.template
The .template directory is where your templates.json file belongs. This file describes the contents of your repository so that Cloud Code knows where to look for your templates. It should look something like the following:

{
    "metadata": {
        "version": "1"
    },
    "templates": [
        {
            "path": "path/to/my/template",
            "name": "My Template",
            "description": "This template helps you create something amazing!",
            "languages": ["lang-1", "lang-2", "lang-3", ...]
        },
        ...
    ]
}
There is an example templates.json file in the .template directory of this repository that you can review.

hello-world
A sample golang template. You can see an entry for this template in the .templates/templates.json file.

Usage
To see an example of how the Custom Templates feature of Cloud Code works, you can configure your IDE to recognize this repository and create applications based on the templates within. Follow the steps below to see Custom Templates in action!

If you're interested in creating your own Custom Template, you can clone this repository, create a new directory containing your template (or make changes to any of the sample templates), and import your local, updated repository into your IDE of choice. Make sure to make any necessary updates to the templates.json file before importing your repository or you might see an error.

IntellJ
Install the Cloud Code plugin for IntelliJ
...
VSCode
Install the Cloud Code plugin for VSCode
...
Powered by Gitiles| Privacy
