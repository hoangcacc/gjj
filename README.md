getgenv().Setting = {
    ["Team"] = "Pirates",
    ["Webhook"] = {
        ["Enable"] = false, 
        ["Url"] = ""
    },
    ["Skip"] = {
        ["Race V4"] = true,
        ["Fruit"] = { 
            "",
            "Venom-Venom",
            "",
            "Portal-Portal"
        }
    },
    ["Chat"] = {
        ["Enabled"] = true,
        ["Content"] = {"Báº£o best config"},
    },
    ["Misc"] = {
        ["Lock Bounty"] = {0, 30000000},
        ["Hide If Low Health"] = true,
        ["Hide Health"] = {4000,5000},
        ["Lock Camera"] = true,
        ["FPS Boost"] = false,
        ["White Screen"] = false,
        ["Bypass TP"] = true, 
        ["Spam All Skill On V4"] = true, 
        ["Random Fruit & Store"] = true,
        ["Random Suprise"] = true
    },
    ["Melee"] = {
        ["Enable"] = true,
        ["Delay"] = 1.5,
        ["Z"] = {["Enable"] = true, ["Hold Time"] = 0},
        ["X"] = {["Enable"] = true, ["Hold Time"] = 0},
        ["C"] = {["Enable"] = true, ["Hold Time"] = 0}
    },
    ["Fruit"] = {
        ["Enable"] = false,
        ["Delay"] = 2,
        ["Z"] = {["Enable"] = true, ["Hold Time"] = 0},
        ["X"] = {["Enable"] = true, ["Hold Time"] = 0},
        ["C"] = {["Enable"] = true, ["Hold Time"] = 0},
        ["V"] = {["Enable"] = true, ["Hold Time"] = 1.25},
        ["F"] = {["Enable"] = false, ["Hold Time"] = 0}
    },
    ["Sword"] = {
        ["Enable"] = true,
        ["Delay"] = 1,
        ["Z"] = {["Enable"] = true, ["Hold Time"] = 0},
        ["X"] = {["Enable"] = true, ["Hold Time"] = 0}
    },
    ["Gun"] = {
        ["Enable"] = false,
        ["Delay"] = 1,
        ["Z"] = {["Enable"] = true, ["Hold Time"] = 0},
        ["X"] = {["Enable"] = true, ["Hold Time"] = 0}
    }
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/vuquocoai123/lua/main/AutoBountyV2Beta"))()
