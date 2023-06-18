local expperlevel = {

	[1] = {exp = 1000}


}


local humanskintypes = {

	[1] = Color3.new(1, 0.635294, 0.466667), -- White

	[2] = Color3.new(0.658824, 0.478431, 0.254902), -- Mixed

	[3] = Color3.new(0.52549, 0.301961, 0.14902), -- Brown

	[4] = Color3.new(0.227451, 0.129412, 0.0627451), -- Black

	[5] = Color3.new(1, 0.643137, 0.403922),

	[6] = Color3.new(0.705882, 0.466667, 0.258824),

	[7] = Color3.new(1, 0.752941, 0.54902),

}


local humanhairtypes = {

	[1] = {

		[1] = Color3.new(0.470588, 0.301961, 0.109804), -- White

		[2] = Color3.new(0, 0, 0), -- Mixed

		[3] = Color3.new(0.152941, 0.152941, 0.152941),

		[4] = Color3.new(1, 0.913725, 0.470588),

		[5] = Color3.new(0.835294, 0.564706, 0.564706), -- Brown

	},

	[2] = {

		[1] = Color3.new(0.219608, 0.137255, 0.0509804), -- White

		[2] = Color3.new(0, 0, 0), -- Mixed

		[3] = Color3.new(0.152941, 0.152941, 0.152941),

		[4] = Color3.new(1, 0.913725, 0.470588),

		[5] = Color3.new(0.835294, 0.564706, 0.564706), -- Brown

	},

	[3] = {

		[1] = Color3.new(0.133333, 0.0823529, 0.0313725), -- White

		[2] = Color3.new(0, 0, 0), -- Mixed

		[3] = Color3.new(0.152941, 0.152941, 0.152941),

		[4] = Color3.new(0.101961, 0.184314, 0.101961),

		[5] = Color3.new(0.211765, 0.14902, 0.266667), -- Brown
	},

	[4] = {

		[1] = Color3.new(0.133333, 0.0823529, 0.0313725), -- White

		[2] = Color3.new(0, 0, 0), -- Mixed

		[3] = Color3.new(0.152941, 0.152941, 0.152941),

		[4] = Color3.new(0.101961, 0.184314, 0.101961),

		[5] = Color3.new(0.211765, 0.14902, 0.266667), -- Brown


	},

	[5] = {

		[1] = Color3.new(0.133333, 0.0823529, 0.0313725), -- White

		[2] = Color3.new(0, 0, 0), -- Mixed

		[3] = Color3.new(0.152941, 0.152941, 0.152941),

		[4] = Color3.new(0.101961, 0.184314, 0.101961),

		[5] = Color3.new(0.211765, 0.14902, 0.266667), -- Brown

	},

	[6] = {

		[1] = Color3.new(0.133333, 0.0823529, 0.0313725), -- White

		[2] = Color3.new(0, 0, 0), -- Mixed

		[3] = Color3.new(0.152941, 0.152941, 0.152941),

		[4] = Color3.new(0.101961, 0.184314, 0.101961),

		[5] = Color3.new(0.211765, 0.14902, 0.266667), -- Brown

	},

	[7] = {


		[1] = Color3.new(0.470588, 0.301961, 0.109804), -- White

		[2] = Color3.new(0, 0, 0), -- Mixed

		[3] = Color3.new(0.152941, 0.152941, 0.152941),

		[4] = Color3.new(1, 0.913725, 0.470588),

		[5] = Color3.new(0.835294, 0.564706, 0.564706), -- Brown

	},

}

local Fishmanskintypes = {

	[1] = Color3.new(1, 0.654902, 0.235294), -- White

	[2] = Color3.new(0.658824, 0.282353, 0.215686), -- Mixed

	[3] = Color3.new(0.313725, 0.52549, 0.376471), -- Brown

	[4] = Color3.new(0.478431, 0.686275, 0.941176), -- Black

	[5] = Color3.new(0.596078, 0.560784, 1),

	[6] = Color3.new(0.654902, 0.705882, 0.423529),

	[7] = Color3.new(0.266667, 0.180392, 0.14902),

}

local Fishmanhairtypes = {

	[1] = {

		[1] = Color3.new(0.470588, 0.301961, 0.109804), -- White

		[2] = Color3.new(0, 0, 0), -- Mixed

		[3] = Color3.new(0.152941, 0.152941, 0.152941), -- Brown

	},

	[2] = {

		[1] = Color3.new(0.419608, 0.180392, 0.137255),-- White

		[2] = Color3.new(0, 0, 0), -- Mixed

		[3] = Color3.new(0.152941, 0.152941, 0.152941), -- Brown

	},

	[3] = {

		[1] = Color3.new(0.419608, 0.180392, 0.137255),-- White

		[2] = Color3.new(0, 0, 0), -- Mixed

		[3] = Color3.new(0.152941, 0.152941, 0.152941), -- Brown

	},

	[4] = {

		[1] = Color3.new(0.266667, 0.384314, 0.52549),-- White

		[2] = Color3.new(0, 0, 0), -- Mixed

		[3] = Color3.new(0.152941, 0.152941, 0.152941), -- Brown

	},

	[5] = {

		[1] = Color3.new(0.301961, 0.286275, 0.509804),-- White

		[2] = Color3.new(0, 0, 0), -- Mixed

		[3] = Color3.new(0.152941, 0.152941, 0.152941), -- Brown

	},

	[6] = {

		[1] = Color3.new(0.329412, 0.352941, 0.211765),-- White

		[2] = Color3.new(0, 0, 0), -- Mixed

		[3] = Color3.new(0.152941, 0.152941, 0.152941), -- Brown

	},

	[7] = {

		[1] = Color3.new(0.113725, 0.0784314, 0.0627451),-- White

		[2] = Color3.new(0, 0, 0), -- Mixed

		[3] = Color3.new(0.152941, 0.152941, 0.152941), -- Brown

	},

}


local MinkSkinTypes = {

	Cat = {

		[1] = Color3.new(0.513725, 0.513725, 0.513725), -- White

		[2] = Color3.new(1, 1, 1), -- Mixed

		[3] = Color3.new(0.890196, 0.592157, 0.345098), -- Brown

		[4] = Color3.new(0.156863, 0.141176, 0.109804), -- Black

		[5] = Color3.new(0.117647, 0.117647, 0.117647),

		[6] = Color3.new(0.196078, 0.113725, 0.231373),

	},

	Bull = {

		[1] = Color3.new(0.137255, 0.137255, 0.137255), -- White

		[2] = Color3.new(1, 1, 1), -- Mixed

		[3] = Color3.new(0.188235, 0.129412, 0.0784314), -- Brown

		[4] = Color3.new(0.156863, 0.0352941, 0.0352941), -- Black

		[5] = Color3.new(0.384314, 0.384314, 0.384314),

		[6] = Color3.new(0.141176, 0.0784314, 0.168627),

	},

	Monkey = {

		[1] = Color3.new(0.368627, 0.215686, 0.105882), -- White

		[2] = Color3.new(1, 1, 1), -- Mixed

		[3] = Color3.new(0.666667, 0.364706, 0.145098), -- Brown

		[4] = Color3.new(0.137255, 0.137255, 0.137255), -- Black

		[5] = Color3.new(0.219608, 0.145098, 0.0784314),

		[6] = Color3.new(0.266667, 0.203922, 0.129412),

	},

	Bunny = {

		[1] = Color3.new(1, 0.964706, 0.709804), -- White

		[2] = Color3.new(1, 1, 1), -- Mixed

		[3] = Color3.new(0.0705882, 0.0392157, 0.0156863), -- Brown

		[4] = Color3.new(0.137255, 0.137255, 0.137255), -- Black

		[5] = Color3.new(0.117647, 0.0784314, 0.0431373),

		[6] = Color3.new(0.266667, 0.203922, 0.129412),

	}


}


local sizeRange = { min = .8, max = 1.2 } -- minimum and maximum possible size

local function doToDescendants(parent,className,toDo)
	for i,v in pairs(parent:GetDescendants()) do
		if v:IsA(className) then
			toDo(v)
		end
	end
end

--local partsToScale = {}

local function resize(character, sizeRatio)
    local partsToScale = {}

    -- Get all descendants of the character
    local descendants = character:GetDescendants()

    -- Iterate over all descendants
    for _, part in pairs(descendants) do
        -- Check if the part is of a type that we want to scale
        if part:IsA("Part") or part:IsA("MeshPart") or part:IsA("Attachment") or part:IsA("Bone") or part:IsA("Weld") or part:IsA("WeldConstraint") or part:IsA("Motor6D") then
            table.insert(partsToScale, part)
        end
    end

    -- Iterate over all parts to scale
    for _, part in pairs(partsToScale) do
        -- If the part is a BasePart (Part or MeshPart)
        if part:IsA("BasePart") then
            if not part:FindFirstChild("OriginalSize") then
                local originalSize = Instance.new("Vector3Value")
                originalSize.Name = "OriginalSize"
                originalSize.Value = part.Size
                originalSize.Parent = part
            end
            part.Size = part.OriginalSize.Value * sizeRatio
        end

        -- If the part is a JointInstance (Weld, WeldConstraint, or Motor6D)
        if part:IsA("JointInstance") then
            if not part:FindFirstChild("OriginalC0") then
                local originalC0 = Instance.new("CFrameValue")
                originalC0.Name = "OriginalC0"
                originalC0.Value = part.C0
                originalC0.Parent = part
            end
            if not part:FindFirstChild("OriginalC1") then
                local originalC1 = Instance.new("CFrameValue")
                originalC1.Name = "OriginalC1"
                originalC1.Value = part.C1
                originalC1.Parent = part
            end
            -- Keep the position part of C0 and C1 unchanged, scale only the orientation part
            part.C0 = CFrame.new(part.OriginalC0.Value.p * sizeRatio, part.OriginalC0.Value - part.OriginalC0.Value.p * sizeRatio)
            part.C1 = CFrame.new(part.OriginalC1.Value.p * sizeRatio, part.OriginalC1.Value - part.OriginalC1.Value.p * sizeRatio)
        end

        -- If the part is a Bone
        if part:IsA("Bone") then
            if not part:FindFirstChild("OriginalTransform") then
                local originalTransform = Instance.new("CFrameValue")
                originalTransform.Name = "OriginalTransform"
                originalTransform.Value = part.Transform
                originalTransform.Parent = part
            end
            -- Scale the position part of the Transform, keep the orientation part unchanged
            part.Transform = CFrame.new(part.OriginalTransform.Value.p * sizeRatio, part.OriginalTransform.Value - part.OriginalTransform.Value.p)
        end
    end
end




--local function checkresize(character)
--    local partsToScale = {}

--    for _, descendant in pairs(character:GetDescendants()) do
--        if descendant:IsA("Part") or descendant:IsA("MeshPart") or descendant:IsA("Attachment") or descendant:IsA("Weld") or descendant:IsA("Motor6D") or descendant:IsA("Bone") or descendant:IsA("WeldConstraint") then
--            table.insert(partsToScale, descendant)
--        end
--    end

--    return partsToScale
--end


local accessorySets = {
	"HeadAccessory",
	"FaceAccessory",
	"BackAccessory",
	"LeftArmAccessory",
	"LeftHandAccessory",
	"RightArmAccessory",
	"RightHandAccessory",
	"WaistAccessory",
	"HandAccessory"
}


