Code and notes based on "The Definitive ANTLR 4 Reference"

Book is using ANTLR 4.0, I'm using 4.9 per the setup instructions here:
https://github.com/tunnelvisionlabs/antlr4/blob/master/doc/getting-started.md

Setup instructions:

Prerequisites)
Be on a UNIX OS. Have Java Installed.

1)
% cd /usr/local/lib
% curl -O https://www.antlr.org/download/antlr-4.9-complete.jar

2)
Add this to ~/.zshrc or equivalent:
export CLASSPATH=".:/usr/local/lib/antlr-4.9-complete.jar:$CLASSPATH"
alias antlr4='java -Xmx500M -cp "/usr/local/lib/antlr-4.9-complete.jar.jar:$CLASSPATH" org.antlr.v4.Tool'
alias grun='java -Xmx500M -cp "/usr/local/lib/antlr-4.9-complete.jar.jar:$CLASSPATH" org.antlr.v4.gui.TestRig'