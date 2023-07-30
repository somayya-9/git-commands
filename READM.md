cp --help
man cp
man ls
sudo su -                                                 root user
sudo yum install vim -y                                   install packages
chmod +x helloworld                                       excuteing file (./helloworld)
chmod -r helloworld                                       remove read permission from file
cat /etc/passwd                                           list users
cat /etc/group                                            list group
su - admin                                                login as admin user
useradd admin                                             add user 
mkdir                                                     creat directory
tree
mv word word1                                             change file name
mv linuxcommands  /root/aws/                              move file into aws folder
chown admin helloworld                                    change root used to admin user
chown :admin helloword                                    change root group to admin group
chown admin:admin helloworld                              change root user to admin user and change root group to admin group
rmdir                                                     remove aws directory
rm   -r     aws                                           remove folder inside file
rm   -r     awsdir                                        remove directory
rm   -rf *                                                forcefully remove all
rm   -rf  helloworld                                      forcefully remove file
grep                                                      it is used to searching
grep "linux" aws                                          search linux
grep  -i "linux" aws                                      search linux avoid casesensitive
grep  -c "linux" aws                                      count number of words
grep  i -c "linux" aws                                    count word in number of lines
grep  -l "linux" aws                                      search linux word in multiply files
grep  -n "linux" aws                                      search linux word in number
grep  -v "linux" aws                                      avoid linux line
grep  -h "linux" *                                        see the all linux lines in diffent lines
grep  -e "linux" *                                        see the all lines with filenames
grep  -r hosts *                                          it search inside directory
grep -f pattern aws azure devops                          inside pattern word matches other files
ls grep host                                              all hostname
sed s/yes/no/  word                                       change word inside file yes to no
sed -i s/yes/no/ word                                     permantely change
sed s/crocodile/rabbit/g' my_pet.txt /tmp/rabbit_pet.txt  override content
sed 's/cat/dog/g'  my_pet.txt                             change words in words in differnt line line same line follow
mkdir -p /opt/devops/cm/ansible                           create all directory one click
ln -s  /opt/devops/cm/ansible.log ansi.log                create shortcut for ansi.log
grep -R <searching>                                       search specific file
cut -d : -f1 /etc/user                                    to get specific column
cat /etc/passwd | awk                                     just like a cut command
df -h                                                     file system size 
free -m                                                   memory size
free -m | grep Mem | awk '{print $1}'                     short cut memory
find /etc -name host*                                     it start with word host end with anything
cmp awsnotes azurenotes                                   comparing in byte wise
gzip awsnotes azurenotes                                  zip files
gunzip awsnotes.gz                                        unzip files
tar -cvzf backup.tar.gz worknote                          zip files
tar -xvzf backup.tar.gz                                   unzip files
truncate -s 50 welcome                                    reduce file size
cat file1.txt file2.txt file3.txt > file4.txt            copy 3 files content in 4th file
split -l 2 file4.txt newfile.txt                          split 1 file into 2 files
chage -m 10 wasadmin                                      set change password every 10 days
chage -d 0 wasadmin                                       password must be change
ps                                                        how many application are there
ps -ef                                                    how many process are running
ps -p 884                                                 to see process application
top                                                       it show the application number
date +"%d/%m/%y"                                          to see date
uptime                                                     to see the current situation of server
hostname -b windowssystem                                 change hostname 
uname -s                                                  to see operating system
uname -r                                                  kernal detailes
uname -m                                                  to see hardware
uname -a                                                  to see all detais
 which python                                             to see the location of python
cal                                                       calender
bc                                                        arithumatic operation
netstat                                                   to show all network srver
netstat -u                                                
ifconfig                                                 to see the network connect
iostat                                                    monioting input and output device
iostate -d -k 1 10                                        which are devices are connecting system how many devices
systemctl                                                 it is used to start stop restart system server
set -e                                                    -
hostnamectl set-hostname admin                            -To change the hostname
cat /etc/os-release                                       -It shows the server detailes
dmidecode                                                 - to check all the detaies of server
arch                                                       - arkistructure
.bashrc,.bash_profile                                      - this two files are used to set up environomental variables