local function updateaccessories(plr, data)
	local char = plr.Character
	local AccessoryModels = char:FindFirstChild("AccessoryModels")
	if not AccessoryModels then
		AccessoryModels = Instance.new("Folder")
		AccessoryModels.Name = "AccessoryModels"
		AccessoryModels.Parent = char
	end

	local function removeAccessoryType(accessoryType)
		for _, accparts in pairs(AccessoryModels:GetChildren()) do
			local accType = accparts:FindFirstChild("AccessoryType")
			if accType and accType.Value == accessoryType then
				accparts:Destroy()
			end
		end

		--for _,statsss in pairs(data:GetChildren()) do
		--	if accessorySets[statsss.Name] then
		--		char.Humanoid.MaxHealth += statsss:FindFirstChild("Boosts"):FindFirstChild("HealthBoost").Value
		--	end
		--end

		if accessoryType == "Head" then
			if char:FindFirstChild("SideFins") then char:FindFirstChild("SideFins").Transparency = 0 end
			if char:FindFirstChild("TopFin") then char:FindFirstChild("TopFin").Transparency = 0 end
			if char:FindFirstChild("BunnyEars") then char:FindFirstChild("BunnyEars").Transparency = 0 end
			if char:FindFirstChild("CatEars") then char:FindFirstChild("CatEars").Transparency = 0 end
			if char:FindFirstChildOfClass("Accessory") then char:FindFirstChildOfClass("Accessory").Handle.Transparency = 0 end
			if char:FindFirstChild("BullHorns") then char:FindFirstChild("BullHorns").Skin.Transparency = 0 char:FindFirstChild("BullHorns").Horns.Transparency = 0 end
		end
	end

	local function addAccessory(accessoryType, accessoryValue, parentPart, cframeRotation)
		if accessoryValue ~= "None" then
			local accModel = game.ReplicatedStorage.Assets.Accessories:FindFirstChild(accessoryValue):Clone()
			accModel.Parent = AccessoryModels

			local accWeld = Instance.new("Weld")
			accWeld.Name = accessoryType .. "AccessoryWeld"
			accWeld.Parent = parentPart
			accWeld.Part0 = parentPart
			accWeld.Part1 = accModel
			accWeld.C1 = accModel:GetAttribute("AccessoryPosition")

			if cframeRotation and (accessoryValue == "FluffyCape" or accessoryValue == "WaistKnot" or accessoryValue == "JokerCape") then
				accWeld.C0 = cframeRotation
			end
			if accessoryValue == "OniMask" then
				accWeld.C0 = CFrame.new(0, 0, 0, 1, -4.60346536e-25, 0, -4.60346536e-25, 1, 0, 0, 0, 1)
			end
			--for _,statsss in pairs(data:GetChildren()) do
			--	if accessorySets[statsss.Name] then

			--	end
			--end



			if accessoryType == "Head" then

				if data:FindFirstChild("Race") and data:FindFirstChild("RaceType") and data.Race.Value == "Mink" and data.RaceType.Value == 0 then
					accModel.Size = accModel.Size * 1.08
				end

				if accModel:FindFirstChild("HideRace") then
					if accModel:FindFirstChild("HideRace").Value == true then
						if char:FindFirstChild("SideFins") then char:FindFirstChild("SideFins").Transparency = 1 end
						if char:FindFirstChild("TopFin") then char:FindFirstChild("TopFin").Transparency = 1 end
						if char:FindFirstChild("BunnyEars") then char:FindFirstChild("BunnyEars").Transparency = 1 end
						if char:FindFirstChild("CatEars") then char:FindFirstChild("CatEars").Transparency = 1 end
						if char:FindFirstChild("BullHorns") then char:FindFirstChild("BullHorns").Skin.Transparency = 1 char:FindFirstChild("BullHorns").Horns.Transparency = 1 end

					end
				end	
				if accModel:FindFirstChild("HideHair") then
					if accModel:FindFirstChild("HideHair").Value == true then
						if char:FindFirstChildOfClass("Accessory") then char:FindFirstChildOfClass("Accessory").Handle.Transparency = 1 end
					end
				end	
			end

			local equipSound = game.ReplicatedStorage.Sounds.AccessoryEquip:Clone()
			equipSound.Parent = accModel
			equipSound:Play()
			delay(1, function()
				equipSound:Destroy()
			end)

			-- Hide all hat accessories
			for _, part in ipairs(parentPart:GetChildren()) do
				if part:IsA("BasePart") then
					part.Transparency = 1
				end
			end
		else
			-- Show all hat accessories
			for _, part in ipairs(parentPart:GetChildren()) do
				if part:IsA("BasePart") then
					part.Transparency = 0
				end
			end
		end
	end



	removeAccessoryType("Head")
	removeAccessoryType("Back")
	removeAccessoryType("Face")
	removeAccessoryType("Waist")

	local HeadAccessory = data:FindFirstChild("HeadAccessory")
	local BackAccessory = data:FindFirstChild("BackAccessory")
	local FaceAccessory = data:FindFirstChild("FaceAccessory")
	local WaistAccessory = data:FindFirstChild("WaistAccessory")

	addAccessory("Head", HeadAccessory and HeadAccessory:FindFirstChild("Name").Value or "None", char.Head, CFrame.new(0, 0, 0, -1, 0, -8.74227766e-08, 0, 1, 0, 8.74227766e-08, 0, -1))

	addAccessory("Back", BackAccessory and BackAccessory:FindFirstChild("Name").Value or "None", char.Torso, CFrame.new(0, 0, 0, -4.37113883e-08, 0, 1, 0, 1, 0, -1, 0, -4.37113883e-08))

	addAccessory("Face", FaceAccessory and FaceAccessory:FindFirstChild("Name").Value or "None", char.Torso, CFrame.new(0, 0, 0, -4.37113883e-08, 0, 1, 0, 1, 0, -1, 0, -4.37113883e-08))

	addAccessory("Waist", WaistAccessory and WaistAccessory:FindFirstChild("Name").Value or "None", char.Torso, CFrame.new(0, 0, 0, -4.37113883e-08, 0, 1, 0, 1, 0, -1, 0, -4.37113883e-08))

	if not HeadAccessory or HeadAccessory:FindFirstChild("Name").Value == "None" then
		removeAccessoryType("Head")

		local equipSound = game.ReplicatedStorage.Sounds.AccessoryEquip:Clone()
		equipSound.Parent = char.Head
		equipSound:Play()
		delay(1, function()
			equipSound:Destroy()
		end)
	end

	if not BackAccessory or BackAccessory:FindFirstChild("Name").Value == "None" then
		removeAccessoryType("Back")

		local equipSound = game.ReplicatedStorage.Sounds.AccessoryEquip:Clone()
		equipSound.Parent = char.Head
		equipSound:Play()
		delay(1, function()
			equipSound:Destroy()
		end)
	end

	if not FaceAccessory or FaceAccessory:FindFirstChild("Name").Value == "None" then
		removeAccessoryType("Necck")

		local equipSound = game.ReplicatedStorage.Sounds.AccessoryEquip:Clone()
		equipSound.Parent = char.Head
		equipSound:Play()
		delay(1, function()
			equipSound:Destroy()
		end)
	end

	if not WaistAccessory or WaistAccessory:FindFirstChild("Name").Value == "None" then
		removeAccessoryType("Necck")

		local equipSound = game.ReplicatedStorage.Sounds.AccessoryEquip:Clone()
		equipSound.Parent = char.Head
		equipSound:Play()
		delay(1, function()
			equipSound:Destroy()
		end)
	end
end


local function loadweaponparts(plr,data)

	local char = plr.Character

	local weapon1stat = data:FindFirstChild("Weapon1")
	local weapon2stat = data:FindFirstChild("Weapon2")
	local weapon3stat = data:FindFirstChild("Weapon3")

	if weapon1stat.Value ~= "None" then
		local weaponmodel = game.ReplicatedStorage.Assets.WeaponModels:FindFirstChild(weapon1stat.Value):Clone()
		weaponmodel.Parent = char
		local weapon1modelweld = Instance.new("Weld")
		weapon1modelweld.Parent = char.Torso
		weapon1modelweld.Part0 = char.Torso
		weapon1modelweld.Part1 = weaponmodel:FindFirstChild("Sheathe")
		weapon1modelweld.C1 = weaponmodel:GetAttribute("oness")

		local equipsound = game.ReplicatedStorage.Sounds.Sword.Equip:Clone()
		equipsound.Parent = weaponmodel:FindFirstChild("Sheathe")
		equipsound:Play()
		delay(1,function()
			equipsound:Destroy()
		end)


	end
	if weapon2stat.Value ~= "None" then
		local weaponmodel = game.ReplicatedStorage.Assets.WeaponModels:FindFirstChild(weapon2stat.Value):Clone()
		weaponmodel.Parent = char
		local weapon2modelweld = Instance.new("Weld")
		weapon2modelweld.Parent = char.Torso
		weapon2modelweld.Part0 = char.Torso
		weapon2modelweld.Part1 = weaponmodel:FindFirstChild("Sheathe")
		weapon2modelweld.C1 = weaponmodel:GetAttribute("twoss")

		local equipsound = game.ReplicatedStorage.Sounds.Sword.Equip:Clone()
		equipsound.Parent = weaponmodel:FindFirstChild("Sheathe")
		equipsound:Play()
		delay(1,function()
			equipsound:Destroy()
		end)


	end
	if weapon3stat.Value ~= "None" then
		local weaponmodel = game.ReplicatedStorage.Assets.WeaponModels:FindFirstChild(weapon3stat.Value):Clone()
		weaponmodel.Parent = char
		local weapon3modelweld = Instance.new("Weld")
		weapon3modelweld.Parent = char.Torso
		weapon3modelweld.Part0 = char.Torso
		weapon3modelweld.Part1 = weaponmodel:FindFirstChild("Sheathe")
		weapon3modelweld.C1 = weaponmodel:GetAttribute("threess")

		local equipsound = game.ReplicatedStorage.Sounds.Sword.Equip:Clone()
		equipsound.Parent = weaponmodel:FindFirstChild("Sheathe")
		equipsound:Play()
		delay(1,function()
			equipsound:Destroy()
		end)

	end

end

