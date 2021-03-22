# problem_remote_access_Win10
problem with remote access in Windows 10

### My profile in 

<a href="https://www.linkedin.com/in/mariliahoshino/"><img src="https://github.com/mariliahoshino/mariliahoshino/blob/master/profile/logo_linkedin.png?raw=true" height="50" widht="400"></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
<a href="https://www.mariliahoshino.com/"> Personal page <img src ="https://github.com/mariliahoshino/mariliahoshino/blob/master/profile/logo_site.png?raw=true" height="50" widht="400"></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
<a href="https://www.instagram.com/mari.zeniti/"><img src = "https://github.com/mariliahoshino/mariliahoshino/blob/master/profile/logo_instagram.png?raw=true"  height="50" widht="400"></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
<a href="https://www.facebook.com/mari.zeniti"><img src="https://github.com/mariliahoshino/mariliahoshino/blob/master/profile/logo_facebook.png?raw=true"   height="50" widht="400"></a>  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
<a href="https://linktr.ee/mariliah"><img src="https://github.com/mariliahoshino/mariliahoshino/blob/master/profile/logo_linktree.png?raw=true"   height="50" widht="400"></a>



After Updates, I have problem with Remote Access and Share HDD on LAN <br>

after search a lot of, I saw a solution: <br>
If your Computer's user have a serial for login, probably won't have this problem <br>

<img src="https://github.com/mariliahoshino/problem_remote_access_Win10/blob/main/pictures/erro_remote_access.jpg?raw=true" height="200" widht="200" > <br>

Firstly check the sharing settings <br>

<img src="https://github.com/mariliahoshino/problem_remote_access_Win10/blob/main/pictures/shared_edit_01.png?raw=true" height="600" widht="600" > <br>
<img src="https://github.com/mariliahoshino/problem_remote_access_Win10/blob/main/pictures/shared_edit_02.png?raw=true" height="600" widht="600" > <br>
<img src="https://github.com/mariliahoshino/problem_remote_access_Win10/blob/main/pictures/shared_edit_03.png?raw=true" height="600" widht="600" > <br>

After checked the profile of network, necessary private (particular) checked <br>

<img src="https://github.com/mariliahoshino/problem_remote_access_Win10/blob/main/pictures/profile_network_01.png?raw=true" height="600" widht="600" > <br>
<img src="https://github.com/mariliahoshino/problem_remote_access_Win10/blob/main/pictures/profile_network_02.png?raw=true" height="600" widht="600" > <br>

After It's necessary check the regedit <br>
Windows + R <br>
regedit -> Enter <br>
the Address  <b> HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\Lsa </b>
checke if <b>LimitBlankPassword</b> is zero "0" <br>
<img src="https://github.com/mariliahoshino/problem_remote_access_Win10/blob/main/pictures/regedit_01.png?raw=true" height="600" widht="¨600" > <br>

After, restart the computer and try again remote access



source<br>
https://answers.microsoft.com/pt-br/windows/forum/windows_10-files/problema-compartilhamento-windows-10/3c2accd0-82c4-4d8a-8d89-323cf546e5dc <br>



