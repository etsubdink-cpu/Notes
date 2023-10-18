# Kail Linux
---
- we have seen kail Linux based on GNOME.
- "kail Linux previously known as **backtrack**"
##  Kail Linux Tools list

1. *Information gathering*: used for information gathering. we have seen the 5 phase of hacking on [[class1;Introduction to ethical hacking]].Eg: nmap, spiderfoot
2. *vulnerabilitly analysis*: tool for finding analysis 
   - vulnerability assessment:- Its difference with pentration test is that vulnerability assessment have check list which means it not wide scope like pentration test. pentration test some times called [proactive] which means its test we do before the attack is done & [reactive]is after the attack happened.Eg: nikto(best for web hacking), nmap
 3. *web application analysis*: used for pentration testing.
 4. *Data base assessment*
   what is data base
      - **A database is a structured collection of data that is organized and stored in a computer system.**
      
 5. *password attacker*: exploiting password for login, Website, application, windows. Eg: hash, john
 6. *wireless attacks*: for exploiting(attacking) wireless system like Wi-Fi, Bluetooth… 
 7. *Reverse engineering*:reverse it to the coding and trying to find problem. Eg: apktool
 8. *Exploitation tools*: used when noticing a vulnerability and want to search more further.Eg: metasploit
 9. *Sniffing and Spoofing*: used to hack networks. Eg: hamster
 10. *POST exploitation*(maintaining access): used after exploitation to access further more.Eg: mimikatz and weevely.
 11. *Forensics*:
    - There is 2 team is cyber security 
        - **red** and **blue** team
        - **Red**(offensive): They are the attackers.
        - **Blue**(Defensive): They are the defender. 
 - **so this Blue team consist Digital Forensic**,Its basically investigating how did attack.

![[red team vs blue team.webp]]




![[redvsblueteam 1.png]]

 12. *Reporting tools*:for reporting. Eg: screen record.
 13. *Social engineering*: Tool used for social engineering.
 14. *System service*
 15. *Usually used app*:consists software with basic purpose.
### Workspace manager
- This feature is same with window because its basically opening different desktop with out closing the other and switching task.
#### Linux commands
- **Shell**(Terminal):which will help us communicate with the kernel, kail Linux default shell is "ZSH".found in previous [[class2;Introduction to Linux]]
  - ![[Capture.png]]
![[root.png]]

  ##### The shell/ Terminal: have 5 part
  1. **username=etsubdink
  2. **Hostname=sikar
  3. **current directory= path(~mean(Home directory,direcctory means folder))
  4. **Privilege'= $-(user), #(root)
  5. **command place= when you click to type the white vertical sign
	    - *Home directory*: ~
	    - *Local directory*: .
	    - *All directory*: *

 ##### Linux command Basics
 There are over 100 commands.
  ![[option.png]]
  ### what is command?
  command is a program that help us to do one task well.
  command is very case sensitive.

1. *ls/List directory*: to list directory, when we start its always in home directory.
 -  This *ls command* have **options**
   - **ls -l** : to see detail information like byte, date...
   - **ls -a**: to see hide file, to know **if one file is hidden there will be a " . " in front of the file name**.(if you want to hidden file simply add the dot sigh in front of the file name.)
   - **ls filename(eg: desktop)**: to see in a specific file
   - **ls -R**(Recursive): This command open each file.
   - *we can combine them, **ls -Rla** and get same result as if we touch the above 3.
2. *cd/change directory*: 
  - This *cd command* have **options**
    - **cd /**: go to root directory
    - **cd** : go to Home
    - **cd..**: 1x back
    - **cd../..**:2x back
    - **cd folder name**: 
*NOTE*: If the folder name have space, put it under"" because the system may recognize it as different folders.

3. *Pwd/ print home directory*: to view in which path we are currently /home/username is ..called home.
4. *echo*: to display something we put in a "quotation".
    - **echo "Text" >file.txt**:*(write)* to write text on specific file.txt, but it will delete the old one and add the new one.
    - **echo "Text" >>file.txt**:*(append)* to write with out deleting the previous.
*NOTE*: >(angle bracket)

5. *cat/head/tail/less*: 
   - **cat**: to display the Whole file.
   - **head**: to display the first n line 
     - n line is the number of line that we choose it to be displayed it could be 1,2,3,4,5....
     - For example to display the first 2 line of the file we write the command **"head- n2 file.txt"**
   - **less**: same function as cat but it will display less.
   - **tail**:same as head but instead of the first n display it will display the last one.
6. **touch**: to create empty file, to create file
7. **mkdir(make directory)**: to create directory, if it have space use the "file name" 
8. **clear**: to clear out the history
9. **rm/remove**:to remove/ delete file.rm command removes empty file only to remove folder that have file we use rm-r
    - The **rm command** have *options*
      - **rm-r**: recursive which is used for deleting *folders.*
      - **rm-i**: no that much difference just this one needs our permission or conformation to delete the folder.
      - **rm-f**: some file will remove easy in that case we use this command to delete them forcefully.
*NOTE*: we can combine them **rm-rf "filename"

10. **cp & mv/copy,move**:
    - **cp [oldfile- new file]  
    - **mv** [oldfile-new file]  

## There are 3 Linux command that will help us to manage our data
 1. **grep**:The grep filter *searches a file for a particular pattern of characters, and displays all lines that contain that pattern.* The pattern that is searched in the file is referred to as the regular expression (grep stands for global search for regular expression and print out).

     - **grep -i** “search” file case insensitive(to search in both capital and small).
     - **grep -c** “search” file and count numbers.
     - **grep -l** “search” displays filename.
     - **grep -R** “search” folder name ,search text in folders.
     - **grep -v**‘term’ filename To display without this term.
     - **grep -n**“term” file To display the term find number.
 ###### Wc-word count
 - It is used to find out number of lines, word count, byte and characters count in the file.
  This **wc command** have *3 option*
   - *wc-l*: count line
   - *wc-w*:count word
   - *wc-c*: count byte
 #### Multiple command executions
 - This help to run/ execute multiple command in 1 line.
 - *There are 3 methods*
    - **AND(&&)**:In command-line interfaces, the "and" operator (&&) is used to execute multiple commands sequentially, one after another, if and only if the previous command succeeds.
    - **OR(||)**: The "or" operator (||) is used to execute a command if the previous command fails.
    - **Piping(|)**: On pipe, will help you run  commands by using the output of the 1st command as the input for the next one.

2. **awk**: To filter texts that are separated in colon.
  *Eg: cat hope.txt|awk'{print $1}* 
3. **sed**: to find and replace text.