game.Players.PlayerAdded:Connect(function(plr)

if plr.Team == game:GetService("Teams").Loading then
	game.ReplicatedStorage.Remotes.UIHandle:FireClient(plr,"PlayerJoined")
end
	--if plr.PlayerGui:FindFirstChild("Starting Screen") then
	--plr.PlayerGui:FindFirstChild("Starting Screen").Enabled = true
	--end
	--if plr.UserId == 3305186906 then
	--	plr:Kick("BANNED FURIA MARCIA")
	--end

	plr.CharacterAdded:Connect(function(char)
		local char = plr.Character

		for _,foundosunds in pairs(char:FindFirstChild("HumanoidRootPart"):GetChildren()) do
			if foundosunds:IsA("Sound") then
				if foundosunds.Name ~= "Swimming" or foundosunds.Name ~= "Splash" then
					foundosunds:Destroy()
				end
			end
		end


		--print(script.Name.." IS INITIALIZING")

		local HPPERLEVEL = 6.6

		local effects = char:FindFirstChild("Effects")
		repeat wait() until  game.ServerStorage.PlayerData:FindFirstChild(plr.Name.."STATS")
		local pdata = game.ServerStorage.PlayerData:FindFirstChild(plr.Name.."STATS")
		--print("APPEARENCE HANDER PRE INSNEWGAME VALUE: "..tostring(pdata.IsNewGame.Value))

		if pdata.IsNewGame.Value == true then
			game.ReplicatedStorage.Remotes.NewGameFound:FireClient(plr)
			pdata.IsNewGame.Value = true
			--print("SET THE IS NEW GAME VALUE TO TRUE! THE VALUE IS ACTUALLY: "..tostring(pdata.IsNewGame.Value))
		end

		-- Server script placed in ServerScriptService

		local function calculateHealth(points)
			local healthincrease = points * HPPERLEVEL
			return healthincrease
		end

		local function updateStats(player)
			local playerData = game.ServerStorage.PlayerData:FindFirstChild(player.Name .. "STATS")
			if not playerData then
				return
			end

			local talents = playerData:FindFirstChild("Talents")
			if not talents then
				return
			end

			local humanoid = player.Character and player.Character:FindFirstChild("Humanoid")
			if not humanoid then
				return
			end

			for _,valuse in pairs(talents:GetChildren()) do
				valuse:Destroy()
			end

			local defaultJump = effects:FindFirstChild("DefaultJump")
			if defaultJump then
				defaultJump.Value = 45
			end

			local defaultWalk = effects:FindFirstChild("DefaultWalk")
			if defaultWalk then
				defaultWalk.Value = 10
			end

			local attackSpeedBoost = effects:FindFirstChild("AttackSpeedBoost")
			if attackSpeedBoost then
				attackSpeedBoost.Value = 0
			end

			if playerData:FindFirstChild("Race").Value == "Lunarian" then
				local HPBoost = Instance.new("NumberValue")
				HPBoost.Name = "HPBoost"
				HPBoost.Value = 25
				local cant = Instance.new("IntValue")
				cant.Name = "NoSave"
				HPBoost.Parent = playerData:FindFirstChild("Talents")
				cant.Parent = HPBoost

				local DamageRedcution = Instance.new("NumberValue")
				DamageRedcution.Name = "DamageReduction"
				DamageRedcution.Value = .10
				local cant = Instance.new("IntValue")
				cant.Name = "NoSave"
				DamageRedcution.Parent = playerData:FindFirstChild("Talents")
				cant.Parent = DamageRedcution
				--else
				--local effects = plr.Character:FindFirstChild("Effects")
				--if effects then
				--    local defaultJump = effects:FindFirstChild("DefaultJump")
				--    if defaultJump then
				--        defaultJump.Value = 45
				--    end

				--    local defaultWalk = effects:FindFirstChild("DefaultWalk")
				--    if defaultWalk then
				--        defaultWalk.Value = 10
				--    end

				--    local attackSpeedBoost = effects:FindFirstChild("AttackSpeedBoost")
				--    if attackSpeedBoost then
				--        attackSpeedBoost.Value = 0
				--    end
				--end

			end

			plr.Character.Humanoid.Health = plr.Character.Humanoid.MaxHealth

			if playerData:FindFirstChild("Race").Value == "Mink" then
				if playerData:FindFirstChild("RaceType").Value == 3 then
					local sum = plr.Character:FindFirstChild("Effects"):FindFirstChild("DefaultJump").Value * .15
					local JumpBoost = Instance.new("NumberValue")
					JumpBoost.Name = "JumpBoost"
					JumpBoost.Value = sum
					local cant = Instance.new("IntValue")
					cant.Name = "NoSave"
					JumpBoost.Parent = playerData:FindFirstChild("Talents")
					cant.Parent = JumpBoost
					--print(plr.Character:FindFirstChild("Effects"):FindFirstChild("DefaultJump").Value * .05)
					plr.Character:FindFirstChild("Effects"):FindFirstChild("DefaultJump").Value += sum
					--else
					--local effects = plr.Character:FindFirstChild("Effects")
					--if effects then
					--    local defaultJump = effects:FindFirstChild("DefaultJump")
					--    if defaultJump then
					--        defaultJump.Value = 45
					--    end

					--    local defaultWalk = effects:FindFirstChild("DefaultWalk")
					--    if defaultWalk then
					--        defaultWalk.Value = 10
					--    end

					--    local attackSpeedBoost = effects:FindFirstChild("AttackSpeedBoost")
					--    if attackSpeedBoost then
					--        attackSpeedBoost.Value = 0
					--    end
					--end
				end
				if playerData:FindFirstChild("RaceType").Value == 0 then

					local ssum = plr.Character:FindFirstChild("Effects"):FindFirstChild("DefaultWalk").Value * .05
					local SpeedBoost = Instance.new("NumberValue")
					SpeedBoost.Name = "SpeedBoost"
					SpeedBoost.Value = ssum
					local cant = Instance.new("IntValue")
					cant.Name = "NoSave"
					SpeedBoost.Parent = playerData:FindFirstChild("Talents")
					cant.Parent = SpeedBoost
					--print(plr.Character:FindFirstChild("Effects"):FindFirstChild("DefaultWalk").Value * .05)
					plr.Character:FindFirstChild("Effects"):FindFirstChild("DefaultWalk").Value += ssum

					local jsum = plr.Character:FindFirstChild("Effects"):FindFirstChild("DefaultJump").Value * .05
					local JumpBoost = Instance.new("NumberValue")
					JumpBoost.Name = "JumpBoost"
					JumpBoost.Value = jsum
					local cant = Instance.new("IntValue")
					cant.Name = "NoSave"
					JumpBoost.Parent = playerData:FindFirstChild("Talents")
					cant.Parent = JumpBoost
					--print(plr.Character:FindFirstChild("Effects"):FindFirstChild("DefaultJump").Value * .05)
					plr.Character:FindFirstChild("Effects"):FindFirstChild("DefaultJump").Value += jsum
					--else
					--local effects = plr.Character:FindFirstChild("Effects")
					--if effects then
					--    local defaultJump = effects:FindFirstChild("DefaultJump")
					--    if defaultJump then
					--        defaultJump.Value = 45
					--    end

					--    local defaultWalk = effects:FindFirstChild("DefaultWalk")
					--    if defaultWalk then
					--        defaultWalk.Value = 10
					--    end

					--    local attackSpeedBoost = effects:FindFirstChild("AttackSpeedBoost")
					--    if attackSpeedBoost then
					--        attackSpeedBoost.Value = 0
					--    end
					--end

				end
				if playerData:FindFirstChild("RaceType").Value == 1 then

					local ssum = plr.Character:FindFirstChild("Effects"):FindFirstChild("DefaultWalk").Value * .1

					local SpeedBoost = Instance.new("NumberValue")
					SpeedBoost.Name = "SpeedBoost"
					SpeedBoost.Value = ssum

					local cant = Instance.new("IntValue")
					cant.Name = "NoSave"
					SpeedBoost.Parent = playerData:FindFirstChild("Talents")
					cant.Parent = SpeedBoost
					--print(plr.Character:FindFirstChild("Effects"):FindFirstChild("DefaultWalk").Value * .1)
					plr.Character:FindFirstChild("Effects"):FindFirstChild("DefaultWalk").Value += ssum

					local AttackSpeedBoost = Instance.new("NumberValue")
					AttackSpeedBoost.Name = "AttackSpeedBoost"
					AttackSpeedBoost.Value = .15
					local cant = Instance.new("IntValue")
					cant.Name = "NoSave"
					AttackSpeedBoost.Parent = playerData:FindFirstChild("Talents")
					cant.Parent = AttackSpeedBoost
					effects:FindFirstChild("AttackSpeedBoost").Value = AttackSpeedBoost.Value
					--else
					--local effects = plr.Character:FindFirstChild("Effects")
					--if effects then
					--    local defaultJump = effects:FindFirstChild("DefaultJump")
					--    if defaultJump then
					--        defaultJump.Value = 45
					--    end

					--    local defaultWalk = effects:FindFirstChild("DefaultWalk")
					--    if defaultWalk then
					--        defaultWalk.Value = 10
					--    end

					--    local attackSpeedBoost = effects:FindFirstChild("AttackSpeedBoost")
					--    if attackSpeedBoost then
					--        attackSpeedBoost.Value = 0
					--    end
					--end

				end
				if playerData:FindFirstChild("RaceType").Value == 2 then

					local ssum = plr.Character:FindFirstChild("Effects"):FindFirstChild("DefaultWalk").Value * .1

					local DamageRedcution = Instance.new("NumberValue")
					DamageRedcution.Name = "DamageReduction"
					DamageRedcution.Value = .10
					local cant = Instance.new("IntValue")
					cant.Name = "NoSave"
					DamageRedcution.Parent = playerData:FindFirstChild("Talents")
					cant.Parent = DamageRedcution
				end
			end

			if playerData:FindFirstChild("Race").Value == "Germa" then

				local DamageRedcution = Instance.new("NumberValue")
				DamageRedcution.Name = "DamageReduction"
				DamageRedcution.Value = .20
				local cant = Instance.new("IntValue")
				cant.Name = "NoSave"
				DamageRedcution.Parent = playerData:FindFirstChild("Talents")
				cant.Parent = DamageRedcution
				--		else
				--local effects = plr.Character:FindFirstChild("Effects")
				--if effects then
				--    local defaultJump = effects:FindFirstChild("DefaultJump")
				--    if defaultJump then
				--        defaultJump.Value = 45
				--    end

				--    local defaultWalk = effects:FindFirstChild("DefaultWalk")
				--    if defaultWalk then
				--        defaultWalk.Value = 10
				--    end

				--    local attackSpeedBoost = effects:FindFirstChild("AttackSpeedBoost")
				--    if attackSpeedBoost then
				--        attackSpeedBoost.Value = 0
				--    end
				--end

			end


			humanoid.MaxHealth = pdata:FindFirstChild("MaxHP").Value

			local maxHealthBoost = talents:FindFirstChild("HPBoost")
			local maxJumpBoost = talents:FindFirstChild("JumpBoost")
			local baseSpeedBoost = talents:FindFirstChild("SpeedBoost")

			-- Update MaxHealth
			--if maxHealthBoost and maxHealthBoost:IsA("NumberValue") then
			--    local currentMaxHealth = humanoid.MaxHealth
			--    local newMaxHealth = currentMaxHealth + maxHealthBoost.Value
			--    if newMaxHealth > currentMaxHealth then
			--        humanoid.MaxHealth = newMaxHealth
			--        --humanoid.Health = humanoid.Health + (newMaxHealth - currentMaxHealth) -- Increase current health proportionally
			--    end
			--end

			for _,acctypess in pairs(pdata:GetChildren()) do
				if acctypess:FindFirstChild("Boosts") then
					local currentMaxHealth = humanoid.MaxHealth
					local newMaxHealth = currentMaxHealth + acctypess:FindFirstChild("Boosts"):FindFirstChild("HealthBoost").Value
					humanoid.MaxHealth = newMaxHealth
				end
			end	

			local playerVigorPoints = pdata:FindFirstChild("Vitality").Value
			local playerDamage = calculateHealth(playerVigorPoints)


			humanoid.MaxHealth += playerDamage 

			-- Update JumpPower
			if maxJumpBoost and maxJumpBoost:IsA("NumberValue") then
				humanoid.JumpPower += maxJumpBoost.Value
				effects:FindFirstChild("DefaultJump").Value += maxJumpBoost.Value
			else
				humanoid.JumpPower = 45
			end

			-- Update WalkSpeed
			if baseSpeedBoost and baseSpeedBoost:IsA("NumberValue") then
				humanoid.WalkSpeed += baseSpeedBoost.Value
				effects:FindFirstChild("DefaultWalk").Value += baseSpeedBoost.Value
			else
				humanoid.WalkSpeed = 10
			end
		end

		-- Listen for changes in Talents folder
		--game.ServerStorage.PlayerData.ChildAdded:Connect(function(child)
		--    if child.Name:match(".+STATS$") then
		--        child.ChildAdded:Connect(function()
		--            updateStats(child)
		--        end)
		--        child.ChildRemoved:Connect(function()
		--            updateStats(child)
		--        end)
		--    end
		--end)


		if char:FindFirstChild("Shirt") then
			char:FindFirstChild("Shirt").ShirtTemplate = game.ReplicatedStorage.Assets.Clothes.Shirts:FindFirstChild(pdata:FindFirstChild("CurrentShirt").Value).ShirtTemplate
			else
			local newshirt = Instance.new("Shirt")
			newshirt.Parent = char
			newshirt.ShirtTemplate = game.ReplicatedStorage.Assets.Clothes.Shirts:FindFirstChild(pdata:FindFirstChild("CurrentShirt").Value).ShirtTemplate
		end

		if char:FindFirstChild("Pants") then
			char:FindFirstChild("Pants").PantsTemplate = game.ReplicatedStorage.Assets.Clothes.Pants:FindFirstChild(pdata:FindFirstChild("CurrentShirt").Value).PantsTemplate
			else
			local newpants = Instance.new("Pants")
			newpants.Parent = char
			newpants.PantsTemplate = game.ReplicatedStorage.Assets.Clothes.Pants:FindFirstChild(pdata:FindFirstChild("CurrentShirt").Value).PantsTemplate
		end

		for _,acc in pairs(plr.Character:GetChildren()) do
			if acc:IsA("Accessory") then
				if not acc:FindFirstChild("Handle"):FindFirstChild("HairAttachment") then
					acc:Destroy()
				else
					acc:FindFirstChild("Handle"):FindFirstChildOfClass("SpecialMesh").TextureId = " "
				end
			end
			if acc:IsA("BasePart") then
				game:GetService("PhysicsService"):SetPartCollisionGroup(acc, "OnlyTouchMap")
			end
			if acc.Name == "Head" then
				acc.Transparency = 1
				if acc:FindFirstChildWhichIsA("Decal") then
					acc:FindFirstChildWhichIsA("Decal"):Destroy()
				end
			end
		end

		local raceparts = {}


		local function LoadRaceParts(charrrr)

			for _,bodyparts in pairs(char:GetDescendants()) do
				if bodyparts:IsA("CharacterMesh") then
					bodyparts:Destroy()
				end
				if bodyparts.Name == "CharacterMesh" then
					bodyparts:Destroy()
				end
			end


			for i,v in pairs(raceparts) do
				v:Destroy()
			end

			local racetype = nil

			--print(plr.Name.."'s Race is set to: "..pdata.Race.Value)
			--print(plr.Name.."'s Race Type is set to: "..pdata.RaceType.Value)

			for _,acc in pairs(plr.Character:GetChildren()) do
				if acc:IsA("Accessory") then
					if not acc:FindFirstChild("Handle"):FindFirstChild("HairAttachment") then
						acc:Destroy()
					else
						acc:FindFirstChild("Handle"):FindFirstChildOfClass("SpecialMesh").TextureId = " "
					end
				end
				if acc.Name == "Head" then
					acc.Transparency = 1
					if acc:FindFirstChildWhichIsA("Decal") then
						acc:FindFirstChildWhichIsA("Decal"):Destroy()
					end
				end
			end


			--if pdata then
			--    -- Ensure "Race" exists and is not nil
			--    if pdata:FindFirstChild("Race") then
			--        local race = pdata:FindFirstChild("Race").Value
			--        -- Ensure "SkinType" and "HairType" exist and are not nil
			--        if pdata:FindFirstChild("SkinType") and pdata:FindFirstChild("HairType") then
			--            local skinType = pdata:FindFirstChild("SkinType").Value
			--            local hairType = pdata:FindFirstChild("HairType").Value

			--            -- Iterate over all accessories in the character
			--            for _, accessory in pairs(charrrr:GetChildren()) do
			--                if accessory:IsA("Accessory") and accessory:FindFirstChild("Handle") then
			--                    local handle = accessory:FindFirstChild("Handle")
			--                    if race == "Human" or race == "Germa" or race == "Skypiean" then
			--                        handle.Color = humanhairtypes[skinType][hairType]
			--                    elseif race == "Lunarian" then
			--                        handle.Color = Color3.new(1, 1, 1)
			--                    elseif race == "Fishman" then
			--                        handle.Color = Fishmanhairtypes[skinType][hairType]
			--                    end
			--                    if race == "Mink" and pdata:FindFirstChild("RaceType") and pdata:FindFirstChild("RaceType").Value == 0 then
			--                        handle.Transparency = 1
			--                    else
			--                        handle.Transparency = 0
			--                    end
			--                end
			--            end
			--        end
			--    end
			--end



			if pdata.Race.Value == "Mink" then
				--print("Loading Mink Assets")

				if pdata.RaceType.Value == 0 then
					racetype = "Monkey"
				end
				if pdata.RaceType.Value == 1 then
					racetype = "Cat"
				end
				if pdata.RaceType.Value == 2 then
					racetype = "Bull"
				end
				if pdata.RaceType.Value == 3 then
					racetype = "Bunny"
				end

				if racetype == "Bull" then
					local raceassets = game.ReplicatedStorage.RaceParts.Mink.Bull
					local horns = raceassets.BullHorns:Clone()
					horns.Parent = char
					horns.Skin.Color = MinkSkinTypes[racetype][pdata:FindFirstChild("SkinType").Value]
					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char.Head
					RacePartsweld.Name = "RaceWeldHead"
					RacePartsweld.Part0 = char.Head
					RacePartsweld.Part1 = horns.Skin
					RacePartsweld.C1 = CFrame.new(0.000160217285, -0.448723793, 0.289962769, 1, 0, 0, 0, 1, 0, 0, 0, 1)
					table.insert(raceparts,horns)

					for _,limb in pairs(char:GetChildren()) do
						if limb:IsA("Part") then
							limb.Color = MinkSkinTypes[racetype][pdata:FindFirstChild("SkinType").Value]
						end
						if limb:FindFirstChild("Head") then
							limb:FindFirstChild("Head").Color = MinkSkinTypes[racetype][pdata:FindFirstChild("SkinType").Value]
						end
						if limb:IsA("Accessory") then
							limb:FindFirstChild("Handle").Color = humanhairtypes[pdata:FindFirstChild("SkinType").Value][pdata:FindFirstChild("HairType").Value]
						end
					end
				end

				if racetype == "Monkey" then
					local raceassets = game.ReplicatedStorage.RaceParts.Mink.Monkey
					local Head = raceassets.MonkeyEars:Clone()
					Head.Parent = char
					local Tail = raceassets.MonkeyTail:Clone()
					Tail.Parent = char
	
					Head.Color = MinkSkinTypes[racetype][pdata:FindFirstChild("SkinType").Value]
					Tail.PrimaryPart.Color = MinkSkinTypes[racetype][pdata:FindFirstChild("SkinType").Value]

					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char.Head
					RacePartsweld.Name = "RaceWeldHead"
					RacePartsweld.Part0 = char.Head
					RacePartsweld.Part1 = Head
					RacePartsweld.C1 = CFrame.new(0.000160217285, -0.019411087, -0.0163421631, 1, -1.9024943e-05, -2.59983618e-10, 1.9024943e-05, 1, 4.37113812e-08, 2.59108179e-10, -4.37113847e-08, 1)
					table.insert(raceparts,Head)

					local RacePartsweld2 = Instance.new("Weld")
					RacePartsweld2.Parent =  char.Torso
					RacePartsweld2.Name = "RaceWeldBack"
					RacePartsweld2.Part0 = char.Torso
					RacePartsweld2.Part1 = Tail.PrimaryPart
					RacePartsweld2.C1 = CFrame.new(-0.00476074219, 0.873481512, -2.33760452, 1, -9.5124733e-07, -1.29983923e-11, 9.51247387e-07, 1, 4.3713932e-08, 1.29568092e-11, -4.3713932e-08, 1 )			
					table.insert(raceparts,Tail)

					Tail.AnimationController.Animator:LoadAnimation(Tail.Idle):Play()
					for _,limb in pairs(char:GetChildren()) do
						if limb:IsA("Part") then
							limb.Color = MinkSkinTypes[racetype][pdata:FindFirstChild("SkinType").Value]
						end
						if limb:FindFirstChild("Head") then
							limb:FindFirstChild("Head").Color = Color3.new(0.835294, 0.533333, 0.392157)
							if pdata:FindFirstChild("SkinType").Value == 2 then
								limb:FindFirstChild("Head").Color = Color3.new(0.564706, 0.627451, 0.690196)
							end
							if pdata:FindFirstChild("SkinType").Value == 4 then
								limb:FindFirstChild("Head").Color = Color3.new(0.372549, 0.372549, 0.372549)
							end
							if pdata:FindFirstChild("SkinType").Value == 5 then
								limb:FindFirstChild("Head").Color = Color3.new(0.729412, 0.505882, 0.356863)
							end
						end
						if limb:IsA("Accessory") then
							limb:FindFirstChild("Handle").Color = MinkSkinTypes[racetype][pdata:FindFirstChild("SkinType").Value]
						end
					end

				end

				if racetype == "Cat" then
					local raceassets = game.ReplicatedStorage.RaceParts.Mink.Cat
					local Head = raceassets.CatEars:Clone()
					Head.Parent = char
					local whislers = raceassets.CatWhiskers:Clone()
					whislers.Parent = char
					local Tail = raceassets.CatTail:Clone()
					Tail.Parent = char

					Head.Color = MinkSkinTypes[racetype][pdata:FindFirstChild("SkinType").Value]
					Tail.PrimaryPart.Color = MinkSkinTypes[racetype][pdata:FindFirstChild("SkinType").Value]


					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char.Head
					RacePartsweld.Name = "RaceWeldHead"
					RacePartsweld.Part0 = char.Head
					RacePartsweld.Part1 = Head
					RacePartsweld.C1 = CFrame.new(0.000160217285, -0.586762428, 0.127353668, 1, 1.22464646e-16, -1.22464884e-16, -1.22464646e-16, 1, 4.37113883e-08, 1.22464884e-16, -4.37113883e-08, 1)
					table.insert(raceparts,Head)

					local RacePartsweld3 = Instance.new("Weld")
					RacePartsweld3.Parent =  char.Head
					RacePartsweld3.Name = "RaceWeldFace"
					RacePartsweld3.Part0 = char.Head
					RacePartsweld3.Part1 = whislers
					RacePartsweld3.C1 = CFrame.new(0.000160217285, 0.217000008, 0.503353119, 1, 2.71050543e-20, -5.6513145e-06, 2.71050543e-20, 1, 0, 5.6513145e-06, 0, 1)
					table.insert(raceparts,whislers)

					whislers:SetAttribute("Elasticity",3)

					local RacePartsweld2 = Instance.new("Weld")
					RacePartsweld2.Parent =  char.Torso
					RacePartsweld2.Name = "RaceWeldBack"
					RacePartsweld2.Part0 = char.Torso
					RacePartsweld2.Part1 = Tail.PrimaryPart
					RacePartsweld2.C1 = CFrame.new(-0.0101318359, 0.866820812, -2.25285721, 1, 1.22462634e-16, -1.60980862e-16, -1.22462621e-16, 1, 4.3716593e-08, 1.60980862e-16, -4.3716593e-08, 1)
					table.insert(raceparts,Tail)

					Tail.AnimationController.Animator:LoadAnimation(Tail.Idle):Play()

					for _,limb in pairs(char:GetChildren()) do
						if limb:IsA("Part") then
							limb.Color = MinkSkinTypes[racetype][pdata:FindFirstChild("SkinType").Value]
						end
						if limb:FindFirstChild("Head") then
							limb:FindFirstChild("Head").Color = MinkSkinTypes[racetype][pdata:FindFirstChild("SkinType").Value]
						end
						if limb:IsA("Accessory") then
							limb:FindFirstChild("Handle").Color = humanhairtypes[pdata:FindFirstChild("SkinType").Value][pdata:FindFirstChild("HairType").Value]
						end
					end

				end

				if racetype == "Bunny" then
					local raceassets = game.ReplicatedStorage.RaceParts.Mink.Bunny
					local Head = raceassets.BunnyEars:Clone()
					Head.Parent = char
					local Tail = raceassets.BunnyTail:Clone()
					Tail.Parent = char

					Head.Color = MinkSkinTypes[racetype][pdata:FindFirstChild("SkinType").Value]
					Tail.Color = MinkSkinTypes[racetype][pdata:FindFirstChild("SkinType").Value]


					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char.Head
					RacePartsweld.Name = "RaceWeldHead"
					RacePartsweld.Part0 = char.Head
					RacePartsweld.Part1 = Head
					RacePartsweld.C1 = CFrame.new(-0.000526428223, -0.961999893, 0.198875427, 1, 2.44929371e-16, -3.30427067e-19, -2.44929371e-16, 1, 7.88381658e-06, 3.32358042e-19, -7.88381658e-06, 1)
					table.insert(raceparts,Head)

					local RacePartsweld2 = Instance.new("Weld")
					RacePartsweld2.Parent =  char.Torso
					RacePartsweld2.Name = "RaceWeldBack"
					RacePartsweld2.Part0 = char.Torso
					RacePartsweld2.Part1 = Tail
					RacePartsweld2.C1 = CFrame.new(0.000473022461, 0.873000145, -0.822128296, 1, 2.44929371e-16, 6.52450663e-20, -2.44929371e-16, 1, -1.75238517e-06, -6.56742762e-20, 1.75238517e-06, 1)
					table.insert(raceparts,Tail)

					delay(1,function()
						Tail:SetAttribute("Elasticity",3)
					end)

					for _,limb in pairs(char:GetChildren()) do
						if limb:IsA("Part") then
							limb.Color = MinkSkinTypes[racetype][pdata:FindFirstChild("SkinType").Value]
						end
						if limb:FindFirstChild("Head") then
							limb:FindFirstChild("Head").Color = MinkSkinTypes[racetype][pdata:FindFirstChild("SkinType").Value]
						end
						if limb:IsA("Accessory") then
							limb:FindFirstChild("Handle").Color = humanhairtypes[pdata:FindFirstChild("SkinType").Value][pdata:FindFirstChild("HairType").Value]
						end
					end

				end	

				--print("Mink Parts Set!")

			end

			if pdata.Race.Value == "Fishman" then
				--print("Loading Mink Assets")

				if pdata.RaceType.Value == 0 then
					racetype = "FishthingGills"
				end
				if pdata.RaceType.Value == 1 then
					racetype = "FishthingSide"
				end
				if pdata.RaceType.Value == 2 then
					racetype = "Octopus"
				end
				if pdata.RaceType.Value == 3 then
					racetype = "SharkArms"
				end
				if pdata.RaceType.Value == 4 then
					racetype = "Shark"
				end
				if pdata.RaceType.Value == 5 then
					racetype = "FishthingTop"
				end







				if racetype == "FishthingGills" then
					local raceassets = game.ReplicatedStorage.RaceParts.Fishman:FindFirstChild(racetype)
					local gills = raceassets.Gills:Clone()
					gills.Parent = char
					gills.Color = Color3.new(1, 0.419608, 0.419608)
					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char.Head
					RacePartsweld.Part0 = char.Head
					RacePartsweld.Part1 = gills
					RacePartsweld.C1 = CFrame.new(-0.000129699707, 0.236475468, 0.000350952148, 1, -2.76207931e-24, 0, 2.76207931e-24, 1, 0, 0, 0, 1)
					table.insert(raceparts,gills)

					for _,limb in pairs(char:GetChildren()) do
						if limb:IsA("Part") then
							limb.Color = Fishmanskintypes[pdata:FindFirstChild("SkinType").Value]
						end
						if limb:FindFirstChild("Head") then
							limb:FindFirstChild("Head").Color = Fishmanskintypes[pdata:FindFirstChild("SkinType").Value]
						end
						if limb:IsA("Accessory") then
							limb:FindFirstChild("Handle").Color = Fishmanhairtypes[pdata:FindFirstChild("SkinType").Value][pdata:FindFirstChild("HairType").Value]
						end
					end
				end

				if racetype == "FishthingSide" then
					local raceassets = game.ReplicatedStorage.RaceParts.Fishman:FindFirstChild(racetype)
					local horns = raceassets.SideFins:Clone()
					horns.Parent = char
					if pdata:FindFirstChild("SkinType") then
						if pdata:FindFirstChild("SkinType") ~= nil then
							horns.Color = Fishmanskintypes[pdata:FindFirstChild("SkinType").Value]
						end
					end
					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char.Head
					RacePartsweld.Part0 = char.Head
					RacePartsweld.Part1 = horns
					RacePartsweld.C1 = CFrame.new(-0.000129699707, 0.015042305, 0.00735092163, 1, 0, 0, 0, 1, 0, 0, 0, 1)
					table.insert(raceparts,horns)

					local raceassets = game.ReplicatedStorage.RaceParts.Fishman:FindFirstChild(racetype)
					local gills = raceassets.Gills:Clone()
					gills.Parent = char
					gills.Color = Color3.new(1, 0.419608, 0.419608)
					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char.Head
					RacePartsweld.Part0 = char.Head
					RacePartsweld.Part1 = gills
					RacePartsweld.C1 = CFrame.new(-0.000129699707, 0.236475468, 0.000350952148, 1, -2.76207931e-24, 0, 2.76207931e-24, 1, 0, 0, 0, 1)
					table.insert(raceparts,gills)

					for _,limb in pairs(char:GetChildren()) do
						if limb:IsA("Part") then
							limb.Color = horns.Color
						end
						if limb:FindFirstChild("Head") then
							limb:FindFirstChild("Head").Color = horns.Color
						end
						if limb:IsA("Accessory") then
							limb:FindFirstChild("Handle").Color = Fishmanhairtypes[pdata:FindFirstChild("SkinType").Value][pdata:FindFirstChild("HairType").Value]
						end
					end
				end

				if racetype == "Octopus" then
					local raceassets = game.ReplicatedStorage.RaceParts.Fishman:FindFirstChild(racetype)
					local horns = raceassets.OctoLeftArm:Clone()
					horns.Parent = char
					if pdata:FindFirstChild("SkinType") then
						if pdata:FindFirstChild("SkinType") ~= nil then
							horns.Color = Fishmanskintypes[pdata:FindFirstChild("SkinType").Value]
						end
					end
					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char["Left Arm"]
					RacePartsweld.Part0 = char["Left Arm"]
					RacePartsweld.Part1 = horns
					RacePartsweld.C1 = CFrame.new(0.517593384, -0.1881814, 0.00644302368, 1, 0, 0, 0, 1, 0, 0, 0, 1)
					table.insert(raceparts,horns)

					local horns2 = raceassets.OctoRightArm:Clone()
					horns2.Parent = char
					horns2.Color = Fishmanskintypes[pdata:FindFirstChild("SkinType").Value]
					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char["Right Arm"]
					RacePartsweld.Part0 = char["Right Arm"]
					RacePartsweld.Part1 = horns2
					RacePartsweld.C1 = CFrame.new(-0.517272949, -0.1881814, 0.00644302368, 1, 0, 0, 0, 1, 0, 0, 0, 1)
					table.insert(raceparts,horns2)

					for _,limb in pairs(char:GetChildren()) do
						if limb:IsA("Part") then
							limb.Color = horns.Color
						end
						if limb:FindFirstChild("Head") then
							limb:FindFirstChild("Head").Color = horns.Color
						end
						if limb:IsA("Accessory") then
							limb:FindFirstChild("Handle").Color = Fishmanhairtypes[pdata:FindFirstChild("SkinType").Value][pdata:FindFirstChild("HairType").Value]
						end
					end
				end

				if racetype == "SharkArms" then
					local raceassets = game.ReplicatedStorage.RaceParts.Fishman:FindFirstChild(racetype)
					local horns = raceassets.FinsLeftArm:Clone()
					horns.Parent = char
					if pdata:FindFirstChild("SkinType") then
						if pdata:FindFirstChild("SkinType") ~= nil then
							if pdata:FindFirstChild("SkinType") then
								if pdata:FindFirstChild("SkinType") ~= nil then
									horns.Color = Fishmanskintypes[pdata:FindFirstChild("SkinType").Value]
								end
							end
						end
					end
					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char["Left Arm"]
					RacePartsweld.Part0 = char["Left Arm"]
					RacePartsweld.Part1 = horns
					RacePartsweld.C1 = CFrame.new(-0.00469207764, -0.0952324867, -0.715816498, 1, 0, 0, 0, 1, 0, 0, 0, 1)
					table.insert(raceparts,horns)

					local raceassets = game.ReplicatedStorage.RaceParts.Fishman:FindFirstChild(racetype)
					local gills = raceassets.Gills:Clone()
					gills.Parent = char
					gills.Color = Color3.new(1, 0.419608, 0.419608)
					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char.Head
					RacePartsweld.Part0 = char.Head
					RacePartsweld.Part1 = gills
					RacePartsweld.C1 = CFrame.new(-0.000129699707, 0.236475468, 0.000350952148, 1, -2.76207931e-24, 0, 2.76207931e-24, 1, 0, 0, 0, 1)
					table.insert(raceparts,gills)

					local horns2 = raceassets.FinsRightArm:Clone()
					horns2.Parent = char
					if pdata:FindFirstChild("SkinType") then
						if pdata:FindFirstChild("SkinType") ~= nil then
							horns2.Color = Fishmanskintypes[pdata:FindFirstChild("SkinType").Value]
						end
					end
					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char["Right Arm"]
					RacePartsweld.Part0 = char["Right Arm"]
					RacePartsweld.Part1 = horns2
					RacePartsweld.C1 = CFrame.new(0.00501251221, -0.0952324867, -0.715816498, 1, 0, 0, 0, 1, 0, 0, 0, 1)
					table.insert(raceparts,horns2)

					for _,limb in pairs(char:GetChildren()) do
						if limb:IsA("Part") then
							limb.Color = horns.Color
						end
						if limb:FindFirstChild("Head") then
							limb:FindFirstChild("Head").Color = horns.Color
						end
						if limb:IsA("Accessory") then
							limb:FindFirstChild("Handle").Color = Fishmanhairtypes[pdata:FindFirstChild("SkinType").Value][pdata:FindFirstChild("HairType").Value]
						end
					end
				end

				if racetype == "Shark" then
					local raceassets = game.ReplicatedStorage.RaceParts.Fishman:FindFirstChild(racetype)
					local horns = raceassets.BackFin:Clone()
					horns.Parent = char
					if pdata:FindFirstChild("SkinType") then
						if pdata:FindFirstChild("SkinType") ~= nil then
							horns.Color = Fishmanskintypes[pdata:FindFirstChild("SkinType").Value]
						end
					end
					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char.Torso
					RacePartsweld.Part0 = char.Torso
					RacePartsweld.Part1 = horns
					RacePartsweld.C1 = CFrame.new(-0.000129699707, -0.318362951, -1.02505493, 1, 4.9365995e-14, 3.89414339e-07, -1.99660336e-14, 1, -7.54978942e-08, -3.89414339e-07, 7.54978942e-08, 1)
					table.insert(raceparts,horns)

					for _,limb in pairs(char:GetChildren()) do
						if limb:IsA("Part") then
							limb.Color = horns.Color
						end
						if limb:FindFirstChild("Head") then
							limb:FindFirstChild("Head").Color = horns.Color
						end
						if limb:IsA("Accessory") then
							limb:FindFirstChild("Handle").Color = Fishmanhairtypes[pdata:FindFirstChild("SkinType").Value][pdata:FindFirstChild("HairType").Value]
						end
					end
				end
				if racetype == "FishthingTop" then
					local raceassets = game.ReplicatedStorage.RaceParts.Fishman:FindFirstChild(racetype)
					local horns = raceassets.TopFin:Clone()
					horns.Parent = char
					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char.Head
					RacePartsweld.Part0 = char.Head
					RacePartsweld.Part1 = horns
					RacePartsweld.C1 = CFrame.new(0.0123214722, -0.856650352, -0.113666534, 1, 0, 0, 0, 1, 0, 0, 0, 1)
					table.insert(raceparts,horns)

					local raceassets = game.ReplicatedStorage.RaceParts.Fishman:FindFirstChild(racetype)
					local gills = raceassets.Gills:Clone()
					gills.Parent = char
					gills.Color = Color3.new(1, 0.419608, 0.419608)
					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char.Head
					RacePartsweld.Part0 = char.Head
					RacePartsweld.Part1 = gills
					RacePartsweld.C1 = CFrame.new(-0.000129699707, 0.236475468, 0.000350952148, 1, -2.76207931e-24, 0, 2.76207931e-24, 1, 0, 0, 0, 1)
					table.insert(raceparts,gills)
					if pdata:FindFirstChild("SkinType") then
						if pdata:FindFirstChild("SkinType") ~= nil then
							horns.Color = Fishmanskintypes[pdata:FindFirstChild("SkinType").Value]
						end
					end
					for _,limb in pairs(char:GetChildren()) do
						if limb:IsA("Part") then
							limb.Color = horns.Color
						end
						if limb:FindFirstChild("Head") then
							limb:FindFirstChild("Head").Color = horns.Color
						end
						if limb:IsA("Accessory") then
							limb:FindFirstChild("Handle").Color = Fishmanhairtypes[pdata:FindFirstChild("SkinType").Value][pdata:FindFirstChild("HairType").Value]
						end
					end
				end

				--print("Fishman Parts Set!")

			end	

			if pdata.Race.Value == "Human" then
				for _,limb in pairs(char:GetChildren()) do
					if limb:IsA("Part") then
						if not pdata:FindFirstChild("SkinType") then limb.Color = humanskintypes[1] else limb.Color = humanskintypes[pdata:FindFirstChild("SkinType").Value] end
					end
					if limb:FindFirstChild("Head") then
						limb:FindFirstChild("Head").Color = humanskintypes[pdata:FindFirstChild("SkinType").Value]
					end
					if limb:IsA("Accessory") then
						limb:FindFirstChild("Handle").Color = humanhairtypes[pdata:FindFirstChild("SkinType").Value][pdata:FindFirstChild("HairType").Value]
					end
				end
			end

			if pdata.Race.Value == "Germa" then
				for _,limb in pairs(char:GetChildren()) do
					if limb:IsA("Part") then
						if not pdata:FindFirstChild("SkinType") then limb.Color = humanskintypes[1] else limb.Color = humanskintypes[pdata:FindFirstChild("SkinType").Value] end
					end
					if limb:FindFirstChild("Head") then
						limb:FindFirstChild("Head").Color = humanskintypes[pdata:FindFirstChild("SkinType").Value]
					end
					if limb:IsA("Accessory") then
						limb:FindFirstChild("Handle").Color = humanhairtypes[pdata:FindFirstChild("SkinType").Value][pdata:FindFirstChild("HairType").Value]
					end
				end
			end

			if pdata.Race.Value == "Skypiean" then
				--print("Loading Skypiean Assets")

				racetype = "Normal"

				if racetype == "Normal" then
					local raceassets = game.ReplicatedStorage.RaceParts.Skypiean:FindFirstChild(racetype)
					local horns = raceassets.WINGS:Clone()
					horns.Parent = char
					--horns.Color = Color3.new(1, 0.419608, 0.419608)
					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char.Torso
					RacePartsweld.Part0 = char.Torso
					RacePartsweld.Part1 = horns
					RacePartsweld.C1 = CFrame.new(-0.000129699707, -0.934058905, -1.10651398, 1, 0, 0, 0, 1, 0, 0, 0, 1)
					table.insert(raceparts,horns)

					for _,limb in pairs(char:GetChildren()) do
						if limb:IsA("Part") then
							if not pdata:FindFirstChild("SkinType") then limb.Color = humanskintypes[1] else limb.Color = humanskintypes[pdata:FindFirstChild("SkinType").Value] end
						end
						if limb:FindFirstChild("Head") then
							limb:FindFirstChild("Head").Color = humanskintypes[pdata:FindFirstChild("SkinType").Value]
						end
						if limb:IsA("Accessory") then
							limb:FindFirstChild("Handle").Color = humanhairtypes[pdata:FindFirstChild("SkinType").Value][pdata:FindFirstChild("HairType").Value]
						end
					end
				end


				--print("Skypiean Parts Set!")

			end	

			if pdata.Race.Value == "Lunarian" then
				--print("Loading Lunarian Assets")

				racetype = "Normal"

				if racetype == "Normal" then
					local raceassets = game.ReplicatedStorage.RaceParts.Lunarian:FindFirstChild(racetype)
					local horns = raceassets.WINGS:Clone()
					horns.Parent = char
					--horns.Color = Color3.new(1, 0.419608, 0.419608)
					local RacePartsweld = Instance.new("Weld")
					RacePartsweld.Parent =  char.Torso
					RacePartsweld.Part0 = char.Torso
					RacePartsweld.Part1 = horns
					RacePartsweld.C1 = CFrame.new(-0.000129699707, -0.934058905, -1.10651398, 1, 0, 0, 0, 1, 0, 0, 0, 1)
					table.insert(raceparts,horns)

					for _,limb in pairs(char:GetChildren()) do
						if limb:IsA("Part") then
							if not pdata:FindFirstChild("SkinType") then limb.Color = humanskintypes[1] else limb.Color = humanskintypes[3] end
						end
						if limb:FindFirstChild("Head") then
							limb:FindFirstChild("Head").Color = humanskintypes[3]
						end
						if limb:IsA("Accessory") then
							limb:FindFirstChild("Handle").Color = Color3.new(1, 1, 1)
						end
					end
				end


				--print("Lunarian Parts Set!")

			end	

		end

		local function formatNumber(num)
			local formatted = tostring(num)
			local k = formatted:gsub("^(-?%d+)(%d%d%d)", '%1,%2')
			while k ~= formatted do
				formatted = k
				k = formatted:gsub("^(-?%d+)(%d%d%d)", '%1,%2')
			end
			return formatted
		end

		local function loadguivisuals()
			if pdata:FindFirstChild("Affiliation") then
				for _,icons in pairs(plr.PlayerGui.MainGui.MainScreen.CoreVisuals.CrewFrame:GetChildren()) do
					if icons:IsA("ImageLabel") then
						icons.Visible = false
					end
				end
				plr.PlayerGui.MainGui.MainScreen.CoreVisuals.CrewFrame:FindFirstChild(pdata:FindFirstChild("Affiliation").Value).Visible = true
			end
		end



		local function updatestyle()

			local weapon1stat = pdata:FindFirstChild("Weapon1").Value
			local weapon2stat = pdata:FindFirstChild("Weapon2").Value
			local weapon3stat = pdata:FindFirstChild("Weapon3").Value

			local weprig = game.ReplicatedStorage.Assets.WeaponRig
			local onewep = weprig["Right Arm"].RightSwordHandle.C1
			local twowep = weprig["Left Arm"].LeftSwordHandle.C1
			local threewep = weprig.Head.HeadSwordHandle.C1

			if weapon1stat == "None" then
				for _,models in pairs(char:FindFirstChild("WeaponModels"):GetChildren()) do
					models:Destroy()
					if plr.Backpack:FindFirstChild("Combat") then
						plr.Backpack:FindFirstChild("Combat"):FindFirstChild("Style").Value = "Brawl"
					end
					if char:FindFirstChild("Combat") then
						char:FindFirstChild("Combat"):FindFirstChild("Style").Value = "Brawl"
					end
				end
			end

			if weapon1stat ~= "None" then
				--for _,models in pairs(char:FindFirstChild("WeaponModels"):GetChildren()) do
				--	models:Destroy()
				--	if plr.Backpack:FindFirstChild("Combat") then
				--		plr.Backpack:FindFirstChild("Combat"):FindFirstChild("Style").Value = "Brawl"
				--	end
				--	if char:FindFirstChild("Combat") then
				--		char:FindFirstChild("Combat"):FindFirstChild("Style").Value = "Brawl"
				--	end
				--end

				if game.ReplicatedStorage.Assets.WeaponModelsHands:FindFirstChild(weapon1stat) then
					if game.ReplicatedStorage.Assets.WeaponModelsHands:FindFirstChild(weapon1stat):FindFirstChild("WeaponType").Value ~= "Sword" then
						--print("Not A Sword")
					else
						--print("Has1SS")
						for _,models in pairs(char:FindFirstChild("WeaponModels"):GetChildren()) do
							models:Destroy()
							if plr.Backpack:FindFirstChild("Combat") then
								plr.Backpack:FindFirstChild("Combat"):FindFirstChild("Style").Value = "Brawl"
							end
							if char:FindFirstChild("Combat") then
								char:FindFirstChild("Combat"):FindFirstChild("Style").Value = "Brawl"
							end
						end


						if plr.Backpack:FindFirstChild("Combat") then
							plr.Backpack:FindFirstChild("Combat"):FindFirstChild("Style").Value = "OneSwordStyle"
						end
						if char:FindFirstChild("Combat") then
							char:FindFirstChild("Combat"):FindFirstChild("Style").Value = "OneSwordStyle"
						end

					end
				end
			end
		end

		local newhead = script.Fake:Clone()
		newhead.Parent = char
		local newheadweld = Instance.new("Weld")
		newheadweld.Parent = char:FindFirstChild("Head")
		newheadweld.Part0 = char:FindFirstChild("Head")
		newheadweld.Part1 = newhead.Head

		--checkresize(char)
		--resize(char,char:GetDescendants(),.4)

		pdata:FindFirstChild("Weapon1").Changed:Connect(function()
			loadweaponparts(plr,pdata)
		end)

		pdata:FindFirstChild("Scale").Changed:Connect(function()
			effects:FindFirstChild("Scale").Value = pdata:FindFirstChild("Scale").Value
		end)

		pdata:FindFirstChild("HasSoru").Changed:Connect(function()
			char.Effects:FindFirstChild("HasSoru").Value = pdata:FindFirstChild("HasSoru").Value
			print("Has Soru is now: "..tostring(pdata:FindFirstChild("HasSoru").Value))
		end)

		pdata:FindFirstChild("Weapon2").Changed:Connect(function()
			loadweaponparts(plr,pdata)
		end)

		pdata:FindFirstChild("Weapon3").Changed:Connect(function()
			loadweaponparts(plr,pdata)
		end)

		pdata:FindFirstChild("InCombat").Changed:Connect(function(val)
			if val == true then
				plr.PlayerGui.MainGui.Combat:Play()
				plr.PlayerGui.MainGui.MainScreen.InCombatTag.Visible = true
			end
			if val == false then
				--plr.PlayerGui.MainGui.Combat:Play()
				plr.PlayerGui.MainGui.MainScreen.InCombatTag.Visible = false
			end
		end)

		pdata:FindFirstChild("RaceType").Changed:Connect(function(val)
			LoadRaceParts(plr.Character)
			updateStats(plr)
			updateaccessories(plr,pdata)
			if pdata.Race.Value == "Mink" then
				if pdata.RaceType.Value == 0 or 1 then
					plr.PlayerGui.Climb.Enabled = true
					else
					plr.PlayerGui.Climb.Enabled = false
				end
			end
		end)

		pdata:FindFirstChild("HeadAccessory"):FindFirstChild("Name").Changed:Connect(function(val)
			updateaccessories(plr,pdata)

			local accessoryID = pdata:FindFirstChild("HeadAccessory"):FindFirstChild("ID").Value  -- Unique identifier for the accessory

			local headAccessory = pdata:FindFirstChild("HeadAccessory")
			local buffs = {}

			if headAccessory then
				local boostsFolder = headAccessory:FindFirstChild("Boosts")
				if boostsFolder then
					buffs.vitality = boostsFolder:FindFirstChild("HealthBoost") and boostsFolder.HealthBoost.Value or 0
					buffs.reduction = boostsFolder:FindFirstChild("DamageReduction") and boostsFolder.DamageReduction.Value or 0
					buffs.agility = boostsFolder:FindFirstChild("StaminaBoost") and boostsFolder.StaminaBoost.Value or 0
				else
					buffs.vitality = 0
					buffs.reduction = 0
					buffs.agility = 0
				end
			else
				buffs.vitality = 0
				buffs.reduction = 0
				buffs.agility = 0
			end


			--SaveAccessoryBuffs(accessoryID, buffs)

			---- When loading the accessory buffs
			--local loadedBuffs = LoadAccessoryBuffs(accessoryID)
			----if loadedBuffs then

			--pdata:FindFirstChild("HeadAccessory"):FindFirstChild("ID").Value = accessoryID

			--  if loadedBuffs["vitality"] then
			--	if pdata:FindFirstChild("HeadAccessory"):FindFirstChild("Boosts"):FindFirstChild("HealthBoost") then
			--	pdata:FindFirstChild("HeadAccessory"):FindFirstChild("Boosts"):FindFirstChild("HealthBoost").Value = loadedBuffs["vitality"]
			--		return
			--	end
			--	local buffval = Instance.new("NumberValue")
			--	buffval.Name = "HealthBoost"
			--	buffval.Value = loadedBuffs["vitality"]
			--	buffval.Parent = pdata:FindFirstChild("HeadAccessory"):FindFirstChild("Boosts")
			--end
			--  if loadedBuffs["reduction"] then
			--	if pdata:FindFirstChild("HeadAccessory"):FindFirstChild("Boosts"):FindFirstChild("DamageReduction") then
			--	pdata:FindFirstChild("HeadAccessory"):FindFirstChild("Boosts"):FindFirstChild("DamageReduction").Value = loadedBuffs["reduction"]
			--		return
			--	end
			--	local buffval = Instance.new("NumberValue")
			--	buffval.Name = "DamageReduction"
			--	buffval.Value = loadedBuffs["reduction"]
			--	buffval.Parent = pdata:FindFirstChild("HeadAccessory"):FindFirstChild("Boosts")
			--end
			--  if loadedBuffs["agility"] then
			--	if pdata:FindFirstChild("HeadAccessory"):FindFirstChild("Boosts"):FindFirstChild("StaminaBoost") then
			--	pdata:FindFirstChild("HeadAccessory"):FindFirstChild("Boosts"):FindFirstChild("StaminaBoost").Value = loadedBuffs["agility"]
			--		return
			--	end
			--	local buffval = Instance.new("NumberValue")
			--	buffval.Name = "StaminaBoost"
			--	buffval.Value = loadedBuffs["agility"]
			--	buffval.Parent = pdata:FindFirstChild("HeadAccessory"):FindFirstChild("Boosts")
			--end
			--else
			--    -- Handle the case where the accessory buffs couldn't be loaded
			--end

		end)
		pdata:FindFirstChild("FaceAccessory"):FindFirstChild("Name").Changed:Connect(function(val)
			updateaccessories(plr,pdata)
		end)
		pdata:FindFirstChild("BackAccessory"):FindFirstChild("Name").Changed:Connect(function(val)
			updateaccessories(plr,pdata)
		end)
		pdata:FindFirstChild("LeftArmAccessory"):FindFirstChild("Name").Changed:Connect(function(val)
			updateaccessories(plr,pdata)
		end)
		pdata:FindFirstChild("RightArmAccessory"):FindFirstChild("Name").Changed:Connect(function(val)
			updateaccessories(plr,pdata)
		end)
		pdata:FindFirstChild("LeftHandAccessory"):FindFirstChild("Name").Changed:Connect(function(val)
			updateaccessories(plr,pdata)
		end)
		pdata:FindFirstChild("RightHandAccessory"):FindFirstChild("Name").Changed:Connect(function(val)
			updateaccessories(plr,pdata)
		end)
		pdata:FindFirstChild("WaistAccessory"):FindFirstChild("Name").Changed:Connect(function(val)
			updateaccessories(plr,pdata)
		end)

		pdata:FindFirstChild("Race").Changed:Connect(function(val)
			LoadRaceParts(plr.Character)
			updateaccessories(plr,pdata)
			updateStats(plr)
		end)

		local maxlevel = 30

		pdata:FindFirstChild("Dexterity").Changed:Connect(function()
			if pdata:FindFirstChild("Dexterity").Value >= maxlevel * 2 then
				pdata:FindFirstChild("Dexterity").Value = 60
			end
			for _,limb in pairs(char:GetChildren()) do
				if limb:IsA("BasePart") and limb.Transparency ~= 1 then
					local hiteff = game.ReplicatedStorage.Particles.Barrage.DexterityIncrease:Clone()
					hiteff.Parent = limb
					for i,v in pairs(hiteff:GetChildren()) do
						if v:IsA("ParticleEmitter") then
							local count = v:GetAttributes("EmitCount")
							--print(count)
							v:Emit(tonumber(count))
						end
					end

					delay(1,function()
						hiteff:Destroy()
					end)

				end
			end

			local bluntsound = game.ReplicatedStorage.Sounds.Coin:Clone()
			bluntsound.Parent = char.HumanoidRootPart
			bluntsound:Play()
			delay(1,function()
				bluntsound:Destroy()
			end)
		end)

		pdata:FindFirstChild("Tenacity").Changed:Connect(function()
			if pdata:FindFirstChild("Tenacity").Value >= maxlevel * 2 then
				pdata:FindFirstChild("Tenacity").Value = 60
			end
			for _,limb in pairs(char:GetChildren()) do
				if limb:IsA("BasePart") and limb.Transparency ~= 1 then
					local hiteff = game.ReplicatedStorage.Particles.Barrage.TenacityIncrease:Clone()
					hiteff.Parent = limb
					for i,v in pairs(hiteff:GetChildren()) do
						if v:IsA("ParticleEmitter") then
							local count = v:GetAttributes("EmitCount")
							--print(count)
							v:Emit(tonumber(count))
						end
					end

					delay(1,function()
						hiteff:Destroy()
					end)

				end
			end

			local bluntsound = game.ReplicatedStorage.Sounds.Coin:Clone()
			bluntsound.Parent = char.HumanoidRootPart
			bluntsound:Play()
			delay(1,function()
				bluntsound:Destroy()
			end)
		end)

		pdata:FindFirstChild("Vigor").Changed:Connect(function()
			if pdata:FindFirstChild("Vigor").Value >= maxlevel * 2 then
				pdata:FindFirstChild("Vigor").Value = 60
			end
			for _,limb in pairs(char:GetChildren()) do
				if limb:IsA("BasePart") and limb.Transparency ~= 1 then
					local hiteff = game.ReplicatedStorage.Particles.Barrage.VigorIncrease:Clone()
					hiteff.Parent = limb
					for i,v in pairs(hiteff:GetChildren()) do
						if v:IsA("ParticleEmitter") then
							local count = v:GetAttributes("EmitCount")
							--print(count)
							v:Emit(tonumber(count))
						end
					end

					delay(1,function()
						hiteff:Destroy()
					end)

				end
			end

			local bluntsound = game.ReplicatedStorage.Sounds.Coin:Clone()
			bluntsound.Parent = char.HumanoidRootPart
			bluntsound:Play()
			delay(1,function()
				bluntsound:Destroy()
			end)
		end)


		pdata:FindFirstChild("Vitality").Changed:Connect(function()

			if pdata:FindFirstChild("Vitality").Value >= maxlevel * 2 then
				pdata:FindFirstChild("Vitality").Value = 60
			end

			for _,limb in pairs(char:GetChildren()) do
				if limb:IsA("BasePart") and limb.Transparency ~= 1 then
					local hiteff = game.ReplicatedStorage.Particles.Barrage.VitalityIncrease:Clone()
					hiteff.Parent = limb
					for i,v in pairs(hiteff:GetChildren()) do
						if v:IsA("ParticleEmitter") then
							local count = v:GetAttributes("EmitCount")
							--print(count)
							v:Emit(tonumber(count))
						end
					end

					delay(1,function()
						hiteff:Destroy()
					end)

				end
			end

			local bluntsound = game.ReplicatedStorage.Sounds.Coin:Clone()
			bluntsound.Parent = char.HumanoidRootPart
			bluntsound:Play()
			delay(1,function()
				bluntsound:Destroy()
			end)

			local playerVigorPoints = pdata:FindFirstChild("Vitality").Value
			local playerDamage = calculateHealth(playerVigorPoints)


			char.Humanoid.MaxHealth += playerDamage 
		end)


		pdata:FindFirstChild("SkinType").Changed:Connect(function(val)
			LoadRaceParts(plr.Character)
			updateaccessories(plr,pdata)
		end)

		pdata:FindFirstChild("HairType").Changed:Connect(function(val)
			LoadRaceParts(plr.Character)
			updateaccessories(plr,pdata)
		end)

		pdata:FindFirstChild("Affiliation").Changed:Connect(function(val)
			loadguivisuals()
		end)

		local isHandlingHealthChanged = false

		for _,copystuff in pairs(game.StarterPack:GetChildren()) do
			local cl = copystuff:Clone()
			cl.Parent = plr.Backpack
		end

		local detailsatt = script.Head.Details:Clone()
		detailsatt.Parent = char.Head
		detailsatt.BillboardGui.Nameplate.Text = "| "..pdata:FindFirstChild("FirstName").Value .. " " .. pdata:FindFirstChild("LastName").Value.." |"
		detailsatt.BillboardGui.Bountyplate.Text = "| Bounty: ".. tostring(formatNumber(pdata:FindFirstChild("Bounty").Value)).." |"



		local function onHealthChanged(newHealth)
			if isHandlingHealthChanged then
				return
			end

			isHandlingHealthChanged = true

			--updateStats(plr)
			pdata:FindFirstChild("MaxHP").Value = 100
			pdata:FindFirstChild("HP").Value = plr.Character.Humanoid.Health

			isHandlingHealthChanged = false
		end

		plr.Character.Humanoid.HealthChanged:Connect(onHealthChanged)

	end)

end)



