# ASUS ROG STRIX B550-XE Gaming Wifi Hackintosh

- Ryzen 5 5600X
- ASUS ROG STRIX B550-XE Gaming Wifi
- Corsair Vengence LPX DDR4-4000 CL16 16GB (2x8GB)
- Patriot Viper Steel DDR4-4000 CL16 16GB (2x8GB)
- Total 32GB RAM, running at 3933 CL16 due to infinity fabric limitations
- PNY CS3040 M.2 NVME SSD (Windows)
- Some Toshiba 2TB Hard Drive
- WD Blue 500GB SSD (MacOS)
- Gigabyte Radeon RX 6800 Gaming OC
- Intel AX200 (Wifi and Bluetooth)
- Opencore 0.9.0
- MacOS Big Sur 11.7.4

# What doesn't work (excluding the issues that only happen on AMD Hackintoshes)

- Airdrop (Use an Apple Airport card instead)

# Additional Notes
- The SMBIOS is the MacPro7,1 (Mac Pro 2019)
- OpenCore logging is disabled as I wanted it to be disabled, you can reenable it in the config.plist by changing the target to 67 in the Misc section
- AMD Patches are set to 6-Cores, change it if your CPU has more cores, read more [here](https://github.com/AMD-OSX/AMD_Vanilla)
- All serial related info and mac address are blanked out, remember to add your own using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)

# [Opencore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
