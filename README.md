# IW8_Fence_Pass


[ About ]


This project allows you to play the PC BattleNet build of Call of Duty Modern Warfare (2019), commonly known as IW8 or MW2019, in completely offline mode.

It was created to bypass the online requirement fence and allow you to safely develop GSC mods offline without worrying about Ricochet bans.

This source has been completed with the help of many people.

Also, the code in this repository is much older than the modded clients in the videos I share on YouTube and Twitter.

Please understand that some of the bugs from that time remain, so this project is intended to help you learn how to get through the offline fenc

Please note that Arxan and Ricochet bypasses are not included.

For information on Arxan bypass, we recommend referring to mallgrab / CWHook.


-----


[ Credit ]

* This credit goes to my latest version of the source, not the source in this repository.

- Main coding                                                             : HiNAtyu                      ( https://github.com/ProjectHiNAtyu )
- Special support (Base code, Tips, IW8 Arxan hint, and all my mentor...) : Sku-111                      ( https://github.com/Sku-111 )
- Network lecture                                                         : rektinator                   ( https://plutonium.pw/ )
- System relation                                                         : mjkzy                        ( https://github.com/mjkzy )
- Some support , Lobby relations , IW8 1.38+ & IW9 Arxan helps            : WantedDeviation              ( https://ko-fi.com/wanteddeviation )
- Inspect, refactor, and improve code                                     : BodNJenie                    ( https://github.com/bodnjenie14/ )
- LUA decompiler & LUA relations                                          : zhm86                        ( https://github.com/zhm86 )
- Very helpful offline patch base source                                  : h00dbyair                    ( https://pastebin.com/uNWFy651 )
- Basic iw8 system and documentation                                      : Project Donetsk              ( https://github.com/ProjectDonetsk/IW8-1.20 )
- arxan Bypass base project                                               : mallgrab / CWHook            ( https://github.com/mallgrab/CWHook )
- arxan Integrity Checks Infos                                            : momo5502 blogs               ( https://momo5502.com/posts/2022-11-17-reverse-engineering-integrity-checks-in-black-ops-3/ )
- Some LUA debugging reference & good support , Lobby relations           : Lebta2
- IW8+ LAN logic hint                                                     : .r4v3n's MW19 Beta LAN Patch ( ** I found these functions by myself by looking at the readme.txt of his Beta, but the original discoverer of this LAN is .r4v3n, so the credit goes to him. ** )
- Darklasterkiller                                                        :for reversing and found the signatur
- MrLedger                                                                :ricochet bypass
- 


-----


[ Credit rule ]

If you use this project itself, copy even a single line of source, or take inspiration from it in any way, please copy and paste all of the above credits into your own GitHub and release page.

This project was not created by me alone, so omitting to give credits would be an insult not only to me but to everyone else as well.

Please be sure to respect credits!

Please be sure to follow these guidelines, as there have been recent issues with fraudulent crediting or not giving credit to the rightful recipients.

If you find any modded clients, particularly those related to IW8, S4, IW9, or JUP, that implement the same features as those implemented in this source but do not have the above credits, it's possible that they were stolen from here...

Don't forget to give credit to .r4v3n, especially for the LAN implementation here!


Also, if there are any clients who have implemented the same functionality and claim that they did not steal from my source, please open source their source and disclose the information.

That way, I can see how it was implemented from the commit log.

Please cooperate by providing open source in case any problems occur.


-----


[ About LAN ]

And about LAN, as stated in the main credits at the top, all IW8+ LAN rights go to .r4v3n.

It's true that the LAN code in this source is completely my own creation.

However, .r4v3n was the first to discover this LAN logic, and we only got the idea from his MW19 Beta LAN Patch.

So if he hadn't dropped that Beta dll, it would have taken us even longer to find the LAN functions.

Those who are implementing LAN in MW19 and elsewhere should consider that it all comes down to .r4v3n.

And I would like to express my gratitude to .r4v3n for all of his releases to date.

Thank you, .r4v3n.

Thank you so much for discovering LAN two years after the Donetsk release.


-----


[ About main code ]

This project was initially started for MW2019 version 1.57.

The reason was simply that I wanted to see Godzilla again (lol).

However, the behavior of Arxan in version 1.57 was very complex and difficult to understand.

Also, I'm not as skilled a client developer as Sku.


Therefore, I changed my approach and started developing for version 1.67.

Thanks to everyone's cooperation and my own efforts, I was able to continue development without giving up.

I don't like waiting for someone else to release something (lol),

so I decided to learn offline build techniques myself.

As mentioned earlier, this project was completed with the cooperation of many people.

This source code is based on Sku's code, combined with code from h00dbyair.

Please don't forget their contributions.


This project currently supports multiple versions of MW2019.

It works for SP/CP/MP/WZ.

LAN functionality is also implemented, so you can play with your friends.

However, since this project was created for my personal testing, there are many bugs that haven't been fixed.

There may still be many issues, so please be aware of these problems when using it.


Feel free to try it. Feedback is welcome, but I can't guarantee that I will address all issues.

I don't intend to use this tool to operate a client.

It was created purely as a personal hobby.

Enjoy!


Finally, this source code is always shared with Sku-111, the main developer of Donetsk.

Thank you, Sku, for supporting Donetsk!


----------


[ Issue ]

I only created this offline bypass for testing purposes so that I can create GSC mods safely.

Therefore, I'm not too concerned about it, but the username is displayed as "Matched Player" on the lobby screen, which seems to be a problem with the process of retrieving the player name from the Lua field model.

You can also spawn bots using the RTM Tool, which has been released separately.

You might be able to do this automatically by hooking into ProcessScriptFile or something similar and dynamically hooking into Lobby_GetPartyData when the game starts.

If I have time, I might fix it, but it's a very low priority.


----------


[ iw8+ Demonware Modded Clients ]


The modding community I currently belong to, commonly known as "iw8-bodnjenie", focuses on MW19 and is developing clients for newer CoD games since then that use the Demonware Emulator.


With the implementation of DWEmu, CoD can emulate a complete online environment, allowing you to play the online experience of that time.

In addition, the servers are separate from the official CoD servers and use our own DW servers, so there is no risk to your CoD account, allowing you to enjoy multiplayer with your friends with peace of mind.


Currently, iw8-bod supports MW2019 versions 1.38 / 1.44 / 1.57 / 1.63 and CoDV. 

We are committed to continuing development so that we can make modded clients for many more versions and game titles playable.


iw8-bod is intended as a free release.

We welcome any willing engineers with coding or reverse engineering skills who want to help with client development!


If you're interested in DWEmu modded clients for recent Call of Duty games from MW2019 onwards, please join the Discord server below. 

We look forward to seeing you!


= - = - = - Discord Server - = - = - =

https://discord.gg/weUkekkMHw

= - = - = - = - = - = - = - = - = - =


----------


[ Promotion ]


- Discord : hinatapoko
- Twitter : https://x.com/KonataGIF
- YouTube : HiNAtyu Studio ( https://www.youtube.com/@hinatyuproject/featured )


I’d be very happy if you could follow, subscribe, like, or comment on my various SNS accounts. 

If you like my work, I'd be happy if you could sponsor or donate.

This will help facilitate the development of new features and fixes.


- Ko-fi : https://ko-fi.com/hinatyustudio
- BTC : 32J66dfWi9dqqWHS2RYR9rFCUNBL88vgUR
- ETH : 0xaE5D5b3e8E865B2bA676a24eF41d5f4CBD315978.
