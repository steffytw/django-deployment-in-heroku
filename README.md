# Deployment of Django in Heroku

- Step 1 : Create an account in [Heroku](https://signup.heroku.com/t/platform?c=7013A000000ib1xQAA&gclid=Cj0KCQjw3s_4BRDPARIsAJsyoLMyAQ08MU3SMAOTHD-gg_kp7ypSIAR0UEnZns2VpUWm4kkUX6AyBeEaAi8UEALw_wcB)

- Step 2 : Download the [Heroku Command Line Interface](https://devcenter.heroku.com/articles/heroku-cli) (CLI) which makes it easy to create and manage your Heroku apps directly from the terminal. It’s an essential part of using Heroku.

- Step 3 : The Heroku CLI requires Git, the popular version control system. If you don’t already have Git installed, complete the following before installing the CLI:

    * [Git installation](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
    * [First-time Git setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

- Step 4 :Run the command heroku on your terminal

```
$ heroku

CLI to interact with Heroku

VERSION
  heroku/7.42.4 linux-x64 node-v12.16.2

USAGE
  $ heroku [COMMAND]

COMMANDS
  access          manage user access to apps
  addons          tools and services for developing, extending, and operating your app
  apps            manage apps on Heroku
  auth            check 2fa status
  authorizations  OAuth authorizations
  autocomplete    display autocomplete installation instructions
  buildpacks      scripts used to compile apps
  certs           a topic for the ssl plugin
  ci              run an application test suite on Heroku
  clients         OAuth clients on the platform
  config          environment variables of apps
  container       Use containers to build and deploy Heroku apps
  domains         custom domains for apps
  drains          forward logs to syslog or HTTPS
  features        add/remove app features
  git             manage local git repository for app
  help            display help for heroku
  keys            add/remove account ssh keys
  labs            add/remove experimental features
  local           run Heroku app locally
  logs            display recent log output
  maintenance     enable/disable access to app
  members         manage organization members
  notifications   display notifications
  orgs            manage organizations
  pg              manage postgresql databases
  pipelines       manage pipelines
  plugins         list installed plugins
  ps              Client tools for Heroku Exec
  psql            open a psql shell to the database
  redis           manage heroku redis instances
  regions         list available regions for deployment
  releases        display the releases for an app
  reviewapps      manage reviewapps in pipelines
  run             run a one-off process inside a Heroku dyno
  sessions        OAuth sessions
  spaces          manage heroku private spaces
  status          status of the Heroku platform
  teams           manage teams
  update          update the Heroku CLI
  webhooks        list webhooks on an app

```
- Step 5 :Login to your heroku account and close the window
```
heroku login
```
