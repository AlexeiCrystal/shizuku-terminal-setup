# How to use
1. Try using a universal script/command
2. If it doesn't work, try to use a separate script/command for your particular terminal
3. if there is no script/command for your terminal, use a script/command from the "Other" section.
4. If none of the previous options works, open Issue

# Universal
**Works in most terminals**
>[!NOTE]
>
>**Terminals in which Universal script/command operability is tested:** Termux, TermOne Plus

**Command:**</br>
Copy command from [this file](/universalShizukuSetupCommand.sh)

</br>**Script:**</br>
**1.** Download script from [this file](universalShizukuSetupScript.sh)
</br>**2.** Copy script to `$HOME`
</br>For example:
```Bash
cp /sdcard/Download/universalShizukuSetupScript.sh $HOME
```
**3.** Run script
</br>For example:
```Bash
sh $HOME/universalShizukuSetupScript.sh
```
# [Termux](https://termux.dev)
*Recommended to use [this package](https://github.com/AlexeiCrystal/termux-shizuku-tools) for Termux*</br></br>
**Command:**</br>
Copy command from [this file](/termuxShizukuSetupCommand.sh)</br>

**Script:**</br>
**1.** Download script from [this file](termuxShizukuSetupScript.sh)
</br>**2.** Copy script to `/data/data/com.termux/files/home`
</br>For example:
```Bash
cp /sdcard/Download/termuxShizukuSetupScript.sh /data/data/com.termux/files/home
```
**3.** Run script
</br>For example:
```Bash
sh /data/data/com.termux/files/home/termuxShizukuSetupScript.sh
```
