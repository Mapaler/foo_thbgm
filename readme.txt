﻿Usage:
step1: Install foo_thbgm.fb2k-component or extract foo_thbgm.dll into fb2k's components folder.
step2: Move thxml file to your game's installation directory.
step3: Using fb2k to open the thxml file, then enjoy your life!

Something you should know:
Foobar2000 v1.1 or newer required to run this plugin.
Four new thbgm entries are added into fb2k's playback menu.

Loop forever means BGM will always loop. Don't forget to disable loop forever mode when converting these BGMs.
Read metadata will use fb2k's built-in splitter and decoder to read real BGM file's music tag instead of thxml. It's not a preset option since it will speed down unpack efficiency a lot.
The plugin can also extract files from raw binary stream or several type of file archives, just check the Extract Files option, all the bgm files will be dumped in a new folder under current path.

Some sound cards don't support play 神霊廟's ghost mode in Kernel Streaming or WASAPI becuase the frequency is 22050Hz.
You have to add resampler in DSP Manager or change the output setting to others.

Feature:
1. A-B loop for any audio format.
2. Directly play bgm files of touhou and some related doujin games below.

Supported Games
The Embodiment of Scarlet Devil (東方紅魔郷)
Perfect Cherry Blossom (東方妖々夢)
Imperishable Night (東方永夜抄)
Phantasmagoria of Flower View (東方花映塚)
Shoot the Bullet (東方文花帖)
Mountain of Faith (東方風神録)
Subterranean Animism (東方地霊殿)
Undefined Fantastic Object (東方星蓮船)
Double Spoiler (ダブルスポイラー～東方文花帖)
Fairy Wars (妖精大戦争～東方三月精)
Ten Desires (東方神霊廟)
Double Dealing Character (東方輝針城)
Immaterial and Missing Power (東方萃夢想)
Scarlet Weather Rhapsody (東方緋想天)
Hisoutensoku (東方非想天則～超弩級ギニョルの謎を追え)
Hopeless Masquerade (東方心綺楼)
Legacy of Lunatic Kingdom （東方紺珠伝）
Impossible Spell Card (弾幕アマノジャク)
Uwabami Breakers (黄昏酒場)
Kioh Gyoku (稀翁玉)
Banshiryuu (幡紫竜) both c67 and later version
Samidare (五月雨)

ChangeLog:
2.0
full support for tfpk
1.2
add tfpk unpacker for 心綺楼
raw stream dump support
1.1
add loop count setting
fix a bug that configuration can't be saved
1.0
add tasfro unpacker for 緋想天&非想天則
add 五月雨 support
fix 幡紫竜 thxml file
0.9
add ac6 unpacker for 幡紫竜c74 and later version
0.8
add common unpacker support
now we can play music in archive if only fb2k can handle it
0.5
add 幡紫竜c67 version support
add python3 script for converting THxxBGM files
add 神霊廟 ghost mode support
0.4
add 萃夢想&黄昏酒場&稀翁玉 support
change tag file from cue to thxml
0.3
fix decode error in foobar2000 1.1.6
0.2
add 紅魔郷 support
0.1
initial release, support all touhou stg games from 妖々夢 to 神霊廟trial

For any feature request or bug report, feel free to contact me at my E-mail address below.

(C) nyfair <nyfair2012@gmail.com>
