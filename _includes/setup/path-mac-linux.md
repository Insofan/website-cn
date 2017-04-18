### Update your path

You can update your PATH variable for the current session only at the command line,
as shown in [Clone the Flutter repo](./#clone-the-repo). You'll probably want to 
update this variable permanently, so you can run `flutter` commands in any terminal session.

The steps for modifying this variable permanently for all terminal sessions are machine-
specific. Typically you add a line to a file that is executed whenever you open 
a new window. For example:

1. Open (or create) `$HOME/.bash_profile`. Note that the file path and filename might be
different on your machine.
1. Add the following line:

   ```
   export PATH=$HOME/flutter/bin:$PATH
   ```
1. Run `source $HOME/.bash_profile` to refresh the current window. 

1. Verify that the `flutter/bin` directory is now in your PATH by running:
   ```
   $ echo $PATH
   ```