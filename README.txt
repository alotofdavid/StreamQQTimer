This is a slightly modified version of QQtimer for streaming that writes to files.
    
I pulled this version of QQ timer in january 2018, but the updates should work with any version as they are very minor.

The updates create text files in the "Files" folder of this zip file. There are files for best/current single, MO3, AVG5 etc.
    
Additionally there is a time list and a short time list, which contains the last 12 recent times.

The point of these files is to be used with OBS streaming software. The software can read from text files, which allows you to setup the information in any way you want. See Twitch.Tv/HaysCubing for exmples.

Since javascript doesn't naturally write to local files, these edits use ActiveX with internet explorer. You must run the timer in internet explorer and allow ActiveX to be used. The timer must be run locally.
      
To use, download and unqip. Open QQtimer.html in internet explorer, and allow activeX. Setup OBS to read the text files.

If you want to look at the modified versions of code, search "WriteToFile", all modified instances have comments wrapped with this phrase.