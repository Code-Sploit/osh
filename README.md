# BSH (*Basic Shell*)
This repository is for a *Basic shell* written in python.

Basic shell alias *bsh* is for beginners in the command line.

If you want to see the *available commands for bsh* then go down the page.

# Installation
    # chmod 755 install
    # ./install

# Removing
    # chmod 755 remove
    # ./remove

# More Info
    bsh is a system that works with sessions.
    If you choose a username in the shell then you get a session named $username.active.u .
    Which is located at $bshdir/tmp/a/ .
    Also you get a pid for starting the python script, that file is located in $bshdir/.data/p/ .
    There is also a admin_pass file, but i am not going to reveal it's location in case hackers hjiack the password!
    You can set it when you run the install script.
    
    Freezing: Still working...
    Watching: Still working...

# Commands For *DEFAULT* Users
    echo "text"
    remove "filename"
    add "filename"
    edit "filename"
    diradd "name"
    list or list "/path/to/directory"
    listall or listall "/path/to/directory"
    clear
    read "filename"
    whereami
    gotodir
    copy "file1" "file2"
    move "file1" "file2"
    lgnadmin
    help "cmd"
    ?

# Commands For *ADMIN* Users
    echo "text"
    remove "filename"
    add "filename"
    diradd "name"
    setowner "file" "name"
    setpremissions "file" "premissions"
    edit "filename"
    list or list "/path/to/directory"
    listall or listall "/path/to/directory"
    clear
    read "filename"
    whereami
    gotodir copy "file1" "file2"
    move "file1" "file2"
    kick "user"
    listusers
    listadmins
    help "cmd"
    ?
