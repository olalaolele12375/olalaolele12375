local allowedUserId = 7400931513 -- UserId của bạn
if game.Players.LocalPlayer.UserId ~= allowedUserId then
    return warn("Bạn không có quyền sử dụng script này.")
end

-- Kiểm tra sự kiện trong game
local function checkEvent()
    local currentEvent = nil
    -- Kiểm tra các sự kiện như Full Moon, Rip Indra, Leviathan, v.v.
    if game:GetService("ReplicatedStorage"):FindFirstChild("FullMoon") then
        currentEvent = "Full Moon"
    elseif game:GetService("ReplicatedStorage"):FindFirstChild("RipIndra") then
        currentEvent = "Rip Indra"
    elseif game:GetService("ReplicatedStorage"):FindFirstChild("Douking") then
        currentEvent = "Douking"
    elseif game:GetService("ReplicatedStorage"):FindFirstChild("Leviathan") then
        currentEvent = "Leviathan"
    elseif game:GetService("ReplicatedStorage"):FindFirstChild("MysteriousIsland") then
        currentEvent = "Đảo Bí ẩn"
    end
    
    -- In sự kiện
    if currentEvent then
        print("Sự kiện phát hiện: " .. currentEvent)
        -- Logic thêm vào để tham gia server có sự kiện này
    else
        print("Không có sự kiện đặc biệt trên server này.")
    end
end

-- Gọi hàm kiểm tra sự kiện
checkEvent()- 👋 Hi, I’m @olalaolele12375
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
olalaolele12375/olalaolele12375 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
