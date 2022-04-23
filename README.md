# chi
 Repository for the Cultural and Heritage Identity mod
 
 This mod is intended as a framework for other mod teams that wish to use the Cultural and Heritage Identity doctrines that I made a while back for the Elder Kings II total conversion mod.
 
 It is *NOT* intended for standalone use.
 
 While there is a fallback generic assignment of the "No Identity" doctrine, it is still recommended to manually add the doctrine in each of your religion files.
 
 If you include this mod into your own one, feel free to modify whatever you want! It is just a framework, the gritty details of how it works in your mod is up to you :)
 
 ## Importing Cultural and Heritage Identity into your mod
 You can import this mod and use it alongside your own, keeping them separated and adding your own edits and effects in the CHI mod itself. That will make it easy to pull any update, but might mess with your own edits from time to time.
 
 You can also copy the files in the CHI directory (common/ and localization/ folders at time of writing) into your own mod. This will make keeping up with the main framework a bit more tedious, but might be easier for your team.
 
 ## What is left for me (or my team) to do?
 It depends on how many vanilla files you edit. Should both your mod and CHI modify the same files, you will need to manually merge them together, although I try to make it as easy as possible. You can find in the next section which vanilla files are edited.
 
 
 Once that is done, your main task will be to tie your faiths to your culture.
 
 To do that, you can refer to common/religion/religions/\_chi\_religions.info and common/on_action/chi\_game\_start\_on\_action.txt
 
 The general idea is to specific in the religion files which culture your faiths need to use, and to link the culture and the faith when the game starts.
