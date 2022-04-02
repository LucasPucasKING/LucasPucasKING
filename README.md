{
	"name": "roblox-ts-game",
	"tree": {
		"$className": "DataModel",
		"ServerScriptService": {
			"$className": "ServerScriptService",
			"TS": {
				"$path": "out/server" // server folder goes in ServerScriptService.TS
			}
		},
		"ReplicatedStorage": {
			"$className": "ReplicatedStorage",
			// this _must_ stay the same (except for the name)
			"rbxts_include": {
				"$path": "include",
				"node_modules": {
					"$path": "node_modules/@rbxts"
				}
			},
			"TS": {
				"$path": "out/shared" // shared folder goes in ReplicatedStorage.TS
			}
		},
		"StarterPlayer": {
			"$className": "StarterPlayer",
			"StarterPlayerScripts": {
				"$className": "StarterPlayerScripts",
				"TS": {
					"$path": "out/client" // client folder goes in StarterPlayer.StarterPlayerScripts.TS
				}
			}
		}
	}
}
https://github.com/LucasPucasKING/LucasPucasKING.git
