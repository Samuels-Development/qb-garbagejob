# Garbage Job V2 For QB-Core

Repost of the official qb-garbagejob, with QB-Target Interaction!

You need to add your own Ped!

# Rework Update
- Job now pays per bag delivered on a configured scale.
- Job Randomises the amount of stops and what stops the user goes to
- Job traks rewards on the server rather than client
- Optional Cryptostick find per stop
- Highly Configurable.

# QB-Target Interaction 

Add this to your Config.TargetModels in the init.lua of the qb-target script, works alongside the ms-peds version available on this GitHub!

		["garbageman"] = {
			models = { 
				"s_m_y_garbage",
			},
				options = {
					{
						type = "client",
						event = "getGarbagePaySlip",
						icon = "fas fa-clipboard",
						label = "Collect Paycheck",
						job = "garbage"
					},
					{
						type = "client",
						event = "GarbageTruckSpawn",
						icon = "fas fa-clipboard",
						label = "Spawn Garbage-Truck",
						job = "garbage"
					},
				},
				distance = 2.5,
			},

