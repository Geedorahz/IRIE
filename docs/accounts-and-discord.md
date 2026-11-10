# Accounts, Steam, Discord and RetroAchievements

Everything here is optional and off until you set it up. Most of it lives in **Settings > Integrations**.

## Users

IRIE opens to a title screen and a user menu. Each user keeps their own favorites, play time, game order and settings. Dolphin saves are kept apart too: whoever plays Dolphin first keeps the saves already on disk, and every user after gets a folder of their own. Press `E` on a user to edit them.

## Account and friends

**Settings > Account** signs you up with a code sent to your email. There is no password. You get a tag like `name#1234`; give it to a friend, or add theirs on the **Social** page.

Friends can see your name, picture, banner, bio, favorites, and what you're playing. **Show friends what I'm playing** on the Social page, or **Status** in the pause menu, turns that off.

## Steam

Choose **Sign in with Steam** (in **Integrations**). IRIE confirms the sign-in with Steam itself. If the Steam app is also signed in on this PC, IRIE adds your installed Steam games to the library, and shows your play history, achievements and which Steam friends are online.

Steam games start through Steam, quietly in the background, and get the pause menu like any other game.

## Discord

- **Show what I'm playing:** create an application at [discord.com/developers](https://discord.com/developers), paste its Application ID, and keep the Discord app open.
- **Who's online:** add your server ID and turn on **Enable Server Widget** in that server's settings.
- **Open server:** set your invite link.
- **Post to a channel:** create a channel webhook and paste its URL. It is stored encrypted by Windows.
- **Find friends who use IRIE:** link Discord on the Social page. Discord only shares friends lists with apps it has approved, so IRIE shows friends who have also linked Discord, and people from your servers.

## RetroAchievements

Add your username and Web API key under **Integrations**. The key is on retroachievements.org under **Settings**, then **Keys**, and is stored encrypted on this PC. The emulator unlocks achievements; IRIE shows them in the pause menu's **Trophies** panel and on your profile. If IRIE can't tell which RetroAchievements game a file is, search for it once and pick it, and IRIE remembers.

## Appear offline

**Status** in the pause menu hides your game from IRIE friends and takes your game off your Discord profile until you choose Online again.
