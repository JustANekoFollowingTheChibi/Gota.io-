 static void UpdatePresence()
    {
        DiscordRichPresence discordPresence;
        memset(&discordPresence, 0, sizeof(discordPresence));
        discordPresence.state = "Playing Solo";
        discordPresence.details = "Neko Chibi";
        discordPresence.startTimestamp = 1507665886;
        discordPresence.endTimestamp = 1507665886;
        discordPresence.largeImageKey = "anime-cat-drawing-52_jpg";
        discordPresence.largeImageText = "Sever: Power";
        discordPresence.smallImageKey = "pin_35_png";
        discordPresence.smallImageText = "Level 110";
        discordPresence.partyId = "ae488379-351d-4a4f-ad32-2b9b01c91657";
        discordPresence.partySize = 1;
        discordPresence.partyMax = 1;
        discordPresence.joinSecret = "= ";
        Discord_UpdatePresence(&discordPresence);
    }
