# Linux

clear man -->to get help/information

mkdir -p Linux/sreekar/devops --create multiple directories

chmod 775 file1.txt. --file permissions

sudo -i --switch to root user

chown user:group filte1.txt. -->to change owner of file

vim file1.txt --to edit or create new file use i to insert

cat file1.txt

tail -100f file1.txt

rm --delete file care full

cp [source] [dest] --copy mv [src] [dest] --move or rename

nano -->to edit find -->to search

ps -->for process ps -ef | grep java

kill --> 3 to thread dumps or -9 for force kill

ifconfig -->IP address /etc/hosts for dns mapping in local machine ping to check network connectivity telnet -->connection with port

more --> 5% from starting less --> 5% from bottom

touch -- to edit/create

export -->to set env variables

ifconfig-- to check ip address ip a

zip -->compress file unzip --> to uncompress files

echo -->to print variable sot text

sudo --> impersonate root user or other users

FQDN -->full qualified domain name

ssh user@FQDN -- to login to linux server

pwd --> print current path scp--> transfer to other servers

sudo passwd username--> to reset password

sudo useradd username to create user

sudoers list -->/etc/sudoers


scp -r file1.txt root@ucernwikidev01.northamerica.cerner.net:/home/


crontab -e
rsync [source] [destination]
rsync -pogr --delete-before root@ucernwikiprd01:/opt/atlassian/confluence-std/confluence/* /opt/atlassian/confluence-std/confluence

apt-get install
sed 's/Unix/Linux/' file1.txt

source
/etc/environment--- to add vaeiable


read username

echo $username

read -s -p "enter password:" pass

echo $pass

ln -sfn [source] [destination] -->sym links short cut for lengthy paths

tar -cvf syed1.tar  files files directory/. --> to compress files
tar -xvf syed1.tar -> to uncompress

cd / --> starting directories
 cd ~ --> user homw directory


Directory	Description
/ (root filesystem)	The root filesystem is the top-level directory of the filesystem. It must contain all of the files required to boot the Linux system before other filesystems are mounted. It must include all of the required executables and libraries required to boot the remaining filesystems. After the system is booted, all other filesystems are mounted on standard, well-defined mount points as subdirectories of the root filesystem.


/bin	The /bin directory contains user executable files.


/boot	Contains the static bootloader and kernel executable and configuration files required to boot a Linux computer.

/dev	This directory contains the device files for every hardware device attached to the system. These are not device drivers, rather they are files that represent each device on the computer and facilitate access to those devices.

/etc	Contains the local system configuration files for the host computer.

/home	Home directory storage for user files. Each user has a subdirectory in /home.

/lib	Contains shared library files that are required to boot the system.

/media	A place to mount external removable media devices such as USB thumb drives that may be connected to the host.
/mnt	A temporary mountpoint for regular filesystems (as in not removable media) that can be used while the administrator is repairing or working on a filesystem.
/opt	Optional files such as vendor supplied application programs should be located here.

/root	This is not the root (/) filesystem. It is the home directory for the root user.

/sbin	System binary files. These are executables used for system administration.

/tmp	Temporary directory. Used by the operating system and many programs to store temporary files. Users may also store files here temporarily. Note that files stored here may be deleted at any time without prior notice.

/usr	These are shareable, read-only files, including executable binaries and libraries, man files, and other types of documentation.
/var	Variable data files are stored here. This can include things like log files, MySQL, and other database files, web server data files, email inboxes, and much more.

