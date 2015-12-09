# realpath
# realpath-osx
Description: <br/>
A Python based implementation of realpath for macosx. <br/>

Usage: <br/>
Check out the code to anywhere your $PATH is happy with, I personally like /usr/local/bin. <br/>
Then perform # sudo chmod +x /usr/local/bin/realpath. <br/>
Test with # realpath <i>filename</i>, it should display the absolute path of the <i>filename</i>. If there are symbolic links to the file, both the absolute path and the 'real' absolute path are displayed.<br/>
<br/>
<br/>
Rant: <br/>
So basically I'm so tired of not having a 'realpath' in macosx and I don't think there is one in homebrew... <br/>
And I think to rewrite a cross-platform c program is a overkill... <br/>
Feel free to do whatever you want with this. If you want to improve it just do it. <br/>
