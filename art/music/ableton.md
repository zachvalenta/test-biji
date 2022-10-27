# TODO

## 参考

📜 https://www.ableton.com/en/manual https://www.reddit.com/r/ableton/
🔍 10 https://www.youtube.com/playlist?list=PLoh4MB-kbBmJGLjNwRNr5qAtDr1V3zcNr
🛣 https://www.youtube.com/playlist?list=PLIiejGE6XOgkelJVUsrqZME4QgQNMDQMv

## current

## queue

* rf
* https://www.youtube.com/watch?v=2kjCxfEZZKo
* https://www.youtube.com/watch?v=1E1wHDH9Szo
* arrangement https://www.youtube.com/watch?v=bQ0NUjaIoQE
* session https://www.youtube.com/watch?v=1aIOxEcxT7I
* templates https://www.youtube.com/watch?v=rfsMXBxyniI

## done

# INTERFACE

🔗 https://www.ableton.com/en/manual/live-keyboard-shortcuts/ https://www.youtube.com/watch?v=1hSPWWRIIbg https://www.youtube.com/watch?v=OvhlDsOyktE

* mapping: Live device https://www.youtube.com/watch?v=l0DM9JbkQBA plugin device https://www.youtube.com/watch?v=r8RmTlFvdPA
* _browser_: collections (user-defined) categories (Ableton-defined) places (fs) https://www.youtube.com/watch?v=S6RauKap338 https://www.youtube.com/watch?v=vTflGptQdYY
* _session view_: non-linear, no timeline https://www.youtube.com/watch?v=LGCxbIw4OR8

goto
* search `cmd f`
* clip/device: `shift tab`
* can't toggle from clip view to session/arragement https://www.reddit.com/r/ableton/comments/1hta53/is_there_a_shortcut_to_switch_view_focus/

display
* clip/device: `cmd alt l`
* file: `cmd alt b`
* info: `shift ?`
* inputs/routing: `cmd alt i` https://www.youtube.com/watch?v=wxGrjJh8SrI
* mixer: `cmd alt m`
* plugin: `cmd alt p`

view
* zoom: `shift +` / `-` or hover over timeline and drag up/down https://www.youtube.com/watch?v=K90v9y5KNv0 2:30
* inc/dec grid resolution `cmd 1/2`
* side scroll with mouse using clip view timeline strip https://www.reddit.com/r/ableton/comments/5id9kv/anyone_know_how_to_side_scroll_in_ableton_with_a/db8t7kf

```
+-------------------------------------------------+
|           SESSION/ARRANGMENT                    |
+------- -----------------------------------------+
| b    | |     track                        |  r  |
| r    | |   |       |                      |  e  |
| o    | |   |       |                      |  t  |
| w    | |   |       |                      |  u  |
| s    | |   |-------|                      |  r  |
| e    | |   | route |                      |  n  |-----
| r    | |   | mix   |                      |     || I |
|      | |   |       |                      |     || O | 
+------+ +----------------------------------------|-----

+-------------------------------------------------+
|           DETAIL VIEW                           |
|----------  -------------------------------------|
|  info   |  |     device/clip                    |
|----------  --------------------------------------
+-------------------------------------------------+
```

## arrangement

https://www.youtube.com/watch?v=WW_DnCnEggA

* allow display to scroll: `cmd shift f`
* zoom to track section: in `z` x `x`
* split: `cmd e`
* consolidate: `cmd j`
* add silience: `cmd i`
* fold all: `alt u`
* equalize track height: `shift h`
* all tracks fit screen: `shift w` 

## clip

https://www.ableton.com/en/manual/clip-view/

