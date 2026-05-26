
# A helper function to open a new terminal window and run a command, defaulting to "dotnet run" if no arguments are given.

runout() {

    # If you don't pass any arguments, default to a plain "dotnet run"

    if [ $# -eq 0 ]; then

        local cmd="dotnet run"

    else

        # Join all arguments passed to the function into a single string

        local cmd="$*"

    fi

  

    echo "Launching in new window: $cmd"

    # Use 'start' to open cmd.exe, using '//k' to keep it open

    start cmd //k "$cmd"

}