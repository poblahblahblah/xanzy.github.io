---
layout: project
project: chef-guard
project_name: Chef-Guard
---

### Tests Section
Each of the different sections will first show the applicable part of the configuration and then explain every config option separately.

~~~ ini
[tests]
  foodcritic      = /opt/chef/embedded/bin/foodcritic
  rubocop         = /opt/chef/embedded/bin/rubocop
~~~

#### foodcritic
The path to the Foodcritic binary. If you do not want Chef-Guard to execute this test, you should leave this field empty.

#### rubocop
The path to the Rubocop binary. If you do not want Chef-Guard to execute this test, you should leave this field empty.