* stop: btn on open clips in track, track-level https://www.ableton.com/en/manual/session-view/#7-1-session-view-clips stop all https://www.youtube.com/watch?v=LGCxbIw4OR8 4:40
* add using pencil `b`
* zoom in/out on note `z / shift z` https://www.youtube.com/watch?v=Paq66RsgpIk 1:05
* edit velocity (1-127) https://www.youtube.com/watch?v=1cFTonBejIQ 3:15
* _launch_: play; modes (toggle seems to be want I want) https://www.ableton.com/en/manual/launching-clips/ in sync according to global quantization https://www.youtube.com/watch?v=LGCxbIw4OR8 1:30
* control starting point of clip w/ length https://www.youtube.com/watch?v=_gDAcf0EUUY 0:50 ++ legato, reverse, transpose
* reverse `r` https://www.youtube.com/watch?v=RKZZHyFrH_0
* fold: only show octaves with midi notes https://www.youtube.com/watch?v=Paq66RsgpIk 0:35
* edit multiple clips at once https://www.youtube.com/watch?v=lxDYmYaaIk0
* select all notes `cmd a` https://www.youtube.com/watch?v=_gDAcf0EUUY 
* (de)activate clip: `0`
* new clip: `cmd shift m` or double click https://www.youtube.com/watch?v=CNP3c7fs9oM 8:50
* new scene: `cmd i` w/ currently playing clips `cmd shift i`
* _clip_: piece of audio [manual 4.3]
* _slot_: where clip is stored [ToL 5]
* _scene_: n clips [manual 4.4] can only play one clip at a time e.g. need scene to play n clips

## tracks

* new track `cmd/shift t` (or drag from file explorer)
* rename track `cmd r`
* group: fold w/ `u` https://www.youtube.com/watch?v=rCEHZ8pTKc4 will send track output to group first and then master https://www.youtube.com/watch?v=wxGrjJh8SrI 2:20
* routing https://www.youtube.com/watch?v=wxGrjJh8SrI
* monitor: in (hear input when track unarmed) auto (hear input when track armed) https://www.youtube.com/watch?v=wxGrjJh8SrI 2:00
* _track_: attribute [ToL 6]
> how to get multiple components per track? https://www.youtube.com/watch?v=kLdn7WrGGPk 3:00
* _arm_: enable track to receive input (MIDI, analog) for recording https://www.youtube.com/watch?v=4auPj7yQ3uY @ 0:10
* _sidechain_: trigger effect on track Y based on signal from track X; increase sidechain input to magnify effect https://www.youtube.com/watch?v=rbuTKgcteKo 2:45
* _return_: place where track can be routed for further effects processing
* _freeze_: turn off effects on track to reduce CPU load https://www.youtube.com/watch?v=a-0gOTm6Qdk
* double/rm across all tracks https://www.youtube.com/watch?v=riOD-fnyCsg 5:00

## transport

+--------------------------------------------------+
|  tempo | arr. position | playback | punch in/out |
+--------------------------------------------------+

* _tranport_: control what plays back or what you can record over
* _insert marker_: set start of playback https://www.youtube.com/watch?v=m84wUU8CQnY 0:35
* arrangement position https://www.youtube.com/watch?v=m84wUU8CQnY 1:25
* _follow_: scroll arrangement view during playback https://www.youtube.com/watch?v=m84wUU8CQnY 1:50
* play selection https://www.youtube.com/watch?v=m84wUU8CQnY 1:15
* play from insert marker `space`
* play from pause `shift space` play from specific location (double click on scrub area)
* _locator_: way to organize song form in arragement view https://www.youtube.com/watch?v=riOD-fnyCsg 3:00
* _brace_: subset of timeline https://www.youtube.com/watch?v=riOD-fnyCsg 3:40
* _punch switch_: prevent recording outside brace
* _loop switch_: loop w/in brace; toggle `ctrl l`
* metronome: control volume using 'preview cue' in return/master section of session view https://www.youtube.com/watch?v=weSlbnURmCE
* `shift record` for arrangment record button while in session view = ararngement view will wait until you start a scene before recording https://www.youtube.com/watch?v=OaQpybm5Pcw 0:50

# RECORDING

* _capture_: post-record whatever MIDI you just entered https://www.youtube.com/watch?v=aJg1UfePwTc
* track audio: turn on interface preamp https://www.youtube.com/watch?v=FcpW7Ftcn7k 1:00, arm track, select input, monitor to output https://www.youtube.com/watch?v=7PbmTaJopec 1:20
* track MIDI: create track (but not clip), session record; overdub https://www.youtube.com/watch?v=4auPj7yQ3uY 1:20
* record session to arrangement: tracks unarmed, need to use back-to-arrangement btn https://www.ableton.com/en/manual/session-view/#7-5-recording-sessions-into-the-arrangement can also drag to arragement https://www.youtube.com/watch?v=OaQpybm5Pcw 4:15

