# 7d2d-Auger-Fix-DF
This is fix for Auger Sound for Darkness Fall
If you Want use it in Vanila edit:
Sounds.xml
Search: "bullethitmetal"
<SoundDataNode name="bullethitmetal"> <AudioSource name="Sounds/AudioSource_Impact"/>
	<Noise ID="0" noise="20" time="3" muffled_when_crouched="0.65" heat_map_strength="0.1" heat_map_time="60"/>
	<AudioClip ClipName="Sounds/ImpactSurface/bullethitmeta1"/>
	<AudioClip ClipName="Sounds/ImpactSurface/bullethitmeta2"/>
	<AudioClip ClipName="Sounds/ImpactSurface/bullethitmeta3"/>
	<LowestPitch name="0.9"/>
	<HighestPitch name="1.0"/>
	<LocalCrouchVolumeScale value="1.0"/> <CrouchNoiseScale value="0.5"/> <NoiseScale value="1"/> <MaxVoices value="3"/> <MaxRepeatRate value="0.01"/> </SoundDataNode>

Change it for that:
<SoundDataNode name="bullethitmetal"> <AudioSource name="Sounds/AudioSource_WeaponFire"/> <NetworkAudioSource name="Sounds/AudioSource_WeaponFire_Network"/>
	<Noise ID="0" noise="20" time="3" muffled_when_crouched="0.65" heat_map_strength="0.1" heat_map_time="60"/>
	<AudioClip ClipName="Sounds/Weapons/Ranged/Pistol/pistol_s_fire1"/>
	<AudioClip ClipName="Sounds/Weapons/Ranged/Pistol/pistol_s_fire2"/>
	<AudioClip ClipName="Sounds/Weapons/Ranged/Pistol/pistol_s_fire3"/>
	<LowestPitch name="0.9"/>
	<HighestPitch name="1.0"/>
	<LocalCrouchVolumeScale value="1.0"/> <CrouchNoiseScale value="0.5"/> <NoiseScale value="1"/> <MaxVoices value="3"/> <MaxRepeatRate value="0.01"/> </SoundDataNode>

Do that same for: "bullethitstone"

I hope I helped :]
Cheer Reflexuss
