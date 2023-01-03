Basic linux commands
Listing commands
ls option_flag arguments --> list the sub directories and files avaiable in the present directory

Examples:

ls -l--> list the files and directories in long list format with extra information

ls -a --> list all including hidden files and directory

ls *.sh --> list all the files having .sh extension.

ls -i  --> list the files and directories with index numbers inodes

 ls -d */ --> list only directories.(we can also specify a pattern)

Directoy commands
pwd --> print work directory. Gives the present working directory.

cd path_to_directory --> change directory to the provided path

cd ~  or just cd  --> change directory to the home directory

cd - --> Go to the last working directory.

 cd .. --> chnage directory to one step back.

 cd ../.. --> Change directory to 2 levels back.

 mkdir  directoryName --> to make a directory in a specific location

Examples:

mkdir newFolder              # make a new folder 'newFolder'

mkdir .NewFolder              # make a hidden directory (also . before a file to make it hidden)

mkdir A B C D                  #make multiple directories at the same time

mkdir /home/user/Mydirectory   # make a new folder in a specific location

mkdir -p  A/B/C/D              # make a nested directory

These are the below commands which I have used while practicing.


 1  yum update -y
    2  sudo su
    3  clear
    4  mkdir new_folder
    5  cd
    6  ls
    7  cd /
    8  ls
    9  cd bin
   10  ls
   11  clear
   12  apt install docker.io
   13  cd /
   14  ls
   15  cd var
   16  ls
   17  cd lib
   18  ls
   19  cd /
   20  cd ..
   21  cd
   22  apt install docker.io
   23  cd
   24  cd /
   25  ls
   26  cd root
   27  whoami
   28  cd home
   29  ls
   30  cd ubuntu
   31  ls
   32  cd new_folder
   33  pwd
   34  cd
   35  pwd
   36  uname
   37  sudo apt install docker.io
   38  sudo su
   39  whoami
   40  sudo su
   41  whoami
   42  history
   43  ls
   44  rmdir new_folder
   45  ls
   46  touch my_file.txt
   47  ls
   48  rm my_file.txt
   49  clear
   50  echo "hello world"
   51  touch new_file.txt
   52  echo "Nishant"
   53  echo "Nishant" > new_file.txt
   54  ls
   55  cat new_file.txt
   56  echo "Nishant is awsome" > new_file.txt
   57  cat new_file.txt
   58  vim new_file.txt
   59  car new_file.txt
   60  cat new_file.txt
   61  mkdir devops
   62  ls
   63  ls -la
   64  cd devops
   65  mkdir test
   66  touch test
   67  mkdir test
   68  ls
   69  cat test
   70  cd test
   71  ls
   72  touch new_file.txt && echo "This is a new file"
   73  touch new_file1.txt && echo "This is a new file" > new_file1.txt
   74  ls
   75  cd ..
   76  pwd
   77  cd devops/test/
   78  cd ../..
   79  cd devops/test
   80  cd ..
   81  ls
   82  cd test/
   83  cp new_file.txt ..
   84  cd ..
   85  ls
   86  cd
   87  ls
   88  cd ..
   89  ls
   90  cd ubuntu
   91  ls
   92  rm new_file.txt
   93  pwd
   94  cp devops/test/new_file1.txt .
   95  ls
   96  rm new_file1.txt
   97  cd devops/test/
   98  ls
   99  cp new_file1.txt/home/ubuntu
  100  cp new_file1.txt ../..
  101  ls
  102  cd
  103  ls
  104  cp -r devops/test .
  105  ls
  106  rmdir test
  107  rm -rf test
  108  ls
  109  cp devops/test
  110  cd -r devops/test .
  111  cp -r devops/test .
  112  ls
  113  touch python java c go
  114  ls
  115  touch file{1..10}.txt
  116  ls
  117  cd devops
  118  ls
  119  rm new_file.txt
  120  ls
  121  cd .
  122  cd ..
  123  ls
  124  mv file* devops/
  125  cd devops/
  126  ls
  127  mv file1.txt super_duper_file1.txt
  128  ls
  129  clear
  130  sudo apt-get update
  131  sudo apt install default-jdk
  132  cd
  133  cd bin
  134  cd bin.
  135  cd bin/
  136  ls
  137  cd bin
  138  cd ..
  139  cd bin
  140  ls
  141  cd ubuntu
  142  ls
  143  cd /
  144  cd bin
  145  docker --version
  146  docker --jdk
  147  ls
  148  java --version
  149  cd
  150  history
  151  ls
  152  mkdir myscripts
  153  ls
  154  cd myscripts
  155  vim haraperi.sh
  156  chmod 700 haraperi.sh
  157  ls
  158  l
  159  bash haraperi.sh
  160  cat new_file.txt
  161  l
  162  bash haraperi.sh
  163  ls
  164  cat haraperi.sh
  165  ls
  166  cd/
  167  cd /
  168  ls
  169  pwd
  170  sudo su
  171  ls
  172  cd ..
  173  cd
  174  ls
  175  pwd
  176  clear
  177  pwd
  178  ls -a
  179  ls -l
  180  ls -d
  181  ls -d */
  182  ls
  183  ls *.sh
  184  ls -*.sh
  185  ls --*.sh
  186  ls -i
  187  cd myscripts
  188  ls
  189  ls *.sh
  190  ls option_flag arguments
  191  ls
  192  cd `
  193  devops
  194  ls
  195  cat `
  196  cd
  197  cd -
  198  cd ../..
  199  mkdir nishant
  200  sudo mkdir nishant
  201  ls
  202  sudo mkdir .nishant1
  203  ls
  204  ls -a
  205  cd .
  206  ls
  207  cd ..
  208  ls
  209  cd home
  210  ls
  211  sudo mkdir /home/nishant/devops1
  212  ls
  213  cd nishant
  214  ls
  215  sudo mkdir -p A/B/C/D
  216  ls
  217  cd A
  218  ls
  219  cd B
  220  ls
  221  cd C
  222  ls
  223  cd D
  224  ls
  225  cd /
  226  ls
  227  sudo su
  228  history
  229  clear
  230  sudo su
  231  cd /
  232  exit
  233  clear
  234  pwd
  235  history
  236  history ?
  237  ls
  238  cd /
  239  ls
  240  cd home
  241  ls
  242  sudo add user nishant
  243  sudo useradd nishant
  244  sudo cat /etc/passwd
  245  ls
  246  w
  247  su nishant
  248  passwd nishant
  249  ls
  250  cd /
  251  ls
  252  cd home
  253  ls
  254  sudo adduser -m test1,test2
  255  su nishant
  256  grep nishant/etc/shadow
  257  exit
  258  su nishant
  259  ls
  260  cd nishant
  261  ls
  262  cd bin
  263  ls
  264  su nishant
  265  grep nishant/etc/passwd
  266  cd ..
  267  grep nishant/etc/passwd
  268  su nishant
  269  chmod 777 nishant
  270  sudo chmod 777 nishant
  271  su nishant
  272  cat nishant/etc/passwd
  273  cat /etc/passwd
  274  sudo passwd nishant
  275  su nishant
  276  cat nishant/etc/shadow
  277  usermod -1 nishant1 nishant
  278  sudo grep nishant/etc/shadow
  279  ls -ltr
  280  su nishant
  281  umask
