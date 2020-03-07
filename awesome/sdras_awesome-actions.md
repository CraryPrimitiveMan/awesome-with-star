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
  - [Static Analysis](#static-analysis)
  - [Monitoring](#monitoring)
  - [Pull Requests](#pull-requests)
  - [GitHub Pages](#github-pages)
  - [Notifications and Messages](#notifications-and-messages)
  - [Deployment](#deployment)
  - [External Services](#external-services)
  - [Frontend Tools](#frontend-tools)
  - [Machine Learning Ops](#machine-learning-ops)
  - [Build](#build)
  - [Cheat Sheet](#cheat-sheet)
- [Tutorials](#tutorials)

## Official Resources

- [Official Site](https://github.com/features/actions)
- [Official Community Forum Board](https://github.community/t5/GitHub-Actions/bd-p/actions)
- [Official Documentation](https://help.github.com/en/actions)
- [Official Actions organization](https://github.com/actions)
  - [actions/virtual-environments](https://github.com/actions/virtual-environments) - GitHub Actions virtual environments. :star:290
  - [actions/runner](https://github.com/actions/runner) - The Runner for GitHub Actions. :star:585
- [GitHub Blog Announcement](https://github.blog/2018-10-17-action-demos/)

### Workflow Examples

- [actions/starter-workflows](https://github.com/actions/starter-workflows) - Starter workflow management. :star:2178
- [actions/example-services](https://github.com/actions/example-services) - Example workflows using service containers. :star:74

### Official Actions

#### Workflow Tool Actions

Tool actions for your workflow.

<!--lint ignore awesome-spell-check-->
- [actions/github](https://github.com/actions/github) - Wraps actions-toolkit into an Action for common GitHub automations. :star:79
- [actions/checkout](https://github.com/actions/checkout) - Setup your repository on your workflow. :star:410
- [actions/upload-artifact](https://github.com/actions/upload-artifact) - Upload artifacts from your workflow. :star:321
- [actions/download-artifact](https://github.com/actions/download-artifact) - Download artifacts from your build. :star:102
- [actions/cache](https://github.com/actions/cache) - Cache dependencies and build outputs in GitHub Actions. :star:836
- [actions/github-script](https://github.com/actions/github-script) - Write a script for GitHub API and the workflow contexts. :star:226

#### Actions for GitHub Automation

Automate management for issues, pull requests, and releases.

- [actions/create-release](https://github.com/actions/create-release) - An Action to create releases via the GitHub Release API. :star:256
- [actions/upload-release-asset](https://github.com/actions/upload-release-asset) - An Action to upload a release asset via the GitHub Release API. :star:159
- [actions/first-interaction](https://github.com/actions/first-interaction) - An action for filtering pull requests and issues from first-time contributors. :star:37
- [actions/stale](https://github.com/actions/stale) - Marks issues and pull requests that have not had recent interaction. :star:128
- [actions/labeler](https://github.com/actions/labeler) - An action for automatically labelling pull requests. :star:222

#### Setup Actions

Set up your GitHub Actions workflow with a specific version of your programming languages.

- [actions/setup-node: Node.js](https://github.com/actions/setup-node) :star:349
- [actions/setup-python: Python](https://github.com/actions/setup-python) :star:139
- [actions/setup-go: Go](https://github.com/actions/setup-go) :star:148
- [actions/setup-dotnet: .NET core sdk](https://github.com/actions/setup-dotnet) :star:124
- [actions/setup-haskell: Haskell (GHC and Cabal)](https://github.com/actions/setup-haskell) :star:28
- [actions/setup-java: Java](https://github.com/actions/setup-java) :star:138
- [actions/setup-ruby: Ruby](https://github.com/actions/setup-ruby) :star:78
- [actions/setup-elixir: Elixir](https://github.com/actions/setup-elixir) :star:87

### Create your Actions

#### JavaScript and TypeScript Actions

- [actions/toolkit](https://github.com/actions/toolkit) - The GitHub ToolKit for developing GitHub Actions. :star:1377
- [actions/hello-world-javascript-action](https://github.com/actions/hello-world-javascript-action) - A template to demonstrate how to build a JavaScript action. :star:41
- [actions/javascript-action](https://github.com/actions/javascript-action) - Create a JavaScript Action. :star:228
- [actions/typescript-action](https://github.com/actions/typescript-action) - Create a TypeScript Action. :star:269
- [actions/http-client](https://github.com/actions/http-client) - A lightweight HTTP client optimized for use with actions, TypeScript with generics and async await. :star:18

#### Docker Container Actions

- [actions/hello-world-docker-action](https://github.com/actions/hello-world-docker-action) - A template to demonstrate how to build a Docker action. :star:29
- [actions/container-toolkit-action](https://github.com/actions/container-toolkit-action) - Template repo for creating container actions using actions/toolkit. :star:39

## Community Resources

### GitHub Tools and Management

- [Declaratively setup GitHub Labels](https://github.com/lannonbr/issue-label-manager-action) :star:104
- [Action to sync GitHub labels in the declarative way](https://github.com/micnncim/action-label-syncer) :star:26
- [Add releases to GitHub](https://github.com/elgohr/Github-Release-Action) :star:22
- [Publish a docker image to Dockerhub](https://github.com/elgohr/Publish-Docker-Github-Action) :star:310
- [Create an issue using content from a file](https://github.com/peter-evans/create-issue-from-file) :star:12
- [Publish GitHub Releases with Assets](https://github.com/softprops/action-gh-release) :star:234
- [GitHub Project Automation+](https://github.com/alex-page/github-project-automation-plus) - Automate GitHub Project cards with any webhook event. :star:38
- [Run GitHub Actions Locally with a web interface](https://github.com/phishy/wflow) :star:124
- [Build and Publish Android debug APK](https://github.com/ShaunLWM/action-release-debugapk) :star:30
- [Generate sequential build numbers for GitHub Actions](https://github.com/einaregilsson/build-number) :star:68
- [Push Git changes to GitHub repository without authentication difficulties](https://github.com/ad-m/github-push-action) :star:172
- [Generate release notes based on your events](https://github.com/Decathlon/release-notes-generator-action) :star:19
- [Create a GitHub wiki page based on the provided markdown file](https://github.com/Decathlon/wiki-page-creator-action) :star:24
- [Label your Pull Requests auto-magically (using committed files)](https://github.com/Decathlon/pull-request-labeler-action) :star:28
- [Add Label to your Pull Requests based on the author team name](https://github.com/JulienKode/team-labeler-action) :star:4
- [Manually trigger your GitHub Actions from a UI](https://www.actionspanel.app)
- [Get a list of file changes with PR/Push](https://github.com/trilom/file-changes-action) :star:5
- [Use private actions in any workflow](https://github.com/InVisionApp/private-action-loader) :star:16
- [Label Your Issues Using the Issue's Contents](https://github.com/damccorm/tag-ur-it) :star:9

### Collection of Actions

- [Use HashiCorp's Terraform](https://github.com/hashicorp/terraform-github-actions) :star:521
- [GitHub Actions for Yarn 1](https://github.com/Borales/actions-yarn) :star:79
- [GitHub Actions for Yarn 2](https://github.com/sergioramos/yarn-actions) :star:10
- [GitHub Actions for Golang](https://github.com/cedrickring/golang-action) :star:83
- [GitHub Actions for R and accompanying #rstats package](http://maxheld.de/ghactions/)
- [GitHub Actions for WordPress](https://github.com/10up/actions-wordpress/) :star:209
- [GitHub Actions for Composer](https://github.com/MilesChou/composer-action) :star:16
- [GitHub Actions for Flutter](https://github.com/subosito/flutter-action) :star:171
- [GitHub Actions for PHP](https://github.com/shivammathur/setup-php) :star:514
- [GitHub Actions for Rust](https://github.com/actions-rs)
- [GitHub Actions for Android](https://github.com/Malinskiy/action-android) :star:75
- [GitHub Actions for Logtalk and Prolog](https://github.com/logtalk-actions)
- [GitHub Actions for Deno](https://github.com/denolib/setup-deno) :star:34
- [GitHub Actions for Unity](https://github.com/webbertakken/unity-actions) :star:97
- [Octions - GitHub Actions for GitHub REST API](https://github.com/maxkomarychev/octions) :star:13

### Utility

- [Setup `ssh-agent`](https://github.com/webfactory/ssh-agent) - Run `ssh-agent` with additional SSH keys to access private repositories. :star:108
- [GitHub Actions Badges for your README](https://github.com/atrox/github-actions-badge) :star:82
- [GitHub Actions for Python project with poetry](https://github.com/abatilo/actions-poetry) :star:43
- [GitHub Actions to compile LaTeX documents](https://github.com/xu-cheng/latex-action) :star:115
- [Update Maxmind Databases](https://github.com/meetup/maxmind-updater) :star:3
- [Debug with SSH over tmate](https://github.com/mxschmitt/action-tmate) - Debug the Action directly by providing a SSH connection. :star:250
- [Unlock git-crypt files](https://github.com/sliteteam/github-action-git-crypt-unlock) :star:6
- [Golang CGO cross compiler](https://github.com/crazy-max/ghaction-xgo) :star:11
- [Run your job on another architecture: arm32, aarch64 and others](https://github.com/uraimo/run-on-arch-action) :star:41
- [Generate a table of contents](https://github.com/technote-space/toc-generator) :star:23
- [Automatically add Label or Assignee to an Issue](https://github.com/Naturalclar/issue-action) :star:20
- [Action to send LGTM reaction as image or GIF when we say lgtm](https://github.com/micnncim/action-lgtm-reaction) :star:23
- [Generate build numbers across multiple scopes](https://github.com/zyborg/gh-action-buildnum) :star:5
- [Publish GitHub release artifacts](https://github.com/skx/github-action-publish-binaries) :star:57
- [Jekyll Diff Action](https://github.com/David-Byrne/jekyll-diff-action) - Diffs the built Jekyll site after a change, and comments the result back to GitHub. :star:1
- [Branch Protection Bot](https://github.com/benjefferies/branch-protection-bot) - Temporarily disable and re-enable "Include administrators" option in branch protection. :star:9
- [Wait for commit statuses](https://github.com/WyriHaximus/github-action-wait-for-status) - Wait until all statuses and checks are successful or any of them has failed and set its status output accordingly. :star:11
- [Get Latest Tag](https://github.com/WyriHaximus/github-action-get-previous-tag) - Get the previous tag from git. :star:7
- [Create Milestone](https://github.com/WyriHaximus/github-action-create-milestone) - Create a new open milestone given the title and description. :star:4
- [Close Milestone](https://github.com/WyriHaximus/github-action-close-milestone) - Close the given milestone. :star:1
- [Action to enforce branch naming rules](https://github.com/deepakputhraya/action-branch-name) :star:6
- [Expose slug of some GitHub variables](https://github.com/marketplace/actions/github-slug)
- [awesome-lint as a GitHub Action](https://github.com/max/awesome-lint) :star:8
- [Action to lint Awesome lists](https://github.com/squadcastHQ/awesome-lint-action) - Uses [awesome-lint](https://github.com/sindresorhus/awesome-lint) to lint awesome lists as an Action. :star:2
- [Edit JSON File](https://github.com/deef0000dragon1/json-edit-action) :star:3
- [Build Slate documentation](https://github.com/Decathlon/slate-builder-action) :star:7
- [Read Properties](https://github.com/christian-draeger/read-properties) - Read values from `.properties` files. :star:5
- [Write Properties](https://github.com/christian-draeger/write-properties) - Write values to `.properties` files. :star:6

#### Environments

- [Create an envfile](https://github.com/SpicyPizza/create-envfile) :star:4
- [Export global environment variables for succeeding build steps](https://github.com/zweitag/github-actions) :star:5
- [Programmatically set environment variables for use in subsequent steps](https://github.com/allenevans/set-env) :star:10
- [Install Conda environments for Python](https://github.com/goanpeca/setup-miniconda) :star:58

#### Dependencies

- [Install NPM dependencies with caching](https://github.com/bahmutov/npm-install) :star:34

#### Semantic Versioning

- [Next SemVers](https://github.com/WyriHaximus/github-action-next-semvers) - Output the next version for major, minor, and patch version based on the given semver version. :star:8
- [Get latest SemVer and branch name given a search string](https://github.com/jessicalostinspace/github-action-get-regex-branch)
- [Cut Release Branch](https://github.com/jessicalostinspace/cut-release-action) - Cuts a release branch given a branch prefix and optional semantic version. :star:2
- [Increment Semantic Version](https://github.com/christian-draeger/increment-semantic-version) - Bump a given semantic version (SemVer), depending on given release type. :star:14

### Static Analysis

- [PHPStan Static code analyzer Action](https://github.com/OskarStark/phpstan-ga) :star:44
- [GraphQL Inspector Action](https://github.com/kamilkisiela/graphql-inspector) :star:659
- [PowerShell static analysis with PSScriptAnalyzer](https://github.com/devblackops/github-action-psscriptanalyzer) :star:30
- [Run tfsec, with reviewdog output on the PR](https://github.com/reviewdog/action-tfsec) 

#### Testing

- [Snyk Test Action](https://github.com/snyk/actions) :star:19
- [Run Tests through Puppeteer, the Headless Chrome Node API](https://github.com/ianwalter/puppeteer) :star:39
- [xUnit Slack Reporter: Sends summary of tests from xUnit reports to a Slack channel](https://github.com/ivanklee86/xunit-slack-reporter) :star:3
- [Run codeception tests](https://github.com/joelwmale/codeception-action) :star:5
- [Run TestCafe tests](https://github.com/DevExpress/testcafe-action) :star:18
- [Run Unity tests](https://github.com/webbertakken/unity-test-runner) :star:17
- [Run Cypress E2E tests](https://github.com/cypress-io/github-action) :star:154
- [Test Ansible roles with Molecule](https://github.com/robertdebock/molecule-action) :star:6

#### Linting

- [PHP Code fixer Action](https://github.com/OskarStark/php-cs-fixer-ga) :star:65
- [Runs Hadolint against a Dockerfile within a repository](https://github.com/burdzwastaken/hadolint-action) :star:7
- [Run ESLint, with reviewdog output on the PR](https://github.com/reviewdog/action-eslint) :star:29
- [JavaScript-based linter for \*.workflow files](https://github.com/OmarTawfik/github-actions-js) :star:12
- [Lint terraform files using tflint, with reviewdog output on the PR](https://github.com/reviewdog/action-tflint) :star:7
- [autopep8: Automatically formats Python code to conform to the PEP 8 style guide](https://github.com/peter-evans/autopep8) :star:20
- [Run `localheinz/composer-normalize` to ensure your PHP project has a normalized `composer.json`](https://github.com/localheinz/composer-normalize-action) :star:22
- [Run Go lint checks on PR event](https://github.com/ArangoGutierrez/GoLinty-Action) :star:5
- [Node.js - Automatically run the `format` and/or `lint` script used by the package](https://github.com/MarvinJWendt/run-node-formatter) :star:13
- [Stylelinter - GitHub Action that runs stylelint](https://github.com/exelban/stylelint) :star:5
- [Run stylelint, with reviewdog output on the PR](https://github.com/reviewdog/action-stylelint) :star:10
- [PyCodeStyle Action - A GitHub Action that leaves a comment on your PR with pycodestyle (autopep8) feedback](https://github.com/ankitvgupta/pycodestyle-action) :star:2
- [wemake-python-styleguide - The strictest and most opinionated python linter ever, with optional reviewdog output on the PR](https://github.com/wemake-services/wemake-python-styleguide) :star:829
- [Run TSLint with status checks and file diff annotations](https://github.com/mooyoul/tslint-actions) :star:21
- [Lint Pull Request commits with commitlint](https://github.com/wagoid/commitlint-github-action) :star:25
- [Run vint, with reviewdog output on the PR](https://github.com/reviewdog/action-vint) :star:6
- [Run mispell, with reviewdog output on the PR](https://github.com/reviewdog/action-misspell) :star:20
- [Run golangci-lint, with reviewdog output on the PR](https://github.com/reviewdog/action-golangci-lint) :star:44
- [Run shellcheck, with reviewdog output on the PR](https://github.com/reviewdog/action-shellcheck) :star:17
- [Catch insensitive, inconsiderate writing in your markdown docs](https://github.com/theashraf/alex-action) :star:7
- [Run dotenv-linter - Lints your .env files like a charm, with optional reviewdog output on the PR](https://github.com/wemake-services/dotenv-linter) :star:162
- [Run dotenv-linter, with reviewdog output on the PR](https://github.com/mgrachev/action-dotenv-linter) :star:1
- [Show and auto-fix linting errors for many programming languages](https://github.com/samuelmeuli/lint-action) :star:37
- [PHP_CodeSniffer With Annotations](https://github.com/chekalsky/phpcs-action) :star:6
- [Linter for markdown (with presets)](https://github.com/avto-dev/markdown-lint) :star:4
- [Stylelint problem matcher to create annotations](https://github.com/xt0rted/stylelint-problem-matcher) :star:8

#### Security

- [A vulnerability scanner for your docker images](https://github.com/phonito/phonito-scanner-action) :star:13
- [Automatically approve and merge Dependabot updates](https://github.com/ridedott/dependabot-auto-merge-action) :star:40
- [Run dlint security linter on your Python code](https://github.com/xen0l/dlint-check)
- [AWS Secrets Manager Actions](https://github.com/say8425/aws-secrets-manager-actions) - Define AWS Secrets Manager secrets to environment values. :star:11
- [Linting your AWS IAM policy documents for correctness and security issues](https://github.com/xen0l/iam-lint) :star:6
- [Secret Spreader](https://github.com/webfactory/secret-spreader) - Not an action per se, but a tool to manage Actions Secrets across a list of repositories. :star:21

#### Code Coverage

- [Scan code with SonarCloud](https://github.com/sonarsource/sonarcloud-github-action) :star:94
- [Send your code coverage to codecov.io](https://github.com/codecov/codecov-action) :star:218
- [Publishing code coverage to CodeClimate](https://github.com/paambaati/codeclimate-action) :star:38

### Monitoring

- [Audit a webpage with Google Chrome's Lighthouse tests](https://github.com/jakejarvis/lighthouse-action) :star:114
- [Runs Lighthouse and posts results to PRs and Slack](https://github.com/foo-software/lighthouse-check-action) :star:40
- [Run Lighthouse in CI using GitHub Actions](https://github.com/treosh/lighthouse-ci-action) :star:375
- [Continuous Benchmarking and Benchmark Visualization for Go](https://github.com/bobheadxi/gobenchdata) :star:34

### Pull Requests

- [Set pull request reviewers based on assignees](https://github.com/pullreminders/assignee-to-reviewer-action) :star:99
- [Open or update pull request on branch push (with branch selection)](https://github.com/vsoch/pull-request-action) :star:54
- [Automatically rebase a PR](https://github.com/cirrus-actions/rebase) :star:307
- [Label pull request once it has a specified number of approvals](https://github.com/pullreminders/label-when-approved-action) :star:70
- [Add labels to Pull Request based on matched file patterns](https://github.com/banyan/auto-label) :star:38
- [Auto approve pull requests](https://github.com/hmarr/auto-approve-action) :star:109
- [Automatically add reviewers to pull request based on the configuration file](https://github.com/kentaro-m/auto-assign-action) :star:15
- [Add labels to Pull Request based on branch name patterns](https://github.com/TimonVS/pr-labeler-action) :star:53
- [Add labels to Pull Request based on total size of the diff](https://github.com/pascalgn/size-label-action) :star:16
- [Automatically merge Pull Requests that are ready](https://github.com/pascalgn/automerge-action) :star:175
- [Verify pull requests contain a ticket reference](https://github.com/vijaykramesh/pr-lint-action) :star:18
- [Create a pull request for changes to your repository in the actions workspace](https://github.com/peter-evans/create-pull-request) :star:122
- [Pull Request Lint](https://github.com/seferov/pr-lint-action) :star:28
- [ChatOps For Pull Requests](https://github.com/machine-learning-apps/actions-chatops) :star:28
- [Prefix title and body of a PR based on text extracted from branch name](https://github.com/tzkhan/pr-update-action) :star:8
- [Block Autosquash Commits](https://github.com/xt0rted/block-autosquash-commits-action) :star:5
- [Automatically Bump and Tag on Merge](https://github.com/anothrNick/github-tag-action) :star:96
- [Automatically Update PRs with Outdated Checks and Squash and Merge the Ones Matching All Branch Protections](https://github.com/tibdex/autosquash) :star:47
- [Merge Pal - automatically update and merge pull requests](https://github.com/maxkomarychev/merge-pal-action) :star:11
- [Enforce naming convention on pull request title](https://github.com/deepakputhraya/action-pr-title) :star:18
- [Pull Request Stuck Notifier](https://github.com/loomble/pull-request-stuck-notifier-action)
- [Lint pull request name with commitlint (Awesome if you squash merge !)](https://github.com/JulienKode/pull-request-name-linter-action) :star:2
- [Block PR merges when Checks for target branches are failing](https://github.com/cirrus-actions/branch-guard) :star:4

### GitHub Pages

- [Deploy a Zola site to GitHub Pages](https://github.com/shalzz/zola-deploy-action) :star:27
- [Build Hugo static content site and publish it to gh-pages branch](https://github.com/khanhicetea/gh-actions-hugo-deploy-gh-pages) :star:29
- [Build a Jekyll site—with Custom Jekyll Plugins & Build Scripts—and deploy it back to the Gh-Pages Branch](https://github.com/BryanSchuetz/jekyll-deploy-gh-pages) :star:62
- [Google Dataset Search Metadata](https://www.github.com/openschemas/extractors/) - And other schema.org extractors to make datasets discoverable from GitHub pages.
- [GitHub Actions for deploying to GitHub Pages with Static Site Generators](https://github.com/peaceiris/actions-gh-pages) :star:601
- [GitHub Action for Hexo](https://github.com/heowc/action-hexo) :star:19
- [Deploy Google Analytics stats to GitHub Pages](https://github.com/cristianpb/analytics-google)
- [A Jupyter Notebook Blogging Platform Powered by GitHub Actions, Pages and Jekyll](https://github.com/fastai/fastpages) :star:446

### Notifications and Messages

- [Send a Discord notification](https://github.com/Ilshidur/action-discord) :star:80
- [Post a Slack message as a bot](https://github.com/pullreminders/slack-action) :star:145
- [Send an SMS from GitHub Actions using Nexmo](https://github.com/nexmo-community/nexmo-sms-action) :star:10
- [Send a Telegram Message](https://github.com/appleboy/telegram-action) :star:135
- [Send a File or Text Message to Discord (custom define color, username or avatar)](https://github.com/appleboy/telegram-action) :star:135
- [Collaborate on tweets using pull requests](https://github.com/gr2m/twitter-together) :star:171
- [Send a Push Notification via Push by Techulus](https://github.com/techulus/push-github-action) :star:13
- [Send email with SendGrid](https://github.com/peter-evans/sendgrid-action) :star:8
- [Send a Push Notification via Join](https://github.com/ShaunLWM/action-join) :star:2
- [New package version checker for npm](https://github.com/MeilCli/npm-update-check-action) :star:3
- [New package version checker for NuGet](https://github.com/MeilCli/nuget-update-check-action) :star:2
- [New package version checker for Gradle](https://github.com/MeilCli/gradle-update-check-action)
- [Send a Push Notification via Pushbullet](https://github.com/ShaunLWM/action-pushbullet) :star:1
- [Create an Outlook Calendar Event using Microsoft Graph](https://github.com/anoopt/ms-graph-create-event)

### Deployment

- [Deploy to Netlify](https://github.com/netlify/actions) :star:207
- [Deploy a Probot App using Actions](https://probot.github.io/docs/deployment/#github-actions)
- [Deploy a playlist to Spotify](https://github.com/swinton/SpotHub) :star:60
- [Deploy VS Code extensions with vsce](https://github.com/lannonbr/vsce-action) :star:34
- [Purge Cloudflare cache after updating a website](https://github.com/jakejarvis/cloudflare-purge-action) :star:17
- [Deploy your DNS configuration using DNS Control](https://github.com/koenrh/dnscontrol-action) :star:15
- [Deploy a Theme to Shopify](https://github.com/pgrimaud/action-shopify) :star:19
- [Trigger multiple GitLab CI Pipeline](https://github.com/appleboy/gitlab-ci-action) :star:23
- [Trigger multiple Jenkins Jobs](https://github.com/appleboy/jenkins-action) :star:32
- [GitHub Action for Homebrew Tap](https://github.com/izumin5210/action-homebrew-tap) :star:5
- [Copy files and artifacts via SSH](https://github.com/appleboy/scp-action) :star:83
- [Executing remote ssh commands](https://github.com/appleboy/ssh-action) :star:235
- [Publish a Python distribution package to PyPI](https://github.com/pypa/gh-action-pypi-publish) :star:106
- [Deploy Static Website to Azure Storage](https://github.com/feeloor/azure-static-website-deploy) :star:12
- [Cross platform Chocolatey CLI to build and publish packages](https://github.com/crazy-max/ghaction-chocolatey) :star:13
- [Deploy iOS Pod Library to Cocoapods](https://github.com/michaelhenry/deploy-to-cocoapods-github-action) :star:7
- [GitHub Action for TencentCloud Serverless](https://github.com/Juliiii/action-scf) :star:3
- [Publish npm (pre)releases](https://github.com/epeli/npm-release/) :star:11
- [Deploy a static site to Surge.sh](https://github.com/yavisht/deploy-via-surge.sh-github-action-template) :star:5
- [GitHub Action for GoReleaser, a release automation tool for Go projects](https://github.com/goreleaser/goreleaser-action) :star:133
- [FTP Deploy Action, Deploys a GitHub project to a FTP server using GitHub actions](https://github.com/SamKirkland/FTP-Deploy-Action) :star:210
- [Publish Article to Dev.to](https://github.com/tylerauerbeck/publish-to-dev.to-action) :star:10
- [Action For Semantic Release](https://github.com/cycjimmy/semantic-release-action) :star:53
- [Deploy a Collection to Ansible Galaxy](https://github.com/artis3n/ansible_galaxy_collection) :star:5
- [Publish module to Puppet Forge](https://github.com/barnumbirr/action-forge-publish) :star:2
- [Build and publish Electron apps](https://github.com/samuelmeuli/action-electron-builder) :star:67
- [Publish a Maven package](https://github.com/samuelmeuli/action-maven-publish) :star:22
- [Build and deploy a theme to Ghost CMS](https://github.com/TryGhost/action-deploy-theme) :star:83
- [Deploy an Ansible role to Ansible Galaxy](https://github.com/robertdebock/galaxy-action) :star:2

#### Docker

- [Update a Docker Hub repository description from README.md](https://github.com/peter-evans/dockerhub-description) :star:44
- [Publish Docker Images to the GitHub Package Registry (GPR)](https://github.com/machine-learning-apps/gpr-docker-publish) :star:32
- [Update a repository's "Full description" on Docker Hub](https://github.com/mpepping/github-actions/tree/master/docker-hub-metadata) :star:4

#### Kubernetes

- [Deploy to any Cloud or Kubernetes Using Pulumi](https://github.com/pulumi/actions) :star:28
- [Deploy to Kubernetes with kubectl](https://github.com/steebchen/kubectl) :star:54
- [Get Kubeconfig File From Google Kubernetes Engine (GKE)](https://github.com/machine-learning-apps/gke-kubeconfig) :star:8

#### AWS

- [Sync/upload a directory to an AWS S3 bucket](https://github.com/jakejarvis/s3-sync-action) :star:144
- [Deploy Lambda code to an existing function](https://github.com/appleboy/lambda-action) :star:36

#### Terraform

- [Generate terraform documentation](https://github.com/Dirrk/terraform-docs) - Uses terraform-docs to generate docs for terraform modules. :star:11
- [An example of using Terraform to validate and apply GitHub administration](https://github.com/asgharlabs/github-terraform/tree/master/.github/workflows) :star:3


### External Services

- [Use a Jenkinsfile](https://github.com/jonico/jenkinsfile-runner-github-actions) :star:113
- [GitHub Action for Firebase](https://github.com/w9jds/firebase-action) :star:177
- [GitHub Action for Contentful Migration CLI](https://github.com/Shy/contentful-action) :star:2
- [GitHub Actions for Pixela (a-know/pi)](https://github.com/peaceiris/actions-pixela) :star:7
- [GitHub Action for Google Cloud Platform (GCP)](https://github.com/exelban/gcloud) :star:71
- [Upload files to any OpenStack Swift service provider](https://github.com/iksaku/openstack-swift-action) :star:1
- [GitHub Action for sending Stack Overflow posts to Slack](https://github.com/logankilpatrick/StackOverflowBot) :star:5
- [Assume AWS role](https://github.com/nordcloud/aws-assume-role/) :star:18

### Frontend Tools

- [Execute Gradle task](https://github.com/MrRamych/gradle-actions) :star:26
- [JS Build Actions](https://github.com/elstudio/actions-js-build) - Run Grunt or Gulp build tasks and commit file changes. :star:19
- [GitHub Action for Gatsby CLI](https://github.com/jzweifel/gatsby-cli-github-action) :star:29
- [Runs a WebPageTest audit and prints the results as commit comment](https://github.com/JCofman/webPagetestAction) :star:34
- [GitHub Actions for Hugo extended](https://github.com/peaceiris/actions-hugo) :star:192
- [Generate OG Image](https://github.com/BoyWithSilverWings/generate-og-image) - Generate customisable open graph images from Markdown files. :star:7
- [GitHub Actions for mdBook](https://github.com/peaceiris/actions-mdbook) :star:22

### Machine Learning Ops

- [Submitting Argo Workflows (Cloud Agnostic)](https://github.com/machine-learning-apps/actions-argo) :star:11
- [Submitting Argo Workflows to GKE](https://github.com/machine-learning-apps/gke-argo) :star:5
- [Query Experiment Tracking Results From Weights & Biases](https://github.com/machine-learning-apps/wandb-action) :star:7
- [Run Parameterized Jupyter Notebooks](https://github.com/yaananth/run-notebook) :star:13

### Build

- [run-cmake](https://github.com/lukka/run-cmake) - Multi platform action to build C/C++ software with [CMake](https://cmake.org) and [Ninja](https://ninja-build.org/). :star:12
- [run-vcpkg](https://github.com/lukka/run-vcpkg) - Multi platform action to build and install C/C++ dependencies with [vcpkg](https://github.com/microsoft/vcpkg). :star:8
- [Build Go applications for multiplatform](https://github.com/izumin5210/action-go-crossbuild)
- [Generate ~/.m2/settings.xml for Maven builds](https://github.com/whelk-io/maven-settings-xml-action) :star:1

### Cheat Sheet

- [GitHub Actions Branding Cheat Sheet](https://haya14busa.github.io/github-action-brandings/)

## Tutorials

- [Continuous deployment of Next.js app with Up](https://medium.com/@romanenko/simple-ci-for-next-js-projects-with-apex-up-github-actions-6f0b1b9a5400)
- [Converting Docker-based Actions to JavaScript/TypeScript](https://httgp.com/converting-github-actions-from-docker-to-javascript/)
- [GitHub Actions CI for Swift/iOS Projects](https://medium.com/rosberryapps/github-actions-ci-for-swift-projects-c129baceed1a)
- [Working with GitHub Actions](https://jeffrafter.com/working-with-github-actions)
- [GitHub Actions for Rails Developers](https://www.youtube.com/watch?v=gGUXydw22zw)
- [GitHub Actions Advent Calendar](https://www.edwardthomson.com/blog/github_actions_advent_calendar.html)
- [Zero Downtime Laravel Deployments with GitHub Actions](https://atymic.dev/blog/github-actions-laravel-ci-cd/)

> Please don't hesitate to make a PR if you have more resources to share. Check out [contributing.md](contributing.md) for more information

## License

[![Creative Commons License](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

