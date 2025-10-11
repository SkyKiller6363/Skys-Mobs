# Modular Kill Tracker

**Overview**  
The Modular Kill Tracker is a versatile system designed to track how many times each player has killed specific mobs. Perfect for everything from simple leaderboards to intricate reward systems, this add-on works right out of the box.

---

## Key Features

- **Easy Integration**  
  Just add `Template: TrackKills` to any mob you want to track.
  
  Or add `Template: TrackKills_Threat` to any boss mob that uses Threat Tables, so multiple players can get points for the kill, instead of just the last player to hit it. 
- **Player-Specific Tracking**  
  Keeps a kill count per player without additional configuration.
- **PlaceholderAPI Compatibility**  
  Use the `%mythic_var_<InternalMobName>Killed%` placeholder to display kill counts in your scoreboard, chat, or other placeholders-supported plugins.
    - Using the `ChangeOutput` eCloud, you can use the following placeholder to make `[Undefined]` return as `0` isntead.
      - `%changeoutput_equals_input:{mythic_var_<InternalMobName>Killed}_matcher:[Undefined]_ifmatch:0_else:{mythic_var_<InternalMobName>Killed}%`


---

## How It Works

1. **Install the Pack**  
   Drop the Modular Kill Tracker files into your server, then reload your configuration.
2. **Add the Template**  
   Attach `Template: TrackKills` to any mob in your MythicMobs files.
3. **View the Kill Counts**  
   - For players with zero kills, the placeholder displays `[Undefined]`.
     - Unless using the `ChangeOutput` eCloud example from above. Then it returns 0.
   - For players with one or more kills, it returns the exact numeric total.

---

## Example Usage

- **Leaderboards**  
  Display the highest kill counts on an in-game leaderboard or on your website.  
- **Reward Systems**  
  Trigger rewards or achievements when players reach a certain kill threshold.

---

## Installation Instructions

1. **Download the Pack Folder**  
   Click [here](https://downgit.github.io/#/home?url=https://github.com/SkyKiller6363/Skys-Mobs/tree/main/Packs/KillTracker) to download the entire pack folder (not just individual files).
2. **Upload to Your Server**  
   Navigate to your server's `plugins/MythicMobs/Packs` directory.
3. **Place the Downloaded Folder**  
   Drag and drop or upload the **unzipped** `KillTracker` folder into the `Packs` directory.
4. **Reload Mythic Mobs**  
   Use the `/mm reload` command to reload MythicMobs so the pack is recognized.

That’s it! Now you can add the Template configurations included in this MythicMobs Pack to your own mobs to start Tracking.