drum programming https://www.youtube.com/playlist?list=PLIiejGE6XOgmHRXKajhtzNwyPGnND3xRN 🗄 mixing/EQ
* _choke point_: playing pad Y cuts off playback of pad X https://www.youtube.com/watch?v=rNsdlJ4I3jk 2:15
* _choke group_: any sample in group will cut off any other sample in group https://www.youtube.com/watch?v=H-YquBXHasE 6:15
* swing https://www.ableton.com/en/blog/humanize-your-drums/ 🗄 arpeggiator
* tuplets https://www.youtube.com/watch?v=nTz8Bjg_9UY 6:00
* can click in but better to use pad to capture your own sense of time https://www.youtube.com/watch?v=_Obkt_ldSoE
> buy a pad controller once you get further w/ programming
* rock https://www.youtube.com/watch?v=BwivarLKKAU&list=PLIiejGE6XOgmHRXKajhtzNwyPGnND3xRN&index=4 https://www.youtube.com/watch?v=dvzJErzWJj4&list=PLIiejGE6XOgmHRXKajhtzNwyPGnND3xRN&index=7 https://www.youtube.com/watch?v=QoUfU7Ujtnw

saving
* save presets and samples to project folder
* checkpoint w/ 'save as copy' https://www.youtube.com/watch?v=M6lIz4Fyc2w
* export: how to https://www.youtube.com/watch?v=JTtSihQ8QX0 no mp3 for Lite 9 but can convert using VLC https://www.youtube.com/watch?v=JTtSihQ8QX0 mp3 in Live 10 https://help.ableton.com/hc/en-us/articles/115000331090-Using-MP3-files

## scratch

## track

## mix

# ZA

DAW design https://reverb.com/news/home-recording-basics-ii-choosing-your-first-audio-interface-and-daw
* _Ableton_: $350; live performance, origins in techno, started as sampler https://www.reddit.com/r/ableton/comments/k1kj3o/is_ableton_11_worth_it_for_you_and_your_workflow/gdslmye couldn't do comping before version 11 https://www.youtube.com/watch?v=qMEjQJSgZWU 17:05 https://www.reddit.com/r/ableton/comments/9yxbxm/can_someone_explain_to_me_how_after_all_of_these/
* _Audacity_: $0; https://en.wikipedia.org/wiki/Audacity_(audio_editor) http://aosabook.org/en/audacity.html
* _Pro Tools_: subscription-only; digital tape machine https://www.youtube.com/watch?v=rMuKUft-4vY https://www.youtube.com/watch?v=f3QsebNUuAc
* _Fruity Loops_: $200; trap https://reverb.com/news/how-generations-of-beatmakers-evolved-with-fruity-loops-and-fl-studio https://splice.com/blog/gross-beat-the-secret-weapon/
* _Logic_: $200; cool how you can label song form https://www.youtube.com/watch?v=sBy_oUGnE-Q
* _Reaper_: $0; hacker mentality https://reasonablypolymorphic.com/blog/linux-daw/ https://news.ycombinator.com/item?id=23438459
* _Serato DJ_: number one in this space https://www.youtube.com/watch?v=EaT7C3cQMnc
* _Serato Studio_: subscription-only; simpler Ableton
* can combine https://reverb.com/news/how-to-combine-2-daws-with-rewire

automation https://www.youtube.com/watch?v=hukVniFeCi8 https://www.youtube.com/watch?v=ZFXrs2-s_YI
* _automation_: savings a change (in EQ/levels/effect) over time [Franz 184]
* toggle w/ `a` https://www.youtube.com/watch?v=iI06kTUtNDg 2:15
* howto https://www.youtube.com/watch?v=IdQYUk8w5jM 0:30 https://www.youtube.com/watch?v=riOD-fnyCsg 5:15 https://www.youtube.com/watch?v=QwSfQM_ES24 4:15
* can automate volume per clip https://www.youtube.com/watch?v=xdwZpIpN6ys 3:50
* _envelope_: instance of automation https://www.youtube.com/watch?v=IdQYUk8w5jM
* _modulation_: 

