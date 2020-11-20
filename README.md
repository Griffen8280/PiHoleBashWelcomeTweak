<h1 align="center">Pihole Bash Welcome Tweak</h1>
<div align="center">

<a href="https://github.com/Griffen8280/PiHoleBashWelcomeTweak/stargazers"><img src="https://img.shields.io/github/stars/Griffen8280/PiHoleBashWelcomeTweak" alt="Stars Badge"/></a>
<a href="https://github.com/Griffen8280/PiHoleBashWelcomeTweak/network/members"><img src="https://img.shields.io/github/forks/Griffen8280/PiHoleBashWelcomeTweak" alt="Forks Badge"/></a>
<a href="https://github.com/Griffen8280/PiHoleBashWelcomeTweak/pulls"><img src="https://img.shields.io/github/issues-pr/Griffen8280/PiHoleBashWelcomeTweak" alt="Pull Requests Badge"/></a>
<a href="https://github.com/Griffen8280/PiHoleBashWelcomeTweak/issues"><img src="https://img.shields.io/github/issues/Griffen8280/PiHoleBashWelcomeTweak" alt="Issues Badge"/></a>
<a href="https://github.com/Griffen8280/PiHoleBashWelcomeTweak/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/Griffen8280/PiHoleBashWelcomeTweak?color=2b9348"></a>
<a href="https://github.com/Griffen8280/PiHoleBashWelcomeTweak/blob/master/LICENSE"><img src="https://img.shields.io/github/license/Griffen8280/PiHoleBashWelcomeTweak?color=2b9348" alt="License Badge"/></a></div>

# A Bash Welcome Tweak similar to Retro-Pie for PiHole

much of the code for this came from the orignal over at: https://github.com/retropie/RetroPie-Setup/blob/master/scriptmodules/supplementary/bashwelcometweak.sh  
I only updated it with a new variable and changed many of the system call backs to work independantly instead of being a part of the
overall menu system used by the RetroPie team.

# Installation 
```
git clone --depth=1 https://github.com/Griffen8280/PiHoleBashWelcomeTweak.git</li>
cd PiHoleBashWelcomeTweak</li>
chmod +x bashwelcometweak.sh</li>
./bashwelcometweak.sh</li>
```
This will install the tweak for the user running it and contains much of the same useful information as the RetroPie tweak
with an updated PiHole logo in ascii art.
