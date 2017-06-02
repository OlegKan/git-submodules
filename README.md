# git-submodules
Android library to test git submodules

Prerequisites:
- exisiting android project which will add this library as a submodule
- clone this repository

1. Open exisiting project and run in terminal:
```
git submodule add https://github.com/OlegKan/git-submodules.git
```
2. Reopen the Android Studio to recieve message like 'Unregestered VCS root detected' and click on 'Add root'

3. Add new module / 'Import Gradle Project', select folder with this repository

4. Add dependency to build.gradle and sync project with gradle files
```
dependencies {
  compile project(':translations')
}
```