misc
* sends and returns https://www.youtube.com/watch?v=SzTGuvAqqfU
* take lane https://www.youtube.com/watch?v=PDO3pLFbmYs&list=PLIiejGE6XOgmHRXKajhtzNwyPGnND3xRN&index=2
* _set_: current state (audio/MIDI, settings, config) https://www.ableton.com/en/manual/live-concepts/#4-2-live-sets
* create default set https://www.youtube.com/watch?v=-RzrcrMruFY
* _MPE_: glissando https://www.reddit.com/r/ableton/comments/k1kj3o/is_ableton_11_worth_it_for_you_and_your_workflow/gdqga3l
* _sample rate_: audio quality metric; uses hertz; 48k is good enough; higher rate is more CPU and disk usage
* _groove_: quantization settings; packs > core library https://www.youtube.com/watch?v=jvT8mNCKLDg 0:30
* _groove pool_: container for grooves; unavailable for Live 10 Intro but showed up in Live 11
* different bpm per scene https://www.youtube.com/watch?v=iI06kTUtNDg
* setup audio input https://www.youtube.com/watch?v=wENbeUNS-IA
* clock sync from Ableton to external https://www.youtube.com/watch?v=GR5V3XFQTyc
* sync https://www.youtube.com/watch?v=TOpzoS36_Sw&list=PLIiejGE6XOgm_iInCjfVc2Rd0ghl5zJAV&index=12
* file extensions: `.adv/g` MIDI `.wav/aif/alc` audio `.asd` created in dir of imported file, helps perf
* Bluetooth causes delays https://www.ableton.com/answers/live-9-and-latency-problem
* keep CPU usage below 75%; lower buffer size = lower latency = high load on CPU
* can transfer license to new machine https://forum.ableton.com/viewtopic.php?t=114514 https://www.reddit.com/r/ableton/comments/5dxh3e/what_is_the_best_way_to_transfer_your_entire/
* release cycle every 5 years https://community.mixedinkey.com/BlogPosts/the-history-of-ableton-live https://www.factmag.com/2018/01/17/ableton-announces-release-date-live-10/
* search is bad (can't grep docs, in-DAW query for 'metronome' returns nothing)

## devices

🔗 https://www.ableton.com/en/manual/live-audio-effect-reference/ https://www.ableton.com/en/live/compare-editions/

mixing
* _channel EQ_: EQ https://www.youtube.com/watch?v=aAwpVte261Y
* _EQ3_: similar to channel EQ https://www.ableton.com/en/manual/live-audio-effect-reference/#22-15-eq-three
* _EQ8_: smart EQ https://www.ableton.com/en/manual/live-audio-effect-reference/#22-14-eq-eight
* _frequency shifter_: dumb EQ
* _gate_: filter out frequency
> diff than auto filter? https://www.youtube.com/watch?v=rbuTKgcteKo 4:00
* _limited_: raise/lower volume
* _multiband dynamics_: EQ-esque; can solo frequency ranges
* _spectrum_: just use EQ
* _utility_: gain, pan, width (100% is stereo, 0% is mono) https://www.youtube.com/watch?v=jEXCEelPlEM 28:45

racks and signal flow https://www.ableton.com/en/manual/instrument-drum-and-effect-racks/
* _rack_: container for n devices into single user-defined device https://www.ableton.com/en/manual/instrument-drum-and-effect-racks/#18-3-looking-at-racks
* signal flow (chain) goes left to right https://www.ableton.com/en/manual/instrument-drum-and-effect-racks/#18-6-drum-racks
* rack types: drum, instrument, effects
* _drum rack_: less about signal flow and more about container for your kit https://www.ableton.com/en/manual/instrument-drum-and-effect-racks/#18-6-drum-racks
* _instrument rack_: bundle together instrument + settings, effects https://www.youtube.com/watch?v=Keafog2wB4E https://www.youtube.com/watch?v=TKH93Dck_X4 2:30
* adjust pitch, velocity of chop in drum rack https://www.youtube.com/watch?v=rNsdlJ4I3jk 1:55
* add samples to drum rack and save as preset https://www.youtube.com/watch?v=0t9M15n2iAA 1:00

other
* _arpeggiator_: same as clicking in 16ths but can change sync to free and subdivisions move from notational value to ms https://www.youtube.com/watch?v=Rg9LGrI3K0k 1:15 hold `cmd` while adjusting rate knob [ibid 1:45]
* _audio effect rack_: container for groups of effects so you can turn they on/off together https://www.youtube.com/watch?v=pCgJpy7B8rY https://www.youtube.com/watch?v=pCgJpy7B8rY
* _cabinet_: emulates live mic setup in room
* _drum buss_: compression https://www.youtube.com/watch?v=4LxhIE169x4
* _delay_: https://www.youtube.com/watch?v=Ss5yOq8nQK4
* _dynamic tube_: delay-esque
* _echo_: like delay but suite-only https://www.ableton.com/en/manual/live-audio-effect-reference/#22-13-echo
* _erosion_: add noise
* _external audio effect_: send signal from Ableton to outboard gear and then route back in; can route external signal through outboard w/out this though https://www.youtube.com/watch?v=K8P-SDSTgeU
> this kinda makes it seem like you can do it sans external audio effect https://www.youtube.com/watch?v=x_82OR2-FXg https://www.youtube.com/watch?v=mvVDnA7oqhU
* _looper_: 类似 Boss loop pedal
* _pedal_: distortion, fuzz https://www.ableton.com/en/manual/live-audio-effect-reference/#22-28-pedal
* _redux_: 8-bit sound
* _saturator_: adds warmth
* _tuner_: key detection https://www.youtube.com/watch?v=1hNvI6vZBAE tuning 808s https://www.youtube.com/watch?v=SW0BEXdeKaM 4:15

semantics
* _device_: instrument https://www.ableton.com/en/manual/working-with-instruments-and-effects/ https://www.youtube.com/watch?v=zcPkcRjPufI
* reference tracks https://www.youtube.com/watch?v=x3fMK4tHFA0
* formats: audio unit (mac) VST (mac/win) https://www.youtube.com/watch?v=N2VjFjUhlR4 1:40
* _preset_: device config 🗄 `categories>instrument`, `places>user-library`
* _pack_: devices + samples https://www.youtube.com/watch?v=TKH93Dck_X4
* _plugin_: third-party device https://reverb.com/news/what-is-a-plugin-the-basics
* can rent w/ payment counting towards overall price aka 'rent-to-own' https://support.splice.com/hc/en-us/categories/360000112288-Rent-To-Own

misc
* create default for new tracks https://www.youtube.com/watch?v=-RzrcrMruFY
* add device by selecting track and then just double clicking effect
* _hot swap_: find similar sound https://www.youtube.com/watch?v=_zm_6drHmVI
* _MaxForLive_: create devices; comes from Max/MSP (lang for programming music) https://en.wikipedia.org/wiki/Fennesz https://cycling74.com/products/max/ some Max stuff you don't get in the Ableton version https://cycling74.com/forums/question-about-max-for-live-vs-max https://splice.com/blog/10-free-max-for-live-devices/
* _Wavetable_: synth; only part of suite https://www.ableton.com/en/manual/live-instrument-reference/#24-10-wavetable

## plugins

🔍 https://reverb.com/software

* _plugin_: software version of effect or instrument [Franz 184]
* https://github.com/spotify/pedalboard

downloaded
* IK: amplitube; app (IK Product Manager app) downloads to 🗄 `/Library/Documentation/IK Multimedia/IK Product Manager`
* Native Instruments: guitar rig; app (Native Instruments native access) downloades to 🗄 `/Library/Audio/Plug-ins`
* Spitfire: labs, symphony orchestra; app (Spitfire audio) downloads to `~/Spitfire` and `/Library/Audio/Plug-ins/VST`

virtual instruments https://www.youtube.com/c/DavidHilowitzMusic/videos https://www.pianobook.co.uk/
* Spitfire has their own label https://sarecordings.com/ and magazine https://composer.spitfireaudio.com/en
* brass: https://www.youtube.com/watch?v=edkTRDz4sEs
* drums: Steinberg groove agent https://www.youtube.com/watch?v=Vyq_VDKlCK8 XLN addictive drums https://www.youtube.com/watch?v=PuXKxZq0lr4 15:45
* guitar: https://reverb.com/software/instruments/ample-sound/15-ample-sound-ample-guitar-m-lite-ii Native Instruments strummed acoustic https://www.youtube.com/watch?v=cj3XZCBkL6k 5:00 Orange Tree dracus https://www.youtube.com/watch?v=-D3_QDjwzaw https://www.orangetreesamples.com/products/evolution-electric-guitar-dracus
* keys: https://www.arturia.com/products/analog-classics/analoglab 📍 https://www.youtube.com/watch?v=HemIatG0W6A https://www.arturia.com/products the nice studios have Arturia https://sonicranch.com/adobe-bungalow https://www.meldaproduction.com/MonasteryGrand Arturia V8 https://www.youtube.com/watch?v=52ZVQovR_YY https://www.youtube.com/watch?v=ovHLyT-khf8
* percussion: https://www.youtube.com/watch?v=8Kf9kUml_tQ
* synth: Wavetable, Operator https://splice.com/blog/how-to-use-ableton-wavetable/ https://splice.com/blog/synth-pad-using-voice U-HE zebralette https://splice.com/blog/best-free-instrument-plugins/
* strings: Spitfire Audio labs https://splice.com/blog/best-free-instrument-plugins/ Ableton likes them https://www.ableton.com/en/live/all-new-features/
* vocals: all-purpose (Izotope nectar) emultate ribbon mic (Waves aphex aural exciter) https://reverb.com/news/how-to-get-the-nashville-sound-in-your-home-studio

amp sims https://blog.andertons.co.uk/learn/are-guitar-plugins-better-than-amps
* Ableton: lite (chorus, compression) https://www.youtube.com/watch?v=OM86Ya2HZ48 amp, cabinet https://www.youtube.com/watch?v=MkkrPGBaCpk
* Archetype gojira: can work for punk https://www.youtube.com/watch?v=N6gKWgpeB20
* Arturia fx: $400 https://splice.com/blog/guitar-effect-chain-arturia-fx-collection/
* IK amplitube: $200 or free version
* Positive Grid bias: $150: https://www.positivegrid.com/ Neely https://www.youtube.com/watch?v=k7I5lWzDWSI
* Native Instruments guitar rig: $200 or free version; Kenny Beats https://www.youtube.com/watch?v=Kfyr3sCV9zg 39:00 https://www.youtube.com/watch?v=k7I5lWzDWSI 9:40 Ableton presets

Native Instruments
* komplete start: instrument library, comes w/ guitar rig player edition
* kontakt: sample library, sampler https://www.youtube.com/watch?v=57ZGNpHG6xw&list=PLIiejGE6XOgm_iInCjfVc2Rd0ghl5zJAV&index=24 https://www.youtube.com/watch?v=ajrX3F_RrOQ&list=PLIiejGE6XOgm_iInCjfVc2Rd0ghl5zJAV&index=28 https://www.youtube.com/watch?v=N6wprMToxSg&list=PLIiejGE6XOgm_iInCjfVc2Rd0ghl5zJAV&index=33 https://www.youtube.com/watch?v=B2iEhJcrHxI&list=PLIiejGE6XOgm_iInCjfVc2Rd0ghl5zJAV&index=34
* komplete kontrol: interface to other NI bundles
* native access: native client necessary to download everything else

## sampling

🗄 `instruments.md` sampling
🔗 https://www.youtube.com/playlist?list=PLIiejGE6XOgkpI_qHtkbBSHXo_uB9Np2l
📹 https://www.youtube.com/user/Sandurz/videos

* _transient_: spike in volume https://reverb.com/news/home-recording-basics-part-ix-tips-to-prep-your-tracks-for-mixing
* _quantization_: align transient to rhymic grid https://www.youtube.com/watch?v=3FlbtZawNTs mathematical definition https://en.wikipedia.org/wiki/Quantization_(signal_processing) https://github.com/makeworld-the-better-one/dither
* https://www.youtube.com/watch?v=GzOGGLjauPQ&list=PLIiejGE6XOgmHRXKajhtzNwyPGnND3xRN&index=10
* Dilla https://www.youtube.com/watch?v=xA0vAqGZi44&list=PLIiejGE6XOgmHRXKajhtzNwyPGnND3xRN&index=12 https://www.youtube.com/watch?v=GfIGArKNrK0&list=PLIiejGE6XOgmHRXKajhtzNwyPGnND3xRN&index=14a https://www.youtube.com/watch?v=HG2yaePQox4&list=PLIiejGE6XOgmHRXKajhtzNwyPGnND3xRN&index=15 https://www.youtube.com/watch?v=Ngq54VDriAg&list=PLIiejGE6XOgmHRXKajhtzNwyPGnND3xRN&index=16
* _grid resolution_: rhythmic divisions of grid
* _transient marker_: https://www.youtube.com/watch?v=ef-p0-NF7Vs @ 1:45 https://www.youtube.com/watch?v=7wo4LY6jxcM 10:30
* _extract groove_: set global quantization according to particular instrument; aka groove template https://reverb.com/news/home-recording-basics-part-ix-tips-to-prep-your-tracks-for-mixing https://www.youtube.com/watch?v=evv8JbnPLCQ&list=PLIiejGE6XOgkShCD04vaHdgUgxZz_uPhg&index=15
* _timestretch_: change audio speed w/out changing pitch https://en.wikipedia.org/wiki/Audio_time_stretching_and_pitch_scaling warp (Ableton) flex time (Logic) pitch-n-time (Serato) Audacity https://www.reddit.com/r/Guitar/comments/3v4tql/how_to_slow_down_music_in_order_to_play_along/cxkczfe aka phase vocoder https://github.com/Muges/audiotsm/ https://librosa.github.io/librosa/generated/librosa.core.phase_vocoder.html?highlight=phase#r93e62eaec025-1 https://github.com/haoyu987/phasevocoder https://duckduckgo.com/?q=python+phase+vocoder&ia=software aka time compression/expansion [Franz 176]

misc
* sample pack https://www.youtube.com/watch?v=w-UAKXLRr6M https://www.youtube.com/watch?v=lHtRw4dkBMY https://www.youtube.com/watch?v=45eMy3EjGGE
* extract vocals https://www.youtube.com/watch?v=Aq-RbMTsa40 acapella https://www.youtube.com/watch?v=nm79yobcz_Q
* detect BPM https://www.youtube.com/watch?v=yEGqT_Xcezc
* mount sample dir https://www.youtube.com/watch?v=0t9M15n2iAA 0:30
* packs https://splice.com/sounds/sound-doctrine/the-revival
* Congo rainforest https://elephantlisteningproject.org/congo-soundscapes-public-database/

---

warp
* how to: manual (warp markers) https://www.youtube.com/watch?v=xaQX4cCZSdA auto (`preferences > record warp`; typically only do for song-length clips) https://courses.noiselab.io/courses/147723/lectures/2193054 @ 1:20
* _warp markers_: set `cmd i` unselect `esc`
* _warp modes_: algo for warp; beats (drums) tone (vocals, bass) texture (ambience) complex (for entire songs; introduced in Ableton 10 https://help.ableton.com/hc/en-us/articles/206407024-Live-Intro-Features-) complex pro (uses more CPU [24.8.8]) https://www.ableton.com/en/manual/audio-clips-tempo-and-warping/#9-3-adjusting-for-good-stretching-quality

---

> it should take this long https://www.youtube.com/watch?v=OzDpTEOxeX4
https://www.youtube.com/watch?v=OhQeExkQnbE
https://www.youtube.com/watch?v=-4BkgL7Sa0o
https://www.youtube.com/watch?v=GrkPX6q9Stg
* https://www.youtube.com/watch?v=kadQYV3yLwU

sampling
* create rack (container for chops) https://www.youtube.com/watch?v=zoAoddp0t6c https://www.reddit.com/r/ableton/comments/ilxfki/thank_you_for_all_of_the_feedback_i_have_released/
* drag rack to track https://www.youtube.com/watch?v=4YFx7kNSpzU @ 1:05 
* map rack to controller https://www.youtube.com/watch?v=zoAoddp0t6c @ 1:00
* put chops on rack https://www.youtube.com/watch?v=vDa7NhPkjII
* 'save preset' in the left side of the clip view https://www.youtube.com/watch?v=zr-1SgidL-I 3:00
* create clip view w/ double click 
* record (record quantization, set metronome to count in)
* https://www.youtube.com/watch?v=45eMy3EjGGE&list=PLIiejGE6XOgmHRXKajhtzNwyPGnND3xRN&index=17&t=1s

process
* warp https://www.youtube.com/watch?v=1I59CN7NKIg&list=PLIiejGE6XOgm_iInCjfVc2Rd0ghl5zJAV&index=10 https://www.youtube.com/watch?v=tlsRVC72hx4&list=PLIiejGE6XOgm_iInCjfVc2Rd0ghl5zJAV&index=11
* chop https://www.youtube.com/watch?v=H07OJpKqSV0 https://www.youtube.com/watch?v=sXp_cHMXhVM https://www.youtube.com/watch?v=vrILeD43SkM https://www.youtube.com/watch?v=09g3q79XNh8
* determine note https://www.youtube.com/watch?v=Wpxca-6W4iI @ 2:00
* 📍 re-slice https://youtu.be/81RNL8Hw9h8

chop
* manual https://www.youtube.com/watch?v=vDa7NhPkjII https://music.stackexchange.com/q/86315/56021 https://forum.ableton.com/viewtopic.php?f=1&t=235118
* Simpler https://www.youtube.com/watch?v=ef-p0-NF7Vs 1:15 https://www.youtube.com/watch?v=jtH61_4r6PQ&list=PLIiejGE6XOgm_iInCjfVc2Rd0ghl5zJAV&index=8 does synth https://www.youtube.com/watch?v=HEORiX0vyTk&list=PLIiejGE6XOgm_iInCjfVc2Rd0ghl5zJAV&index=25
* sampler: Serato https://www.youtube.com/watch?v=EaT7C3cQMnc https://www.youtube.com/watch?v=EaT7C3cQMnc
* Decent Sampler https://www.youtube.com/watch?v=UxPRmD_RNCY&list=PLIiejGE6XOgm_iInCjfVc2Rd0ghl5zJAV&index=22
* other (slice-to-MIDI on Standard, Sampler on Suite)

* stretch out / freeze single note https://www.reddit.com/r/ableton/comments/3xa4rn/how_to_stretchwarp_a_very_short_audio_clip_into_a/
* https://soundfly.com/courses/how-to-make-your-first-beat-in-ableton-live/lessons/creating-and-using-a-drum-rack https://www.youtube.com/channel/UC97dIa6c0oux0SazHHVnoCA/videos
* https://www.youtube.com/watch?v=PmATlGuMOqc&lc=UgwXZdDKk8-EwajyCB94AaABAg https://www.youtube.com/channel/UC9tj-S42S2MvCkhQKtHJ0Xw/videos https://www.youtube.com/watch?v=4DtYett8BKo https://www.youtube.com/watch?v=0f2KrrzsuUo just add clips to scene https://www.reddit.com/r/ableton/comments/9c2nr0/does_anyone_know_how_fkj_used_the_apc40_mkii_in/ https://soundfly.com/courses/capturing-and-warping-samples-in-ableton-live https://www.youtube.com/watch?v=QdVEez20X_s 2:30 https://www.youtube.com/watch?v=-OtCo-6hO5w https://www.youtube.com/watch?v=H07OJpKqSV0 https://www.youtube.com/watch?v=ef-p0-NF7Vs https://www.youtube.com/watch?v=kZCDGmOP8XY https://www.youtube.com/watch?v=xaQX4cCZSdA https://soundfly.com/courses/capturing-and-warping-samples-in-ableton-live
