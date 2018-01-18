follw the given link to understand step by step app building process(also you can read the pdf tutorial):
   https://github.com/codepath/android_guides/wiki/Basic-Todo-App-Tutorial  

if all the process works well then its fine
if not then the problem might occure for connecting *FileUtils*
for this problem you will have to do as follows:

Look at the step from the link or pdf named: <<<Persist Items to File>>>
avoid following <<<Persist Items to File>>> step. follow below steps 

step1: go to the link-->  http://commons.apache.org/proper/commons-io/download_io.cgi
step2: download: (Binaries) commons-io-2.6-bin.zip
step3: extract the zip file
step4: copy the jar file (for example: commons-io-2.6) and paste it to your app/libs directory. see b.png as example
step5: do sync:  Tools => Android => Sync Project with Gradle Files
step6: then again follow the pdf or link as given