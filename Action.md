Adguard
-------------
https://adguard.com/en/adguard-android

Start Action

>autoset://start/service?intent={"action":"android.intent.action.SEND","packageName":"com.adguard.android","className":"com.adguard.android.ServiceManager","ekey1":"ACTION","etype1":"i","evalue1":"2"}

Stop Action

>autoset://start/service?intent={"action":"android.intent.action.SEND","packageName":"com.adguard.android","className":"com.adguard.android.ServiceManager","ekey1":"ACTION","etype1":"i","evalue1":"4"}

----------

Adguard - new version Automation function
-------------
https://adguard.com/en/adguard-android

Start Action

>autoset://start/broadcast?intent={"action":"start","packageName":"com.adguard.android","className":"com.adguard.android.receivers.AutomationReceiver","ekey1":"password","etype1":"s","evalue1":"Your PIN code"}

Stop Action

>autoset://start/broadcast?intent={"action":"stop","packageName":"com.adguard.android","className":"com.adguard.android.receivers.AutomationReceiver","ekey1":"password","etype1":"s","evalue1":"Your PIN code"}

----------

Poweramp
-------------
https://play.google.com/store/apps/details?id=com.maxmpz.audioplayer

Play Action

>autoset://start/service?intent={"action":"com.maxmpz.audioplayer.API_COMMAND","packageName":"com.maxmpz.audioplayer","className":"com.maxmpz.audioplayer.player.PlayerService","ekey1":"cmd","etype1":"i","evalue1":"1"}

Pause Action

>autoset://start/service?intent={"action":"com.maxmpz.audioplayer.API_COMMAND","packageName":"com.maxmpz.audioplayer","className":"com.maxmpz.audioplayer.player.PlayerService","ekey1":"cmd","etype1":"i","evalue1":"2"}

----------

Onkyo HF Player
-------------
https://play.google.com/store/apps/details?id=com.onkyo.jp.musicplayer

Play/Pause Toggle Action

>autoset://start/service?intent={"action":"com.onkyo.jp.musicplayer.MusicPlayerService.ACTION_PLAY_TOGGLE","packageName":"com.onkyo.jp.musicplayer","className":"com.onkyo.jp.musicplayer.service.MusicPlayerService"}


----------

Blackplayer EX
-------------
https://play.google.com/store/apps/details?id=com.kodarkooperativet.blackplayerex

Play Action

>autoset://start/service?intent={"ekey1":"remote_action","etype1":"i", "evalue1":"22","packageName":"com.kodarkooperativet.blackplayerex","className":"com.kodarkooperativet.blackplayerex.MusicService"}

----------

Melon
-------------
https://play.google.com/store/apps/details?id=com.iloen.melon

Play/Pause Toggle Action

>autoset://start/service?intent={"action":"com.iloen.melon.intent.action.commandservice.add","packageName":"com.iloen.melon","className":"com.iloen.melon.playback.CommandService","data":"melonapp://service=nowplaylist"}

----------

Bugs Music
-------------
https://play.google.com/store/apps/details?id=com.neowiz.android.bugs

Play Action

>autoset://start/service?intent={"action":"com.neowiz.android.bugs.musicservicecommand.play","packageName":"com.neowiz.android.bugs","className":"com.neowiz.android.bugs.service.MusicService"}
