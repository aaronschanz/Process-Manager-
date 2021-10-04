# Process-Manager-
Program PMan (Process Manager) is able to create a process (and run it in background), present a list of process, terminate/stop/start a process and show stat of a process.  


How to use PMan
Step 1: compile test files that you want to use
Step 2: execute "make" in terminal to compile PMan
Step 3: execute "./PMan" in terminal to run PMan
Step 4: input supported commands in PMan

Supported commands of PMan:
1. bg <cmd>: start program <cmd> in the background. Make sure to include the relative directory.
2. bglist: display a list of all the programs currently executing in the background and the total count of background jobs
3. bgkill <pid>: terminate process <pid>
4. bgstop <pid>: temporarily stop process <pid>
5. bgstart <pid>: restart process <pid> which has been previously stopped
6. pstat <pid>: list comm, state, utime, stime, rss, voluntary_ctxt_switches and nonvoluntary_ctxt_switches of process <pid>
7. exit: exit returns from the main function of PMan.c and ends the program.
