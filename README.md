local a=Instance.new("ScreenGui")local b=Instance.new("Frame")local c=Instance.new("TextButton")local d=Instance.new("UIGradient")local e=Instance.new("UICorner")local f=Instance.new("TextBox")local g=Instance.new("UICorner")local h=Instance.new("TextBox")local i=Instance.new("UICorner")local j=Instance.new("TextLabel")local k=Instance.new("TextLabel")local l=Instance.new("UICorner")local m=Instance.new("ImageButton")local n=Instance.new("TextLabel")local o=Instance.new("UICorner")local p=Instance.new("TextLabel")a.Name=" "a.Parent=game.Players.LocalPlayer:WaitForChild("PlayerGui")a.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;a.ResetOnSpawn=false;b.Name="LoginFrame"b.Parent=a;b.Active=true;b.BackgroundColor3=Color3.fromRGB(30,30,30)b.Position=UDim2.new(0.0500000007,0,0.200000003,0)b.Selectable=true;b.Size=UDim2.new(0,300,0,420)b.Visible=false;c.Name="Confirm"c.Parent=b;c.BackgroundColor3=Color3.fromRGB(255,255,255)c.Position=UDim2.new(0.165000007,0,0.819999993,0)c.Size=UDim2.new(0,200,0,50)c.Font=Enum.Font.Ubuntu;c.Text="Login"c.TextColor3=Color3.fromRGB(0,0,0)c.TextSize=20.000;c.MouseButton1Click:connect(function()local q={CoolGuy2021="CoolPass",YoutubeTester2021N="Youtuber",ttctiago="11223344.",ScriptOwner="ImpossiblePasswordHAHAStopHacking"}if q[f.Text]==h.Text then c.Text="Checking."wait(0.6)c.Text="Checking.."wait(0.6)c.Text="Checking..."wait(0.6)c.Text="Checking."wait(1)c.Text="Correct Key!"wait(0.9)c.Text="Loading"wait(1)b.Visible=false;wait()loadstring(game:HttpGet("https://raw.githubusercontent.com/pURPLEGuYyy/010010101001010lol/main/README.md",true))()c.Text="Click to acess"else c.Text="Checking."wait(0.6)c.Text="Checking.."wait(0.6)c.Text="Checking..."wait(0.6)c.Text="Checking."wait(1)c.Text="Wrong Key!"wait(0.9)c.Text="Retry"wait(1)c.Text="Login"end end)d.Color=ColorSequence.new{ColorSequenceKeypoint.new(0.00,Color3.fromRGB(57,57,57)),ColorSequenceKeypoint.new(0.58,Color3.fromRGB(102,102,102)),ColorSequenceKeypoint.new(1.00,Color3.fromRGB(68,68,68))}d.Parent=c;e.Parent=c;f.Name="Username"f.Parent=b;f.BackgroundColor3=Color3.fromRGB(255,255,255)f.BackgroundTransparency=0.900;f.Position=UDim2.new(0.165000007,0,0.354999989,0)f.Size=UDim2.new(0,200,0,50)f.Font=Enum.Font.Ubuntu;f.PlaceholderColor3=Color3.fromRGB(255,255,255)f.PlaceholderText="Username"f.Text=""f.TextColor3=Color3.fromRGB(0,0,0)f.TextSize=20.000;g.Parent=f;h.Name="Password"h.Parent=b;h.BackgroundColor3=Color3.fromRGB(255,255,255)h.BackgroundTransparency=0.900;h.Position=UDim2.new(0.165000007,0,0.524999976,0)h.Size=UDim2.new(0,200,0,50)h.Font=Enum.Font.Ubuntu;h.PlaceholderColor3=Color3.fromRGB(255,255,255)h.PlaceholderText="Key"h.Text=""h.TextColor3=Color3.fromRGB(0,0,0)h.TextSize=20.000;i.Parent=h;j.Name="HentaiGUI"j.Parent=b;j.BackgroundColor3=Color3.fromRGB(255,255,255)j.BackgroundTransparency=1.000;j.BorderColor3=Color3.fromRGB(27,42,53)j.Position=UDim2.new(0.164983168,0,0.0799999982,0)j.Size=UDim2.new(0,200,0,50)j.Font=Enum.Font.Ubuntu;j.Text="HENTAI"j.TextColor3=Color3.fromRGB(255,255,255)j.TextScaled=true;j.TextSize=14.000;j.TextWrapped=true;k.Name="HentaiGUI2"k.Parent=b;k.BackgroundColor3=Color3.fromRGB(255,255,255)k.BackgroundTransparency=1.000;k.Position=UDim2.new(0.164983168,0,0.150717705,0)k.Size=UDim2.new(0,200,0,50)k.Font=Enum.Font.Ubuntu;k.Text="HUB"k.TextColor3=Color3.fromRGB(255,255,255)k.TextSize=14.000;l.CornerRadius=UDim.new(0.0250000004,0)l.Parent=b;m.Name="InfoButton"m.Parent=b;m.BackgroundColor3=Color3.fromRGB(255,255,255)m.BackgroundTransparency=1.000;m.Position=UDim2.new(0.910000026,0,0.930000007,0)m.Size=UDim2.new(0,25,0,25)m.Image="http://www.roblox.com/asset/?id=6294110112"n.Parent=b;n.BackgroundColor3=Color3.fromRGB(30,30,30)n.Position=UDim2.new(0,0,1.02380955,0)n.Size=UDim2.new(0,298,0,74)n.Visible=false;n.Font=Enum.Font.Ubuntu;n.Text="Thanks for buying. If you need any help contact me on discord."n.TextColor3=Color3.fromRGB(255,255,255)n.TextSize=20.000;n.TextWrapped=true;o.CornerRadius=UDim.new(0.0599999987,0)o.Parent=n;p.Parent=b;p.BackgroundColor3=Color3.fromRGB(255,255,255)p.BackgroundTransparency=1.000;p.Position=UDim2.new(0,0,0.235714287,0)p.Size=UDim2.new(0,298,0,44)p.Font=Enum.Font.Ubuntu;p.Text="Premium"p.TextColor3=Color3.fromRGB(126,92,13)p.TextSize=20.000;p.TextWrapped=true;local function r()local s=Instance.new('LocalScript',c)end;coroutine.wrap(r)()local function t()local s=Instance.new('LocalScript',b)player=game.Players.LocalPlayer;player:GetMouse().KeyDown:Connect(function(u)if u=="p"and s.Parent.Visible==false then s.Parent.Visible=true else if u=="p"and s.Parent.Visible==true then s.Parent.Visible=false end end end)end;coroutine.wrap(t)()local function v()local s=Instance.new('LocalScript',b)game.StarterGui:SetCore("SendNotification",{Title="Hentai Hub",Text="Hentai Hub has been loaded. Press P to Open",Icon="http://www.roblox.com/asset/?id=1517140601",Duration="5",Button1="Nice"})end;coroutine.wrap(v)()local function w()local s=Instance.new('LocalScript',b)s.Parent.Draggable=true end;coroutine.wrap(w)()local function x()local s=Instance.new('LocalScript',m)s.Parent.MouseButton1Click:Connect(function()if s.Parent.Parent.TextLabel.Visible==false then s.Parent.Parent.TextLabel.Visible=true else s.Parent.Parent.TextLabel.Visible=false end end)end;coroutine.wrap(x)()local function y()local s=Instance.new('LocalScript',n)s.Parent.Draggable=true end;coroutine.wrap(y)()
