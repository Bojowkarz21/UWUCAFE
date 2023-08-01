# UWUCAFE
UWUCAFE, fullwork, job, interior, memorygame (:

Prefix by chief.bojowkarz

Leaked by Xentiss#7406

ox_inventory/data/items.lua

	['kawiarnia_kawa'] = {
		label = 'Zywkła kawa',
		weight = 20,
	},

	

	['kawiarnia_ziarna'] = {
		label = 'Ziarna kawy',
		weight = 20,
	},


	['kawiarnia_owoce'] = {
		label = 'Owoce',
		weight = 20,
	},


	['coffee'] = {
		label = 'Kawa',
		weight = 25,
		client = {
			status = { thirst = 350000 },
			anim = { dict = 'mp_player_intdrink', clip = 'loop_bottle' },
			prop = { model = `p_ing_coffeecup_01`, pos = vec3(0.01, 0.01, 0.06), rot = vec3(5.0, 5.0, -180.5) },
			usetime = 2500,
		}
	},

	['coffeee'] = {
		label = 'Kawa Cappucino ',
		weight = 25,
		client = {
			status = { thirst = 350000 },
			anim = { dict = 'mp_player_intdrink', clip = 'loop_bottle' },
			prop = { model = `p_ing_coffeecup_01`, pos = vec3(0.01, 0.01, 0.06), rot = vec3(5.0, 5.0, -180.5) },
			usetime = 2500,
		}
	},
	
	['coffeeee'] = {
		label = 'Kawa Latte',
		weight = 25,
		client = {
			status = { thirst = 350000 },
			anim = { dict = 'mp_player_intdrink', clip = 'loop_bottle' },
			prop = { model = `p_ing_coffeecup_01`, pos = vec3(0.01, 0.01, 0.06), rot = vec3(5.0, 5.0, -180.5) },
			usetime = 2500,
		}
	},

ox_inventory/data/stashes.lua

	{
		coords = vec3(-584.08, -1062.05, 22.34),  
		target = {
			loc = vec3(-584.08, -1062.05, 22.34), 
			length = 1,
			width = 1,
			heading = 340,
  	minZ = 21.34,
  	maxZ = 23.34,
			label = 'Sprawdz tace'
		},
		name = 'kawka2',
		label = 'Taca #1',
		owner = false,
		slots = 5,
		weight = 70000,
	},

	
	{
		coords = vec3(-583.88, -1059.23, 22.34),  
		target = {
			loc = vec3(-583.88, -1059.23, 22.34), 
			length = 1,
			width = 1,
			heading = 340,
  	minZ = 21.34,
  	maxZ = 23.34,
			label = 'Sprawdz tace'
		},
		name = 'kawka1',
		label = 'Taca #1',
		owner = false,
		slots = 5,
		weight = 70000,
	},

		{
		coords = vec3(-598.34, -1063.11, 22.34),
		target = {
			loc = vec3(-598.34, -1063.11, 22.34),
			length = 5.0,
			width = 2.0,
			heading = 0,
			minZ = 20.34,
            maxZ = 23.34,
			label = 'Otwórz Magazyn'
		},
		name = 'kawiarnia_l',
		label = 'Magazyn',
		owner = false,
		slots = 50,
		weight = 70000,
		groups = {['kawiarnia'] = 0}
	},
