# Un Repeater (for mac only)

When you don't want to repeat your most mundane tasks again. Un Repeater provides simple control from status bar.
Start or stop session with a click.

## How it works
1. Drop your scripts in scripts folder and make sure they are numbered
    - Place start related scripts in `scripts/start-hooks` folder
    - Place stop related scripts in `scripts/stop-hooks` folder
    - Also, if you want to run start/stop hook scripts in non block mode, simply add `.noblock` to it
        E.g: If a certain script blocks and if we still want to execute subsequent numbered scripts
2. Run the program from CLI `SESSION_ROOT="session-data" go run main.go`. Where $SESSION_ROOT refers to folder in which collected session details will be preserved
3. From status bar, you can start or stop a session

## Screenshots

### Start session from status bar
![Start Session](./start-session.png)

### Stop session from status bar
![Stop Session](./stop-session.png)
