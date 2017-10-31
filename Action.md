## Onkyo HF Player Play/Pause Toggle 
autoset://start/service?intent={"action":"com.onkyo.jp.musicplayer.MusicPlayerService.ACTION_PLAY_TOGGLE","packageName":"com.onkyo.jp.musicplayer","className":"com.onkyo.jp.musicplayer.service.MusicPlayerService"}

## Blackplayer EX Play Action
autoset://start/service?intent={"ekey1":"remote_action","etype1":"i", "evalue1":"22","packageName":"com.kodarkooperativet.blackplayerex","className":"com.kodarkooperativet.blackplayerex.MusicService"}

## Bugs Music Play Action
autoset://start/service?intent={"action":"com.neowiz.android.bugs.musicservicecommand.play","packageName":"com.neowiz.android.bugs","className":"com.neowiz.android.bugs.service.MusicService"}

## Poweramp Play/Pause Toggle Action
#### Play
autoset://start/service?intent={"action":"com.maxmpz.audioplayer.API_COMMAND","packageName":"com.maxmpz.audioplayer","className":"com.maxmpz.audioplayer.player.PlayerService","ekey1":"cmd","etype1":"i","evalue1":"1"}
#### Pause
autoset://start/service?intent={"action":"com.maxmpz.audioplayer.API_COMMAND","packageName":"com.maxmpz.audioplayer","className":"com.maxmpz.audioplayer.player.PlayerService","ekey1":"cmd","etype1":"i","evalue1":"1"}

## Adguard Start/Stop Action
#### Start
autoset://start/service?intent={"action":"android.intent.action.SEND","packageName":"com.adguard.android","className":"com.adguard.android.ServiceManager","ekey1":"ACTION","etype1":"i","evalue1":"2"}

#### Stop
autoset://start/service?intent={"action":"android.intent.action.SEND","packageName":"com.adguard.android","className":"com.adguard.android.ServiceManager","ekey1":"ACTION","etype1":"i","evalue1":"4"}


