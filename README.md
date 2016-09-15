# Idle_Random_Map
Changes server to a random map from list of maps when server has defined number of players after a defined time.
By default server will change maps when there are 0 players on for 5 minutes.
## Cvars:
1. sm_irm_idle_time: Time limit to change map (Default: 5)
2. sm_irm_log_map_change: Enables or disables map selection logging (Default: 0)
3. sm_irm_players_change: How many players on server to start map change timer (Default: 0)

## Maps:
Maps are read from addons/sourcemod/configs/idle_random_map.ini
One map per line

Allied Modders thread:
https://forums.alliedmods.net/showthread.php?t=280036