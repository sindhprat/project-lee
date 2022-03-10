# plist-to-alias-code

Take an Apple plist, which looks like XML and turn it into a file of aliases for use in bash 

I need help poddies. I have an Apple p-list used by OSX for Text Replacement. Weirdly, it doesn't work within terminal and I can't figure out how to make that happen. So, I'd like to enlist your support in figuring it out programatically. I could do this myself of course, but it would be good to see if we can work it out together. Plus I think that it would be good for us all to see how others approach a problem and try to solve it.

The p-list is in the repository. That is your starting point. My first thought is to parse the file using a bash script or a shell/unix commmand, but if you want to go to the next level, you could look at incorporating Python or Java or another language to get it done. Python in particular, has lots of libraries that can be used for specific tasks and from memory, parsing XML is in one of these libraries I speak of.

Just a thought of course. Do it your way, but basically you want to turn this 

**<dict>
		<key>phrase</key>
		<string>git checkout </string>
		<key>shortcut</key>
		<string>zgch</string>
</dict>
**

into this 
  
**alias zgch='git checkout '**
  
So that when I type 'zgch' in terminal I get 'git checkout ' written for me. 

As a bonus, you can use these aliases yourself, but only once we complete the task! Go fourth and conquer poddies 😊
