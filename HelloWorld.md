Last login: Wed Apr  9 08:35:45 on ttys000
elodia-coles-macbook:~ elodiacole$ git
usage: git [--version] [--help] [-C <path>] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p|--paginate|--no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

The most commonly used git commands are:
   add        Add file contents to the index
   bisect     Find by binary search the change that introduced a bug
   branch     List, create, or delete branches
   checkout   Checkout a branch or paths to the working tree
   clone      Clone a repository into a new directory
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   fetch      Download objects and refs from another repository
   grep       Print lines matching a pattern
   init       Create an empty Git repository or reinitialize an existing one
   log        Show commit logs
   merge      Join two or more development histories together
   mv         Move or rename a file, a directory, or a symlink
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects
   rebase     Forward-port local commits to the updated upstream head
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index
   show       Show various types of objects
   status     Show the working tree status
   tag        Create, list, delete or verify a tag object signed with GPG

'git help -a' and 'git help -g' lists available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
elodia-coles-macbook:~ elodiacole$ ls
1099sgareb2013.pdf
Applications
Applications (Parallels)
CTX.DAT
Cosmetics, Fragrance, Skin Care and Gifts.pdf
Desktop
Documents
Downloads
Dropbox
Elodia Cole 11.tax2011
Google Drive
Johnnie Cole 11.tax2011
Justinmind
Library
Movies
Music
Parallels, Inc. (para) Online Store - Order Completed.pdf
Pictures
Public
Sites
Untitled 3.txt
Untitled.rtf
clean_kbct_final.csv
clean_kbct_tmp.csv
clean_kbct_tmp2.csv
clean_kbct_tmp3.csv
combinecsv.pl
cor_uid.txt
ctest4.txt
datatables images
directoryparse.plx.txt
ectax11.pdf
file.txt
file2.txt
file_list.txt
jobq.dat
kbct_file_list.txt
kbct_file_list2.txt
kbct_lesion06282012upload-calc-fix.csv
kbct_list.csv
kbct_list2.csv
kbct_list_file2.txt
localcen.txt
mammo_file_list.txt
mammo_list_final.xlsx
sagg_uid.txt
script1.rtf
stest4.txt
tab_file.txt
temp1.txt
test2.txt
test3.txt
test4.txt
trans_uid.txt
ttest4.txt
elodia-coles-macbook:~ elodiacole$ mkdir ~/test-repo
elodia-coles-macbook:~ elodiacole$ cd ~/test-repo
elodia-coles-macbook:test-repo elodiacole$ git init
Initialized empty Git repository in /Users/elodiacole/test-repo/.git/
elodia-coles-macbook:test-repo elodiacole$ git remote add origin https://github.com/eco9500net/test-repo.git
elodia-coles-macbook:test-repo elodiacole$ cd ..
elodia-coles-macbook:~ elodiacole$ ls
1099sgareb2013.pdf
Applications
Applications (Parallels)
CTX.DAT
Cosmetics, Fragrance, Skin Care and Gifts.pdf
Desktop
Documents
Downloads
Dropbox
Elodia Cole 11.tax2011
Google Drive
Johnnie Cole 11.tax2011
Justinmind
Library
Movies
Music
Parallels, Inc. (para) Online Store - Order Completed.pdf
Pictures
Public
Sites
Untitled 3.txt
Untitled.rtf
clean_kbct_final.csv
clean_kbct_tmp.csv
clean_kbct_tmp2.csv
clean_kbct_tmp3.csv
combinecsv.pl
cor_uid.txt
ctest4.txt
datatables images
directoryparse.plx.txt
ectax11.pdf
file.txt
file2.txt
file_list.txt
jobq.dat
kbct_file_list.txt
kbct_file_list2.txt
kbct_lesion06282012upload-calc-fix.csv
kbct_list.csv
kbct_list2.csv
kbct_list_file2.txt
localcen.txt
mammo_file_list.txt
mammo_list_final.xlsx
sagg_uid.txt
script1.rtf
stest4.txt
tab_file.txt
temp1.txt
test-repo
test2.txt
test3.txt
test4.txt
trans_uid.txt
ttest4.txt
elodia-coles-macbook:~ elodiacole$ cd datasciencecoursera
-bash: cd: datasciencecoursera: No such file or directory
elodia-coles-macbook:~ elodiacole$ history
   10  ls
   11  cd Network Utility.app
   12  cd "Network Utility.app"
   13  ls
   14  cd Contents
   15  ls
   16  cd Resources
   17  ls
   18  stroke 10.0.0.2 80 80
   19  ./stroke 10.0.0.2 80 80
   20  ls
   21  cd ..
   22  ls
   23  cd ..
   24  ls
   25  cd 
   26  ls
   27  cd ..
   28  ls
   29  cd ..
   30  ls
   31  cd Applications
   32  ls
   33  cd AMPPS
   34  cd Ampps.app
   35  Ampps.app
   36  ./Ampps.app
   37  ls
   38  ls
   39  cd
   40  ls
   41  cd ..
   42  ls
   43  cd ..
   44  ls
   45  cd Applications
   46  ls
   47  cd AMPPS
   48  ls
   49  Ampps.app
   50  exit
   51  irb
   52  exit
   53  ipconfig
   54  ipconfig /all
   55  ls
   56  whois
   57  exit
   58  php
   59  which php
   60  php -version
   61  ls
   62  cd Downloads
   63  ls
   64  cd AimTemplateBuilder
   65  ls
   66  cd bin
   67  ls
   68  ./run.sh
   69  run.sh
   70  run
   71  ./run.bat
   72  ls
   73  cd ..
   74  printf "%-10s %10s %10s %50s %s\n" "UID" "subject" "KBCTc""plane"
   75  printf "%-10s %10s %15s %50s %s\n" "UID" "subject" "KBCTc""plane"
   76  printf "%-10s %10s %15s %20s\n" "UID" "subject" "KBCTc""plane"
   77  printf "%-10s %10s %15s %20s\n" "UID" "subject" "KBCTc"  "plane"
   78  printf "%-10s %10s %15s %40s\n" "UID" "subject" "KBCTc"  "plane"
   79  awk '($1 != /.jpg$/ -F*\ {printf "%-10s %10s\n", $3, $0 ;}'
   80  awk '($1 != /.jpg$/ {printf "%-10s %10s\n", $3, $0 ;}'
   81  awk '($1 != /.jpg$/ {printf "%-10s %10s\n", $3, $0 ;}' file_list.txt
   82  awk '($1 !~ /.jpg$/ {printf "%-10s %10s\n", $3, $0 ;}' file_list.txt
   83  cat file_list
   84  ls
   85  cat file_list.txt
   86  cat file_list.txt | awk
   87  gawk
   88  awk -F\ '{print $3, $4, $5}' file_list.txt
   89  ls
   90  awk -F\ '{print $3, $4, $5;}' file_list.txt
   91  awk -F\ '{print $3, $4, $5;}' file_list.txt >test.txt
   92  cat file_list.txt | awk -F\ '{print $3,$4,$5 ;}'
   93  awk
   94  cat file_list.txt
   95  awk -F\ '{print $3, $4, $5;}' file_list.txt
   96  awk -F\ '{print $3, $4, $5;}' file_list
   97  awk
   98  printf
   99  printf "%-10s %10s %50s %s\n" "UID" "subject" "KBCTc""plane"
  100  printf "%-10s %10s %10s %50s\n" "UID" "subject" "KBCTc""plane"
  101  printf "%-10s %10s %10s %50s %s\n" "UID" "subject" "KBCTc""plane""
  102  printf "%-10s %10s %10s %50s %s\n" "UID" "subject" "KBCTc""plane"
  103  printf "%-10s %10s %10s %50s %s\n" "UID" "subject" "KBCTc""plane"
  104  exit
  105  quit
  106  end
  107  x
  108  F:\KBCTSnapImages\11-0013\T\1023.jpg
  109  awk  -F\  ' {/!~jpg$/ print $3, $4, $5;}' file
  110  awk  -F\  ' /!~jpg$/ {print $3, $4, $5;}' file
  111  cat file
  112  ls
  113  cat file.txt
  114  awk  -F\  ' /!~jpg$/ {print $3, $4, $5;}' file.txt
  115  ls
  116  ls test.txt
  117  cat test.txt
  118  awk  -F\  ' {print $3, $4, $5;}' file.txt
  119  cat file.txt
  120  ls test.txt
  121  awk
  122  awk -F\ '{print $3, $4, $5, $0;}' file
  123  awk
  124  awk '{print ;}' file.txt
  125  awk -F\ '{print $3, $4, $5;}' file.txt
  126  awk /!=jpg$/ FS\ '{print $3, $4, $5;}' file.txt
  127  awk /!=jpg$/ -FS\ '{print $3, $4, $5;}' file.txt
  128  awk /!=jpg$/ -F\ '{print $3, $4, $5;}' file.txt
  129  awk  -F^\ '{print $3, $4, $5;}' file.txt
  130  awk '{print $3, $4, $5;}' file.txt
  131  awk 'BEGIN {FS="\"}; {print $3, $4, $5;}' file.txt
  132  awk 'BEGIN {FS="\"}; {print $3, $4, $5;}' file.txt
  133  awk -F\\\\ '{print $3, $4, $5;}' file.txt
  134  awk -F- '{printf "%s%s\n", $1,$2;} file2.txt
  135  awk -F- '{printf "%s%s\n", $1,$2;}' file2.txt
  136  awk -F- '{printf "%s%s\n", $1,$2;}' file2.txt
  137  awk -F- '{printf "%s%s\n", $1,$2;}' file.txt
  138  ./script
  139  script1
  140  ./script1.sh
  141  ./script1
  142  awk  -F\\\\ ' {print $3, $4, $0, $5;}' file_list.txt  > temp1.txt
  143  cat temp1.txt
  144  awk  -F\\\\ ' {print $3, $4, $0, $5;}' file_list.txt 
  145  awk  -F\\\\ ' {print $3, $4, $5;}' file_list.txt 
  146  awk  -F\\\\ ' {print $3, $4, $5, $0;}' file_list.txt 
  147  awk  /C/ '{print $0;}' file_list.txt 
  148  awk  /C/ '{print;}' file_list.txt 
  149  cat file_list.txt
  150  awk  '/C/ {print $0;}' file_list.txt 
  151  awk -F\\\\'{printf "%-10s%-10s%s\n", $3,$4,$5}' file_list.txt 
  152  awk -F\\\\'{printf "%-10s %-10s %s\n", $3,$4,$5}' file_list.txt 
  153  awk '-F\\\\{printf "%-10s %-10s %s\n", $3,$4,$5}' file_list.txt 
  154  awk -F\\\\ '{print $3,$4,$5}' file_list.txt 
  155  awk -F\\\\ '{print $3,$4,$5}' file_list.txt>test2.txt 
  156  awk -F- '{printf "%s%s\n", $1,$2;}' test2.txt 
  157  awk -F- '{printf "%s%s\n", $1,$2;}' test2.txt>test3.txt 
  158  awk -F. '{print $1;}' test3.txt 
  159  awk -F. '{print $1;}' test3.txt > test4.txt
  160  awk -F\t '{printf "%s%s%s\n", $1,$2,$3;}' test4.txt
  161  awk  '{printf "%s%s%s\n", $1,$2,$3;}' test4.txt
  162  awk '/C/ {print $0;}'test4.txt 
  163  awk '/C/ {print $0;}' test4.txt 
  164  awk '/C/ {print $0;}' test4.txt > ctest4.txt
  165  awk '/S/ {print $0;}' test4.txt > stest4.txt
  166  awk '/T/ {print $0;}' test4.txt > ttest4.txt
  167  cat text1.txt
  168  cat test1.txt
  169  ls
  170  cat test2.txt
  171  cat ctest4.txt
  172  cat stest4.txt
  173  cat ctest4.txt
  174  ls
  175  cat test.txt
  176  cat test2.txt
  177  ls
  178  awk -F\\\\ '{print $1, $2, $3, $4, $5}' file_list.txt > tab_file.txt
  179  cat tab_file.txt
  180  awk -F- '{print $1, $2;}' tab_file.txt
  181  awk -F- '{printf "%s%s\n" $1, $2;}' tab_file.txt
  182  awk -F- '{printf "%s%s\n", $1, $2;}' tab_file.txt
  183  awk '{UID= $3; $3 = ; 
  184  awk '{UID= $3 ; print UID, $0}' datatables images rrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrtkbct_file_list.txt
  185  ls
  186  ls
  187  cat test2.txt
  188  ls
  189  cat tab_file.txt
  190  awk '{print $3,$4,$5;}' tab_file.txt
  191  awk '{printf "%s%s%s\n", $3,$4,$5;}' tab_file.txt
  192  ls
  193  cat test2.txt
  194  awk '{print $1, $1}; test2.txt
  195  exit
  196  end
  197  '
  198  awk '{print $1, $1;}' test2.txt
  199  ls
  200  ca tab_file.txt
  201  cat tab_file.txt
  202  awk '(print $0, $0:}' tab_file.txt
  203  awk '(print $0, $0;}' tab_file.txt
  204  awk '(print $3 $4 $5, $1 $2 $3 $4 $5;}' tab_file.txt
  205  awk '(print $3 $4 $5;}' tab_file.txt
  206  awk '{print $3 $4 $5, $1, $2, $3, $4, $5;}' tab_file.txt
  207  awk '{print $3 $4 $5;}' tab_fil
  208  awk '{print $0 $3 $4 $5;}' tab_file.txt
  209  awk '{print $0, $3 $4 $5;}' tab_file.txt
  210  awk '{print $0;}' tab_file.txt
  211  awk -F. '{print $3 $4 $5:}
  212  awk -F. '{print $3 $4 $5;}
  213  awk -F. '{print $3 $4 $5}
  214  {print $0;}' tab_list.txt
  215  awk -F. '{print $3 $4 $5}
  216  {print $0;}' tab_file.txt
  217  awk -F.\ '{print $3 $4 $5;}
  218  {print $0;}' tab_file.txt
  219  awk -F.\ '{print $3 $4 $5}
  220  {print $0;}' tab_file.txt
  221  awk -F. '{print $3 $4 $5}' tab_file.txt
  222  awk -F. '{print $3 $4 $5;}' tab_file.txt
  223  ls
  224  cat ttest4.txt
  225  awk '{printf "%s%s%s\n", $1, $2, $3;}' ttest4.txt > trans_uid.txt
  226  cat trans_uid.txt
  227  ls
  228  awk '{printf "%s%s%s\n", $1, $2, $3;}' ctest4.txt > cor_uid.txt
  229  awk '{printf "%s%s%s\n", $1, $2, $3;}' stest4.txt > sagg_uid.txt
  230  awk -F\\\\ "{print $0, $6;}' kbct_file_list.txt
  231  '
  232  "
  233  awk -F\\\\ '{print $0, $6;}' kbct_file_list.txt
  234  ls
  235  cat file_list.txt
  236  awk -F\\\\ '{print $0, $6;}' datatables images\kbct_file_list.txt
  237  awk -F\\\\ '{print $0, $6;}' kbct_file_list.txt
  238  ls
  239  cat file.txt
  240  cat file2.txt
  241  awk 'NR==FNR {
  242  cat[$1]=$2; next
  243  }
  244  {
  245  print $0, cat[$1]
  246  }' test.txt test2.txt
  247  ls
  248  cat test.txt
  249  cat test.txt
  250  cat test2.txt
  251  awk 'NR==FNR {
  252  cat[$1]=$2; next
  253  }
  254  {
  255  print $0, cat[$1]
  256  }' test3.txt test2.txt
  257  awk 'NR==FNR {
  258  cat[$1]=$2; next
  259  }
  260  {
  261  print $0, cat[$4]
  262  }' test3.txt test2.txt
  263  cat test3.txt
  264  cat test4.txt
  265  ls
  266  cat test2.txt
  267  ls
  268  ls
  269  cat test3.txt
  270  cat test2.txt
  271  ls
  272  cat test4.txt
  273  ifconfig/ -a
  274  ifconfig -a
  275  ls
  276  ls ttest4.txt
  277  cat ttest4.txt
  278  ls
  279  perl
  280  ls
  281  cat kbct_file_list.txt
  282  cat testImages1.txt
  283  cat kbct_file_list.txt
  284  combinecsv.pl
  285  ls
  286  perl combinecsv.pl
  287  cat ttest4.txt
  288  ls
  289  cat temp1.txt
  290  ls
  291  perl combinecsv.pl 2,3,4;0 ttest4.txt trans_uid.txt
  292  perl combinecsv.pl 2,3,4;1 ttest4.txt trans_uid.txt
  293  cat trans_uid.txt
  294  ls
  295  awk '{sub("\\\\",","); print $0}' kbct_file_list.txt
  296  awk '{gsub("\\\\",","); print $0}' kbct_file_list.txt
  297  awk '{gsub("\\\\",","); print $0}' kbct_file_list.txt > kbct_list.csv
  298  perl combinecsv.pl 6,7,8;0; kbct_list.csv kbct_file_list.txt
  299  perl combinecsv.pl 6,7,8;0 kbct_list.csv kbct_file_list.txt
  300  perl combinecsv.pl "6,7,8;0" kbct_list.csv kbct_file_list.txt
  301  perl combinecsv.pl "5,6,7;1" kbct_list.csv kbct_file_list.txt
  302  perl combinecsv.pl "7,8,9;1" kbct_list.csv kbct_file_list.txt > clean_kbct_tmp.csv
  303  cat clean_kbct_tmp.csv
  304  cat kbct_list.csv
  305  perl combinecsv.pl "7,8,9;1;" kbct_list.csv kbct_file_list.txt > clean_kbct_tmp.csv
  306  cat clean_kbct_tmp.csv
  307  perl combinecsv.pl "7,8;1;" kbct_list.csv kbct_file_list.txt > clean_kbct_tmp.csv
  308  cat clean_kbct_tmp.csv
  309  perl combinecsv.pl "7,8;1;" kbct_list.csv kbct_file_list.txt > clean_kbct_tmp.csv
  310  cat kbct_list.csv
  311  awk '{gsub(/./, ","); print} kbct_list.csv > kbct_list2.csv
  312  awk '{gsub(/./, ","); print}' kbct_list.csv > kbct_list2.csv
  313  awk '{gsub(/./, ","); print}' kbct_list.csv > kbct_list2.csv
  314  cat kbct_list2.csv
  315  awk '{sub(".", ","); print $0}' kbct_list.csv > kbct_list2.csv
  316  cat kbct_list2.csv
  317  rm kbct_list2.csv
  318  awk '{gsub(".", ","); print $0}' kbct_list.csv > kbct_list2.csv
  319  cat kbct_list2.csv
  320  awk '{gsub("\.\", ","); print $0}' kbct_list.csv > kbct_list2.csv
  321  awk '{gsub("\.\", ","); print}' kbct_list.csv > kbct_list2.csv
  322  rm kbct_list2.csv
  323  awk '{gsub(\.\, ","); print}' kbct_list.csv > kbct_list2.csv
  324  awk '{gsub(\.\, ","); print $0}' kbct_list.csv > kbct_list2.csv
  325  awk '{gsub(/./, ","); print $0}' kbct_list.csv > kbct_list2.csv
  326  cat kbct_list2.csv
  327  awk '{sub(/./, ","); print $0}' kbct_list.csv > kbct_list2.csv
  328  cat kbct_list2.csv
  329  awk '{sub(/\./, ","); print $0}' kbct_list.csv > kbct_list2.csv
  330  cat kbct_list2.csv
  331  history
  332  perl combinecsv.pl "7,8,9;1" kbct_list2.csv kbct_file_list.txt > clean_kbct_tmp.csv
  333  cat clean_kbct_tmp.csv
  334  cat kbct_list2.csv
  335  cat clean_kbct_tmp.csv
  336  ls
  337  cat file.txt
  338  sed '/,$/d' file.txt
  339  sed '/,$/d' clean_kbct_tmp.csv > clean_kbct_tmp2.csv
  340  cat clean_kbct_tmp2.csv
  341  rm clean_kbct_tmp2.csv
  342  cat clean_kbct_tmp.csv
  343  ls
  344  history
  345  awk '{printf $0\n}', kbct_list_file.txt > kbct_list_file2.txt
  346  awk '{printf "%s\n", $0}', kbct_list_file.txt > kbct_list_file2.txt
  347  awk '{printf "%s\n", $1}', kbct_list_file.txt > kbct_list_file2.txt
  348  awk '{printf "%s\n", $1}' kbct_list_file.txt > kbct_list_file2.txt
  349  cat kbct_list_file.txt
  350  ls
  351  awk '{printf "%s\n", $1}' kbct_file_list.txt > kbct_file_list2.txt
  352  cat kbct_file_list2.txt
  353  awk '{printf "%s\n", $0}' kbct_file_list.txt > kbct_file_list2.txt
  354  cat kbct_file_list2.txt
  355  perl combinecsv.pl "7,8,9;1" kbct_list2.csv kbct_file_list2.txt > clean_kbct_tmp.csv
  356  cat cleaan_kbct_tmp.csv
  357  cat clean_kbct_tmp.csv
  358  history
  359  cat kbct_file_list2.txt
  360  cat kbct_file_list.txt
  361  history
  362  cat kbct_list2.csv
  363  history
  364  cat clean_kbct_tmp.csv
  365  vi clean_kbct_tmp.csv
  366  ls
  367  cat test.txt
  368  rm test.txt
  369  cat temp1.txt
  370  ls
  371  cat file_list.txt
  372  ls
  373  cat kbct_list.csv
  374  perl '{chomp($0);}' clean_kbct_tmp.csv > clean_kbct_tmp2.csv 
  375  perl {chomp($0);} clean_kbct_tmp.csv > clean_kbct_tmp2.csv 
  376  perl chomp($0); clean_kbct_tmp.csv > clean_kbct_tmp2.csv 
  377  perl 'chomp($0);' clean_kbct_tmp.csv > clean_kbct_tmp2.csv 
  378  chomp($0); clean_kbct_tmp.csv > clean_kbct_tmp2.csv 
  379  chomp(); clean_kbct_tmp.csv > clean_kbct_tmp2.csv 
  380  chomp() clean_kbct_tmp.csv > clean_kbct_tmp2.csv 
  381  perl chomp
  382  awk chomp
  383  perl chomp($0 =<>); clean_kbct_tmp.csv > clean_kbct_tmp2.csv
  384  perl chomp($0 = <>); clean_kbct_tmp.csv > clean_kbct_tmp2.csv
  385  perl chomp( ); clean_kbct_tmp.csv > clean_kbct_tmp2.csv
  386  perl chomp(); clean_kbct_tmp.csv > clean_kbct_tmp2.csv
  387  cat clean_kbct_tmp2.csv
  388  cat clean_kbct_tmp.csv
  389  ls
  390  perl join('.', $1,$2,$3); clean_kbct_tmp.csv > clean_kbct_tmp2.csv
  391  awk '{printf "%s%s%s\n", $1, $2, $3;}' clean_kbct_tmp.csv > clean_kbct_tmp2.csv
  392  cat clean_kbct_tmp2.csv
  393  awk -F,\ '{printf "%s%s%s\n", $1, $2, $3;}' clean_kbct_tmp.csv > clean_kbct_tmp2.csv
  394  awk -F, '{printf "%s%s%s\n", $1, $2, $3;}' clean_kbct_tmp.csv > clean_kbct_tmp2.csv
  395  cat clean_kbct_tmp2.csv
  396  awk -F- '{printf "%s%s\n", $1, $2;}' clean_kbct_tmp2.csv > clean_kbct_tmp3.csv
  397  cat clean_kbct_tmp3.csv
  398  ls
  399  perl combineCSV.pl "1;1" clean_kbct_tmp3.csv clean_kbct_tmp.csv > clean_kbct_final.csv
  400  cat clean_kbct_final.csv
  401  perl combineCSV.pl "1;1,2,3,4,5" clean_kbct_tmp3.csv clean_kbct_tmp.csv > clean_kbct_final.csv
  402  cat clean_kbct_final.csv
  403  perl combineCSV.pl "1;1,2,3,4" clean_kbct_tmp3.csv clean_kbct_tmp.csv > clean_kbct_final.csv
  404  cat clean_kbct_final.csv
  405  perl if ($3 eq "C") {print $1,$2,$3,$4,$5;} clean_kbct_final.csv > clean_c_kbct_final.csv
  406  perl if ($3 == "C") {print $1,$2,$3,$4,$5\n;} clean_kbct_final.csv > clean_c_kbct_final.csv
  407  perl if.pl ($3 == "C") {print $1,$2,$3,$4,$5\n;} clean_kbct_final.csv > clean_c_kbct_final.csv
  408  awk '{ if($3 =="C") print $1,$2,$3,$4,$5\n;}' clean_kbct_final.csv > clean_c_kbct_final.csv
  409  awk '{ if ($3 =="C") print $1,$2,$3,$4,$5;}' clean_kbct_final.csv > clean_c_kbct_final.csv
  410  cat clean_c_kbct_final.csv
  411  awk '{ if ($3 =="C") print $1,$2,$3,$4,$5;}' clean_kbct_final.csv
  412  cat clean_kbct_final.csv
  413  awk -F, '{ if ($3 =="C") print $1,$2,$3,$4,$5;}' clean_kbct_final.csv > clean_c_kbct_final.csv
  414  cat clean_c_kbct_final.csv
  415  awk -F, '{ if ($3 =="S") print $1,$2,$3,$4,$5;}' clean_kbct_final.csv > clean_s_kbct_final.csv
  416  awk -F, '{ if ($3 =="T") print $1,$2,$3,$4,$5;}' clean_kbct_final.csv > clean_t_kbct_final.csv
  417  cat clean_t_kbct_final.csv
  418  ls
  419  exit
  420  ls
  421  ls
  422  cd ..
  423  cd ..
  424  cd Applications
  425  ls
  426  cd XAMPP
  427  ls
  428  cd htdocs
  429  ls
  430  chmod
  431  man chmod
  432  ls -la
  433  chown
  434  man chown
  435  chmod 
  436  cd php
  437  ls
  438  ls -la
  439  cd ..
  440  ls
  441  ls -la
  442  chown
  443  man ls
  444  chown root file_importex.php
  445  chown root file_importec.php
  446  man chown
  447  chmod 777 file_importec.php
  448  chmod 777 RestCallRequest.php
  449  ls
  450  cd php
  451  ls
  452  s -la
  453  ls -la
  454  ls
  455  cd ..
  456  ls
  457  chown
  458  chown admin file_importec.php
  459  ls -la
  460  chown root file_importec.php
  461  chown elodicacole RestCallRequest.php
  462  chown elodiacole RestCallRequest.php
  463  ls
  464  ls -la
  465  ls -la 
  466  cd xampp
  467  ls
  468  cd..
  469  exit
  470  ls
  471  realpath test2.txt
  472  cd Applications
  473  ls
  474  cd ..
  475  cd ..
  476  ls
  477  cd C:
  478  ls
  479  cd ..
  480  ls
  481  cd Applications
  482  ls
  483  cd XAMPP
  484  ls
  485  cd htdocs
  486  ls
  487  $PWDfile_importec.php
  488  PWDfile_importec.php
  489  dirs
  490  find /Applications/XAMPP/htdocs/file_importec.php -type f
  491  find /Applications/XAMPP/htdocs/file_importec.php
  492  exit
  493  /usr/local/git/bin/git
  494  git
  495  git
  496  git config --global user.name eco9500net
  497  git config --global user.email ebcole@me.com
  498  git config --list
  499  exit
  500  git
  501  ls
  502  mkdir ~/test-repo
  503  cd ~/test-repo
  504  git init
  505  git remote add origin https://github.com/eco9500net/test-repo.git
  506  cd ..
  507  ls
  508  cd datasciencecoursera
  509  history
elodia-coles-macbook:~ elodiacole$ mkdir ~/datasciencecoursera
elodia-coles-macbook:~ elodiacole$ cd ~/datasciencecoursera
elodia-coles-macbook:datasciencecoursera elodiacole$ git init
Initialized empty Git repository in /Users/elodiacole/datasciencecoursera/.git/
elodia-coles-macbook:datasciencecoursera elodiacole$ git remote add origin https://github.com/eco9500net/datasciencecoursera.git
elodia-coles-macbook:datasciencecoursera elodiacole$ vi HelloWorld.md

## This is a markdown file
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
-- INSERT --
