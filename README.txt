I - Description
I made this plugin for my community Zombie4Ever.eu and was allowed to share it.
Will play a song(Youtube or others) while the map change. Player can enable/disable this by typing !ms. The preference will be saved.
Force a map change will not work.

II - Cvars
"drapi_mapchange_sound_timer" set on panel will play the sound 1 seoncde before the map change otherwise you can set a time after the win panel popup. This number should be less than the "mp_match_restart_delay" CSGO cvar.

III - Configs
"addons/sourcemod/configs/drapi/mapchange_sounds.cfg"

"Sounds"
{
    "Sounds"
    {
            "Mapchange"
        {
            "1"                 "https://soundcloud.com/spinnin-deep/martin-solveig-1-feat-sam-whiteclub-mix#t=0:47 | Martin Solveig - +1 (feat. Sam White)(Club Mix)"
            "2"                 "https://soundcloud.com/doornrecords/tony-junior-dropgun-cobra-sander-van-doorn-identity-premiere-available-june-22#t=0:53 | Tony Junior & Dropgun - Cobra"
            "3"                 "https://soundcloud.com/skinkofficial/showtek-satisfied-feat-vassy-preview#t=0:53 | Showtek - Satisfied (feat. VASSY)"
            "4"                 "https://soundcloud.com/thero-official/ill-be-good#t=0:00 | Jaymes Young - I'll Be Good (Thero Remix)"
        }
    }
}  
The correct way: <URL>space | space <TITLE>. Between the url don't forget space and add the symbol |
Put you url song like the example. The song will be chosen randomly.
Note youtube have sometimes adverts.

IV - Videos
How it looks

V - Bugs
FIX - I didn't try but I think it will be a mess with plugin who play song at round end like AbNeR Round End Sounds

VI - Credits
Credits to hannes96 for the idea.

VII - Services
Youtube: OK. Note sometimes you have commercials ads.
Soundcloud: OK. Note you need to put #t=0:00 at the end of url to play the song automatically.

VIII - Changelogs
V1.0.3
-You can set the Title of the song in the "addons/sourcemod/configs/drapi/mapchange_sounds.cfg"
-Added one translation sentence

V1.0.2
-Added cvar "drapi_mapchange_sound_timer" set on panel will play the sound 1 seconde before the map change otherwise you can set a time after the win panel popup. This number should be less than the "mp_match_restart_delay" CSGO cvar.

V1.0.1
-Will turn off all sounds possible(game sounds, map sounds, plugins sounds) before playing the mapchange song.