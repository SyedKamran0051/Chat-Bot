# Chat-Bot

As we will be using TCP socket for this purpose, and therefore we will be using
AD_INET and SOCK_STREAM flags. After analyzing different functions required for
our solution, we divided our coding into two parts that is Client part and the other
for Server part.
Then after importing the required libraries we break our task into sub tasks such
as accepting the incoming connection which is just a loop that waits forever for
the incoming connection , broadcasting messages which basically send the
message to all the connected clients , and handling particular client. We have use
bind() method in order to connect it to specific IP address so it can listen to the
incoming requests. We have also included accept() and close() functions. The
accept method is used to initiate a connection with the particular client whereas
close is used to terminate the particular connection that has been made.
We have use tkinter library which is a GUI method most commonly used to create
GUI application. Our chat box is also password protected and when clients
connect to the server it asked for username and password which upon verification
will allow them to send a message.
