

Introduction:
  1, Trie is used as data structure for storage and lookup because its efficiencty and effective space occupation. 
  2, Handler would read file (or by other ways) to get data and keep all words in the arraylist, Handler would call 
     loadData API to load records into data bank. 
     Only the words which contains Alphabet(a-zA-Z)only could be accepted into databank.
     In the current application, all characters are changed into lower case for storage and lookup 
     because Trie in this version support [a-z] only, refactor is needed in order to support upper case or numeric


There are 3 items:
  1, srouce files named as AutoComplete_src+test.zip
  2, executable JAR file named as AutoComplete_JAR.zip
  3, design and description of this application.
  
How to run the JAR file:
  1, uncompress JAR zip;
  2, open Terminal (Mac OS), or cmd.exe (windows), enter the uncompressed folder
     apply 'java -jar AutoComplete.jar'
     prompt will come out, input prefix is requested
  3, wordlist.txt is the file, content inside can be changed and will be reflected immediately (maxium 5 seconds)
  4, log4j.properties is the configuration file of log4j
  5, log will be generated under ./logs/matchup.log
  
  
  