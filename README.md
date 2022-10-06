# week-one-practice
first attempt 
Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Install the latest PowerShell for new features and improvements! https://aka.ms/PSWindows

PS C:\Users\15053\OneDrive\Desktop> cd .\Promineo_Tech\
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech> cd .\Week-01-CLI_Source_Control_and_Variables\
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git commit
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got '15053@Envy.(none)')
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git config --global user.name galabren07
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git add .
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git commit -m 'README.md'
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got '15053@Envy.(none)')
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables>  git config --global user.name galabren07
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> omit global
omit : The term 'omit' is not recognized as the name of a cmdlet,
function, script file, or operable program. Check the spelling of the
name, or if a path was included, verify that the path is correct and try
again.
At line:1 char:1
+ omit global
+ ~~~~
    + CategoryInfo          : ObjectNotFound: (omit:String) [], CommandNot
   FoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>

PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> echo " week-one-practice"
 week-one-practice
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git commit -m " first attempt"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got '15053@Envy.(none)')
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables>  git config --global user.name galabren07
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables>  git config --global user.name galabren07
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git init
Initialized empty Git repository in C:/Users/15053/OneDrive/Desktop/Promineo_Tech/Week-01-CLI_Source_Control_and_Variables/.git/
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git config user.name " galabren07"
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git config user,email " galabrenda07@outlook.com"
error: key does not contain a section: user,email
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git add *
fatal: pathspec '*' did not match any files
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git config --global user.email galabren07@outlook.com
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git config --global user.name galabren07
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git add .
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git commit -m " practice"
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>

PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git config --get
error: wrong number of arguments, should be from 1 to 2
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    --worktree            use per-worktree config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-pattern]
    --get-all             get all values: key [value-pattern]
    --get-regexp          get values for regexp: name-regex [value-pattern]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value-pattern]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-pattern]
    --unset-all           remove all matches: name [value-pattern]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    --fixed-value         use string equality when comparing values to 'value-pattern'
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <type>     value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)
    --show-scope          show scope of config (worktree, local, global, system, command)
    --default <value>     with --get, use default value when missing entry

PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git remote add < README.md >.\.git\
At line:1 char:16
+ git remote add < README.md >.\.git\
+                ~
The '<' operator is reserved for future use.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorReco
   rdException
    + FullyQualifiedErrorId : RedirectionNotSupported

PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git remote add < README.MD >
At line:1 char:16
+ git remote add < README.MD >
+                ~
The '<' operator is reserved for future use.
At line:1 char:29
+ git remote add < README.MD >
+                             ~
Missing file specification after redirection operator.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorReco
   rdException
    + FullyQualifiedErrorId : RedirectionNotSupported

PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git commit
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>

PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> get remote add " README.md"
get : The term 'get' is not recognized as the name of a cmdlet, function,
script file, or operable program. Check the spelling of the name, or if a
path was included, verify that the path is correct and try again.
At line:1 char:1
+ get remote add " README.md"
+ ~~~
    + CategoryInfo          : ObjectNotFound: (get:String) [], CommandNotF
   oundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git remote -v
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git add--all
git: 'add--all' is not a git command. See 'git --help'.
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git --help
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git commit -am " README.MD"
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git mv foo bar
fatal: bad source, source=foo, destination=bar
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git commit
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> cd .
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git init
Reinitialized existing Git repository in C:/Users/15053/OneDrive/Desktop/Promineo_Tech/Week-01-CLI_Source_Control_and_Variables/.git/
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> git add README.md
fatal: pathspec 'README.md' did not match any files
PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> first attempt
first : The term 'first' is not recognized as the name of a cmdlet,
function, script file, or operable program. Check the spelling of the
name, or if a path was included, verify that the path is correct and try
again.
At line:1 char:1
+ first attempt
+ ~~~~~
    + CategoryInfo          : ObjectNotFound: (first:String) [], CommandNo
   tFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables> commit b316e2dfb4ba579e6d5cc7f965b6e9be63a9249d
commit : The term 'commit' is not recognized as the name of a cmdlet,
function, script file, or operable program. Check the spelling of the
name, or if a path was included, verify that the path is correct and try
again.
At line:1 char:1
+ commit b316e2dfb4ba579e6d5cc7f965b6e9be63a9249d
+ ~~~~~~
    + CategoryInfo          : ObjectNotFound: (commit:String) [], CommandN
   otFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\15053\OneDrive\Desktop\Promineo_Tech\Week-01-CLI_Source_Control_and_Variables>
