# API Integration Page & API

This is a sample data driven API integrations page that is hosted on Github, making it something that any API provider can fork and easily put to use, showing the possible integrations with other APIs available when you use their APIs.

This project is <a href="https://github.com/{{ site.github_user }}/{{ site.github_repo }}">forkable using the Github repository</a>, and will run on any site using Jekyll, which makes Github Pages a very suitable place to run data and API driven solutions like this.

There are two API integrations pages available here, <a href="http://api.integration.tool.apievangelist.com/">one for a detailed listing</a>, and <a href="http://api.integration.tool.apievangelist.com/integrations-icons/">another for a more icon based listing</a>. Both use Liquid to access the YAML integrations data store in <a href="https://github.com/api-evangelist-tools/api-integration/tree/master/_data">the _data folder</a> for the project.

In addition to human listing pages, that can run in any API website or portal, there is an API available for accessing API integrations in a machine-readable way. I provide endpoints for filtering by category, and will be adding other endpoints in future versions.

While the integrations YAML data is stored in <a href="https://github.com/api-evangelist-tools/api-integration/tree/master/_data">the _data folder</a> within the Github repository for this site, the data is managed via the Google Spreadsheet, and synced by running the pull spreadsheet script for integrations with a valid Github OAuth token--when successful, it updates the YAML data store with the latest data.

While not 100% documented, this site is meant to be forked, and reskinned with your own graphical website look, and managed with your own data, showing what integrations are available for your API platform. You can add a subdomain to the cname for the Github repo, making it a standalone API integration page that matches the rest of your API website or portal.

If you have any questions, or would like me to deploy an API integration page for your API, you can submit <a href="https://github.com/{{ site.github_user }}/{{ site.github_repo }}/issues">a Github Issue for the project</a>, and I'll get back to you with more information.