game.ReplicatedStorage.Remotes.EquipWeapon.OnServerEvent:Connect(function(plr,eqtype,EqTool)
	local char = plr.Character
	local effects = char:FindFirstChild("Effects")
	local pdata = game.ServerStorage.PlayerData:FindFirstChild(plr.Name.."STATS")

	local weapon1stat = pdata:FindFirstChild("Weapon1")
	local weapon2stat = pdata:FindFirstChild("Weapon2")
	local weapon3stat = pdata:FindFirstChild("Weapon3")

	if eqtype == "Weapon" then

		if weapon1stat.Value == "None" then
			weapon1stat.Value = EqTool.Name
			loadweaponparts(plr,pdata)
			EqTool:Destroy()
		elseif weapon1stat.Value ~= "None" and weapon2stat.Value == "None" then
			weapon2stat.Value = EqTool.Name
			loadweaponparts(plr,pdata)
			EqTool:Destroy()
		elseif weapon1stat.Value ~= "None" and weapon2stat.Value ~= "None" and weapon3stat.Value == "None" then
			weapon3stat.Value = EqTool.Name
			loadweaponparts(plr,pdata)
			EqTool:Destroy()
		end

	end

end)


local carrywelds = {} -- Create an empty table to store the carry welds
carry = false
cancrrrrr = true
local carryweldz = {} -- Create an empty table to store the carry welds

