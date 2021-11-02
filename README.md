# Github Actions Examples

A collection of github actions examples for certain use cases

## Conditionally run or skip job

- Run job if check passed ([example](.github/workflows/run-job-if-check-passed.yml))

![run job if check passed screenshots](https://i.imgur.com/F7YFvsW.png)

- Skip job if check failed ([example](.github/workflows/skip-job-if-check-failed.yml))

![skip job if check failed screenshots](https://i.imgur.com/Jar8WA0.png)

## Concurrency

- Make sure that only one workflow can be ran ([example](.github/workflows/concurrency.yml))

![concurrency screenshots](https://i.imgur.com/u7PjPz9.png)

## Environment Variables

- There are many environment variables defined by github actions

```
ACCEPT_EULA=Y
AGENT_TOOLSDIRECTORY=/opt/hostedtoolcache
ANDROID_HOME=/usr/local/lib/android/sdk
ANDROID_NDK_HOME=/usr/local/lib/android/sdk/ndk-bundle
ANDROID_NDK_LATEST_HOME=/usr/local/lib/android/sdk/ndk/23.0.7599858
ANDROID_NDK_ROOT=/usr/local/lib/android/sdk/ndk-bundle
ANDROID_SDK_ROOT=/usr/local/lib/android/sdk
ANT_HOME=/usr/share/ant
AZURE_EXTENSION_DIR=/opt/az/azcliextensions
BOOTSTRAP_HASKELL_NONINTERACTIVE=1
CHROMEWEBDRIVER=/usr/local/share/chrome_driver
CHROME_BIN=/usr/bin/google-chrome
CI=true
CONDA=/usr/share/miniconda
DEBIAN_FRONTEND=noninteractive
DEPLOYMENT_BASEPATH=/opt/runner
DOTNET_MULTILEVEL_LOOKUP=0
DOTNET_NOLOGO=1
DOTNET_SKIP_FIRST_TIME_EXPERIENCE=1
GECKOWEBDRIVER=/usr/local/share/gecko_driver
GITHUB_ACTION=__run
GITHUB_ACTIONS=true
GITHUB_ACTION_REF=
GITHUB_ACTION_REPOSITORY=
GITHUB_ACTOR=jonz94
GITHUB_API_URL=https://api.github.com
GITHUB_BASE_REF=
GITHUB_ENV=/home/runner/work/_temp/_runner_file_commands/set_env_35fa6b5e-ea39-4180-b334-f456bc9c5c6d
GITHUB_EVENT_NAME=workflow_dispatch
GITHUB_EVENT_PATH=/home/runner/work/_temp/_github_workflow/event.json
GITHUB_GRAPHQL_URL=https://api.github.com/graphql
GITHUB_HEAD_REF=
GITHUB_JOB=print
GITHUB_PATH=/home/runner/work/_temp/_runner_file_commands/add_path_35fa6b5e-ea39-4180-b334-f456bc9c5c6d
GITHUB_REF=refs/heads/main
GITHUB_REPOSITORY=jonz94/github-actions-examples
GITHUB_REPOSITORY_OWNER=jonz94
GITHUB_RETENTION_DAYS=90
GITHUB_RUN_ATTEMPT=1
GITHUB_RUN_ID=1411732307
GITHUB_RUN_NUMBER=1
GITHUB_SERVER_URL=https://github.com
GITHUB_SHA=7f9929b212228db309586482cf045a3bb82d154a
GITHUB_WORKFLOW=env
GITHUB_WORKSPACE=/home/runner/work/github-actions-examples/github-actions-examples
GOROOT_1_14_X64=/opt/hostedtoolcache/go/1.14.15/x64
GOROOT_1_15_X64=/opt/hostedtoolcache/go/1.15.15/x64
GOROOT_1_16_X64=/opt/hostedtoolcache/go/1.16.9/x64
GOROOT_1_17_X64=/opt/hostedtoolcache/go/1.17.2/x64
GRAALVM_11_ROOT=/usr/local/graalvm/graalvm-ce-java11-21.2.0
GRADLE_HOME=/usr/share/gradle-7.2
HOME=/home/runner
HOMEBREW_CELLAR=/home/linuxbrew/.linuxbrew/Cellar
HOMEBREW_CLEANUP_PERIODIC_FULL_DAYS=3650
HOMEBREW_NO_AUTO_UPDATE=1
HOMEBREW_PREFIX=/home/linuxbrew/.linuxbrew
HOMEBREW_REPOSITORY=/home/linuxbrew/.linuxbrew/Homebrew
HOMEBREW_SHELLENV_PREFIX=/home/linuxbrew/.linuxbrew
INVOCATION_ID=e541ecf58f284a9c90744155f2c2b581
ImageOS=ubuntu20
ImageVersion=20211017.0
JAVA_HOME=/usr/lib/jvm/adoptopenjdk-11-hotspot-amd64
JAVA_HOME_11_X64=/usr/lib/jvm/adoptopenjdk-11-hotspot-amd64
JAVA_HOME_8_X64=/usr/lib/jvm/adoptopenjdk-8-hotspot-amd64
JOURNAL_STREAM=8:22206
LANG=C.UTF-8
LEIN_HOME=/usr/local/lib/lein
LEIN_JAR=/usr/local/lib/lein/self-installs/leiningen-2.9.7-standalone.jar
NVM_DIR=/home/runner/.nvm
PATH=/home/linuxbrew/.linuxbrew/bin:/home/linuxbrew/.linuxbrew/sbin:/home/runner/.local/bin:/opt/pipx_bin:/usr/share/rust/.cargo/bin:/home/runner/.config/composer/vendor/bin:/usr/local/.ghcup/bin:/home/runner/.dotnet/tools:/snap/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin
PERFLOG_LOCATION_SETTING=RUNNER_PERFLOG
PIPX_BIN_DIR=/opt/pipx_bin
PIPX_HOME=/opt/pipx
POWERSHELL_DISTRIBUTION_CHANNEL=GitHub-Actions-ubuntu20
RUNNER_NAME=GitHub Actions 6
RUNNER_OS=Linux
RUNNER_PERFLOG=/home/runner/perflog
RUNNER_TEMP=/home/runner/work/_temp
RUNNER_TOOL_CACHE=/opt/hostedtoolcache
RUNNER_TRACKING_ID=github_ea71f366-dd69-4503-a8a2-befcedf94fdf
RUNNER_USER=runner
RUNNER_WORKSPACE=/home/runner/work/github-actions-examples
SELENIUM_JAR_PATH=/usr/share/java/selenium-server-standalone.jar
SGX_AESM_ADDR=1
SHLVL=0
STATS_KEEPALIVE=true
SWIFT_PATH=/usr/share/swift/usr/bin
USER=runner
VCPKG_INSTALLATION_ROOT=/usr/local/share/vcpkg
XDG_CONFIG_HOME=/home/runner/.config
_=/usr/bin/env
```
