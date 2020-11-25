# Linux-Terminal-Simulation

Simulated bash shell with your own shell that can implements following Linux commands with one option if mentioned with it.<br/>
(A) Basic terminal navigation commands:<br/>
    a. ls (option: -a)<br/>
    b. cd<br/>
(B) Displaying the file content on the terminal:<br/>
    a. cat (option: -n)<br/>
(C) File and directory manipulation commands:<br/>
    a. mkdir (option: -m)<br/>
    b. cp (option: -u)<br/>
(D) Sort and filter data commands:<br/>
    a. sort (option: -r)<br/>
    b. grep (option: -n)<br/>


I. name_shell looks exactly like normal linux terminal, where you can enter the
commands from standard input followed by its arguments.<br/>
II. name-shell prompt looks exactly like linux shell prompt showing its current working
directory. (eg: user@system_pc:~$).<br/>
III. Any illegal command or unrecognized argument should show a meaningful error to the user
without crashing name_shell.<br/>
IV. name_shell also supports exit command to smoothly exit the shell by printing a
meaningful message without forcefully exiting the process.<br/>
V. name_shell also support up and down arrows and should implement command
history.<br/>

## Requirements

Operating System: Ubuntu<br/>
compiler: g++<br/>

## Dependencies

git clone https://github.com/jamiejennings/rosie-pattern-language.git<br/>
cd rosie-pattern-language/<br/>
make<br/>

## Compile

g++ Linux_term_sim.cpp -w -lreadline <br/>

## Run

./a.out<br/>

