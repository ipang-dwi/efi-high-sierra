# efi-high-sierra
EFI partition High Sierra for Asus X45C - www.firstplato.com

<img src="https://raw.githubusercontent.com/ipang-dwi/efi-high-sierra/master/ss/0.png"/>

Setelah mencoba MacOS Mojave, akhirnya memutuskan untuk turun ke MacOS High Sierra. Dan ternyata merupakan keputusan yang bijak. Kini Asus X45C, si teman lama, almost became a <b><i>Perfect Hackintosh Laptop</i></b> for daily used.

<img src="https://raw.githubusercontent.com/ipang-dwi/efi-high-sierra/master/ss/2.png"/>

Machine :
- Brand : Asus
- Type : X45C
- BIOS version : 208

Specs :
- Procie : Intel Core i3-2350M 2.3GHz
- VGA : Intel HD3000
- HDD : Toshiba 500GB SATA2 5400RPM, replace with SSD Avexir 120GB SATA3
- ODD : Panasonic DVD-RW SATA2, replace with HDD HGST 1TB 7200RPM mod HDD Caddy
- RAM : Micron 2GB DDR3 1333, extended with Samsung 8GB DDR3L 1600
- Additional : USB Mouse Rexus Xierra X3

Perfect work :
- VGA : Intel HD3000, native tanpa kext, terdeteksi secara cantik di High Sierra 10.13.6
- Audio : latest AppleALC.kext + layout-id : 21 by acidanthera. Lancar jaya, auto switch output.
- Camera / USB 2.0 Asus Webcam : latest USBInjectAll.kext
- LAN Realtek RTL8411 : RealtekRTL8111.kext
- Wifi Atheros 9485 : patch IO80211Family.kext dari Muhammad Arif Isnaini, Forum Hackintosh Indonesia. Tested totally full speed.
- RAM Dual Channel : native tanpa kext, 2GB DDR3 1333 + 8GB DDR3 1600, yang menarik clockspeed yang dipakai yang 1600.
- Baterai, termasuk indikatornya, shutdown, restart, sleep/hibernate : patch manual referensi dari om Rehabman + latest ACPIBatteryManager.kext
- Tombol Fn, bekerja normal semua, hanya buat Brightness UP and Down yang gak bisa.
- Brightness : latest SSDT-PNLF.aml dari om Rehabman, work pakai slider, tombol Fn bingung gak bisa belum coba remapping.
- USB Mouse 7D : SensibleSideButtons dari om Alexei Baboulevitch, tested lancar jaya USB Mouse Rexus Xierra X3

Didn't work :
- Realtek card reader, sudah hukum alam. 

Running Apps on Screenshot :
- Apple terminal
- <a href="https://github.com/dylanaraps/neofetch" target="blank">neofetch</a>
- <a href="http://www.figlet.org/" target="blank">figlet</a>
- <a href="https://cmus.github.io/" target="blank">cmus</a>

Installed Apps :
- <a href="http://cvad-mac.narod.ru/index/0-4" target="blank">Kext Utility</a>
- <a href="https://sourceforge.net/projects/cloverefiboot/" target="blank">Clover Theme Manager</a>
- <a href="https://sourceforge.net/projects/cloverefiboot/" target="blank">Clover Configurator</a>
- <a href="https://sourceforge.net/projects/dpcimanager/" target="blank">DPCI Manager</a>
- <a href="https://bitbucket.org/RehabMan/os-x-maciasl-patchmatic/src" target="blank">MaciASL-patchmatic</a>
- <a href="https://www.fatcatsoftware.com/plisteditpro/" target="blank">PlistEdit</a>
- <a href="https://sensible-side-buttons.archagon.net" target="blank">SensibleSideButton</a>
- <a href="https://www.google.com/chrome/" target="blank">Google Chrome</a>
- <a href="https://keep.google.com/" target="blank">Google Keep</a>
- <a href="http://xdman.sourceforge.net/" target="blank">XDM</a>
- <a href="https://sourceforge.net/projects/xchm/" target="blank">xCHM</a>
- <a href="https://www.videolan.org/vlc/index.html" target="blank">VLC</a>
- <a href="https://www.sublimetext.com/" target="blank">SublimeText</a>
- <a href="https://code.visualstudio.com/" target="blank">VSCode</a>
- <a href="https://brew.sh/" target="blank">Brew</a>
- <a href="https://git-scm.com/" target="blank">git</a>
- <a href="https://github.com/dylanaraps/neofetch" target="blank">Neofetch</a>
- <a href="http://www.figlet.org/" target="blank">Figlet</a>

Deleted Apps :
Almost all unneeded apps bawaan installer. :)

Bagi yang ingin mencoba install, mungin memiliki Laptop/PC dengan spesifikasi yang hampir sama, bisa baca <a href="https://github.com/ipang-dwi/efi-high-sierra/wiki" target="blank">di sini</a>. Sudah disertai link koleksi Vanilla DMG + Clover, direct access.

Akhir kata, terima kasih kepada semua pihak, baik yang sudah maupun belum atau lupa saya sebutkan. Terutama teman-teman di grup FB Forum Hackintosh Indonesia. Jika ada yang butuh bantuan patch DSDT atau sharing, bisa contact saya.

<img src="https://raw.githubusercontent.com/ipang-dwi/efi-high-sierra/master/ss/xchm.png"/>

Feel free to reach me on :
- https://www.firstplato.com
- https://www.facebook.com/firstplato
- admin@firstplato.com
- WA o856 48587 856
