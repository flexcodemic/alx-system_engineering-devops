# This is my first script on shell basics...

0-current_working_directory
#!/bin/bash
printf "pwd" >> $0-current_working_directory

1-listit
#!/bin/bash
ls

2-bring_me_home
#!/bin/bash
cd ~

3-listfiles
#!/bin/bash
ls -l

4-listmorefiles
#!/bin/bash
ls -al

5-listfilesdigitonly
#!/bin/bash
ls al

6-firstdirectory
#!/bin/bash
mkdir /tmp/my_first_directory

7-movethatfile
#!/bin/bash
mv /tmp/betty /tmp/my_first_directory

8-firstdelete
#!/bin/bash
rm /tmp/my_first_directory/betty

9-firstdirdeletion
#!/bin/bash
rm -rf /tmp/my_first_directory

10-back
#!/bin/bash
cd ../

11-lists
#!/bin/bash
ls -al ../boot

12-file_type
#!/bin/bash
printf "iamafile\n" >> $12-file_type

13-symbolic_link
#!/bin/bash
ln -s /bin/ls _ls_

14-copy_html
#!/bin/bash
cp -u*.html

100-lets_move
#!/bin/bash
mv [[:upper:]]* /tmp/u

101-clean_emacs
#!/bin/bash
rm *~

102-tree
#!/bin/bash
mkdir -p welcome/to/school

103-commas
#!/bin/bash
ls -xamp

school.mgc
#!/bin/bash
0 string SCHOOL School data
!:mime file/School
