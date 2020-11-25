# Linux-Terminal-Simulation

Simulated bash shell with your own shell that can implements following Linux commands with one option if mentioned with it.
(A) Basic terminal navigation commands:
    a. ls (option: -a)
    b. cd
(B) Displaying the file content on the terminal:
    a. cat (option: -n)
(C) File and directory manipulation commands:
    a. mkdir (option: -m)
    b. cp (option: -u)
(D) Sort and filter data commands:
    a. sort (option: -r)
    b. grep (option: -n)


I. name_shell looks exactly like normal linux terminal, where you can enter the
commands from standard input followed by its arguments.
II. name-shell prompt looks exactly like linux shell prompt showing its current working
directory. (eg: user@system_pc:~$).
III. Any illegal command or unrecognized argument should show a meaningful error to the user
without crashing name_shell.
IV. name_shell also supports exit command to smoothly exit the shell by printing a
meaningful message without forcefully exiting the process.
V. name_shell also support up and down arrows and should implement command
history.

# Requirements

Operating System: Ubuntu
compiler: g++

# Dependencies

git clone https://github.com/jamiejennings/rosie-pattern-language.git
cd rosie-pattern-language/
make

# Compile

g++ Linux_term_sim.cpp -w -lreadline

# Run

./a.out
