# Hackintosh on Intel 13th gen i5-13400F and ASRock B760M Pro RS/D4
Opencore Bootloader

<h1>System information:</h1>
<list>
  <li>Mainboard: ASROCK B760M Pro RS/D4 (mATX form factor)</li>
  <li>CPU: Intel Core i5-13400F (base freq: 2.5GHz, 4 E-cores boost up to 3.3GHz, 6 P-cores boost up to 4.6GHz with Hyper Threading enabled)</li> 
  <li>RAM: 4x 8GB Corsair Vengeance LPX DDR4 @ 3200MHz (with XMP 2.0 enabled)</li>
  <li>GPU: AMD Radeon RX 470 4GB (Intel GPU Not Support while CPU 13th need CPU-ID fake)</li>
  <li>Disks: 1x 256GB Toshiba Kioxia M.2 SSD (NVMe) + 1x 1TB Lexar NM610 M.2 SSD (NVMe)</li>
  <li>Audio Codec: ALC897 (layout 12)</li>
  <li>Wifi/Bluetooth: BCM94360CS2 (from Macbook Air 2017) + adapter to NGFF M.2 key A/E</li>
  <li>Ethernet: Realtek RTL8125BG 2.5G</li>
</list>

<h1>UEFI Bios Preparing:</h1>
<list>
  <li>Reset Default UEFI</li>
  <list>Disable</list>
    <li>SafeBoot</li>
    <li>PTT</li>
    <li>Trust Plaform TPM</li>
  <list>Enable</list>
    <li>4G Decode</li>
</list>
