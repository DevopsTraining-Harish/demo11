# demo11
   68  touch java.class
   69  git add java.class 
   70  git commit -m "with ignoring "
   71  ls
   72  touch .gitignore
   73  vi .gitignore 
   74  git add .gitignore 
   75  git commit -m "adding .gitignore"
   76  git push origin development
   77  touch sample.log
   78  git add sample.log 
   79  touch sample.class
   80  git add sample.log  sample.class 
   81  git --help
   82  git lod
   83  git log
   84  git commit --amend
   85  git log
   86  git config --local user.name nh1234
   87  git config --local user.email nh1234@ibm.com
   88  git log
   89  git commit --reset-author
   90  git commit --amend --reset-author
   91  git log
   92  git log
   93  git --help
   94  clear
   95  git log
   96  git rebase --help
   97  git rebase -i 30aa45356c250e6e86cad3b85285600f55969484
   98  git status
   99  git pull
  100  git status
  101  git rebase -i 30aa45356c250e6e86cad3b85285600f55969484
  102  git commit -a -m "fdsf"
  103  git rebase -i 30aa45356c250e6e86cad3b85285600f55969484
  104  git rebase -i 30aa45356c250e6e86cad3b85285600f55969484
  105  git rebase --continue
  106  git rebase --edit-todo
  107  git rebase --edit-todo
  108  git rebase --edit-todo
  109  git rebase --continue
  110  git commit --amend
  111  git rebase --continue
  112  git log
  113  ls
  114  cd
  115  pwd
  116  ls
  117  cd web-app/
  118  ls
  119  mvn compile
  120  ls
  121  cat pom.xml 
  122  mvn test
  123  mvn package
  124  ls -lrt
  125  cd target/
  126  ls
  127  java -jar web-app-1.0-SNAPSHOT.jar 
  128  clear
  129  cat ../pom.xml 
  130  clear
  131  cd ..
  132  mvn install
  133  ls
  134  mvn clean
  135  ls
  136  mvn deploy
  137  clear
  138  mvn install -DskipTests
  139  mvn install -DskipTests=false
  140  mvn install -DskipTests=true
  141  cat pom.xml 
  142  notepad++ pom.xml 
  143  notepad++ pom.xml 
  144  notepad++ 
  145  pwd
  146  cd web-app/
  147  ls
  148  notepad++ pom.xml 
  149  Harish Narla
  150  pwd
  151  cd Desktop/
  152  ls
  153  cd Ali-Working-Copy/
  154  clear
  155  ls
  156  cd ../
  157  mkdir Harish-Working-Copy
  158  cd Harish-Working-Copy/
  159  clear
  160  git clone /d/git_remote_repo/demo-remote-repo Repo
  161  cd Repo
  162  ls -a
  163  ls .git/
  164  cat .git/config
  165  git remote
  166  git remote -v
  167  ls
  168  touch 1.txt
  169  git status
  170  git add 1.txt 
  171  git status
  172  git commit -m "jira-2334"
  173  git log
  174  git push origin master
  175  git lsfiles /d/git_remote_repo/demo-remote-repo
  176  git ls-files /d/git_remote_repo/demo-remote-repo
  177  git ls-files
  178  git log
  179  vi 1.txt 
  180  git status
  181  git add 1.txt 
  182  git commit -m "jira-2334"
  183  git log
  184  clear
  185  git log
  186  git push origin master
  187  git log
  188  git --help
  189  clear
  190  pwd
  191  git remote 
  192  git remote -v
  193  git --help
  194  clear
  195  ls
  196  git status
  197  git pull origin master
  198  ls
  199  git mv 1.txt sample.txt
  200  git status
  201  git diff 
  202  git restore --staged  1.txt
  203  git status
  204  git restore --staged sample.txt 
  205  ls
  206  git status
  207  git add sample.txt 
  208  git add 1.txt 
  209  git status
  210  git commit -m "JIRA-456 renaming file"
  211  git status
  212  ls
  213  git log
  214  git remote -v
  215  git status
  216  ls 
  217  ls -a
  218  cat .git/config
  219  cat .git/HEAD
  220  git status
  221  git remote -v
  222  git branch
  223  git branch -r
  224  clear
  225  git --help
  226  git status
  227  git log
  228  git show master
  229  git log
  230  git show f2c6acdee9cb71910a885a5e82de7eb456f4da84
  231  git log
  232  git show b5be42bf8415f33f3d9c3c4e5bba355882187ac2
  233  git diff
  234  vi sample.txt 
  235  git diff
  236  git log --oneline
  237  git log 
  238  git diff
  239  git log sample.txt
  240  git status
  241  git push origin master
  242  git status
  243  git commit -a -m "fggfFD"
  244  git log
  245  status
  246  git status
  247  clear
  248  git --help
  249  git log
  250  git --help
  251  git grep this
  252  git grep jdk11.0_21
  253  clear
  254  git diff master origin/master
  255  git status
  256  git diff master/sample.txt origin/master/sample.txt
  257  git diff master origin/master -- sample.txt
  258  clear
  259  git --help
  260  git log
  261  git bisect b5be42bf8415f33f3d9c3c4e5bba355882187ac2
  262  git status
  263  git bisect reset
  264  git --help
  265  clear
  266  pwd
  267  git branch dvelopment
  268  git branch --list
  269  git branch development
  270  git branch --list
  271  git branch --help
  272  clear
  273  git branch 
  274  git branch -r
  275  git branch ---remotes
  276  git branch --remotes
  277  git branch --all
  278  git branch -a
  279  clear
  280  git switch development
  281  ls
  282  cat sample.txt 
  283  gi tlog
  284  git log
  285  clear
  286  touch Readme.MD
  287  git status
  288  git add  Readme.MD 
  289  git commit -m "JIRA-4444 Working on Development"
  290  git status
  291  git push origin development
  292  git branch -r
  293  git branch 
  294  git branch task1
  295  git branch
  296  git diff master task1
  297  git show master task1
  298  clear
  299  git switch task1
  300  vi Readme.MD 
  301  git status
  302  git add Readme.MD 
  303  git status
  304  clear
  305  git status
  306  git commit -m "committed in task1 branch"
  307  git switch development
  308  git merge task1
  309  git status
  310  git log
  311  clear
  312  ls
  313  cat Readme.MD 
  314  git log
  315  git diff
  316  git diff20ccb221e242105743dee5370575dd8eae54633d  cd31800986f4496a88d292d2a0a133a3e2bfaae6
  317  git diff 20ccb221e242105743dee5370575dd8eae54633d  cd31800986f4496a88d292d2a0a133a3e2bfaae6
  318  clear
  319  git diff master development
  320  git diff task1 development -- sample.txt
  321  git diff task1 development -- Readme.MD
  322  git diff task1 development  Readme.MD
  323  git diff --help
  324  clear
  325  git branch --list
  326  git branch -D dvelopment
  327  git branch --list
  328  git branch -r
  329  git push origin task1
  330  git branch -a
  331  git branch -D task1
  332  git branch -a
  333  git checkout task1
  334  git branch
  335  git switch master
  336  git branch -a
  337  git branch -D task1
  338  git branch -r
  339  git branch 
  340  git branch -r 
  341  git branch -l
  342  git branch -D master
  343  clear
  344  git reflog
  345  git branch task1 20ccb22
  346  git branch 
  347  git switch task1
  348  ls
  349  car Readme.MD 
  350  cat Readme.MD 
  351  git push origin task1
  352  git push 
  353  git branch -r
  354  git checkout task1
  355  git checkout -b release1
  356  git log
  357  clear
  358  git branch
  359  git reflog
  360  git show-branch
  361  git show-branch -a
  362  git parent
  363  clear
  364  git show-branch -a  | grep *
  365  git show-branch -a 
  366  git show-branch -a | grep '*' 
  367  git rev-parse --help
  368  git rev-list
  369  clear
  370  git rev-parse --abbrev-ref HEAD
  371  git show-branch -a | grep '*' | grep -v \"$(git rev-parse --abbrev-ref HEAD)\"
  372  git show-branch -a | grep '*' | grep -v \"$(git rev-parse --abbrev-ref HEAD)\" | head -n1
  373  git log --graph
  374  clear
  375  git log --graph --oneline
  376  git log --graph --decorate
  377  git log --graph --decorate --oneline
  378  git log --graph
  379  clear
  380  git log --oneline --graph --decorate task1
  381  git reflog
  382  clear
  383  git reflog show
  384  git reflog show task1
  385  git reflog show release1
  386  git reflog show development
  387  git reflog show release1
  388  git reflog show task1
  389  pwd
  390  git switch master
  391  git pull
  392  git branch test
  393  git reflog show test
  394  git ls-remote
  395  git remote show  development
  396  git remote show development
  397  git remote show 
  398  git remote show origin/development
  399  git remote show origin
  400  git push
  401  git remote show origin
  402  git switch development
  403  git sttaus
  404  git status
  405  git pull
  406  git pull origin development
  407  git remote show origin
  408  git push
  409  git branch -r
  410  git push --set-upstream origin development
  411  git remote show origin
  412  clear
  413  git --help
  414  git log
  415  git reset --hard 5dc415af8a2a8be2ba733799eeb15fa013c25d8f
  416  git log
  417  git switch release1 
  418  git tag v1.0.0
  419  git tag --list
  420  git tags
  421  git tag
  422  git push 
  423  git config
  424  git config --list
  425  git pusll
  426  git pull origin release1
  427  git remote 
  428  git remote  show origin
  429  git branch -r
  430  git push
  431  git switch master
  432  git push origin master
  433  git pull origin development
  434  clear
  435  git push
  436  git push --tags
  437  history > git-commands-10-03-2024.txt
  438  ls
  439  history
  440  git reflog show task1
  441  git reflog show master
  442  git reflog show development
  443  clear
  444  git info
  445  git mailinfo
  446  git mailinfo -m "test" git-commands-10-03-2024.txt devopstraining.harish08@gmail.com 
  447  git mailinfo -m "test" git-commands-10-03-2024.txt devopstraining.harish08@gmail.com info
  448  git mailinfo  "test" git-commands-10-03-2024.txt devopstraining.harish08@gmail.com info
  449  git mailinfo  "test" git-commands-10-03-2024.txt devopstraining.harish08@gmail.com>info
  450  clear
  451  cd ../
  452  cd ..
  453  cd Harish-Working-Copy/
  454  clear
  455  mkdir Maven-Module-project
  456  cd Maven-Module-project/
  457  mvn archetype:generate -DgroupId=com.flipkart -DartifactId=core
  458  mvn archetype:generate -DgroupId=com.flipkart -DartifactId=service
  459  mvn archetype:generate -DgroupId=com.flipkart -DartifactId=webapp
  460  ls
  461  mvn archetype:generate -DgroupId=com.flipkart -DartifactId=Maven-module-project
  462  clear
  463  ls
  464  mv core Maven-module-project/
  465  mv service Maven-module-project/
  466  mv webapp Maven-module-project/
  467  ls
  468  cd Maven-module-project/
  469  ls
  470  vi pom.xml 
  471  clear
  472  vi pom.xml 
  473  vi core/pom.xml 
  474  clear
  475  mvn package
  476  clear
  477  mvn compile
  478  clear
  479  mvn compile
  480  clear
  481  mvn compile
  482  clear
  483  mvn compile
  484  mvn package
  485  cd ../..
  486  cd Repo/
  487  ls
  488  git shortlog
  489  git shortlog --commit-ID
  490  git shortlog -s
  491  git shortlog -s -e
  492  git shortlog -s -e -n
  493  git shortlog -s -e -n -c
  494  git shortlog -c
  495  git log --pretty=short
  496  git shortlog dd
  497  git shortlog -d
  498  git log --pretty=short 
  499  ssh administrator@192.168.91.137
  500  pwd
  501  ls
  502  cd Desktop/
  503  ls
  504  cd Ali-Working-Copy/
  505  clear
  506  ls
  507  git init demo11
  508  cd demo11
  509  ls -a
  510  rm -rf .git
  511  ls
  512  git status
  513  clear
  514  cd ..
  515  ls
  516  cd demo11
  517  git status
  518  clear
  519  echo "# demo11" >> README.md
  520  ls
  521  cat README.md 
  522  git init
  523  ls -a
  524  cd ..
  525  git init demo22
  526  cd demo11/
  527  git add README.md
  528  git commit -m "first commit"
  529  git log
  530  git branch -M master
  531  cd ../demo-local-repo/
  532  git remote
  533  clear
  534  cd ../demo11
  535  git remote add origin https://github.com/DevopsTraining-Harish/demo11.git
  536  git status
  537  git remote
  538  git remote -r
  539  git remote -v
  540  clear
  541  git push -u origin master
  542  cd ..
  543  history
  544  mkdir test
  545  cd test
  546  clear
  547  git clone https://github.com/DevopsTraining-Harish/demo11.git
  548  cd demo11/
  549  ls
  550  cat README.md 
  551  git log
  552  touch 2.txt
  553  git status
  554  git add 2.txt 
  555  git status
  556  git commit -m "Second commit"
  557  git log
  558  git push origin master
  559  git branch
  560  git branch -r
  561  git pull
  562  git branch -r
  563  git switch development
  564  git checkout master
  565  git switch development
  566  ls
  567  history >> README.md 
