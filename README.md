# VIS_Game_Boy_DMG
![image](images/VIS_DMGs.jpg)
This project was born with the aim of saving corroded boards of **Gameboy DMGs** or **SNES Super Gameboy adapter**s. For this reason, I developed replacement PCBs by using modern electronic components. Several exisisting DMG mods are included:
- **Lipo power board** that also provides the negative voltage required for the **original LCD** (this voltage can be turned off through a switch if an **IPS screen** is used). Thanks to a **brand new 2.5A DC jac**k, a lipo battery can be safely charged at 0.5 or 1 A. In addition, it is possible to **play while charging** by using only the current coming from the DC jack.
- **Audio board** with all the audio circuits on it in which **1w speaker** or the **original speaker** is directly connected (Audio is not sent to the front PCB, and, for this reason, any power absorbing on the front PCB does not affect audio). Audio amplifier can be disabled to save battery life or to use only the pro-sound jack.
- **Integrated bivert chip**.
- I also developed a **replica of the OSD IPS (v4 or v5) board** with **button LEDs** and **tactile buttons**.
- **Housing shell doesn't require any cut** apart from those required by the IPS LCD mod.

Videos related to this project can be found on my [YouTube Channel](https://www.youtube.com/channel/UC17bQxOnCBejYQG4rzEg3jA).

## Disclaimer

**Before I go any further, please read this VERY important disclaimer if you are thinking about making this yourself.**

If you choose to build this project yourself, be warned - this is a considerably advanced and expensive build. You must be comfortable with the fact that you may lose or damage expensive components. **You are 100% liable for any damage done to your property or yourself. I am not responsible for any damage or loss of property incurred while attempting this project or after completion of the project - you alone accept all risk.** While I am confident in this design, I cannot claim full compatibility with every system configuration. And there may be latent issues that have yet to crop up. I will update this repo if I encounter any, and if you see anything I may have missed or some dubious design choice, feel free to ask questions or comment as such. Corrections are welcome. However, I **will not** obligate myself to provide tech support. You accept all risks and costs associated with this build if you choose to attempt it.

**DO NOT attempt this project if you are uncomfortable or inexperienced with detailed electronics troubleshooting or are not proficient in soldering! You will, AT MINIMUM, need to be proficient in drag soldering and hot air reflowing. If you have not gained proficiency in these soldering skills, DO NOT ATTEMPT THIS PROJECT.**

## Switches/selectors

Before assembling the console, the following switches or selectors must be properly set:
  - The switch on the mainboard to **turn ON/OFF the bivert chip**.
  - The selector on the mainboard to **use normal video or biverted video**.
  - The switch on the powerboard to **turn ON/OFF the negative voltage** required by the **original LCD**.
  - The selector on the powerboard to **set 0.5 A or 1 A charger**.
  - The switch on the IPS board to **turn ON/OFF the button LEDs**.
    
Finally, from the battery compartment, it is possible to **ENABLE/DISABLE the audio amplifier** without opening the console.

## Donor parts

In this project, the **strictly required donor parts** are only the **CPU** (that can be sourced from a donor DMG mainboard or a SNES super Gameboy adapter) and a **link-port** (that can be sourced from a donor DMG mainboard or from a 4 player adapter DMG-07).

Other **optional components to desolder** from a donor console are:
  - **RAM** chips (can be sourced from a donor DMG mainboard or a SNES super Gameboy adapter) or the Alliance AS6C6264-55SIN RAM chips can be purchased.
  - **Card slot connector, volume wheel, and quartz oscillator** can be sourced from a donor DMG mainboard or can be simply purchased on Aliexpress.
  - **Power switch** can be sourced from a donor DMG mainboard, or a brand new switch can be purchased at any electronic components shop (see BOM file).

## Setup instructions

The most **difficult parts** of the project are the following:
  - **Desolder** the components from the donor console by using a hot air gun. For this step, I suggest searching videos on youtube regarding the **SYF Game Gear** setup in which it is shown how to desolder the game gear CPU.
  - **Drag soldering** a 0.5 mm pitch SMD component. Also, in this case, you can refer to the videos made for the **SYF Game Gear** since solder the Game Gear single CPU version has the same type of difficulty.

Finally, it is required to solder easy things like e.g. 0805 and 0603 SMD resistors and capacitors and so on. Take a look at the setup video on my [YouTube Channel](https://www.youtube.com/channel/UC17bQxOnCBejYQG4rzEg3jA) in order to understand and follow all the setup steps. 

**Tip:** Differently from the video, you can use the brand new power switch directly (you find it in the BOM file) because a perfect combination between the original and the new switches is very hard to obtain. If you use the new button reported in the BOM file, firstly, it is not required to shorter the black plastic, and, then, to make it all good, you can add a little tape, as shown in the following photos, to fit the space better.

![image](images/button_fit.jpg)

## Contacts

**email**: vis.modding@gmail.com <br />

**discord**: you can find me as *vis_modding* on several servers (BennVenn, Mouse Bit Lab, Retrosix modding, Game Boy).
