loadstring(game:HttpGet(("https://raw.githubusercontent.com/daucobonhi/Ui-Redz-V2/refs/heads/main/UiREDzV2.lua")))()

       local Window = MakeWindow({
         Hub = {
         Title = "CUONGNE",
         Animation = "2010"
         },
        Key = {
        KeySystem = false,
        Title = "Key System",
        Description = "",
        KeyLink = "",
        Keys = {"1234"},
        Notifi = {
        Notifications = true,
        CorrectKey = "Running the Script...",
       Incorrectkey = "The key is incorrect",
       CopyKeyLink = "Copied to Clipboard"
      }
    }
  })

       MinimizeButton({
       Image = "http://www.roblox.com/asset/?id=128933802535491",
       Size = {60, 60},
       Color = Color3.fromRGB(10, 10, 10),
       Corner = true,
       Stroke = false,
       StrokeColor = Color3.fromRGB(255, 0, 0)
      })
      
------ Tab
     local Tab1o = MakeTab({Name = "MAIN"})     
     
-------TOGGLE 

    
------- BUTTON
    
    AddButton(Tab1o, {
     Name = "fram",
    Callback = function()
	  game.Players.LocalPlayer:Kick("Bị ban 9999 ngày vì nói xấu anh cường đẹp zai")
  end
  })
----- Dropdown 


----- Section        

----- Paragraph 
                    
   Paragraph = AddParagraph(Farm, {"a", ""})
