# About .github

The .github directory houses workflows, issue templates, pull request templates, funding information, and some other files specific to that project.

But another special repository you can create is the .github repository. It acts as a fallback for all of your repositories that don't have an actual .github directory with issue templates and other community health files.

For example, say I have a repository named .github with generic bug report and feature request issue templates. And say I create another repository called new-project, but I don't add a .github directory with issue templates to it.

Then if someone goes to the new-project repo and opens an issue, they'll be presented with an option to choose from the generic templates already in the .github directory.

Similarly, if I add a code of conduct to my .github repository, it will be shown across all my repositories that don't explicitly have one.
