getgenv().petsGoConfig = {
    -- Event config
    -- true will open event gift bag/egg
    -- false will auto mail gift bag/egg
    CONSUME_EVENT_GIFT_BAG = true,
    CONSUME_EVENT_EGG = true, -- Hype eggs not included

    WEBHOOK_URL = "https://discord.com/api/webhooks/1304677344148979772/cS81U8uDXdR-4O7vst5Wk59u82Fa6ij2lSNvORYTT6bSy8gyvPQ-c2UbaD7nfKVRYHSZ",
    MAILING_WEBHOOK_URL = "https://discord.com/api/webhooks/1311596125861576714/v6zVuGK0w7_B-KBXblHLyBxnifZr98KKa51a_mtx3zPvGOOkU9tGdpVjHN1mV4JX0g8v",
    DISCORD_ID = "1120232109165006859",  -- Required!!! (For public-webhook)
    WEBHOOK_ODDS = 200000000, -- Minimum Pet Odds To Trigger Webhook

    DIAMOND_EGG = true,  -- true = Diamond Egg, false = F2P Egg
    
    MAILING = true,  -- Auto mail
    MAIL_FISHING_ROD = true,  -- true = mail, false = keep fishing rod on account (FASTER Fishing)
    MAIL_WEBHOOK_ODDS = 100000000, -- Minimum Pet Odds To Trigger MAIL Webhook
    MAIL_PET_ODDS = 100000000,  -- Minimum Pet Odds To Mail
    USERNAME_TO_MAIL = "HBT_NKB374XSH6" -- Mail Pet To Username
}

loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/e81ea00ef49a917bb1242da4f41dc4f9.lua"))()
