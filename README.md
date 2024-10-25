users = {'YaEsta_EnUs0', ', 'ErrorGamer11', 'rafael_army9', 'Jeffelop2002', 'Subaru_Badass', 'bookiesalt2', 'Robloxame555',

	

	--Remover el darkzbiade, BemYaer, L4superLEGIT, jwn2odi2,Scripting_Business, yashwant_gaming0 el domingo (script por invitacion)
}


local isBuyer = falsea
local me = game:GetService('Players').LocalPlayer


local function checkIsBuyer()
	for _, v in pairs(users) do
		if string.lower(v) == string.lower(me.Name) then
			isBuyer = true
			break
		end
	end
end

while not isBuyer do
	checkIsBuyer()
end
