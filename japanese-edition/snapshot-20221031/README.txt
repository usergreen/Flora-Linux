2022-10-21 01:23 JST
updated: 2022-10-31 12:05 JST

This is a definite Japanese Edition with Xfce Desktop, because once the Live ISO starts up everything is ready to use in Japanese language environment. Besides, you are free to choose any keyboard layout of your own.

Read this README.txt file first, before using this snapshot for x64 architecture.
The ISO image can be used as Live USB/DVD or for HDD installation.

This snapshot is based on Official MX-21.2.1_x64 Wildflower 18 September 2022.
As for this snapshot, it is shown as "Flora Linux-21.2.1_x64 (September 31, 2022 )" at the boot menu.

User: demo
Demo password: demo
Root password: root

** Downloading sites
An updated version is usually available at https://sourceforge.net/projects/flora-linux/

** Origin of this snapshot.iso"
Modified from the latest Official release of
MX-21.2.1_x64 Wildflower 18 September 2022
Downloaded from MX mirror at
https://ftp.riken.jp/Linux/mxlinux-iso/MX/Final/Xfce/

** Default localization (L10n)
Supported default options are:
ja_JP.UTF-8 - Japanese locale for Japan
C locale

Note:
To change another locale after system booting, logout a present desktop session. Then, click on the upper right corner on the login screen, and choose a locale from a drop-down list. Simply logout and then login again can change a locale for a desktop session.

** Multilingualization (m17n) support
In order to enable Japanese input, click IME toolbar which appears at the same place. Then select item "Anthy". Now you can start Japanese input by pressing Shift + Space key, or alternatively "半/全 漢字" key if your keyboard is Japanese layout.
To return to previous (direct) mode, just press the same key.
If you need another input method for many other languages, add m17n support by installing uim-m17nlib package as follows:
 # apt install uim-m17nlib

** About Universal Input Method (uim)
Uim is an input method module library which supports various scripts and can act as a front end for a range of input methods, including Anthy, Canna, or SKK (for Japanese), Pinyin (for Chinese), Byeoru (for Korean), and M17n (for many other languages). Most of its functions are implemented in Scheme, so it's very simple and flexible.

If you want to use UimToolbar utilities, which shows and controls uim mode, for system tray, add the following, too.

 $ uim-toolbar-gtk3-systray &

** Terms of use
See https://mxlinux.org/terms-of-use/
"Anyone distributing a respin that we do not host ourselves must specify that it is a respin in the names of a website, ISO or download location. For example: mx-respin. Furthermore, it must be specified clearly somewhere that products are based on MX Linux but are not connected with it in any official way.
The name "MX Linux" may not be used as part of a respin-project's website title or in the project's iso/media without making clear that the it is not an official part of MX Linux."

This Live ISO image was released in a hope that it would be useful. Therefore you are allowed to redistribute or modify under the GNU General Public License v.3. Its full text can be found both at https://www.gnu.org/licenses/gpl-3.0.html and onboard at /usr/share/common-licenses/GPL-3. But please be noted that the trademark "MX Linux" and its logo exclusively belong to MX Linux Dev Team, which means it is firmly prohibited for commercial usage without permission.

README.txt was created and written
by Green

