# Add this mod to Stellaris

Go to C:\Users\\<User Name\>\Documents\Paradox Interactive\Stellaris\mod\

1. Put a new folder in there with "gurkonier_variety" as folder name.

2. Put a file "gurkonier_variety.mod" in there with the content
```
version="0.1"
tags={
	"Graphics"
}
name="Gurkonier Variety"
supported_version="2.8.1"
path="C:/Users/<User Name>/Documents/Paradox Interactive/Stellaris/mod/gurkonier_variety"
remote_file_id="2376791378"
```

1. Pull this repository inside the "gurkonier_variety" folder.



# Add new category

1. In ./flags/ add a new folder with your category as an id. (Not the display name. For example if you want a category "My Flags" add a "my_flags" folder there)
2. In ./localisation/ open the gurkonier_variety_l_\<language\>.yaml and add a new category as follow:
```
    FLAG_CATEGORY_<category_id>:<increment this number> "<category display name>"
```
3. Do this for every language.
   
    You may add new languages by adding a file called gurkonier_variety_l_\<language\>.yaml and changing the first line l_\<language\> to your language.

# Add an Icon
1. Create a new Icon as .png or .jpg with the size 128x128 or resize a downloaded Icon
2. If not already done, make the icon black and white. All black parts will be transparent and all the white parts will be golden.
3. Go to https://9kenm.github.io/stellaris-emblem-maker/ and drag your image file in there.
4. Download the emblem via the "Download Emblems" Button.
5. Go to ./flags/\<category\>/ and drag the content of the downloaded zip into this folder.

If you want to rename this file (because the name already exists) rename every file in the root-, small- and map-folder.