# alu-shell / processes_and_signals

Processes and signals exercises. Each file is a Bash script starting with `#!/usr/bin/env bash`.

| File | Description |
|---|---|
| 0-what-is-my-pid | Displays its own PID |
| 1-list_your_processes | Lists all processes, all users, as a hierarchy |
| 2-show_your_bash_pid | Lines containing "bash" from the process list |
| 3-show_your_bash_pid_made_easy | PID and name of every process containing "bash", without `ps` |
| 4-to_infinity_and_beyond | Prints "To infinity and beyond" every 2s, forever |
| 5-dont_stop_me_now | Stops `4-to_infinity_and_beyond`, using `kill` |
| 6-stop_me_if_you_can | Stops `4-to_infinity_and_beyond`, without `kill`/`killall` |
| 67-stop_me_if_you_can | Stops `7-highlander`, without `kill`/`killall` |
| 7-highlander | Runs forever, prints "I am invincible!!!" on SIGTERM |
| 8-beheaded_process | Kills `7-highlander` for good |
| 10-process_and_pid_file | Writes its PID to a file, reacts to SIGINT/SIGTERM/SIGQUIT |
| manage_my_process | Writes "I am alive!" to `/tmp/my_process` every 2s, forever |
| 11-manage_my_process | init-style script: start / stop / restart `manage_my_process` |
