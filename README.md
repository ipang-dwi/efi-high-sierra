# efi-high-sierra
EFI partition High Sierra for Asus X45C - www.firstplato.com

<img src="https://raw.githubusercontent.com/ipang-dwi/efi-high-sierra/master/ss/0.png"/>

Setelah mencoba MacOS Mojave, akhirnya memutuskan untuk turun ke MacOS High Sierra. Dan ternyata merupakan keputusan yang bijak. Kini Asus X45C, si teman lama, almost became a <b><i>Perfect Hackintosh Laptop</i></b> for daily used.

<img src="https://raw.githubusercontent.com/ipang-dwi/efi-high-sierra/master/ss/2.png"/>

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

Feel free to reach me on :
- https://www.firstplato.com
- https://www.facebook.com/firstplato
- admin@firstplato.com
- WA o856 48587 856
