## How to start a new website

### Repository

For each conference year we should create a dedicated repository named `<year>`.rubyunconf.eu for the website.

### DNS

Setup a subdomain for each conference https://`<year>`.rubyunconf.eu and redirect from https://rubyunconf.eu to the current conference subdomain https://2019.rubyunconf.eu

### Workflow

* Create a new repository `2020.rubyunconf.eu`
* Push code from `2019.rubyunconf.eu` to `2020.rubyunconf.eu`
* Setup DNS for https://2020.rubyunconf.eu
* Start over and edit the website as you want
* Change redirect at [rubyunconf.eu](https://github.com/rubyunconfeu/website-root-redirector) to `2020.rubyunconf.eu`
* Party on :tada:

### Advantages

* We will gain stable links - links will continue to work next year 
* Keep it simple - we don't have to fiddle around with last years decisions 
* The old conference website stays available in its original form