game.ReplicatedStorage.Remotes.Carry.OnServerEvent:Connect(function(plr, state)
	local char = plr.Character
	local hrp = char.HumanoidRootPart
	print("Recieved Carry")
	if state == true then
		carry = true
		local closest = nil -- Variable to hold the closest character
		local minDistance = 10 -- Variable to hold the minimum distance

		for _, nearby in pairs(game.Workspace.Alive:GetChildren()) do
			if nearby:FindFirstChild("Effects"):FindFirstChild("Knocked") and not nearby:FindFirstChild("Effects"):FindFirstChild("Died") then 
				if nearby ~= char and nearby.HumanoidRootPart then
					local distance = (nearby.HumanoidRootPart.Position - hrp.Position).magnitude
					-- Check if the current character is closer than the closest character found so far
					if distance < minDistance and nearby.Effects:FindFirstChild("Knocked") and cancrrrrr then
						closest = nearby -- Update the closest character
						minDistance = distance -- Update the minimum distance
						carry = true
						cancrrrrr = false
						closest.Humanoid:SetStateEnabled(Enum.HumanoidStateType.PlatformStanding, true)
						closest.Humanoid:SetStateEnabled(Enum.HumanoidStateType.GettingUp, false)
						closest.Humanoid:ChangeState(Enum.HumanoidStateType.FallingDown)

						local carryweld = Instance.new("Weld")
						carryweld.C1 = CFrame.new(1.23240662, 0.0300750732, -1.75585151, -1, 1.19724868e-12, 1.99672904e-05, 1.99672904e-05, 5.96047229e-08, 1, 7.10388449e-15, 1, -5.96047229e-08)
						carryweld.Parent = hrp
						carryweld.Part0 = hrp
						carryweld.Part1 = closest.HumanoidRootPart
						table.insert(carrywelds, carryweld)

						local carrval = Instance.new("NumberValue")
						carrval.Name = "Carried"
						carrval.Parent = closest.Effects
						--               table.insert(carryweldz, carrval)


						local pcarrval = Instance.new("ObjectValue")
						pcarrval.Name = "Carrying"
						--pcarrval.Value = closest
						pcarrval.Parent = char.Effects


						for _, limbz in pairs(closest:GetChildren()) do
							if limbz:IsA("BasePart") or limbz:IsA("MeshPart") then
								limbz.CollisionGroup = "Phantom"
								limbz.Massless = true
								if limbz.Name == "Torso" then
									limbz.CanCollide = true
								end
							end
						end


						-- Check and modify collision and mass properties of limbs
						local humanoid = closest.Humanoid
						--local limbs = humanoid:GetPlayingAnimationTracks()
						--for _, limb in pairs(limbs) do
						--    local part = limb.Name
						--    if limb.Motor and limb.Motor.CanCollide and part ~= "Carried" then
						--        limb.Motor.CanCollide = false
						--        limb.Motor.Massless = true
						--        local resetProperties = Instance.new("BindableEvent")
						--        resetProperties.Name = "ResetProperties"
						--        resetProperties.Parent = limb.Motor
						--        resetProperties.Event:Connect(function()
						--            limb.Motor.CanCollide = true
						--            limb.Motor.Massless = false
						--            resetProperties:Destroy()
						--        end)
						--    end
						--end

						local playanimvictim = closest.Humanoid:LoadAnimation(game.ReplicatedStorage.Animations.Carried)
						playanimvictim.Name = "Carried"
						playanimvictim:Play()	

						closest.Humanoid:SetStateEnabled(Enum.HumanoidStateType.PlatformStanding, true)
						closest.Humanoid:SetStateEnabled(Enum.HumanoidStateType.GettingUp, false)
						closest.Humanoid:ChangeState(Enum.HumanoidStateType.FallingDown)

						spawn(function()
							while carry == true do
								closest.Humanoid:SetStateEnabled(Enum.HumanoidStateType.PlatformStanding, true)
								closest.Humanoid:SetStateEnabled(Enum.HumanoidStateType.GettingUp, false)
								closest.Humanoid:ChangeState(Enum.HumanoidStateType.FallingDown)
								-- Check and modify collision and mass properties of limbs

								for _, limbz in pairs(closest:GetChildren()) do
									if limbz:IsA("BasePart") or limbz:IsA("MeshPart") then
										limbz.CollisionGroup = "Phantom"
										limbz.Massless = true
										if limbz.Name == "Torso" then
											limbz.CanCollide = false
										end
									end
								end
								wait()
							end
						end)

					end
				end
			end
		end
	elseif state == false then
		carry = false
		for i = #carrywelds, 1, -1 do
			local child = carrywelds[i]
			if child:IsA('Weld') then
				child:Destroy()
			end
			table.remove(carrywelds, i)
		end

		for _,newstuff in pairs(carryweldz) do
			newstuff:Destroy()
		end

		for _, nearby in pairs(game.Workspace.Alive:GetChildren()) do
			if nearby ~= char and nearby.HumanoidRootPart and nearby.Effects:FindFirstChild("Carried") then
				nearby.Humanoid:SetStateEnabled(Enum.HumanoidStateType.PlatformStanding, false)

				-- Reset collision and mass properties of limbs
				for _, limbz in pairs(nearby:GetChildren()) do
					if limbz:IsA("BasePart") or limbz:IsA("MeshPart") then
						limbz.CollisionGroup = "CharacterModels"
						limbz.Massless = false
						if limbz.Name == "Torso" then
							limbz.CanCollide = true
						end
					end
				end

				for i,v in pairs(nearby.Humanoid:GetPlayingAnimationTracks()) do
					v:Stop()
				end

				if nearby.Effects:FindFirstChild("Carried") then
					nearby.Effects.Carried:Destroy()
				end
				if char.Effects:FindFirstChild("Carrying") then
					char.Effects:FindFirstChild("Carrying"):Destroy()
				end

				local ragv = Instance.new("NumberValue")
				ragv.Name = "Ragdolled"
				ragv.Parent = nearby.Effects

				cancrrrrr = true	

				local humanoid = nearby.Humanoid
				--local limbs = humanoid:GetPlayingAnimationTracks()
				--for _, limb in pairs(limbs) do
				--    if limb.Motor and limb.Motor:FindFirstChild("ResetProperties") then
				--        limb.Motor.ResetProperties:Fire()
				--    end
				--end
			end
		end
	end
end)


