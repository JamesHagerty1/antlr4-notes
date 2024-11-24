Everything in here started with just the grammar file Hello.g4. Check it out.

Generating the other files from Hello.g4:
% antlr4 Hello.g4
% javac *.java

Then try:
% grun Hello r -tokens      # start the TestRig on grammar Hello at rule r
Typing: "hello parrt"       # input for the recognizer that you type
Then ctrl+D

Or for a different format of above output, do the same but with:
% grun Hello r -tree

Or with a GUI!
% grun Hello r -gui