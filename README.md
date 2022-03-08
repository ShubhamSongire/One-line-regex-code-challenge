# One-line-regex-code-challenge
This is online challenge where I have made code which solves multiple requirements of problem in single line using nested loop method. Where I have successfully delivered my solution of challenge.
# Challenge task is as follows.
For this project, you will mine text from Shakespeare's famous play Hamlet. You will only mine
from Act I. The corresponding text file can be found inside the same zipped folder. <br>
What to do?<br>
1. First mine all the sentences in Act I using regular expressions. Please remove the
characters’ names. Here is an example: <br>
### Before step1: <br>
BARNARDO Who's there?<br>
FRANCISCO<br>
Nay, answer me. Stand and unfold yourself.<br>
### After step1:<br>
Who's there?<br>
Nay, answer me.<br>
Stand and unfold yourself.<br><br>
### Things to consider:<br>
a. Note that sentences end with a period (.) or a question mark (?) or an
exclamation mark (!). However, sometimes period (.) can be found in the
middle of a sentence, for example, Ph.D. , Mr. , Mrs. Dr., etc. An
interesting thing to note is that period, when appears at the end of a
sentence, is usually also followed by an uppercase letter which is a part of
the next sentence. This idea will stay true for most cases in Act I. <br>
b. Note that you will have to be careful to detect the beginning of a
sentence. Sentences cannot include a character’s name unless it is a part
of the dialog. That means, “BARNARDO Who's there?” is not accepted,
because “BARNARDO” is indicating the speaker’s name and not part of
the dialog. So “BARNARDO” should not be included when mining the
sentence. Only “Who’s there?” should be mined. However, “Get thee to
bed, Francisco.” is a valid sentence and should be included, because
“Francisco” is a part of the dialog.<br>
c. Also note that some sentences start with a single quote (’). These
sentences should not be ignored.<br>
d. The above three are just examples, and more patterns may exist. You are
encouraged to observe more patterns and use that knowledge to write a 