--game.ReplicatedStorage.Remotes.Carry.OnServerEvent:Connect(function(plr, state)
--	local char = plr.Character
--	local hum = char.Humanoid
--	local effects = char.Effects

--	if char:FindFirstChild("Carrying") then
--		char.Carrying:Destroy()
--		--print("Stopped Carry")
--	else
--		if effects:FindFirstChild("Stunned") or effects:FindFirstChild("Ragdolled") or effects:FindFirstChild("Invis") then
--			return
--		end

--		local grippp = false

--		for i, v in pairs(game.Workspace.Alive:GetChildren()) do
--			if v.Effects:FindFirstChild("Ragdolled") and v.Effects:FindFirstChild("Knocked") and not v.Effects:FindFirstChild("Carried") and v.Humanoid.Health > 0 and not v.Effects:FindFirstChild("NoCarry") then
--				local mag = (char.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude

--				if mag < 6.5 and not grippp then
--					local changeBack = {}
--					if v.Effects:FindFirstChild("Carried") then
--						return
--					end
--					grippp = true
--					local carriedVal = Instance.new("BoolValue", v.Effects)
--					carriedVal.Name = "Carried"
--					local Seat = Instance.new("Seat", char)
--					Seat.CanCollide = false
--					Seat.Anchored = false
--					Seat.Massless = true
--					Seat.Size = Vector3.new(3, 1, 4)
--					Seat.Transparency = 1
--					Seat.CFrame = plr.Character.HumanoidRootPart.CFrame * CFrame.new(0, 0, -1)
--					Seat.Name = "Carrying"
--					local weld = Instance.new("WeldConstraint")
--					weld.Parent = Seat
--					weld.Part1 = plr.Character.Torso
--					weld.Part0 = Seat
--					Seat:Sit(v.Humanoid)
--					if v.Effects:FindFirstChild("Ragdolled") then
--						v.Effects:FindFirstChild("Ragdolled"):Destroy()
--					end
--					table.insert(changeBack, v)

--        v.Humanoid:SetStateEnabled(Enum.HumanoidStateType.GettingUp, false)
--        v.Humanoid:ChangeState(Enum.HumanoidStateType.FallingDown)

--					local change
--					change = Seat.Changed:Connect(function()
--						if Seat.Occupant == nil then
--							if v and v:FindFirstChild("Humanoid") then
--								v.Humanoid.Sit = false
--								local eff = v:FindFirstChild("Effects")
--								if eff then
--									local ragdolled = Instance.new("Folder")
--									ragdolled.Name = "Ragdolled"
--									ragdolled.Parent = eff
--									local executable = Instance.new("Folder")
--									executable.Name = "Executable"
--									executable.Parent = eff
--								end
--							end
--							Seat:Destroy()
--							change:Disconnect()
--						end
--					end)

--					for i, ggz in pairs(v:GetDescendants()) do
--						if ggz:IsA("BasePart") and not ggz.Massless then
--					table.insert(changeBack, ggz)
--					ggz.Massless = true
--					ggz.CollisionGroup = "Phantom"
--					end
--					end
--				v.Humanoid.PlatformStand = true

--				repeat
--					wait()
--	        v.Humanoid:ChangeState(Enum.HumanoidStateType.FallingDown)
--        v.Humanoid:SetStateEnabled(Enum.HumanoidStateType.GettingUp, false)
--				until Seat.Parent ~= char or char.Effects:FindFirstChild("Ragdolled") or char.Effects:FindFirstChild("Invis") or not Seat.Parent or not carriedVal.Parent

--				--print("Carry Stopped?!?!?", Seat.Parent ~= char, char.Effects:FindFirstChild("Ragdolled"), char.Effects:FindFirstChild("Ragdolled"), Seat.Parent, carriedVal.Parent)

--				if v and v:FindFirstChild("Humanoid") then
--					v.Humanoid.Sit = false
--					local eff = v:FindFirstChild("Effects")
--					if eff then
--						local ragdolled = Instance.new("Folder")
--						ragdolled.Name = "Ragdolled"
--						ragdolled.Parent = eff
--						local executable = Instance.new("Folder")
--						executable.Name = "Executable"
--						executable.Parent = eff
--					end
--				end

--				for _, tablestuff in pairs(changeBack) do
--					if tablestuff:FindFirstChild("Humanoid") then
--						tablestuff:FindFirstChild("Humanoid").PlatformStand = true
--						for _, limbs in pairs(tablestuff:GetChildren()) do
--							if limbs:IsA("MeshPart") or limbs:IsA("Part") or limbs:IsA("BasePart") then
--								limbs.Massless = false
--								limbs.CollisionGroup = "Default"
--							end
--						end
--					end
--				end

--				Seat:Destroy()
--				change:Disconnect()
--				carriedVal:Destroy()
--			end
--		end
--	end
--end
--end)

--gripsetup = {}
--cangetgripped = false
--gettinggripped = false
--grippedperson = nil

--game.ReplicatedStorage.Remotes.Grip.OnServerEvent:Connect(function(plr,state)
--	print("Recieved Grip")
--	local char = plr.Character
--	local hrp = char.HumanoidRootPart

--	if state == true then
--		carry = true
--		local closest = nil -- Variable to hold the closest character
--		local minDistance = 10 -- Variable to hold the minimum distance
--		for _, nearby in pairs(game.Workspace.Alive:GetChildren()) do
--			if nearby:FindFirstChild("Effects"):FindFirstChild("Knocked") and not nearby:FindFirstChild("Effects"):FindFirstChild("Died") then
--				if nearby ~= char and nearby.HumanoidRootPart then
--					local distance = (nearby.HumanoidRootPart.Position - hrp.Position).magnitude
--					-- Check if the current character is closer than the closest character found so far
--					if distance < minDistance and nearby.Effects:FindFirstChild("Knocked") and cancrrrrr and not nearby.Effects:FindFirstChild("Died") then
--						closest = nearby -- Update the closest character
--						minDistance = distance -- Update the minimum distance
--						grippedperson = closest

--						local gripval = Instance.new("NumberValue")
--						gripval.Name = "GettingGripped"
--						gripval.Parent = closest.Effects

--						local gripval2 = Instance.new("NumberValue")
--						gripval2.Name = "Gripping"
--						gripval2.Parent = char.Effects

--						--local speedval = Instance.new("NumberValue")
--						--speedval.Name = "Speed"
--						--speedval.Value = -999999999
--						--speedval.Parent = char.Effects
--						--local JumpVal = Instance.new("NumberValue")
--						--JumpVal.Name = "Jump"
--						--JumpVal.Value = -999999999
--						--JumpVal.Parent = char.Effects

--						char.Humanoid.AutoRotate = false				

--						local speedval2 = Instance.new("NumberValue")
--						speedval2.Name = "Speed"
--						speedval2.Value = -999999999
--						speedval2.Parent = closest.Effects
--						local JumpVal2 = Instance.new("NumberValue")
--						JumpVal2.Name = "Jump"
--						JumpVal2.Value = -999999999
--						JumpVal2.Parent = closest.Effects

--						gettinggripped = true

--						if closest.Effects:FindFirstChild("Ragdolled") then
--							closest.Effects:FindFirstChild("Ragdolled"):Destroy()
--						end

--						closest.HumanoidRootPart.Anchored = true


--						closest.HumanoidRootPart.Position = char.HumanoidRootPart.CFrame * CFrame.new(-.7,0,-3.8).Position
--						closest.HumanoidRootPart.Orientation = char.HumanoidRootPart.Orientation + Vector3.new(0, 180, 0)

--						local gripanim = char.Humanoid:LoadAnimation(game.ReplicatedStorage.Animations.Brawl.Grip)
--						local grippedanim = closest.Humanoid:LoadAnimation(game.ReplicatedStorage.Animations.Brawl.Gripped)
--						gripanim.Name = "Gripping"
--						grippedanim.Name = "GetGripped"
--						gripanim:Play()
--						grippedanim:Play()

--						spawn(function()
--							while gettinggripped == true do
--								wait()
--								--nearby.Humanoid.AutoRotate = false
--								--char.Humanoid.AutoRotate = false

--								if char.Effects:FindFirstChild("Stunned") then
--									closest.HumanoidRootPart.Anchored = false
--									gripanim:Stop()
--									grippedanim:Stop()
--									gripval:Destroy()
--									gripval2:Destroy()
--									--speedval:Destroy()
--									--JumpVal:Destroy()
--									char.Humanoid.AutoRotate = true
--									speedval2:Destroy()
--									JumpVal2:Destroy()
--									local gripval2 = Instance.new("NumberValue")
--									gripval2.Name = "Ragdolled"
--									gripval2.Parent = closest.Effects
--									break end
--							end
--						end)


--						gripanim:GetMarkerReachedSignal("Kill"):Connect(function()
--							--print("Killed Enemy")
--							closest.HumanoidRootPart.Anchored = false
--							gettinggripped = false
--							--print("Breaking JOints")
--							char.Humanoid.AutoRotate = true
--							for i,v in pairs(grippedperson.Humanoid:GetPlayingAnimationTracks()) do
--								if v.Name == "GetGripped" then
--									v:Stop()
--								end
--							end
--							for i,v in pairs(char.Humanoid:GetPlayingAnimationTracks()) do
--								if v.Name == "Gripping" then
--									v:Stop()
--								end
--							end
--							for i,v in pairs(grippedperson:FindFirstChild("Effects"):GetChildren()) do
--								if v.Name == "GettingGripped" then
--									v:Destroy()
--								end
--							end
--							for i,v in pairs(char:FindFirstChild("Effects"):GetChildren()) do
--								if v.Name == "Gripping"  then
--									v:Destroy()
--								end
--							end
--							local gripval2 = Instance.new("NumberValue")
--							gripval2.Name = "Died"
--							gripval2.Parent = closest.Effects
--							nearby.Humanoid.Health = 0
--						end)			
--					end
--				end
--			end
--		end
--	elseif state == false then
--		gettinggripped = false
--		if not grippedperson:FindFirstChild("Humanoid") then return end
--		grippedperson.HumanoidRootPart.Anchored = false
--		for i,v in pairs(grippedperson.Humanoid:GetPlayingAnimationTracks()) do
--			if v.Name == "GetGripped" then
--				v:Stop()
--			end
--		end
--		for i,v in pairs(char.Humanoid:GetPlayingAnimationTracks()) do
--			if v.Name == "Gripping" then
--				v:Stop()
--			end
--		end
--		for i,v in pairs(grippedperson:FindFirstChild("Effects"):GetChildren()) do
--			if v.Name == "GettingGripped" then
--				v:Destroy()
--			end
--		end
--		for i,v in pairs(char:FindFirstChild("Effects"):GetChildren()) do
--			if v.Name == "Gripping"  then
--				v:Destroy()
--			end
--		end
--		local gripval2 = Instance.new("NumberValue")
--		gripval2.Name = "Ragdolled"
--		gripval2.Parent = grippedperson.Effects
--	end

--end)
