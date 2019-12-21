# Information comes from [sdras/awesome-actions](https://github.com/sdras/awesome-actions)
<p align="center">
  <br>
    <img src="awesome-actions.png" width="150"/>
  <br>
</p>

# Awesome Actions [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <!--lint ignore no-dead-urls--> [![GitHub Actions status | sdras/awesome-actions](https://github.com/sdras/awesome-actions/workflows/Lint%20Awesome%20List/badge.svg)](https://github.com/sdras/awesome-actions/actions?workflow=Lint+Awesome+List)

> A curated list of awesome things related to [GitHub Actions](https://github.com/actions).

Actions are triggered by GitHub platform events directly in a repo and run on-demand workflows either on Linux, Windows or macOS virtual machines or inside a container in response. With GitHub Actions you can automate your workflow from idea to production.

## Contents

- [Official Resources](#official-resources)
  - [Workflow Examples](#workflow-examples)
  - [Official Actions](#official-actions)
  - [Create your Actions](#create-your-actions)
- [Community Resources](#community-resources)
  - [GitHub Tools and Management](#github-tools-and-management)
  - [Collection of Actions](#collection-of-actions)
  - [Utility](#utility)
  - [Testing and Linting](#testing-and-linting)
  - [Security](#security)
  - [Pull Requests](#pull-requests)
  - [GitHub Pages](#github-pages)
  - [Notifications and Messages](#notifications-and-messages)
  - [Deployment](#deployment)
  - [External Services](#external-services)
  - [Frontend Tools](#frontend-tools)
  - [Internet of Things (IOT)](#internet-of-things-iot)
  - [Machine Learning Ops](#machine-learning-ops)
  - [Performance Monitoring](#performance-monitoring)
  - [Cheat Sheet](#cheat-sheet)
- [Tutorials](#tutorials)

## Official Resources

- [Official Site](https://github.com/features/actions)
- [Official Community Forum Board](https://github.community/t5/GitHub-Actions/bd-p/actions)
- [Official Documentation](https://help.github.com/en/actions/automating-your-workflow-with-github-actions)
- [Official Actions organization](https://github.com/actions)
  - [actions/virtual-environments](https://github.com/actions/virtual-environments) - GitHub Actions virtual environments. :star:102
- [GitHub Blog Announcement](https://github.blog/2018-10-17-action-demos/)

### Workflow Examples

- [actions/starter-workflows](https://github.com/actions/starter-workflows) - Starter workflow management. :star:1659
- [actions/example-services](https://github.com/actions/example-services) - Example workflows using service containers. :star:57

### Official Actions

#### Workflow Tool Actions

Tool actions for your workflow.

<!--lint ignore awesome-spell-check-->
- [actions/github](https://github.com/actions/github) - Wraps actions-toolkit into an Action for common GitHub automations. :star:54
- [actions/checkout](https://github.com/actions/checkout) - Setup your repository on your workflow. :star:224
- [actions/upload-artifact](https://github.com/actions/upload-artifact) - Upload artifacts from your workflow. :star:225
- [actions/download-artifact](https://github.com/actions/download-artifact) - Download artifacts from your build. :star:67
- [actions/cache](https://github.com/actions/cache) - Cache dependencies and build outputs in GitHub Actions. :star:623
- [actions/github-script](https://github.com/actions/github-script) - Write a script for GitHub API and the workflow contexts. :star:141

#### Actions for GitHub Automation

Automate management for issues, pull requests, and releases.

- [actions/create-release](https://github.com/actions/create-release) - An Action to create releases via the GitHub Release API. :star:138
- [actions/upload-release-asset](https://github.com/actions/upload-release-asset) - An Action to upload a release asset via the GitHub Release API. :star:81
- [actions/first-interaction](https://github.com/actions/first-interaction) - An action for filtering pull requests and issues from first-time contributors. :star:26
- [actions/stale](https://github.com/actions/stale) - Marks issues and pull requests that have not had recent interaction. :star:98
- [actions/labeler](https://github.com/actions/labeler) - An action for automatically labelling pull requests. :star:165

#### Setup Actions

Set up your GitHub Actions workflow with a specific version of your programming languages.

- [actions/setup-node: Node.js](https://github.com/actions/setup-node) :star:240
- [actions/setup-python: Python](https://github.com/actions/setup-python) :star:103
- [actions/setup-go: Go](https://github.com/actions/setup-go) :star:117
- [actions/setup-dotnet: .NET core sdk](https://github.com/actions/setup-dotnet) :star:90
- [actions/setup-haskell: Haskell (GHC and Cabal)](https://github.com/actions/setup-haskell) :star:25
- [actions/setup-java: Java](https://github.com/actions/setup-java) :star:100
- [actions/setup-ruby: Ruby](https://github.com/actions/setup-ruby) :star:56
- [actions/setup-elixir: Elixir](https://github.com/actions/setup-elixir) :star:54

### Create your Actions

#### JavaScript and TypeScript Actions

- [actions/toolkit](https://github.com/actions/toolkit) - The GitHub ToolKit for developing GitHub Actions. :star:1051
- [actions/hello-world-javascript-action](https://github.com/actions/hello-world-javascript-action) - A template to demonstrate how to build a JavaScript action. :star:29
- [actions/javascript-action](https://github.com/actions/javascript-action) - Create a JavaScript Action. :star:179
- [actions/typescript-action](https://github.com/actions/typescript-action) - Create a TypeScript Action. :star:201

#### Docker Container Actions

- [actions/hello-world-docker-action](https://github.com/actions/hello-world-docker-action) - A template to demonstrate how to build a Docker action. :star:17
- [actions/container-toolkit-action](https://github.com/actions/container-toolkit-action) - Template repo for creating container actions using actions/toolkit. :star:28

## Community Resources

### GitHub Tools and Management

- [Declaratively setup GitHub Labels](https://github.com/lannonbr/issue-label-manager-action) :star:97
- [Action to sync GitHub labels in the declarative way](https://github.com/micnncim/action-label-syncer) :star:21
- [Run GitHub Actions Locally](https://github.com/nektos/act) :star:2836
- [Alternative (Python-based) for Running GitHub Actions Locally](https://github.com/systemslab/popper) :star:148
- [Manage GitHub Action workflows and actions by cli](https://github.com/inextensodigital/actions/tree/master/github-workflow) - Allows you to script edition. :star:37
- [GitHub Action Builder and Previewer](https://create-github-action.now.sh/)
- [Add releases to GitHub](https://github.com/elgohr/Github-Release-Action) :star:19
- [Publish a docker image to Dockerhub](https://github.com/elgohr/Publish-Docker-Github-Action) :star:210
- [Create an issue using content from a file](https://github.com/peter-evans/create-issue-from-file) :star:6
- [Publish GitHub Releases with Assets](https://github.com/softprops/action-gh-release) :star:170
- [GitHub Project Automation+](https://github.com/alex-page/github-project-automation-plus) - Automate GitHub Project cards with any webhook event. :star:27
- [Run GitHub Actions Locally with a web interface. Supports new YAML syntax](https://github.com/phishy/wflow) :star:70
- [Build and Publish Android debug APK](https://github.com/ShaunLWM/action-release-debugapk) :star:22
- [Generate sequential build numbers for GitHub Actions](https://github.com/einaregilsson/build-number) :star:43
- [Push Git changes to GitHub repository without authentication difficulties](https://github.com/ad-m/github-push-action) :star:80

### Collection of Actions

- [Many linters and autofixers for various languages](https://github.com/bltavares/actions) :star:107
- [Node.js Actions Toolkit](https://github.com/JasonEtco/actions-toolkit) :star:658
- [Use HashiCorp's Terraform](https://github.com/hashicorp/terraform-github-actions) :star:447
- [GitHub Actions for Yarn](https://github.com/Borales/actions-yarn) :star:66
- [GitHub Actions for Golang](https://github.com/cedrickring/golang-action) :star:73
- [Android Build and Emulator Actions](https://github.com/vgaidarji/android-github-actions) :star:53
- [GitHub Actions for R and accompanying #rstats package](http://maxheld.de/ghactions/)
- [GitHub Actions for WordPress](https://github.com/10up/actions-wordpress/) :star:195
- [GitHub Actions for Composer](https://github.com/MilesChou/composer-action) :star:14
- [GitHub Actions for Flutter](https://github.com/subosito/flutter-action) :star:111
- [GitHub Actions for PHP](https://github.com/shivammathur/setup-php) :star:339
- [GitHub Actions for Rust](https://github.com/actions-rs)
- [GitHub Actions for Yarn - new syntax](https://github.com/sergioramos/yarn-actions) :star:7
- [GitHub Actions for Android](https://github.com/Malinskiy/action-android) :star:47
- [GitHub Actions for Logtalk and Prolog](https://github.com/logtalk-actions)
- [GitHub Actions for Deno](https://github.com/denolib/setup-deno) :star:24
- [GitHub Actions for Unity](https://github.com/webbertakken/unity-actions) :star:35
- [Octions - GitHub Actions for GitHub REST API](https://github.com/maxkomarychev/octions) :star:1

### Utility

- [Sleep](https://github.com/maddox/actions/tree/master/sleep) :star:358
- [Wait for 200](https://github.com/maddox/actions/tree/master/wait-for-200) :star:358
- [Run Cake tasks](https://github.com/gep13/cake-actions) :star:1
- [Run psake tasks](https://github.com/devblackops/psake-github-actions) :star:7
- [SSH](https://github.com/maddox/actions/tree/master/ssh) - Run SSH commands on a server. :star:358
- [Setup `ssh-agent`](https://github.com/webfactory/ssh-agent) - Run `ssh-agent` with additional SSH keys to access private repositories. :star:66
- [General purpose HTTP client for Actions, wrapping HTTPie](https://github.com/swinton/httpie-action) :star:63
- [Run pandoc](https://github.com/maxheld83/pandoc) - The swiss army knife for document conversions. :star:27
- [Debug Action](https://github.com/hmarr/debug-action) - Print environment variables and event to the Actions logs. :star:21
- [Gate actions by filtering if files matching a pattern have been touched](https://github.com/cds-snc/github-actions/tree/master/touched) :star:46
- [Scan for secrets in your source code](https://github.com/cds-snc/github-actions/tree/master/seekret) :star:46
- [Review the licenses of your node dependencies](https://github.com/cds-snc/github-actions/tree/master/node-license-checker) :star:46
- [A GitHub Action to check your project's dependencies](https://github.com/iheanyi/licensed-action) :star:6
- [Check if package.json dependencies have changed](https://github.com/bencooper222/check-for-node-dep-changes)
- [Update a repository's "Full description" on Docker Hub](https://github.com/mpepping/github-actions/tree/master/docker-hub-metadata) :star:2
- [GitHub Actions Badges for your README](https://github.com/atrox/github-actions-badge) :star:69
- [GitHub Actions for Python project with poetry](https://github.com/abatilo/actions-poetry) :star:23
- [GitHub Actions to compile LaTeX documents](https://github.com/xu-cheng/latex-action) :star:79
- [Create an envfile](https://github.com/SpicyPizza/create-envfile) :star:3
- [Update Maxmind Databases](https://github.com/meetup/maxmind-updater) :star:2
- [Debug with SSH over tmate](https://github.com/mxschmitt/action-tmate) - Debug the Action directly by providing a SSH connection. :star:183
- [Unlock git-crypt files](https://github.com/sliteteam/github-action-git-crypt-unlock) :star:5
- [Golang CGO cross compiler](https://github.com/crazy-max/ghaction-xgo) :star:6
- [Export global environment variables for succeeding build steps](https://github.com/zweitag/github-actions) :star:5
- [Programmatically set environment variables for use in subsequent steps](https://github.com/allenevans/set-env) :star:3
- [Run your job on another architecture: arm32, aarch64 and others](https://github.com/uraimo/run-on-arch-action) :star:17
- [Generate a table of contents](https://github.com/technote-space/toc-generator) :star:10
- [Automatically add Label or Assignee to an Issue](https://github.com/Naturalclar/issue-action) :star:13
- [Action to send LGTM reaction as image or GIF when we say lgtm](https://github.com/micnncim/action-lgtm-reaction) :star:22
- [Generate build numbers across multiple scopes](https://github.com/zyborg/gh-action-buildnum) :star:1
- [Restrict cursing action](https://github.com/sobolevn/restrict-cursing-action) - Moderator bot for your project, automatically removes bad language. :star:7
- [Publish GitHub release artifacts](https://github.com/skx/github-action-publish-binaries) :star:35
- [Jekyll Diff Action](https://github.com/David-Byrne/jekyll-diff-action) - Diffs the built Jekyll site after a change, and comments the result back to GitHub. :star:1
- [Branch Protection Bot](https://github.com/benjefferies/branch-protection-bot) - Temporarily disable and re-enable "Include administrators" option in branch protection. :star:6
- [Next SemVers](https://github.com/WyriHaximus/github-action-next-semvers) - Output the next version for major, minor, and patch version based on the given semver version. :star:5
- [Wait for commit statuses](https://github.com/WyriHaximus/github-action-wait-for-status) - Wait until all statuses and checks are successful or any of them has failed and set its status output accordingly. :star:7
- [Get Latest Tag](https://github.com/WyriHaximus/github-action-get-previous-tag) - Get the previous tag from git. :star:3
- [Create Milestone](https://github.com/WyriHaximus/github-action-create-milestone) - Create a new open milestone given the title and description. :star:1
- [Close Milestone](https://github.com/WyriHaximus/github-action-close-milestone) - Close the given milestone. :star:1
- [Action to enforce branch naming rules](https://github.com/deepakputhraya/action-branch-name) :star:2
- [Install NPM dependencies with caching](https://github.com/bahmutov/npm-install) :star:17
- [Expose slug of some GitHub variables](https://github.com/marketplace/actions/github-slug)

### Testing and Linting

- [Runs Hadolint against a Dockerfile within a repository](https://github.com/burdzwastaken/hadolint-action) :star:4
- [Test your Actions Locally](https://github.com/tschoffelen/gha) :star:48
- [Lint a Dockerfile](https://github.com/jwr0/dockerfile-linter-action) (using replicatedhq/dockerfilelint) :star:5
- [NPM Audit](https://github.com/JasonEtco/npm-audit-fix-action) :star:28
- [PHP Code fixer Action](https://github.com/OskarStark/php-cs-fixer-ga) :star:61
- [PHP Psalm Static code analyzer Action](https://github.com/mickaelandrieu/psalm-ga) :star:7
- [PHPStan Static code analyzer Action](https://github.com/OskarStark/phpstan-ga) :star:35
- [PHPQA toolsuite Action](https://github.com/mickaelandrieu/phpqa-ga) :star:4
- [GraphQL Inspector Action](https://github.com/kamilkisiela/graphql-inspector) :star:563
- [Snyk CLI Test Action](https://github.com/clarkio/snyk-cli-action) :star:17
- [PowerShell static analysis with PSScriptAnalyzer](https://github.com/devblackops/github-action-psscriptanalyzer) :star:30
- [Run web performance audits using Sitespeed.io](https://github.com/sitespeedio/sitespeed.io/tree/master/docker/github-action) :star:3662
- [Run Tests through Puppeteer, the Headless Chrome Node API](https://github.com/ianwalter/puppeteer) :star:32
- [Run ESLint with status checks and file diff annotations](https://github.com/gimenete/eslint-action) :star:116
- [Run ESLint, with reviewdog output on the PR](https://github.com/reviewdog/action-eslint) :star:20
- [JavaScript-based linter for \*.workflow files](https://github.com/OmarTawfik/github-actions-js) :star:12
- [Send your latest code coverage score to Coveralls.io](https://github.com/gavinhenderson/coveralls-action) :star:4
- [Lint a Dockerfile using Hadolint](https://github.com/cds-snc/github-actions/tree/master/docker-lint) :star:46
- [Lint terraform files using tflint](https://github.com/cds-snc/github-actions/tree/master/tf-lint) :star:46
- [Lint terraform files using tflint, with reviewdog output on the PR](https://github.com/reviewdog/action-tflint) :star:5
- [Validate Puppet modules using Puppet PDK](https://github.com/mpepping/github-actions/tree/master/pdk-validate) :star:2
- [Scan git commits for secrets with gitleaks](https://github.com/eshork/gitleaks-action) :star:14
- [Scan code with SonarCloud](https://github.com/sonarsource/sonarcloud-github-action) :star:66
- [Send your code coverage to codecov.io](https://github.com/codecov/codecov-action) :star:153
- [autopep8: Automatically formats Python code to conform to the PEP 8 style guide](https://github.com/peter-evans/autopep8) :star:17
- [xUnit Slack Reporter: Sends summary of tests from xUnit reports to a Slack channel](https://github.com/ivanklee86/xunit-slack-reporter) :star:1
- [Publishing code coverage to CodeClimate](https://github.com/paambaati/codeclimate-action) :star:21
- [Run codeception tests](https://github.com/joelwmale/codeception-action) :star:2
- [Audit a webpage with Google Chrome's Lighthouse tests](https://github.com/jakejarvis/lighthouse-action) :star:66
- [Run `localheinz/composer-normalize` to ensure your PHP project has a normalized `composer.json`](https://github.com/localheinz/composer-normalize-action) :star:18
- [Run Go lint checks on PR event](https://github.com/ArangoGutierrez/GoLinty-Action) :star:5
- [Node.js - Automatically run the `format` and/or `lint` script used by the package](https://github.com/MarvinJWendt/run-node-formatter) :star:13
- [Continuous Benchmarking and Benchmark Visualization for Go](https://github.com/bobheadxi/gobenchdata) :star:22
- [Stylelinter - GitHub Action that runs stylelint](https://github.com/exelban/stylelint) :star:4
- [Run stylelint, with reviewdog output on the PR](https://github.com/reviewdog/action-stylelint) :star:9
- [PyCodeStyle Action - A GitHub Action that leaves a comment on your PR with pycodestyle (autopep8) feedback](https://github.com/ankitvgupta/pycodestyle-action) :star:2
- [wemake-python-styleguide - The strictest and most opinionated python linter ever, with optional reviewdog output on the PR](https://github.com/wemake-services/wemake-python-styleguide) :star:638
- [Run TSLint with status checks and file diff annotations](https://github.com/mooyoul/tslint-actions) :star:13
- [Lint Pull Request commits with commitlint](https://github.com/wagoid/commitlint-github-action) :star:11
- [Run vint, with reviewdog output on the PR](https://github.com/reviewdog/action-vint) :star:3
- [Run mispell, with reviewdog output on the PR](https://github.com/reviewdog/action-misspell) :star:16
- [Run golangci-lint, with reviewdog output on the PR](https://github.com/reviewdog/action-golangci-lint) :star:31
- [Run shellcheck, with reviewdog output on the PR](https://github.com/reviewdog/action-shellcheck) :star:13
- [Build Go applications for multiplatform](https://github.com/izumin5210/action-go-crossbuild)
- [Catch insensitive, inconsiderate writing in your markdown docs](https://github.com/theashraf/alex-action) :star:7
- [Run TestCafe tests](https://github.com/DevExpress/testcafe-action) :star:15
- [Run Unity tests](https://github.com/webbertakken/unity-test-runner) :star:3
- [Run Cypress E2E tests](https://github.com/cypress-io/github-action) :star:62
- [Run dotenv-linter - Lints your .env files like a charm, with optional reviewdog output on the PR](https://github.com/wemake-services/dotenv-linter) 

### Security

- [A vulnerability scanner for your docker images](https://github.com/phonito/phonito-scanner-action) :star:8
- [Automatically approve and merge Dependabot updates](https://github.com/ridedott/dependabot-auto-merge-action) :star:15

### Pull Requests

- [Set pull request reviewers based on assignees](https://github.com/pullreminders/assignee-to-reviewer-action) :star:63
- [Open or update pull request on branch push (with branch selection)](https://github.com/vsoch/pull-request-action) :star:37
- [Post gif on check fail](https://github.com/jessfraz/shaking-finger-action) :star:89
- [Cleanup branches after merge](https://github.com/jessfraz/branch-cleanup-action) :star:406
- [Automatically rebase a PR](https://github.com/cirrus-actions/rebase) :star:259
- [Evaluate Clojure in the issue comment](https://github.com/repetitive/actions/tree/master/clojure) :star:12
- [Create Pull Request when branch is pushed](https://github.com/repetitive/actions/tree/master/auto-pull-request) :star:12
- [Label pull request once it has a specified number of approvals](https://github.com/pullreminders/label-when-approved-action) :star:53
- [Add labels to Pull Request based on matched file patterns](https://github.com/banyan/auto-label) :star:31
- [Auto approve pull requests](https://github.com/hmarr/auto-approve-action) :star:87
- [Automatically add reviewers to pull request based on the configuration file](https://github.com/kentaro-m/auto-assign) :star:71
- [Auto-commit back any changes made by previous actions](https://github.com/cds-snc/github-actions/tree/master/auto-commit) :star:46
- [Add labels to Pull Request based on branch name patterns](https://github.com/TimonVS/pr-labeler-action) :star:41
- [Add labels to Pull Request based on total size of the diff](https://github.com/pascalgn/size-label-action) :star:11
- [Automatically merge Pull Requests that are ready](https://github.com/pascalgn/automerge-action) :star:110
- [Verify pull requests contain a ticket reference](https://github.com/vijaykramesh/pr-lint-action) :star:12
- [Create a pull request for changes to your repository in the actions workspace](https://github.com/peter-evans/create-pull-request) :star:68
- [Pull Request Lint](https://github.com/seferov/pr-lint-action) :star:19
- [ChatOps For Pull Requests](https://github.com/machine-learning-apps/actions-chatops) :star:16
- [Prefix title and body of a PR based on text extracted from branch name](https://github.com/tzkhan/pr-update-action) :star:5
- [Block Autosquash Commits](https://github.com/xt0rted/block-autosquash-commits-action) :star:4
- [Automatically Bump and Tag on Merge](https://github.com/anothrNick/github-tag-action) :star:58
- [Automatically Update PRs with Outdated Checks and Squash and Merge the Ones Matching All Branch Protections](https://github.com/tibdex/autosquash) :star:29
- [Merge Pal - automatically update and merge pull requests](https://github.com/maxkomarychev/merge-pal-action) :star:6
- [Enforce naming convention on pull request title](https://github.com/deepakputhraya/action-pr-title) :star:7
- [Pull Request Stuck Notifier](https://github.com/loomble/pull-request-stuck-notifier-action)

### GitHub Pages

- [Deploy a Zola site to GitHub Pages](https://github.com/shalzz/zola-deploy-action) :star:18
- [Visualize your Dockerfile with a Container Tree](https://www.github.com/vsoch/containertree)
- [Build Hugo static content site and publish it to gh-pages branch](https://github.com/khanhicetea/gh-actions-hugo-deploy-gh-pages) :star:25
- [Build a Jekyll site—with Custom Jekyll Plugins & Build Scripts—and deploy it back to the Gh-Pages Branch](https://github.com/BryanSchuetz/jekyll-deploy-gh-pages) :star:50
- [Google Dataset Search Metadata](https://www.github.com/openschemas/extractors/) - And other schema.org extractors to make datasets discoverable from GitHub pages.
- [Deploy assets to GitHub pages](https://github.com/maxheld83/ghpages) - No building, just deploying. :star:130
- [GitHub Actions for deploying to GitHub Pages with Static Site Generators](https://github.com/peaceiris/actions-gh-pages) :star:397
- [GitHub Action for Hexo](https://github.com/heowc/action-hexo) :star:15
- [Deploy Google Analytics stats to GitHub Pages](https://github.com/cristianpb/analytics-google)

### Notifications and Messages

- [Confucious Wisdom (Pull Request Failure Message)](https://github.com/vsoch/confucious-actions) :star:5
- [Send a Discord notification](https://github.com/Ilshidur/action-discord) :star:51
- [Send a Slack message](https://github.com/apex/actions/tree/master/slack) :star:156
- [Post a Slack message as a bot](https://github.com/pullreminders/slack-action) :star:109
- [Update Twitter status](https://github.com/xorilog/twitter-action) :star:30
- [Generate Tweet content to share pull request file(s) after merge](https://github.com/vsoch/twitter-share-action/tree/master/pull_request_share)
- [Send an SMS from GitHub Actions using Nexmo](https://github.com/nexmo-community/nexmo-sms-action) :star:8
- [Trigger emails with release notes with SendGrid](https://github.com/bitoiu/release-notify-action) :star:53
- [Send email on failed GitHub Checks](https://github.com/cirrus-actions/email) :star:7
- [Report webpack stats to packtracker.io](https://github.com/packtracker/github-action) :star:17
- [Send a Telegram Message](https://github.com/appleboy/telegram-action) :star:98
- [Send a File or Text Message to Discord (custom define color, username or avatar)](https://github.com/appleboy/telegram-action) :star:98
- [Collaborate on tweets using pull requests](https://github.com/gr2m/twitter-together) :star:118
- [Send a Push Notification via Pushover.net](https://github.com/maddox/actions/tree/master/pushover) :star:358
- [Send a dynamic notification to any service using Apprise](https://github.com/cstuder/apprise-ga) :star:12
- [Send a Push Notification via Push by Techulus](https://github.com/techulus/push-github-action) :star:8
- [Send email with SendGrid](https://github.com/peter-evans/sendgrid-action) :star:6
- [Send a Push Notification via Join](https://github.com/ShaunLWM/action-join) :star:1
- [New package version checker for npm](https://github.com/MeilCli/npm-update-check-action) :star:1
- [New package version checker for NuGet](https://github.com/MeilCli/nuget-update-check-action) :star:2
- [New package version checker for Gradle](https://github.com/MeilCli/gradle-update-check-action)
- [Send a Push Notification via Pushbullet](https://github.com/ShaunLWM/action-pushbullet)
- [Create an Outlook Calendar Event using Microsoft Graph](https://github.com/anoopt/ms-graph-create-event)

### Deployment

- [Deploy to Netlify](https://github.com/netlify/actions) :star:190
- [Deploy a Probot App using Actions](https://probot.github.io/docs/deployment/#github-actions)
- [Deploy a playlist to Spotify](https://github.com/swinton/SpotHub) :star:53
- [Deploy a serverless app to AWS Lambda with Up](https://github.com/apex/actions/tree/master/up) :star:156
- [Deploy serverless infrastructure with AWS SAM](https://github.com/apex/actions/tree/master/aws/sam) :star:156
- [Deploy a Node.js function to AWS Lambda and invoke it using the Serverless framework](https://github.com/swinton/serverless) :star:3
- [Deploy VS Code extensions with vsce](https://github.com/lannonbr/vsce-action) :star:25
- [Deploy a Node.js App to Azure](https://github.com/sdras/example-azure-node) :star:66
- [Deploy via rsync over ssh](https://github.com/maxheld83/ghaction-rsync) :star:49
- [Deploy to any Cloud or Kubernetes Using Pulumi](https://github.com/pulumi/actions) :star:25
- [Deploy a Cloudflare worker](https://github.com/cpilsworth/cloudflare-worker-action) :star:8
- [Deploy your DNS configuration using DNS Control](https://github.com/koenrh/dnscontrol-action) :star:12
- [Using surge.sh, deploy your branch specific storybook as a pull request deployment](https://github.com/codeship/storybook-surge-github-action) :star:12
- [Create Release Archive](https://github.com/lubusIN/actions/tree/master/archive) :star:27
- [Publish WordPress Plugin](https://github.com/lubusIN/actions/tree/master/wordpress) :star:27
- [Deploy a Theme to Shopify](https://github.com/pgrimaud/action-shopify) :star:11
- [Trigger multiple GitLab CI Pipeline](https://github.com/appleboy/gitlab-ci-action) :star:18
- [Trigger multiple Jenkins Jobs](https://github.com/appleboy/jenkins-action) :star:27
- [GitHub Deployment API](https://github.com/unacast/actions/tree/master/github-deploy) :star:22
- [GitHub Action for zem](https://github.com/artemnovichkov/action-zem) :star:5
- [GitHub Action for Homebrew](https://github.com/artemnovichkov/action-homebrew) :star:6
- [GitHub Action for Homebrew Tap](https://github.com/izumin5210/action-homebrew-tap) :star:3
- [Deploy Lambda code to an existing function](https://github.com/appleboy/lambda-action) :star:23
- [Copy files and artifacts via SSH](https://github.com/appleboy/scp-action) :star:41
- [Executing remote ssh commands](https://github.com/appleboy/ssh-action) :star:123
- [Deploy to Kubernetes with kubectl](https://github.com/steebchen/kubectl) :star:36
- [Update a Docker Hub repository description from README.md](https://github.com/peter-evans/dockerhub-description) :star:26
- [Purge Cloudflare cache after updating a website](https://github.com/jakejarvis/cloudflare-purge-action) :star:11
- [Sync/upload a directory to an AWS S3 bucket](https://github.com/jakejarvis/s3-sync-action) :star:66
- [Publish a Python distribution package to PyPI](https://github.com/pypa/gh-action-pypi-publish) :star:77
- [Deploy Static Website to Azure Storage](https://github.com/feeloor/azure-static-website-deploy) :star:7
- [Cross platform Chocolatey CLI to build and publish packages](https://github.com/crazy-max/ghaction-chocolatey) :star:7
- [Deploy iOS Pod Library to Cocoapods](https://github.com/michaelhenry/deploy-to-cocoapods-github-action) :star:4
- [GitHub Action for TencentCloud Serverless](https://github.com/Juliiii/action-scf) :star:2
- [Publish npm (pre)releases](https://github.com/epeli/npm-release/) :star:7
- [Publish Docker Images to the GitHub Package Registry (GPR)](https://github.com/machine-learning-apps/gpr-docker-publish) :star:26
- [Get Kubeconfig File From Google Kubernetes Engine (GKE)](https://github.com/machine-learning-apps/gke-kubeconfig) :star:5
- [Deploy a static site to Surge.sh](https://github.com/yavisht/deploy-via-surge.sh-github-action-template) :star:1
- [GitHub Action for GoReleaser, a release automation tool for Go projects](https://github.com/goreleaser/goreleaser-action) :star:95
- [FTP Deploy Action, Deploys a GitHub project to a FTP server using GitHub actions](https://github.com/SamKirkland/FTP-Deploy-Action) :star:123
- [Publish Article to Dev.to](https://github.com/tylerauerbeck/publish-to-dev.to-action) :star:8
- [Action For Semantic Release](https://github.com/cycjimmy/semantic-release-action) :star:30
- [Deploy a Collection to Ansible Galaxy](https://github.com/artis3n/ansible_galaxy_collection) :star:1
- [An example of using Terraform to validate and apply GitHub administration](https://github.com/asgharlabs/github-terraform/tree/master/.github/workflows)
- [Publish module to Puppet Forge](https://github.com/barnumbirr/action-forge-publish) :star:1

### External Services

- [Use a Jenkinsfile](https://github.com/jonico/jenkinsfile-runner-github-actions) :star:104
- [Configure a DNS Record on Cloudflare](https://github.com/xorilog/cloudflare-dns-action) :star:13
- [Firebase](https://github.com/natemoo-re/action-firebase)
- [GitHub Action for Firebase](https://github.com/w9jds/firebase-action) :star:113
- [GitHub Action for JFrog CLI](https://github.com/retgits/actions/tree/master/jfrog-cli) :star:2
- [GitHub Action for Contentful Migration CLI](https://github.com/Shy/contentful-action) :star:1
- [GitHub Actions for Pixela (a-know/pi)](https://github.com/peaceiris/actions-pixela) :star:4
- [GitHub Action for Google Cloud Platform (GCP)](https://github.com/exelban/gcloud) :star:45
- [Upload files to any OpenStack Swift service provider](https://github.com/iksaku/openstack-swift-action)
- [GitHub Action for sending Stack Overflow posts to Slack](https://github.com/logankilpatrick/StackOverflowBot) :star:3
- [Assume AWS role](https://github.com/nordcloud/aws-assume-role/) :star:14

### Frontend Tools

- [Execute Gradle task](https://github.com/MrRamych/gradle-actions) :star:22
- [JS Build Actions](https://github.com/elstudio/actions-js-build) - Run Grunt or Gulp build tasks and commit file changes. :star:14
- [Ember CLI Actions](https://github.com/NuckChorris/ember-cli-actions) :star:1
- [GitHub Action for Gatsby CLI](https://github.com/jzweifel/gatsby-cli-github-action) :star:20
- [Runs a WebPageTest audit and prints the results as commit comment](https://github.com/JCofman/webPagetestAction) :star:27
- [GitHub Actions for Hugo extended](https://github.com/peaceiris/actions-hugo) :star:126
- [Generate OG Image](https://github.com/BoyWithSilverWings/generate-og-image) - Generate customisable open graph images from Markdown files. :star:5
- [Runs Lighthouse and posts results to PRs and Slack](https://github.com/foo-software/lighthouse-check-action) :star:24
- [GitHub Actions for mdBook](https://github.com/peaceiris/actions-mdbook) :star:15

### Internet of Things (IOT)

- [Home Assistant Command](https://github.com/maddox/actions/tree/master/home-assistant) :star:358

### Machine Learning Ops

- [Submitting Argo Workflows (Cloud Agnostic)](https://github.com/machine-learning-apps/actions-argo) :star:7
- [Submitting Argo Workflows to GKE](https://github.com/machine-learning-apps/gke-argo) :star:3
- [Query Experiment Tracking Results From Weights & Biases](https://github.com/machine-learning-apps/wandb-action) :star:5
- [Run Parameterized Jupyter Notebooks](https://github.com/yaananth/run-notebook) :star:7

### Performance Monitoring

- [Run Lighthouse in CI using GitHub Actions](https://github.com/treosh/lighthouse-ci-action) :star:288

### Cheat Sheet

- [GitHub Actions Branding Cheat Sheet](https://haya14busa.github.io/github-action-brandings/)

## Tutorials

- [Introducing GitHub Actions](https://css-tricks.com/introducing-github-actions/)
- [Deploying to Firebase Hosting with GitHub Actions](https://natemoo.re/posts/action-firebase)
- [Building GitHub Actions in Node.js](https://jasonet.co/posts/building-github-actions-in-node/)
- [GitHub Actions on Android project](http://vgaidarji.me/blog/2019/01/27/github-actions)
- [GitHub Actions for PHP Developers](https://stefanzweifel.io/posts/github-actions-for-php-developers/)
- [Continuous deployment of Next.js app with Up](https://medium.com/@romanenko/simple-ci-for-next-js-projects-with-apex-up-github-actions-6f0b1b9a5400)
- [Converting Docker-based Actions to JavaScript/TypeScript](https://httgp.com/converting-github-actions-from-docker-to-javascript/)
- [GitHub Actions CI for Swift/iOS Projects](https://medium.com/rosberryapps/github-actions-ci-for-swift-projects-c129baceed1a)
- [Working with GitHub Actions](https://jeffrafter.com/working-with-github-actions)
- [GitHub Actions for Rails Developers](https://www.youtube.com/watch?v=gGUXydw22zw)

> Please don't hesitate to make a PR if you have more resources to share. Check out [contributing.md](contributing.md) for more information

## License

[![Creative Commons License](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

