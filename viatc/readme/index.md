ViATc
=====
ViATc - Vim mode at Total Commander  
2021/12/19  version 0.5.5.4  
![viatc_logo credit: https://github.com/linxinhong](https://magicstep.github.io/viatc/viatc_logo.jpg?raw=true "viatc_logo")  
<sub>image credit: <A href="https://github.com/linxinhong" target="_blank">https://github.com/linxinhong</a></sub><br>  
This software works on Windows as an addition to "Total Commander"  :floppy_disk: - the greatest file manager :100: (keyboard friendly, two panels, advanced search, comparator, multi-rename, FTP, plugins) get it from www.ghisler.com  
ViATc tries to resemble the work-flow of Vim and web browser plugins like Vimium or better yet SurfingKeys.

What ViATc does to Total Commander (called later TC):
- it's only a separate addition, easily disabled, it doesn't modify TC
- adds more shortcuts, you can add and reconfigure them
- adds more functionality - supports all that AutoHotkey does, not just TC

![image credit: https://www.itqiyi.com/archives/2073](https://magicstep.github.io/viatc/viatc=Vim(AHK)TC.png?raw=true "viatc_logo")  
<sub> image credit: https://www.itqiyi.com/archives/2073  </sub>

Download
========
To get the most recent script (without exe), download  
https://github.com/magicstep/ViATc-English/archive/master.zip  

The below zip file contains an exe file, very likely it is older than the above script. I promise that the exe file is clean, however compiled AHK scripts trigger antiviruses so you might have to add an exception.   
<a href="https://magicstep.github.io/viatc/ViATc-0.5.5.4_executable.zip">ViATc-0.5.5.4_executable.zip</a> 2021/12/19  <br>

Yet older versions at https://magicstep.github.io/viatc/old.html  

Installation
============
- After downloading ViATc, extract, put it in any location and use it.  
- You can run the script if you have Autohotkey installed. Download and install Autohotkey, it is powerful for many purposes. https://autohotkey.com  
- Run ViATc and look for a new icon in the tray, right-click on it and choose Help or Settings to get accustomed to the shortcuts.

Settings
========
You can add and remove shortcuts via the ViATc Settings window. After changes you must click Save or OK (OK will save and reload ViATc).  
You can also add and remove shortcuts directly in the ini file. Reload ViATc manually after any changes made directly in the ini file to take effect.  
In the ini file all lines that begin with a semicolon ; are ignored. It's a standard comment in ini files.  
CapsLock is mapped as Escape. To bypass this use Ctrl+CapsLock  

Usage
=====
A subset of best commands:

j  = Down (5j=5lines)  
k  = Up  
f  = Page Down (5f=5pages)  
b  = Page Up  
t  = open tab, same as Ctrl+t  
x  = close tab, same as Ctrl+w  
d  = directory hotlist, same as Ctrl+d  
o  = open drive drop-box, same as Alt+F1 or Alt+F2  
u  = go up in directory, same as Backspace  
i  = Enter  
cc = Delete  
ma = mark a  
'a = go to mark a  
ah = help  
as = settings  
ar = reload  
sm = show mappings from ini file  
an = show menu to create a new file from template  
zw = toggle one wide panel  
gg = go top  
G  = go bottom  
r  = simple rename, same as Shift+F6  
Shift+r  = fancy rename with a vim emulator  
Ctrl+[   = Esc  
Capslock = Esc  

Author
======
- Author of the original Chinese version is linxinhong https://github.com/linxinhong
- Translator and maintainer of the English version is magicstep https://github.com/magicstep
  You can contact me with the same nickname @gmail.com
- Contributors: uqqu
- Project's easy website https://magicstep.github.io/viatc
- Full project at https://github.com/magicstep/ViATc-English
