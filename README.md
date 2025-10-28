# vaxviz-staging

**DO NOT COMMIT MANUALLY TO THIS REPOSITORY!**

Vaxviz-staging exists purely to support a staging instance of github pages for [vaxviz](https://github.com/vimc/vaxviz).

Pushes to the main branch of vaxviz will trigger a workflow which will build the app and commit the dist folder to 
this repo, which in turn will trigger a deploy to the staging instance: https://vimc.github.io/vaxviz

The production instance of vaxviz is is here: https://vaxviz.vaccineimpact.org/

Updates to production are triggered by releases of the vaxviz repository.
