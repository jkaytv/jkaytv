if not game:IsLoaded() then repeat game.Loaded:Wait() until game:IsLoaded() end
-- FPS Lock
setfpscap(60)

-- Quest / เควส
_G.Quest = { 
    ['Dojo Quest (8 Belt)'] = false, --New!⭐
    ['RGB Aura Haki'] = true, 
    ['Pull Lever'] = true,
    ['Quest Dough Awaken'] = true
}
-- Race / เผ่า
_G.Race = { 
    ['Select Race'] = {'','Fishman','Skypiea',''},
    ['Lock Race'] = false,
    ['Evo Race V3'] = true
}
-- Melee / หมัด
_G.Melee = { 
    ['Godhuman'] = true
}
-- Sword / ดาบ
_G.Sword = { 
    ['Saber'] = true,
    ['Midnight Blade'] = false,
    ['Shisui'] = true,
    ['Saddi'] = true,
    ['Wando'] = true,
    ['Yama'] = true,
    ['Koko'] = false,
    ['Rengoku'] = true,
    ['Canvander'] = true,
    ['Buddy Sword'] = true,
    ['Twin Hooks'] = false,
    ['SpikeyTrident'] = true,
    ['Hallow Scryte'] = true,
    ['Dark Dagger'] = true,
    ['Tushita'] = true,
    ['True Triple Katana'] = true,
    ['Cursed Dual Katana'] = true,
    ['Shark Anchor'] = true,
    ['Dragonheart'] = true --New!⭐
}
-- Farm Gun / ฟามปืน
_G.Gun = {  
    ['Kabucha'] = true,
    ['Acidum Rifle'] = true,
    ['Soul Guitar'] = true, 
    ['Serpent Bow'] = true,
    ['Dragonstorm'] = true --New!⭐
}
-- Devil Fruit / ผลปีศาจ
_G.Fruit = { 
    ['Main Fruit'] = {'nil'},
    ['Select Fruit'] = {'Dark-Dark','Magma-Magma'}
}
-- Mastery / มาสเตอรี่
_G.Mastery = { 
    ['Melee'] = true,
    ['Sword'] = true,
    ['Fruit'] = true
}
-- Setting / ตั้งค่าหลัก
_G.Setting = {
    ['FPS Booster Super X10'] = false, -- for AWP, Wave
    ['FPS Booster'] = true,
    ['Auto Close Ui'] = false
}

script_key="dOLZCgZrmLBUiEkvANYqubhZJKJGNPTU";
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/58876769bc015b00b9a3008484e99085.lua"))()
