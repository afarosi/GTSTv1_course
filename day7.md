# Finishing for Linux!
## Script installation
* Some hacking tools are developed by some peoples and those peoples make it
open-source, that means we can get those scripts/programs from github.
* So we can download and use it. For this purpose git have a feature called ‘clone’
* Syntax
    ○ git clone <link_of_the_script_from_github>
## Script modules
* Scripts are made with scripting languages(programming) like
{ python,bash,go,ruby,...}
* So when we use these programming languages to do tasks their is something
called modules/libraries these are needed to run the script as the
dependencies.
* Example:
1 Python: to install python modules we use -> pip install <modulename>
i. For requirements ﬁle -> pip install -r requirements.txt
2 Go: to install go modules -> go install <modulename>
3 Ruby: to install ruby modules -> gem install <modulename>
## Python installation
* If pip is not found there will be an error
* It will install
* If the package is already installed:
## Go package installation
* Go scripts are scripts made with go-lang(go programming language).
* There are 2 installation methods.
    - Old version
    - New version
* Old version
    - go to github.com:capotej/groupcache-db-experment.git
* New version
    - Downloading the package
    - Moving the ﬁle to /usr/bin( the default download place is
## Errors you may encounter
* Don’t close apt while installation
* Repository errors, if this happened you can ﬁx it using
   - sudo apt edit-sources
   - And more…
* For those kinds of errors what you have to do is google/youtube { detail we will see this while we learn Footprinting }
## If you need help on linux about commands
* You can use
* man (manual)
    - This will give you the whole manual and instruction of a tool or command.
 - man <yourcommand>
* Keys: arrow keys for navigation | q for quit
## Help
* Some Commands have help
option.
   -  <yourcommand> -h
   - <yourcommand> -help
   - <yourcommand> - -help
   ## Linux Processes & Services
* As we interact with Linux, we create numbered instances of running programs called“processes”
* To get the processes:
  - ps [options]
* More commands
  - ps -> for process running on my shell
  - ps -A -> view all running process
  - ps -u username -> view users process
* PID - Process ID
* To stop process
  - Kill [options] [PID]
* More on kill
   - kill -19 PID -> to stop the process
   - kill -18 PID -> to resume the process we stopped
   - kill -9 PID -> to Stop a process immediately
   - there are 31 options.
## Foreground / background
* Thus far, we have run commands at the prompt and waited for them to complete. We call this running in the “foreground.”
* Use the “&” operator, to run programs in the “background” or press ^Z
* To get the background process back to foreground
  - Fg
* To stop a process going inside your shell just press ^C
## Null device
* /dev/null - Redirects output to nowhere.
* If you want to ignore output, you can send it to the null device, /dev/null.
The null device is a special file that throws away whatever is fed to it.
You may hear people refer to it as the bit bucket.
If you do not want to see errors on your screen and you do not want to save them to a
file, you can redirect them to /dev/null
* On shell output there are 2 things.
To redirect the errors from a command result we do
command 2> ﬁlename
=> here if you check the ﬁle you saved on it have errors only
To redirect the error-FREE output
STDERR = 2
STDOUT = 1
command 1>ﬁlename
So if we redirect our commands output to /dev/null we will get error free result
command 2> /dev/null
## alias
Used to give a name to some bunch of
commands.
Example: if i wanted to name ls -la ‘rex so
any time i want to get output of ls -la i just
type rex
But this doesn’t work after you closed the
terminal
If you want to make it work…
alias rex=’ls -la’
You will add it to your shell conﬁg ﬁle
Example for bash and ﬁsh, zsh…
## Tmux - Terminal Multiplexer
Tmux is used to classify our terminal work.
You can install it using apt. On kali it is built-in
Then to start it just type ‘tmux’\
To Create conﬁg ﬁle type
nano .tmux.conf
Type this
■ unbind C-b
■ unbind l
■ set -g prefix C-a
■ unbind %
■ bind e split-window -h
■ bind o split-window -v
■ set -g base-index 1
■ setw -g pane-base-index 1
Save it | exit tmux and open again
## Wget
* Is a tool used to download ﬁles from websites/servers Syntax
   - wget [options] [link]
   - wget https://tldp.org/LDP/intro-linux/intro-linux.pdf
# CLASS is OVER!
