# Getserved.me website

Getserved's website.

### Publication

The website is hosted on surge.sh (see more details below).

##### Core Surge commands

In order to update the website, you need to run the command `surge` from the directory root of the repository:
* Publication: `surge`
* Adding a collaborator: `surge --add name1@domain1.com, name2@domain2.com`

### Information

#### Hosting provided

We are making the most of [surge.sh](http://surge.sh) to easily publish the website, and host it for free. In order to publish a new version,

To add permission

#### DNS Management and CDN solution

We are using cloudflare to handle DNS. Contact Alex <alex@getserved.me> for any information or request regarding DNS.

#### Email Form

TODO

### Workflow

Github flow:
* create a new branch for each fix or improvements.
* pull request the change, wait for approval
* merge back to master

Important: only master is meant to be publish to surge. Before publication through surge, it is preferable to add a tag to master, incrementing the version.

Note: master is protected so no force push allowed
