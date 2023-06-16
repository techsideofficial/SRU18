# SRU18 

* A merge of mine and mattkc's Sonic Runners Decomps but also a port of the decomps to Unity 2018

# How to setup silly Sonic Runners Decompilation

By: SnesFX/TyDev

1. Download files from repo (duh!1111)

2. Extract files from repo (duh x2!!1111)

3. Download the files from [here](https://github.com/itsmattkc/RunnersAssetBundleDecomp)

4. Open the zip and Open the RunnersAssetBundleDecomp-master folder

5. Copy the files

6. Go to wherever you extracted the decomp and go into the Assets folder

7. Make a folder called AssetBundles

8. Paste Everything there

9. Download Unity 2018.2.19f1 if you don't have it

10. Open the project in Unity

11. Build or Download [Outrun](https://github.com/fluofoxxo/outrun)

12. Navigate to Assets/Scripts/ and open NetBaseUtil.cs with VSC
    
13. Find the variable `mActionServerUrlTable `
    
14. Edit every string in the `mActionServerUrlTable` array to `http://<IP>:<PORT>/` where `<IP>` is replaced by the IP for your instance and `<PORT>` is replaced by the port for your instance (Default: 9001)
    
15. Repeat step 14 for `mSecureActionServerUrlTable`
    
16. If you have an assets server, use its IP and port to replace the values in `mAssetURLTable` and `mInformationURLTable` to `http://<IP>:<PORT>/assets/` and `http://<IP>:<PORT>/information/` respectively
    
17. Click File -> Save File
    
18. Enjoy!

# Note

* This is still a work in progress and this is being done by one person only, so expect development to be slow.

# Credits

* SnesFX - Decomp

* MattKc - Decomp
