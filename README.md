Scuffed Linux Loader 🍆

A working Linux loader for PS5 phat/slim firmware 12.00, 12.02, 12.20, 12.40, 12.60 and 12.70

It needs a PS5 Linux image on USB or SSD, and it arms once per boot — power-cycle to arm again.

**A please from me to you all, use the discussion tab for any image fixes you had to make so others can use/try out, example a black screen fix on Bazzite, make sure you add your FW, Image link, how you fixed etc**

**I wont do a fix for pro as it's ghey, if someone has the fix send me something that works and i will add it here**

**ANYONE CAN FORK THIS, EDIT ETC, JUST PLEASE CREDIT**

## Get the pieces 

I recommended this image as it patches WiFi, add 1440p etc
- **PS5 Bazzite Deck** https://github.com/VivaLaVent/ps5-bazzite-deck/releases
  
- **The AIO .elf Loader**
  
- More images you can test yourselves here - https://github.com/ps5-linux/ps5-linux-image/releases/tag/latest

## How to
I seriously recommend using a SSD in a enclosure, USB flash drives are just way too slow for use
1. Flash the image using Rufus and plug the drive into a rear USB-A port or the bottom front USB-C port.
2. On a freshly jailbroken (relaspe) console, run the loader. Don't use autoloader, manually send it after a relaspe jailbreak. -----> *DO NOT SEND ANY OTHER PAYLOADS OTHER THAN THE AIO MAKE SURE ITS A FRESH RELASPE JAILBREAK ONLY* <-----
4. It arms and drops to rest mode — wait for the orange light to stop blinking, then press power.
5. Linux boots. One arm per boot, so power-cycle before trying again, first boot can take a while.

**Your mileage may vary, try a simple restart and try again if any panics, make sure no other payloads are being sent by an autoloader, fresh boot -> relaspe jailbreak -> send the aio. If your PS5 has gone into rest mode, you woke it and it stays solid white light and you have no picture on screen your issue is the image itself not the payload and you will need to find patches/fixes yourself.**

## Credits

- **rmux** — the 12.40 CFI check address, taken from his developer build
- **ps5-linux** — the loader source and the Ubuntu image this build boots
- **soniciso1** — the loader fork this build is based on, and the image archive
- **Ouroboroshen** — his 13.00 / 13.20 tables, used to cross-check our own 12.40 console
- **gzimbric** — his 11.60 port, the reference we checked the wake path against
- **PS5Dev** — Byepervisor and its HV escape, which our kernel read/write work builds on
- **j4lenj** — the original MT7921 module port that one is built from

  
 Discord 12.xx Bros POGGERS
 All below gave me their dumps and/or verified and booted into Linux
- **Ben3Code,Jawshr,Inkredible** 12.70 (confirmed)
- **Shortykun** 12.20 (confirmed)
- **Cupido** 12.40 (confirmed)
- **MagmaEye** 12.60 (confirmed)
- **4killerbeast,Rokkun** 12.00 (confirmed)
- **Darks/frandizzle_** 12.02 (confirmed)
