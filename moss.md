Moss (for a Measure Of Software Similarity) is an automatic system for determining the similarity of programs.
Steps to run MOSS on Linux:

To obtain a Moss account, send a mail message to moss@moss.stanford.edu. The body of the message should appear exactly as follows:
registeruser 
mail username@domain

You will then get a reply containing the script that you will need to save as “moss.pl”. Just make sure that your system has the “perl” folder within the “/usr/bin/“ folder or change the path of the perl folder on the very first line of the script to be compatible to your machine.

Now set the execute permission using the command “chmod ug+x moss.pl”. This should allow you to send your queries to the Stanford server. 

Now submit the query to the server using the command similar to the following "./moss.pl -l cc -c "Run moss lab3b" -d TestMoss/&#42;/&#42;.cpp". Here -l is used to set the language which is C++ in the above case, -c is for the caption (optional) and -d is used to specify the directory. Note that &#42; is used to consider all such files. In the above example, within the TestMoss folder consider all folders and within them look for all .cpp files.

The result on submitting a query such as above would be:
Checking files . . .<br />
OK <br />
Uploading..................................... <br />
Uploading..................................... <br />
Uploading..................................... <br />
Uploading..................................... <br />
Uploading..................................... <br />
.
.
.
.
Query submitted.  Waiting for the server's response. <br />
http://moss.stanford.edu/results/989790299 <br />
