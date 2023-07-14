Options: Information about the patch
==
### [YouTube](https://github.com/inotia00/revanced-patches/tree/revanced-extended#-comgoogleandroidyoutube)

### [YouTube Music](https://github.com/inotia00/revanced-patches/tree/revanced-extended#-comgoogleandroidappsyoutubemusic)

### [Reddit](https://github.com/inotia00/revanced-patches/tree/revanced-extended#-comredditfrontpage)

### [Vanced MicroG](https://github.com/inotia00/revanced-patches/tree/revanced-extended#-commgoogleandroidgms)

Patches that need to be included or excluded depending on the situation
==

### If you want the ROOT version:
- Don't Select MicroG Support
- Don't Select Custom Package Name

Using CLI: `-e microg-support`(YouTube) or `-e music-microg-support`(YouTube Music)

### If you want the MMT Icon:
- Select Custom Branding Icon MMT
- Don't select Custom Branding Icon Revancify Red
- Don't select Custom Branding Icon Revancify Blue

Using CLI: `-i custom-branding-icon-mmt` `-e custom-branding-icon-revancify-red` `-e custom-branding-icon-revancify-blue`

### If you want the Revancify Red Icon:
- Select Custom Branding Icon Revancify Red
- Don't select Custom Branding Icon MMT
- Don't select Custom Branding Icon Revancify Blue


Using CLI: `-i custom-branding-icon-revancify-red` `-e custom-branding-icon-mmt` `-e custom-branding-icon-revancify-blue` 

### If you want the Revancify Blue Icon:
- Select Custom Branding Icon Revancify Blue
- Don't select Custom Branding Icon MMT
- Don't select Custom Branding Icon Revancify Red


Using CLI: `-i custom-branding-icon-revancify-blue` `-e custom-branding-icon-mmt` `-e custom-branding-icon-revancify-red`

### If you want the Original YouTube Icon:
- Don't select Custom Branding Icon MMT
- Don't select Custom Branding Icon Revancify Red
- Don't select Custom Branding Icon Revancify Blue

Using CLI: `-e custom-branding-icon-revancify-blue` `-e custom-branding-icon-mmt` `-e custom-branding-icon-revancify-red`


### If you want a Custom App Name (Default: ReVanced Extended):
- Select Custom Branding Name

Using CLI: `-i custom-branding-name`

※ You can change the app name directly by editing `options.json` in an editor.


### If you want the Original YouTube App Name:
- Don't select Custom Branding Name

Using CLI: `-e custom-branding-name`


### If you want the stock YouTube Theme:
- Don't select Theme
- Don't select Materialyou

Using CLI: `-e theme` `-e materialyou`


### If you want a custom Theme (Default: Black):
- Select Theme
- Don't select Materialyou

Using CLI: `-i theme` `-e materialyou`

※ You can change the theme by editing `options.json` in an editor and entering the desired HEX code.

### If you want MaterialYou Theme (Only for Android 12+):
(Material Light Theme + Material Dark Theme)
- Don't select Theme
- Select Materialyou

Using CLI: `-e theme` `-i materialyou`

### If you want MaterialYou Theme (Only for Android 12+) + Custom Theme (Default theme: Black):
(Material Light Theme + Custom Dark Theme)
- Select Theme
- Select Materialyou

Using CLI: `-i theme` `-i materialyou`

※ You can change the theme by editing `options.json` in an editor and entering the desired HEX code.

### If you want to Force Premium Header:
- Select Force Premium Heading

Using CLI: `-i force-premium-heading`

※ Even if you do not select this patch option, you can toggle the Premium Header on/off in the Layout settings.

※ If you select this patch option, the Premium Header is enforced and the Premium Header toggle is removed from the Layout settings.

### If you want the Splash Animation:
- Select Add Splash Animation
- Don't select Custom Branding Icon MMT
- Don't select Custom Branding Icon Revancify Red
- Don't select Custom Branding Icon Revancify Blue 

Using CLI: `-i add-splash-animation` `-e custom-branding-icon-revancify-blue` `-e custom-branding-icon-mmt` `-e custom-branding-icon-revancify-red`
