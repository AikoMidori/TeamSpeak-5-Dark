<h1>Windows 11 inspired TeamSpeak 5 skin</h1>

<h1>Instructions</h1>

<h2>Instructions</h2>

Download the file as zip from githib end extract the folder to:
`%AppData%/TeamSpeak/Default/extensions`

When that's done, open the TeamSpeak 5 client and navigate
to 

>Settings > Appearance

and enable User Theme and select the skin you want to use.

<h2>Customization</h2>

The skin supports modifications and customization within the `.css` theme file. 

example: `lightgreen.css`

Needless to say that this is not easy for everyone to understand and so I will do my best to explain the best I can to help you understand editing the file.

First things first, you're going to need a IDE to open the files with. I recommend `notepad++` for starters or `microsoft studio code` for more experienced users. Once downloaded, open the file with the selected program and scroll down  or use ctrl+f in the IDE to search for the section:
>/* modifications */

 ---

<h2>Modifications</h2>

![css](https://i.postimg.cc/fTGPPbtq/download.png)

<h2>Default TS5 Background</h2>

This is the default TeamSpeak client background, it has been turned off because we are using another image.

    --defaultbg: none !important; /* default background img */

If you want to turn it on, please turn off the custombg first.
Change `none` to `flex`

    --defaultbg: flex !important; /* default background img */
___

<h2>Custom Background</h2>

This is the image used for client background.

    --custombg: url(./girl_green.png) !important; /* custom background img */

If you want to turn it off, simply add `/*` at the start of the line.

    /* --custombg: url(./girl_green.png) !important; /* custom background img */

___

<h2>Chat Background</h2>

    --customchatbg: flex !important; /* chat custom background img */

This is the image used for the chat background, if you want to turn it off, simply change `flex` to `none`

    --customchatbg: none !important; /* chat custom background img */
___

<h2>Chat Background Blur</h2>

This option blurs the image of the chat background. The higher the number, the higher the blur.

    --imageblur: blur(50px) !important; /* blur the chat custom background img */
___


<h2>Credits</h2>

- Shiina
- TeamSpeak
- TS Community
- Artwork Authors

<h1>Contact</h1>

You can reach me on discord or send me a mssg on github.
- Shiina♪#0001 - Discord
- [Github](https://github.com/AikoMidori) - AikoMidori
