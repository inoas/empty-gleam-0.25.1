# new_0_25_1_project

```shell
❯ asdf install gleam 0.25.1
❯ asdf global gleam 0.25.1
❯ gleam --version
gleam 0.25.1
❯ gleam new new_0_25_1_project
Your Gleam project new_0_25_1_project has been successfully created.
The project can be compiled and tested by running these commands:

  cd new_0_25_1_project
  gleam test

❯ cd new_0_25_1_project
❯ git add .
❯ git commit -m 'empty 0.25.1 project'
[main (root-commit) 6574818] empty 0.25.1 project
 6 files changed, 84 insertions(+)
 create mode 100644 .github/workflows/test.yml
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 gleam.toml
 create mode 100644 src/new_0_25_1_project.gleam
 create mode 100644 test/new_0_25_1_project_test.gleam
❯ git remote add origin https://github.com/inoas/empty-gleam-0.25.1.git
git branch -M main
git push -u origin main
error: remote origin already exists.
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 16 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (12/12), 2.27 KiB | 2.27 MiB/s, done.
Total 12 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/inoas/empty-gleam-0.25.1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
```
