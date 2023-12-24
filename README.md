# Usage

1. Connect to application via ssh (default password: pass)

    ```bash
    ~/home$ ssh -p 2222 user@localhost
    Password authentication
    Password: [password]
    
    Please type `help` to see available commands
    basic::>help
    AVAILABLE COMMANDS
    
    Built-In Commands
            clear: Clear the shell screen.
            exit, quit: Exit the shell.
            help: Display help about available commands.
            history: Display or save the history of previously run commands
            postprocessors: Display the available post processors
            script: Read and execute commands from a file.
            stacktrace: Display the full stacktrace of the last error.
    
    Demo Command
            authentication: Authentication command
            echo: Echo command
            pojo: Pojo command
            table-complex: Complex table command
            table-simple: Simple table command
    
    Jmx Commands
            jmx-info: Displays information about jmx mbean. Use -a option to query attribute values.
            jmx-invoke: Invoke operation on object name.
            jmx-list: List jmx mbeans.
    
    Manage Sessions Commands
          * manage-sessions-info: Displays session
          * manage-sessions-list: Displays active sessions
          * manage-sessions-stop: Stop session
    
    System Commands
            system-env: List system environment.
            system-properties: List system properties.
            system-threads: Thread command.
    
    Commands marked with (*) are currently unavailable.
    Type `help <command>` to learn more.
    ```
