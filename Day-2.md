---

---

--- Before Day-2 ---
I already knew basic terminal commands such as `ls`, `cd`, and `pwd`, but I did not fully understand how Linux locates commands through the PATH variable, how shell scripts are executed, or how environment variables persist across terminal sessions.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Day-2 Checklist

* [x] I understand what `PATH` is and why commands like `python` work without full paths
* [x] I can navigate the filesystem without clicking — using `cd`, `ls`, and `pwd` only
* [x] I can read, search, and inspect files using `cat`, `head`, `tail`, `grep`, and `wc`
* [x] I can edit a file using `nano` (open, edit, save, exit)
* [x] I understand pipes (`|`) and redirection (`>`, `>>`, `2>`) and can chain commands
* [x] I can set an environment variable in `.bashrc` and apply it with `source ~/.bashrc`
* [x] I know the difference between `export VAR=value` (available to child processes) and just `VAR=value` (shell-local)

--- After Day-2 ---
I learned how Linux searches for commands using the PATH variable, how shell scripts are executed, how file permissions affect execution, and how `.bashrc` can be used to configure a shell environment. I also gained a better understanding of environment variables, command chaining, and text-processing utilities commonly used in Linux.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

--- Feedback (Suggestions for the TDS Team) ---
The demonstrations explaining PATH resolution and `.bashrc` were especially useful because they helped connect Linux concepts with practical usage. More guided exercises involving shell scripts, grep, pipes, and environment variables would make it easier for beginners to gain confidence with command-line workflows.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

---

---

Personal Notes:

* PATH is a list of directories searched for executable commands.
* `echo $?` shows the exit status of the previous command.
* `chmod +x` grants execute permission to a file.
* `.bashrc` runs when a new shell session starts.
* `export` makes variables available to child processes.
* Commands can be combined using pipes and redirection.

