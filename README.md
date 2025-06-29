# GUIDE FOR ANYONE HAVING AN UNSUPPORTED FILE FORMAT IN THEIR DANCES FOLDER

1. Pick any song you wanted and download it.
2. Head over to File Explorer, which you know where Downloads are.
3. Select a file, copy/cut it, or drag it over to the Dances folder.
4. Once it has been applied, head over to your executor.
5. Search for any "Sound69.SoundId = customasset("")" you like to put
-- Example
              local function stopanim()
           if loopsplaying>0 then 
                loopsplaying-=1
           end
            playanother = true 
            playanother = true 
            playanother = true 
            playanother = true 
            sound69.PlaybackSpeed = 1
            if playbacktrack == true then 
                           if lol ~= true then 
            sound69.SoundId = customasset("Dances/MIX. 02 - BOTHERED!.ogg") <--- This one!
                else 
                      sound69.SoundId = customasset("Dances/MIX. 02 - BOTHERED!.ogg")  <--- And, this one!
                end
            sound69.Volume = .75
            else 
                sound69:Stop()
            end
6. Rename the customasset("") and copy the entire audio file's name.
7. Once you had it applied, you can test it out the script in Just a Baseplate.
