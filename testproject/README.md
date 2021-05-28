# testproject


Flutter har sin egna get started/install länk nedan
https://flutter.dev/docs/get-started/install/macos

## Getting Started


For MAC
## Downloading straight from GitHub 
1. $ git clone https://github.com/flutter/flutter.git -b stable
## Update your path
2. You can update your PATH variable for the current session at the command line, as shown in Get the Flutter SDK. You’ll probably want to update this variable permanently, so you can run flutter commands in any terminal session.

The steps for modifying this variable permanently for all terminal sessions are machine-specific. Typically you add a line to a file that is executed whenever you open a new window. For example:

1.Determine the path of your clone of the Flutter SDK. You need this in Step 3.
2.Open (or create) the rc file for your shell. Typing echo $SHELL in your Terminal tells you which shell you’re using. If you’re using Bash, edit $HOME/.bash_profile or $HOME/.bashrc. If you’re using Z shell, edit $HOME/.zshrc. If you’re using a different shell, the file path and filename will be different on your machine.
3.Add the following line and change [PATH_OF_FLUTTER_GIT_DIRECTORY] to be the path of your clone of the Flutter git repo:


4. $ export PATH="$PATH:[PATH_OF_FLUTTER_GIT_DIRECTORY]/bin"
Run source $HOME/.<rc file> to refresh the current window, or open a new terminal window to automatically source the file.
Verify that the flutter/bin directory is now in your PATH by running:


5. $ echo $PATH
Verify that the flutter command is available by running:


6. $ which flutter

-----
![image](https://user-images.githubusercontent.com/72130785/119954137-fae54700-bf9e-11eb-87e0-7b0b01080cfc.png)




For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
