# MKDocs Readme

- `mkdocks.yml`
  - `site_name` and `site_url` are bare minimum to specify.
  - new docs are auto picked and added to navs. If you specify pages in nav, you will have to do for all the pages you add, any new ones too.

- Deployment
  - `mkdocs gh-deploy` to deploy to github
    - creates `gh-pages` branch on local and adds site to it.
    - pushes this branch to remote as default.

- Issues
  - pushes static site, needs build. Can be resolved with GitHub actions.


- Github Actions
  - GitHub Actions is yet another free option from GitHub, which is basically a build server in the cloud
  - have a build server automatically pick up changes in Markdown source files and build the static website directly on the build server.
  - More on git page



- Links
  - <https://blog.elmah.io/deploying-a-mkdocs-documentation-site-with-github-actions/>
