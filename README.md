# linux-foundations
## Beginner to the Linux Terminal

pwd: open up the terminal and tells us what directory we are in.
e.g. /Users/apple

cd: means change directory meaning go to another directory somewhere on the system.
e.g. cd Downloads/ ----> (base) apple@yousongpingdeMacBook-Air Downloads %

Go back to the home directory:  1. cd /Users/apple <br>
                                2.cd ~ <br>
                                3.cd <br>

Clear the screen: type “clear”

ls: the list of the command, list the contents of the directory you’re currently in.

touch file1.txt: add a new file “file1”

nano file1.txt: write the content in the file1.

cat file1.txt: read the content of the file1.

mv file1.txt GIC/: move the file1 to the GIC folder.

cp file2.txt GIC/: copy the file2 to the GIC folder.

rm file1.txt GIC/ remove the file1 from GIC folder.

`mkdir` new =  create a folder in the command line.
 
rm -rf new/- remove everything with in the dictionary

which: Who exactly is executing this command?(which ls, which python3)

/bin: The directory containing the most basic system commands 

whereis: List all the relevant paths in the system where this program is located.

sudo: Execute the following commands with administrator (root) privileges.

echo, printf: print

printf “1\n2\n3”
1 <br>
2 <br>
3 <br>

head file2.txt ( print file2.txt first 10 line)

head -n 15 file2.txt(print the first 15 lines)

tail file2.txt( print file2 last 10 line )

ls -l (Use "detailed format" to start the file information in the current directory.)

Chmod: Used to modify file or directory permissions <br>
755: I can modify it myself, but others can only read and execute it. <br>
644: I can edit it myself, but others can only read it. <br>
700: Only I can access <br>
600: Only I can read and write <br>
777: Full control for everyone <br>

history: View the history of commands you have entered in the terminal.

!+number (Locate the corresponding position)

!! (Represents the previous command)

The most common scenarios: <br>
If I forgot to add “sudo” before “apt update”, I don’t need to input it again, directly input 
“sudo !!”, terminal will automatically expand into “sudo apt update”

apt: Advanced Package Tool(Commands used to install, update, and uninstall software.) <br>
E.g. 1. sudo apt install nmap (install) <br>
     2. sudo apt remove nmap (remove) <br>
     3. sudo apt upgrade <br>
update: Check if there is a new version. Only the "information database" is updated; the software on the computer will not be modified.<br>
upgrade: Based on the new version information from the recent update, upgrade the installed software.<br>

ping: Whether the computer can "connect" to the target host, and what the network latency is. <br>
e.g: ping google.com (N) (search DNS -->get IP-->ping IP)<br>
       ping 8.8.8.8 (Y) (Test the Internet)<br>
The DNS resolution is faulty, not the network is down.

wget: URL<br>
wget https://example.com/file.zip<br>
Download files directly to your local machine from a URL (HTTP / HTTPS / FTP).<br>

cal: calendar

ls -lah = Show all files + details + human-executable size
