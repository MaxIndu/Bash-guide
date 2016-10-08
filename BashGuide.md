# Bash Guide
---

Bash guide for those who need to work with linux terminal.

### Navigation
---

#### Displaying a basic listing

#### ls
Using ```ls``` to show the directory structure.

```shell
$ ls
Desktop    Dump          Interviews  name.txt   Programs         Templates
Documents  FYP           Java        Pictures   Public           temp.txt
Downloads  IdeaProjects  Music       pmlibrary  PycharmProjects  Videos

```

#### ls -F

The -F parameter flags the directories with a forward slash (/), to help identify them in the listing. Similarly, it fl ags executable files with an asterisk (*), to help you more easily fi nd fi les that can be run on the system.

``` bash
$ ls -F
BashGuide.md  Ocaml/  Today TODO.txt*  view.png

```

#### ls -a

The -a parameter shows all the files that are hidden or not. Hidden files are started with . (dot). Here, the resulting first . means current directory. second .. (two dots) means parent directory. You can navigate to the parent directory by entering ```cd ..`` in the terminal. If you enter ```cd .`` it will stay in the same directory.

``` bash
$ ls -a
.  ..  BashGuide.md  Ocaml  Today TODO.txt  view.png

```

#### ls -R -F 
The -R parameter is another option the ls command can use. Called the recursive option, it shows files that are contained within subdirectories in the current directory. If you have lots of subdirectories, this can be quite a long listing.

``` bash
$ ls -F -R
.:
BashGuide.md  Ocaml/  Today TODO.txt*  view.png

./Ocaml:
sec*  sec.ml  untitled

```
