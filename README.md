## Sublime, Git, Github link them together

### 1.Add the SSH key into the Github and run it in the terminal
1.You need to use "Command+Shift+Dot" shortcut to see the hiden file"id_rsa" and 
"id_rsa.pua";  
[See hidden files on Mac via Finder](https://setapp.com/how-to/show-hidden-files-on-mac#:~:text=See%20hidden%20files%20on%20Mac%20via%20Finder&text=In%20Finder%2C%20open%20up%20your,2%20to%20hide%20them%20again!). 
2.To view the id_rsa.pub, you could drag this file into the chrome browser, and paste the key into the git hub SSH Key location.   
### 2.The Error “The authenticity of host 'github.com' can't be established. RSA key fingerprint ” fixing  While you connect the SSH with github. 
You should simply be able to answer 'yes' to fix the error.  
[Error “The authenticity of host 'github.com' can't be established. RSA key fingerprint ”](https://stackoverflow.com/questions/47707922/error-the-authenticity-of-host-github-com-cant-be-established-rsa-key-finge). 

### 3.Clone the prooject into the local.  
[How to clone a Github Gist via SSH protocol?](https://stackoverflow.com/questions/18019142/how-to-clone-a-github-gist-via-ssh-protocol). 

### 4.GTM executable not found” bullet box will appear

1.You need to use the Package control to install the GTM.  
[ Every time Sublime text3 is started, a “GTM executable not found” bullet box will appear.](https://ddcode.net/2019/05/11/every-time-sublime-text3-is-started-a-gtm-executable-not-found-bullet-box-will-appear/). 


### 5.Add the Git plugin into the Sublime Tex3. 
```
{

	"git_binary": "git安装目录\\Git\\cmd\\git.exe"
}
```
[sublime 安装插件GitGutter报错，git binary cannot be found等等](https://www.shuzhiduo.com/A/x9J2kjE56o/). 

### 6.Git could not push the content into the github
With the Git:commit this step, you just need to type the commit content into the
commit_edit file, then just close the file, do not save this file, and make sure that all the file in the fold do not select the"save" option,just let the command plate to handle it.
[Git error: src refspec master does not match any error: failed to push some refs [duplicate]](https://stackoverflow.com/questions/12452042/git-error-src-refspec-master-does-not-match-any-error-failed-to-push-some-refs). 

## Resource:  
[Sublime Text3 配置Git环境](https://segmentfault.com/a/1190000008761006). 
