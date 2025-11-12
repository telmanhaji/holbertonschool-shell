This readme file describes all from project "Shell, processes and signals"
It is important project for learning objective below:
What is a PID
What is a process
How to find a process` PID
How to kill a process
What is a signal
What are the 2 signals that cannot be ignored

Task 0. Script "0-what-is-my-pid" - script that displays its own PID.
Task 1. Script "1-list_your_processes" -  script that displays a list of currently running processes. Requirements:
	A. Must show all processes, for all users, including those which might not have a TTY
	B. Display in a user-oriented format
	C. Show process hierarchy
Task 2. "2-show_your_bash_pid" - script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.
Requirements:
	A.You cannot use pgrep
	B. The third line of your script must be # shellcheck disable=SC2009 (for more info about ignoring shellcheck errorvia link: https://intranet.hbtn.io/rltoken/VyROy_2Z_WNSgVg-r1kz2g)
Task 3. "3-show_your_bash_pid_made_easy" - script that displays the PID, along with the process name, of processes whose name contain the word bash.
Requirements: You cannot use ps
Task 4. "4-to_infinity_and_beyond" - script that displays To infinity and beyond indefinitely. Requirements: In between each iteration of the loop, add a sleep 2.
Task 5. "5-dont_stop_me_now" - Bash script that stops 4-to_infinity_and_beyond process. Requirements: You must use kill.
Task 6. "6-stop_me_if_you_can" - script that stops 4-to_infinity_and_beyond process. Requirements: You cannot use kill or killall.
Task 7. "7-highlander" - script that displays:
	A. To infinity and beyond indefinitely
	B.With a sleep 2 in between each iteration
	C. I am invincible!!! when receiving a SIGTERM signal
Make a copy of your 6-stop_me_if_you_can script, name it 67-stop_me_if_you_can, that kills the 7-highlander process instead of the 4-to_infinity_and_beyond one.
Task 8. "8-beheaded_process" - script that kills the process 7-highlander.
Task 9. "10-process_and_pid_file" - script that:
	A. Creates the file /var/run/myscript.pid containing its PID
	B. Displays To infinity and beyond indefinitely
	C. Displays I hate the kill command when receiving a SIGTERM signal
	D. Displays Y U no love me?! when receiving a SIGINT signal
	E. Deletes the file /var/run/myscript.pid and terminates itself when receiving a SIGQUIT or SIGTERM signal
Task 10. "11-manage_my_process, manage_my_process" - script 11-manage_my_process that manages manage_my_process.
