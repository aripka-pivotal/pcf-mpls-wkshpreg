# pcf-mpls-wkshpreg
hugo project for mpls workshop registrations

this workshop registration developed from - https://github.com/rjain-pivotal/pcf-hugo-workshop.  See that README for further details on developing a workshop content site.

To publish this site to cloud foundry do the following
* install hugo (see https://github.com/rjain-pivotal/pcf-hugo-workshop)
* clone this project
* navigate to the cloned project directory
* execute hugo to generate content (settings will be taken from config.toml)
* create a Staticfile in public directory using "touch" command
* ensure manifest.yml is correct for desired urls
* execute push 
* validate content and map production host if not default host, or included in manifest file
