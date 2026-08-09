# processes_and_signals

Bash scripts covering Linux processes, PIDs and signals.

## Learning objectives

- What is a PID
- What is a process
- How to find a process' PID
- How to kill a process
- What is a signal
- What are the 2 signals that cannot be ignored

## Files

| File | Description |
| ---- | ----------- |
| `0-what-is-my-pid` | Displays its own PID |
| `1-list_your_processes` | Displays a list of currently running processes |
| `2-show_your_bash_pid` | Displays the process lines containing the word `bash` |
| `3-show_your_bash_pid_made_easy` | Displays the PID and name of the processes containing `bash` |
| `4-to_infinity_and_beyond` | Displays `To infinity and beyond` every 2 seconds, forever |
| `5-dont_stop_me_now` | Stops `4-to_infinity_and_beyond` with `kill` |
| `6-stop_me_if_you_can` | Stops `4-to_infinity_and_beyond` with `pkill` |
| `7-highlander` | Like task 4, but answers `I am invincible!!!` to SIGTERM |
| `8-beheaded_process` | Kills `7-highlander` with SIGKILL |
