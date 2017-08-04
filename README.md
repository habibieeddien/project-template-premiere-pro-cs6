### Project Template untuk Adobe Premiere Pro CS6 ###

* HDV Frame Size : 1280 x 720 (standard recomended)

* Best settings editing dan export untuk Youtube, Vimeo.

* Frame Rate : 29,7 FPS


### Struktur Folder ###

* `assets` : untuk menyimpan seluruh asset video

* `assets\audios` : untuk menyimpan asset file audio *Narator/Vocal* (.mp3, .ogg, .wav)

* `assets\bgm` : untuk menyimpan asset file *Background Music* (.mp3, .ogg, .wav, .mp4)

* `asset\docs` : untuk menyimpan asset file Storyboard, Storyline, Scenario, Scripting (.doc, .docx, .ppt, .pptx)

* `asset\images` : untuk menyimpan asset file Logo, Icon, Image, Panorama, Bumper (.png, .jpg, .jpeg, .psd)

* `asset\sfx` : untuk menyimpan asset file Sound Effect, Button Effect, Text Effect, Moving, Sliding, Showing (.mp3, .ogg, .wav)

* `asset\videos` untuk menyimpan asset file Video (.mp4, .mov, .avi, .3gp, .mpeg)


### Struktur Project Adobe Premiere Pro CS6 Workspace ###

* `audios`

* `bgm`

* `images`

* `sequences` : berisi per bagian scene video, kemudian di satukan dalam *Main Scene*

* `sfx`

* `titles` : berisi text, shape, bumper

* `videos`


### Best Settings Export ###

File > Export > Media (Ctrl + M - windows)

**Export Settings**

Format : H.264

Preset : HD 720p 29.97

Output Name : Ubah nama file hasil export (beri versi misal: v1.0, v1.2, dst), dan letakkan di folder project

*Video Tab Settings*

Video size : 1280 x 720

Aspect : Square Pixels (1.0)

Profile : High

Level : 5.1

Checklist : *Render at Maximum Depth*

Bitrate Encoding : VBR, 2 pass

Target Bitrate : 18 Mbps

Max. Bitrate : 18 Mbps

*Audio Tab Settings*

Audio Codec : AAC

Sample Rate: 48000 Hz

Channels : Stereo

Audio Quality : High

Bitrate : 256 kbps

*Penting* : checklist `Use Maximum Render Quality`

Preview hasil export dapat dilihat di samping kiri. Jika semua sudah cocok, lakukan *Export*. Estimasi file size dapat dilihat pada `Estimed File Size`.


### Catatan Penting ###

* Terkadang semua settings dalam template ini tidak dapat muncul disebabkan *video codec* dalam Sistem Operasi belum lengkap.

* Dapat menginstall terlebih dahulu seperti QuickTime, MPC, VLC.