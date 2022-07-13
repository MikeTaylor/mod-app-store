# Informal register of issues for `mod-app-store`

* **DONE** -- Generate descriptors from templates
* **DONE** -- Create a git repo containing FAM files ([`example-folio-app-source`](https://github.com/MikeTaylor/example-folio-app-source))
* **DONE** -- Handle GET on `/admin/health`, returning response code 200
* Parse command-line argumennts to allow e.g. `-p 3001` to change port
* Read git repo from within `mod-app-store`
* Configuration of which git repos to use
* Handle GET on `/app-store-apps`, using git response
* Searching and sorting
* Response caching
* Optional arguments to control use of cache
* Handle CRUD for git repo configuration
* Proper README.md
* Write RAML for supported web-services
* Transition to using the GitHub tracker for issues
* Automated tests
* GitHub Actions for publishing