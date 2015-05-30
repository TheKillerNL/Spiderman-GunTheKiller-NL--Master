How To Install this Gun to Your DarkRP 
Server DarkRP Version 2.6+
errors contact me on steam: http://steamcommunity.com/profiles/76561198042717456
Place this addon in your addons folder

Spiderman Job PLace your own model and you are done 
Configure
Place this Code in jobs.lua from darkpmodification-master/lua/darkrpcustomthings/jobs.lua 

Tip! Edit jobs.lua with Notepad++
--------------------------------------------------------------------------------	
     TEAM_SPIDERMAN = DarkRP.createJob("Spiderman", { -- That's TEAM_PIRATE (Used for like AddCustomDoorgroup or Add to only that group to a door. Also, never use the same TEAM_)
        color = Color(90, 30, 255, 10), -- Chat / Scoreboard Color
        model = "models/player/....", -- Model; to add multiple use  {"models/../model1.mdl","models/../model2.mld},  NOTE the extra comma after the bracket.
        description = [[Im Spiderman i Fly And fly and help people with my glock :) BUY SPIDERMAN GUN IN THE SHOP CATERGORY SHIPMENTS]], --Description for Job.
        weapons = {"weapon_glock2", "spiderman's_swep"}, -- Weapons for a job. Seperate them with a "," eg: "med_kid", "armor_kit" always finish the last one without a ","
        command = "spiderman", --Chat command for job. Don't use the same as another teams.
        max = 2, -- Maximum amount of players for this job.
        salary = 100, -- The salary they get paid.
        admin = 0, -- Requires Admin? 1 for yes, 0 for no.
        vote = false, -- Do they need to vote? true for yes, false for no.
        hasLicense = false, -- Do they have a license for weapons?
     })