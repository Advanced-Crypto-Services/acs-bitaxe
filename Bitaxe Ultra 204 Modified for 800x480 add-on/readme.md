```
Open Source is Intrinsic to Bitcoin
```
# The bitaxeUltra
bitaxe is a fully open source hardware Bitcoin ASIC miner. Ultra is the 3rd major revision of the bitaxe that now includes the BM1366 ASIC from the S19XP

## Bitaxe Ultra 204 Modified for 800x480 add-on
- **This model is based on the Bitaxe Ultra 204 model, but modified for the 800x480 resolution of the add-on. Used with the following projects:**
- https://github.com/Advanced-Crypto-Services/acs-esp-miner
- https://github.com/Advanced-Crypto-Services/acs-bitaxe-lcd-800x480

![image](https://github.com/user-attachments/assets/efe543b3-1d29-4b8d-b131-bd687566cd65)

### Modifications: 
- Added addtional i2C pins for the 800x480 LCD
- Added 4.7k pull-up resistors to the i2C pins for better signal integrity
- Added 5V_OUT for powering the LCD
- Added a Fuse on both 5V_OUT and V_IN
- Added third heatsink mounting hole for better stability with Tower Cooler
- Changed the BOOT and RESET buttons to 90 degree angled buttons for better access when inside and enclosure
