# Developing for GoIV

## Setting Up
* Download and install [Git] (https://git-scm.com/)
* Set up [Git with GitHub] (https://help.github.com/articles/set-up-git/)
* Download and install [Android Studio] (https://developer.android.com/studio/index.html)
* Set up [Android Development Environment] (https://spring.io/guides/gs/android/)
* Install [Lombok IntelliJ Plugin] (https://github.com/mplushnikov/lombok-intellij-plugin#installation)
* Enable annotation processing (Configure > Settings > Build, Execution, Deployment > Compiler > Annotation Processors)
* [Fork this repo] (https://help.github.com/articles/fork-a-repo/)
* Open the Project in Android Studio
* Copy the Project's Code Style Scheme (File > Settings > Editor > Code Style > Scheme > Manage > Select 'Default' > Copy to Project)

## Optional Set-up
Set up Git on Android Studio (Configure > Settings > Version Control > Git) - Automates Git commands through Android Studio

## Syncing the Fork
[Syncing your fork] (https://help.github.com/articles/syncing-a-fork/) will keep it up to date with the latest commits on the main repo. This will also reduce the chances of getting merge conflicts. Always sync your fork before working on it!

## Contributing with Pull Requests

### Splitting Pull Requests
Please open separate PR's for separate bug fixes or features. It helps us to review your PR's.

### Writing Good Commit Messages
Please take the time to write helpful commit messages. This makes the review of your PR's much easier. It also helps other people to understand the code later on if they are contributing to this project.

You can do so by following these *rules* (taken from this great [article](http://chris.beams.io/posts/git-commit/)):

* Separate subject from body with a blank line
* Limit the subject line to 69 characters
* Use the imperative mood in the subject line
* Wrap the body at 72 characters
* Use the body to explain what and why vs. how
