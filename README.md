--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 124 | Scripts: 30 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.new
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["KORTOX"] = [[new]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false;


-- StarterGui.new.baza
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(40, 41, 41);
G2L["2"]["Size"] = UDim2.new(0, 607, 0, 401);
G2L["2"]["Position"] = UDim2.new(0.41645, 0, 0.41567, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[baza]];


-- StarterGui.new.baza.zadnica
G2L["3"] = Instance.new("Frame", G2L["2"]);
G2L["3"]["BorderSizePixel"] = 0;
G2L["3"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["3"]["Size"] = UDim2.new(0, 595, 0, 391);
G2L["3"]["Position"] = UDim2.new(0.00988, 0, 0.01071, 0);
G2L["3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3"]["Name"] = [[zadnica]];


-- StarterGui.new.baza.zadnica.UIStroke
G2L["4"] = Instance.new("UIStroke", G2L["3"]);
G2L["4"]["Transparency"] = 0.86;
G2L["4"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["4"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.ImageLabel
G2L["5"] = Instance.new("ImageLabel", G2L["3"]);
G2L["5"]["BorderSizePixel"] = 0;
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5"]["Image"] = [[rbxassetid://95272865678017]];
G2L["5"]["Size"] = UDim2.new(0, 595, 0, 2);
G2L["5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.ImageLabel.animation
G2L["6"] = Instance.new("LocalScript", G2L["5"]);
G2L["6"]["Name"] = [[animation]];


-- StarterGui.new.baza.zadnica.backgroundimage
G2L["7"] = Instance.new("ImageLabel", G2L["3"]);
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["ImageTransparency"] = 0.93;
G2L["7"]["Image"] = [[http://www.roblox.com/asset/?id=14675747337]];
G2L["7"]["Size"] = UDim2.new(0, 574, 0, -365);
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["BackgroundTransparency"] = 1;
G2L["7"]["Name"] = [[backgroundimage]];
G2L["7"]["Position"] = UDim2.new(0.01681, 0, 0.96931, 0);


-- StarterGui.new.baza.zadnica.prikol
G2L["8"] = Instance.new("Frame", G2L["3"]);
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8"]["Size"] = UDim2.new(0, 1, 0, 365);
G2L["8"]["Position"] = UDim2.new(0.17647, 0, 0.03581, 0);
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["Name"] = [[prikol]];
G2L["8"]["BackgroundTransparency"] = 0.85;


-- StarterGui.new.baza.zadnica.buttons
G2L["9"] = Instance.new("Frame", G2L["3"]);
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["Size"] = UDim2.new(0, 101, 0, 391);
G2L["9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9"]["Name"] = [[buttons]];
G2L["9"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.buttons.UIListLayout
G2L["a"] = Instance.new("UIListLayout", G2L["9"]);
G2L["a"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.new.baza.zadnica.buttons.rage
G2L["b"] = Instance.new("TextButton", G2L["9"]);
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["TextSize"] = 14;
G2L["b"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["b"]["Size"] = UDim2.new(0, 100, 0, 85);
G2L["b"]["BackgroundTransparency"] = 1;
G2L["b"]["Name"] = [[rage]];
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Text"] = [[]];


-- StarterGui.new.baza.zadnica.buttons.rage.ImageLabel
G2L["c"] = Instance.new("ImageLabel", G2L["b"]);
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["Image"] = [[rbxassetid://8547236654]];
G2L["c"]["Size"] = UDim2.new(0, 78, 0, 71);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["BackgroundTransparency"] = 1;
G2L["c"]["Position"] = UDim2.new(0.16, 0, 0.17647, 0);


-- StarterGui.new.baza.zadnica.buttons.rage.LocalScript
G2L["d"] = Instance.new("LocalScript", G2L["b"]);



-- StarterGui.new.baza.zadnica.buttons.visuals
G2L["e"] = Instance.new("TextButton", G2L["9"]);
G2L["e"]["BorderSizePixel"] = 0;
G2L["e"]["TextSize"] = 14;
G2L["e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["e"]["Size"] = UDim2.new(0, 100, 0, 85);
G2L["e"]["BackgroundTransparency"] = 1;
G2L["e"]["Name"] = [[visuals]];
G2L["e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["Text"] = [[]];


-- StarterGui.new.baza.zadnica.buttons.visuals.ImageLabel
G2L["f"] = Instance.new("ImageLabel", G2L["e"]);
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["ImageTransparency"] = 0.47;
G2L["f"]["Image"] = [[rbxassetid://8547254518]];
G2L["f"]["Size"] = UDim2.new(0, 67, 0, 71);
G2L["f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["BackgroundTransparency"] = 1;
G2L["f"]["Position"] = UDim2.new(0.16, 0, 0.17647, 0);


-- StarterGui.new.baza.zadnica.buttons.visuals.LocalScript
G2L["10"] = Instance.new("LocalScript", G2L["e"]);



-- StarterGui.new.baza.zadnica.buttons.movement
G2L["11"] = Instance.new("TextButton", G2L["9"]);
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["TextSize"] = 14;
G2L["11"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["11"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["11"]["Size"] = UDim2.new(0, 100, 0, 85);
G2L["11"]["BackgroundTransparency"] = 1;
G2L["11"]["Name"] = [[movement]];
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["Text"] = [[]];


-- StarterGui.new.baza.zadnica.buttons.movement.ImageLabel
G2L["12"] = Instance.new("ImageLabel", G2L["11"]);
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["ImageTransparency"] = 0.47;
G2L["12"]["Image"] = [[rbxassetid://110954096488294]];
G2L["12"]["Size"] = UDim2.new(0, 54, 0, 51);
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["BackgroundTransparency"] = 1;
G2L["12"]["Position"] = UDim2.new(0.22, 0, 0.29412, 0);


-- StarterGui.new.baza.zadnica.buttons.movement.LocalScript
G2L["13"] = Instance.new("LocalScript", G2L["11"]);



-- StarterGui.new.baza.zadnica.buttons.info
G2L["14"] = Instance.new("TextButton", G2L["9"]);
G2L["14"]["BorderSizePixel"] = 0;
G2L["14"]["TextSize"] = 14;
G2L["14"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["14"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["14"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["14"]["Size"] = UDim2.new(0, 100, 0, 85);
G2L["14"]["BackgroundTransparency"] = 1;
G2L["14"]["Name"] = [[info]];
G2L["14"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["14"]["Text"] = [[]];


-- StarterGui.new.baza.zadnica.buttons.info.LocalScript
G2L["15"] = Instance.new("LocalScript", G2L["14"]);



-- StarterGui.new.baza.zadnica.buttons.info.ImageLabel
G2L["16"] = Instance.new("ImageLabel", G2L["14"]);
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["16"]["ImageTransparency"] = 0.47;
G2L["16"]["Image"] = [[http://www.roblox.com/asset/?id=18754976792]];
G2L["16"]["Size"] = UDim2.new(0, 43, 0, 41);
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["BackgroundTransparency"] = 1;
G2L["16"]["Position"] = UDim2.new(0.28, 0, 0.35294, 0);


-- StarterGui.new.baza.zadnica.combat_f
G2L["17"] = Instance.new("Frame", G2L["3"]);
G2L["17"]["BorderSizePixel"] = 0;
G2L["17"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["17"]["Size"] = UDim2.new(0, 54, 0, 41);
G2L["17"]["Position"] = UDim2.new(-0.01008, 0, -0.01279, 0);
G2L["17"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["17"]["Name"] = [[combat_f]];
G2L["17"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.combat_f.knopka
G2L["18"] = Instance.new("Frame", G2L["17"]);
G2L["18"]["BorderSizePixel"] = 0;
G2L["18"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["18"]["Size"] = UDim2.new(0, 465, 0, 47);
G2L["18"]["Position"] = UDim2.new(2.31481, 0, 0.4878, 0);
G2L["18"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["18"]["Name"] = [[knopka]];


-- StarterGui.new.baza.zadnica.combat_f.knopka.UIStroke
G2L["19"] = Instance.new("UIStroke", G2L["18"]);
G2L["19"]["Transparency"] = 0.86;
G2L["19"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["19"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.combat_f.knopka.ImageLabel
G2L["1a"] = Instance.new("ImageLabel", G2L["18"]);
G2L["1a"]["BorderSizePixel"] = 0;
G2L["1a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1a"]["Image"] = [[rbxassetid://95272865678017]];
G2L["1a"]["Size"] = UDim2.new(0, 465, 0, 2);
G2L["1a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1a"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.combat_f.knopka.ImageLabel.animation
G2L["1b"] = Instance.new("LocalScript", G2L["1a"]);
G2L["1b"]["Name"] = [[animation]];


-- StarterGui.new.baza.zadnica.combat_f.knopka.TextLabel
G2L["1c"] = Instance.new("TextLabel", G2L["18"]);
G2L["1c"]["BorderSizePixel"] = 0;
G2L["1c"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["1c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["TextSize"] = 14;
G2L["1c"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["BackgroundTransparency"] = 1;
G2L["1c"]["Size"] = UDim2.new(0, 287, 0, 45);
G2L["1c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["Text"] = [[KillAura]];
G2L["1c"]["Position"] = UDim2.new(0.03226, 0, 0.04255, 0);


-- StarterGui.new.baza.zadnica.combat_f.knopka.TextButton
G2L["1d"] = Instance.new("TextButton", G2L["18"]);
G2L["1d"]["BorderSizePixel"] = 0;
G2L["1d"]["TextSize"] = 14;
G2L["1d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["1d"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1d"]["Size"] = UDim2.new(0, 109, 0, 28);
G2L["1d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1d"]["Text"] = [[Click!]];
G2L["1d"]["Position"] = UDim2.new(0.74839, 0, 0.21277, 0);


-- StarterGui.new.baza.zadnica.combat_f.knopka.TextButton.UIStroke
G2L["1e"] = Instance.new("UIStroke", G2L["1d"]);
G2L["1e"]["Transparency"] = 0.86;
G2L["1e"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["1e"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.combat_f.knopka.TextButton.LocalScript
G2L["1f"] = Instance.new("LocalScript", G2L["1d"]);



-- StarterGui.new.baza.zadnica.combat_f.knopka
G2L["20"] = Instance.new("Frame", G2L["17"]);
G2L["20"]["BorderSizePixel"] = 0;
G2L["20"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["20"]["Size"] = UDim2.new(0, 465, 0, 47);
G2L["20"]["Position"] = UDim2.new(2.31481, 0, 1.92683, 0);
G2L["20"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["20"]["Name"] = [[knopka]];


-- StarterGui.new.baza.zadnica.combat_f.knopka.UIStroke
G2L["21"] = Instance.new("UIStroke", G2L["20"]);
G2L["21"]["Transparency"] = 0.86;
G2L["21"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["21"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.combat_f.knopka.ImageLabel
G2L["22"] = Instance.new("ImageLabel", G2L["20"]);
G2L["22"]["BorderSizePixel"] = 0;
G2L["22"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["22"]["Image"] = [[rbxassetid://95272865678017]];
G2L["22"]["Size"] = UDim2.new(0, 465, 0, 2);
G2L["22"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.combat_f.knopka.ImageLabel.animation
G2L["23"] = Instance.new("LocalScript", G2L["22"]);
G2L["23"]["Name"] = [[animation]];


-- StarterGui.new.baza.zadnica.combat_f.knopka.TextLabel
G2L["24"] = Instance.new("TextLabel", G2L["20"]);
G2L["24"]["BorderSizePixel"] = 0;
G2L["24"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["24"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["24"]["TextSize"] = 14;
G2L["24"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["24"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["24"]["BackgroundTransparency"] = 1;
G2L["24"]["Size"] = UDim2.new(0, 287, 0, 45);
G2L["24"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["24"]["Text"] = [[Kill All]];
G2L["24"]["Position"] = UDim2.new(0.03226, 0, 0.04255, 0);


-- StarterGui.new.baza.zadnica.combat_f.knopka.TextButton
G2L["25"] = Instance.new("TextButton", G2L["20"]);
G2L["25"]["BorderSizePixel"] = 0;
G2L["25"]["TextSize"] = 14;
G2L["25"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["25"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["25"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["25"]["Size"] = UDim2.new(0, 109, 0, 28);
G2L["25"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["25"]["Text"] = [[Click!]];
G2L["25"]["Position"] = UDim2.new(0.74839, 0, 0.21277, 0);


-- StarterGui.new.baza.zadnica.combat_f.knopka.TextButton.UIStroke
G2L["26"] = Instance.new("UIStroke", G2L["25"]);
G2L["26"]["Transparency"] = 0.86;
G2L["26"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["26"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.combat_f.knopka.TextButton.LocalScript
G2L["27"] = Instance.new("LocalScript", G2L["25"]);



-- StarterGui.new.baza.zadnica.combat_f.knopka
G2L["28"] = Instance.new("Frame", G2L["17"]);
G2L["28"]["BorderSizePixel"] = 0;
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["28"]["Size"] = UDim2.new(0, 465, 0, 47);
G2L["28"]["Position"] = UDim2.new(2.31481, 0, 3.4878, 0);
G2L["28"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["Name"] = [[knopka]];


-- StarterGui.new.baza.zadnica.combat_f.knopka.UIStroke
G2L["29"] = Instance.new("UIStroke", G2L["28"]);
G2L["29"]["Transparency"] = 0.86;
G2L["29"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["29"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.combat_f.knopka.ImageLabel
G2L["2a"] = Instance.new("ImageLabel", G2L["28"]);
G2L["2a"]["BorderSizePixel"] = 0;
G2L["2a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2a"]["Image"] = [[rbxassetid://95272865678017]];
G2L["2a"]["Size"] = UDim2.new(0, 465, 0, 2);
G2L["2a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2a"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.combat_f.knopka.ImageLabel.animation
G2L["2b"] = Instance.new("LocalScript", G2L["2a"]);
G2L["2b"]["Name"] = [[animation]];


-- StarterGui.new.baza.zadnica.combat_f.knopka.TextLabel
G2L["2c"] = Instance.new("TextLabel", G2L["28"]);
G2L["2c"]["BorderSizePixel"] = 0;
G2L["2c"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["2c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2c"]["TextSize"] = 14;
G2L["2c"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2c"]["BackgroundTransparency"] = 1;
G2L["2c"]["Size"] = UDim2.new(0, 287, 0, 45);
G2L["2c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2c"]["Text"] = [[AimBot ( keycode e )]];
G2L["2c"]["Position"] = UDim2.new(0.03226, 0, 0.04255, 0);


-- StarterGui.new.baza.zadnica.combat_f.knopka.TextButton
G2L["2d"] = Instance.new("TextButton", G2L["28"]);
G2L["2d"]["BorderSizePixel"] = 0;
G2L["2d"]["TextSize"] = 14;
G2L["2d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2d"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["2d"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2d"]["Size"] = UDim2.new(0, 109, 0, 28);
G2L["2d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2d"]["Text"] = [[Click!]];
G2L["2d"]["Position"] = UDim2.new(0.74839, 0, 0.21277, 0);


-- StarterGui.new.baza.zadnica.combat_f.knopka.TextButton.UIStroke
G2L["2e"] = Instance.new("UIStroke", G2L["2d"]);
G2L["2e"]["Transparency"] = 0.86;
G2L["2e"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["2e"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.combat_f.knopka.TextButton.LocalScript
G2L["2f"] = Instance.new("LocalScript", G2L["2d"]);



-- StarterGui.new.baza.zadnica.visuals_f
G2L["30"] = Instance.new("Frame", G2L["3"]);
G2L["30"]["Visible"] = false;
G2L["30"]["BorderSizePixel"] = 0;
G2L["30"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["30"]["Size"] = UDim2.new(0, 54, 0, 41);
G2L["30"]["Position"] = UDim2.new(-0.01008, 0, -0.01279, 0);
G2L["30"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["30"]["Name"] = [[visuals_f]];
G2L["30"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.visuals_f.knopka
G2L["31"] = Instance.new("Frame", G2L["30"]);
G2L["31"]["BorderSizePixel"] = 0;
G2L["31"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["31"]["Size"] = UDim2.new(0, 465, 0, 47);
G2L["31"]["Position"] = UDim2.new(2.31481, 0, 0.4878, 0);
G2L["31"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["31"]["Name"] = [[knopka]];


-- StarterGui.new.baza.zadnica.visuals_f.knopka.UIStroke
G2L["32"] = Instance.new("UIStroke", G2L["31"]);
G2L["32"]["Transparency"] = 0.86;
G2L["32"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["32"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.visuals_f.knopka.ImageLabel
G2L["33"] = Instance.new("ImageLabel", G2L["31"]);
G2L["33"]["BorderSizePixel"] = 0;
G2L["33"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["33"]["Image"] = [[rbxassetid://95272865678017]];
G2L["33"]["Size"] = UDim2.new(0, 465, 0, 2);
G2L["33"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["33"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.visuals_f.knopka.ImageLabel.animation
G2L["34"] = Instance.new("LocalScript", G2L["33"]);
G2L["34"]["Name"] = [[animation]];


-- StarterGui.new.baza.zadnica.visuals_f.knopka.TextLabel
G2L["35"] = Instance.new("TextLabel", G2L["31"]);
G2L["35"]["BorderSizePixel"] = 0;
G2L["35"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["35"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["35"]["TextSize"] = 14;
G2L["35"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["35"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["35"]["BackgroundTransparency"] = 1;
G2L["35"]["Size"] = UDim2.new(0, 287, 0, 45);
G2L["35"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["35"]["Text"] = [[ESP]];
G2L["35"]["Position"] = UDim2.new(0.03226, 0, 0.04255, 0);


-- StarterGui.new.baza.zadnica.visuals_f.knopka.TextButton
G2L["36"] = Instance.new("TextButton", G2L["31"]);
G2L["36"]["BorderSizePixel"] = 0;
G2L["36"]["TextSize"] = 14;
G2L["36"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["36"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["36"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["36"]["Size"] = UDim2.new(0, 109, 0, 28);
G2L["36"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["36"]["Text"] = [[Click!]];
G2L["36"]["Position"] = UDim2.new(0.74839, 0, 0.21277, 0);


-- StarterGui.new.baza.zadnica.visuals_f.knopka.TextButton.UIStroke
G2L["37"] = Instance.new("UIStroke", G2L["36"]);
G2L["37"]["Transparency"] = 0.86;
G2L["37"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["37"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.visuals_f.knopka.TextButton.LocalScript
G2L["38"] = Instance.new("LocalScript", G2L["36"]);



-- StarterGui.new.baza.zadnica.visuals_f.knopka
G2L["39"] = Instance.new("Frame", G2L["30"]);
G2L["39"]["BorderSizePixel"] = 0;
G2L["39"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["39"]["Size"] = UDim2.new(0, 465, 0, 47);
G2L["39"]["Position"] = UDim2.new(2.31481, 0, 1.92683, 0);
G2L["39"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["Name"] = [[knopka]];


-- StarterGui.new.baza.zadnica.visuals_f.knopka.UIStroke
G2L["3a"] = Instance.new("UIStroke", G2L["39"]);
G2L["3a"]["Transparency"] = 0.86;
G2L["3a"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["3a"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.visuals_f.knopka.ImageLabel
G2L["3b"] = Instance.new("ImageLabel", G2L["39"]);
G2L["3b"]["BorderSizePixel"] = 0;
G2L["3b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3b"]["Image"] = [[rbxassetid://95272865678017]];
G2L["3b"]["Size"] = UDim2.new(0, 465, 0, 2);
G2L["3b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3b"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.visuals_f.knopka.ImageLabel.animation
G2L["3c"] = Instance.new("LocalScript", G2L["3b"]);
G2L["3c"]["Name"] = [[animation]];


-- StarterGui.new.baza.zadnica.visuals_f.knopka.TextLabel
G2L["3d"] = Instance.new("TextLabel", G2L["39"]);
G2L["3d"]["BorderSizePixel"] = 0;
G2L["3d"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["3d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3d"]["TextSize"] = 14;
G2L["3d"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3d"]["BackgroundTransparency"] = 1;
G2L["3d"]["Size"] = UDim2.new(0, 287, 0, 45);
G2L["3d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3d"]["Text"] = [[FOV changer]];
G2L["3d"]["Position"] = UDim2.new(0.03226, 0, 0.04255, 0);


-- StarterGui.new.baza.zadnica.visuals_f.knopka.TextButton
G2L["3e"] = Instance.new("TextButton", G2L["39"]);
G2L["3e"]["BorderSizePixel"] = 0;
G2L["3e"]["TextSize"] = 14;
G2L["3e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3e"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["3e"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3e"]["Size"] = UDim2.new(0, 109, 0, 28);
G2L["3e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3e"]["Text"] = [[Click!]];
G2L["3e"]["Position"] = UDim2.new(0.74839, 0, 0.21277, 0);


-- StarterGui.new.baza.zadnica.visuals_f.knopka.TextButton.UIStroke
G2L["3f"] = Instance.new("UIStroke", G2L["3e"]);
G2L["3f"]["Transparency"] = 0.86;
G2L["3f"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["3f"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.visuals_f.knopka.TextButton.LocalScript
G2L["40"] = Instance.new("LocalScript", G2L["3e"]);



-- StarterGui.new.baza.zadnica.movement_f
G2L["41"] = Instance.new("Frame", G2L["3"]);
G2L["41"]["Visible"] = false;
G2L["41"]["BorderSizePixel"] = 0;
G2L["41"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["41"]["Size"] = UDim2.new(0, 54, 0, 41);
G2L["41"]["Position"] = UDim2.new(-0.01008, 0, -0.01279, 0);
G2L["41"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["41"]["Name"] = [[movement_f]];
G2L["41"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.movement_f.knopka
G2L["42"] = Instance.new("Frame", G2L["41"]);
G2L["42"]["BorderSizePixel"] = 0;
G2L["42"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["42"]["Size"] = UDim2.new(0, 465, 0, 47);
G2L["42"]["Position"] = UDim2.new(2.31481, 0, 0.4878, 0);
G2L["42"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["42"]["Name"] = [[knopka]];


-- StarterGui.new.baza.zadnica.movement_f.knopka.UIStroke
G2L["43"] = Instance.new("UIStroke", G2L["42"]);
G2L["43"]["Transparency"] = 0.86;
G2L["43"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["43"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.movement_f.knopka.ImageLabel
G2L["44"] = Instance.new("ImageLabel", G2L["42"]);
G2L["44"]["BorderSizePixel"] = 0;
G2L["44"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["44"]["Image"] = [[rbxassetid://95272865678017]];
G2L["44"]["Size"] = UDim2.new(0, 465, 0, 2);
G2L["44"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["44"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.movement_f.knopka.ImageLabel.animation
G2L["45"] = Instance.new("LocalScript", G2L["44"]);
G2L["45"]["Name"] = [[animation]];


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextLabel
G2L["46"] = Instance.new("TextLabel", G2L["42"]);
G2L["46"]["BorderSizePixel"] = 0;
G2L["46"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["46"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["46"]["TextSize"] = 14;
G2L["46"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["46"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["46"]["BackgroundTransparency"] = 1;
G2L["46"]["Size"] = UDim2.new(0, 287, 0, 45);
G2L["46"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["46"]["Text"] = [[Speed]];
G2L["46"]["Position"] = UDim2.new(0.03226, 0, 0.04255, 0);


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton
G2L["47"] = Instance.new("TextButton", G2L["42"]);
G2L["47"]["BorderSizePixel"] = 0;
G2L["47"]["TextSize"] = 14;
G2L["47"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["47"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["47"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["47"]["Size"] = UDim2.new(0, 109, 0, 28);
G2L["47"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["47"]["Text"] = [[Click!]];
G2L["47"]["Position"] = UDim2.new(0.74839, 0, 0.21277, 0);


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton.UIStroke
G2L["48"] = Instance.new("UIStroke", G2L["47"]);
G2L["48"]["Transparency"] = 0.86;
G2L["48"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["48"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton.LocalScript
G2L["49"] = Instance.new("LocalScript", G2L["47"]);



-- StarterGui.new.baza.zadnica.movement_f.knopka
G2L["4a"] = Instance.new("Frame", G2L["41"]);
G2L["4a"]["BorderSizePixel"] = 0;
G2L["4a"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["4a"]["Size"] = UDim2.new(0, 465, 0, 47);
G2L["4a"]["Position"] = UDim2.new(2.31481, 0, 1.92683, 0);
G2L["4a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4a"]["Name"] = [[knopka]];


-- StarterGui.new.baza.zadnica.movement_f.knopka.UIStroke
G2L["4b"] = Instance.new("UIStroke", G2L["4a"]);
G2L["4b"]["Transparency"] = 0.86;
G2L["4b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["4b"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.movement_f.knopka.ImageLabel
G2L["4c"] = Instance.new("ImageLabel", G2L["4a"]);
G2L["4c"]["BorderSizePixel"] = 0;
G2L["4c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4c"]["Image"] = [[rbxassetid://95272865678017]];
G2L["4c"]["Size"] = UDim2.new(0, 465, 0, 2);
G2L["4c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4c"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.movement_f.knopka.ImageLabel.animation
G2L["4d"] = Instance.new("LocalScript", G2L["4c"]);
G2L["4d"]["Name"] = [[animation]];


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextLabel
G2L["4e"] = Instance.new("TextLabel", G2L["4a"]);
G2L["4e"]["BorderSizePixel"] = 0;
G2L["4e"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["4e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4e"]["TextSize"] = 14;
G2L["4e"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4e"]["BackgroundTransparency"] = 1;
G2L["4e"]["Size"] = UDim2.new(0, 287, 0, 45);
G2L["4e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4e"]["Text"] = [[Inf Jump]];
G2L["4e"]["Position"] = UDim2.new(0.03226, 0, 0.04255, 0);


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton
G2L["4f"] = Instance.new("TextButton", G2L["4a"]);
G2L["4f"]["BorderSizePixel"] = 0;
G2L["4f"]["TextSize"] = 14;
G2L["4f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4f"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["4f"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4f"]["Size"] = UDim2.new(0, 109, 0, 28);
G2L["4f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4f"]["Text"] = [[Click!]];
G2L["4f"]["Position"] = UDim2.new(0.74839, 0, 0.21277, 0);


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton.UIStroke
G2L["50"] = Instance.new("UIStroke", G2L["4f"]);
G2L["50"]["Transparency"] = 0.86;
G2L["50"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["50"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton.LocalScript
G2L["51"] = Instance.new("LocalScript", G2L["4f"]);



-- StarterGui.new.baza.zadnica.movement_f.knopka
G2L["52"] = Instance.new("Frame", G2L["41"]);
G2L["52"]["BorderSizePixel"] = 0;
G2L["52"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["52"]["Size"] = UDim2.new(0, 465, 0, 47);
G2L["52"]["Position"] = UDim2.new(2.31481, 0, 3.39024, 0);
G2L["52"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["52"]["Name"] = [[knopka]];


-- StarterGui.new.baza.zadnica.movement_f.knopka.UIStroke
G2L["53"] = Instance.new("UIStroke", G2L["52"]);
G2L["53"]["Transparency"] = 0.86;
G2L["53"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["53"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.movement_f.knopka.ImageLabel
G2L["54"] = Instance.new("ImageLabel", G2L["52"]);
G2L["54"]["BorderSizePixel"] = 0;
G2L["54"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["54"]["Image"] = [[rbxassetid://95272865678017]];
G2L["54"]["Size"] = UDim2.new(0, 465, 0, 2);
G2L["54"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["54"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.movement_f.knopka.ImageLabel.animation
G2L["55"] = Instance.new("LocalScript", G2L["54"]);
G2L["55"]["Name"] = [[animation]];


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextLabel
G2L["56"] = Instance.new("TextLabel", G2L["52"]);
G2L["56"]["BorderSizePixel"] = 0;
G2L["56"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["56"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["56"]["TextSize"] = 14;
G2L["56"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["56"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["56"]["BackgroundTransparency"] = 1;
G2L["56"]["Size"] = UDim2.new(0, 287, 0, 45);
G2L["56"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["56"]["Text"] = [[Fly]];
G2L["56"]["Position"] = UDim2.new(0.03226, 0, 0.04255, 0);


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton
G2L["57"] = Instance.new("TextButton", G2L["52"]);
G2L["57"]["BorderSizePixel"] = 0;
G2L["57"]["TextSize"] = 14;
G2L["57"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["57"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["57"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["57"]["Size"] = UDim2.new(0, 109, 0, 28);
G2L["57"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["57"]["Text"] = [[Click!]];
G2L["57"]["Position"] = UDim2.new(0.74839, 0, 0.21277, 0);


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton.UIStroke
G2L["58"] = Instance.new("UIStroke", G2L["57"]);
G2L["58"]["Transparency"] = 0.86;
G2L["58"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["58"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton.LocalScript
G2L["59"] = Instance.new("LocalScript", G2L["57"]);



-- StarterGui.new.baza.zadnica.movement_f.knopka
G2L["5a"] = Instance.new("Frame", G2L["41"]);
G2L["5a"]["BorderSizePixel"] = 0;
G2L["5a"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["5a"]["Size"] = UDim2.new(0, 465, 0, 47);
G2L["5a"]["Position"] = UDim2.new(2.31481, 0, 4.87805, 0);
G2L["5a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5a"]["Name"] = [[knopka]];


-- StarterGui.new.baza.zadnica.movement_f.knopka.UIStroke
G2L["5b"] = Instance.new("UIStroke", G2L["5a"]);
G2L["5b"]["Transparency"] = 0.86;
G2L["5b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["5b"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.movement_f.knopka.ImageLabel
G2L["5c"] = Instance.new("ImageLabel", G2L["5a"]);
G2L["5c"]["BorderSizePixel"] = 0;
G2L["5c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5c"]["Image"] = [[rbxassetid://95272865678017]];
G2L["5c"]["Size"] = UDim2.new(0, 465, 0, 2);
G2L["5c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5c"]["BackgroundTransparency"] = 1;



-- StarterGui.new.baza.zadnica.movement_f.knopka.ImageLabel.animation
G2L["5d"] = Instance.new("LocalScript", G2L["5c"]);
G2L["5d"]["Name"] = [[animation]];


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextLabel
G2L["5e"] = Instance.new("TextLabel", G2L["5a"]);
G2L["5e"]["BorderSizePixel"] = 0;
G2L["5e"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["5e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5e"]["TextSize"] = 14;
G2L["5e"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5e"]["BackgroundTransparency"] = 1;
G2L["5e"]["Size"] = UDim2.new(0, 287, 0, 45);
G2L["5e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5e"]["Text"] = [[No clip]];
G2L["5e"]["Position"] = UDim2.new(0.03226, 0, 0.04255, 0);


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton
G2L["5f"] = Instance.new("TextButton", G2L["5a"]);
G2L["5f"]["BorderSizePixel"] = 0;
G2L["5f"]["TextSize"] = 14;
G2L["5f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5f"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["5f"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5f"]["Size"] = UDim2.new(0, 109, 0, 28);
G2L["5f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5f"]["Text"] = [[Click!]];
G2L["5f"]["Position"] = UDim2.new(0.74839, 0, 0.21277, 0);


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton.UIStroke
G2L["60"] = Instance.new("UIStroke", G2L["5f"]);
G2L["60"]["Transparency"] = 0.86;
G2L["60"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["60"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton.LocalScript
G2L["61"] = Instance.new("LocalScript", G2L["5f"]);



-- StarterGui.new.baza.zadnica.movement_f.knopka
G2L["62"] = Instance.new("Frame", G2L["41"]);
G2L["62"]["BorderSizePixel"] = 0;
G2L["62"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["62"]["Size"] = UDim2.new(0, 465, 0, 47);
G2L["62"]["Position"] = UDim2.new(2.31481, 0, 6.31707, 0);
G2L["62"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["62"]["Name"] = [[knopka]];


-- StarterGui.new.baza.zadnica.movement_f.knopka.UIStroke
G2L["63"] = Instance.new("UIStroke", G2L["62"]);
G2L["63"]["Transparency"] = 0.86;
G2L["63"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["63"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.movement_f.knopka.ImageLabel
G2L["64"] = Instance.new("ImageLabel", G2L["62"]);
G2L["64"]["BorderSizePixel"] = 0;
G2L["64"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["64"]["Image"] = [[rbxassetid://95272865678017]];
G2L["64"]["Size"] = UDim2.new(0, 465, 0, 2);
G2L["64"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["64"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.movement_f.knopka.ImageLabel.animation
G2L["65"] = Instance.new("LocalScript", G2L["64"]);
G2L["65"]["Name"] = [[animation]];


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextLabel
G2L["66"] = Instance.new("TextLabel", G2L["62"]);
G2L["66"]["ZIndex"] = 2;
G2L["66"]["BorderSizePixel"] = 0;
G2L["66"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["66"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["66"]["TextSize"] = 14;
G2L["66"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["66"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["66"]["BackgroundTransparency"] = 1;
G2L["66"]["Size"] = UDim2.new(0, 287, 0, 45);
G2L["66"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["66"]["Text"] = [[Ctrl + left click tp]];
G2L["66"]["Position"] = UDim2.new(0.03226, 0, 0.04255, 0);


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton
G2L["67"] = Instance.new("TextButton", G2L["62"]);
G2L["67"]["BorderSizePixel"] = 0;
G2L["67"]["TextSize"] = 14;
G2L["67"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["67"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["67"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["67"]["Size"] = UDim2.new(0, 109, 0, 28);
G2L["67"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["67"]["Text"] = [[Click!]];
G2L["67"]["Position"] = UDim2.new(0.74839, 0, 0.21277, 0);


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton.UIStroke
G2L["68"] = Instance.new("UIStroke", G2L["67"]);
G2L["68"]["Transparency"] = 0.86;
G2L["68"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["68"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton.LocalScript
G2L["69"] = Instance.new("LocalScript", G2L["67"]);



-- StarterGui.new.baza.zadnica.info_f
G2L["6a"] = Instance.new("Frame", G2L["3"]);
G2L["6a"]["Visible"] = false;
G2L["6a"]["BorderSizePixel"] = 0;
G2L["6a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6a"]["Size"] = UDim2.new(0, 54, 0, 41);
G2L["6a"]["Position"] = UDim2.new(-0.01008, 0, -0.01279, 0);
G2L["6a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6a"]["Name"] = [[info_f]];
G2L["6a"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.info_f.knopka
G2L["6b"] = Instance.new("Frame", G2L["6a"]);
G2L["6b"]["BorderSizePixel"] = 0;
G2L["6b"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["6b"]["Size"] = UDim2.new(0, 465, 0, 47);
G2L["6b"]["Position"] = UDim2.new(2.31481, 0, 0.4878, 0);
G2L["6b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6b"]["Name"] = [[knopka]];


-- StarterGui.new.baza.zadnica.info_f.knopka.UIStroke
G2L["6c"] = Instance.new("UIStroke", G2L["6b"]);
G2L["6c"]["Transparency"] = 0.86;
G2L["6c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["6c"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.info_f.knopka.ImageLabel
G2L["6d"] = Instance.new("ImageLabel", G2L["6b"]);
G2L["6d"]["BorderSizePixel"] = 0;
G2L["6d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6d"]["Image"] = [[rbxassetid://95272865678017]];
G2L["6d"]["Size"] = UDim2.new(0, 465, 0, 2);
G2L["6d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6d"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.info_f.knopka.ImageLabel.animation
G2L["6e"] = Instance.new("LocalScript", G2L["6d"]);
G2L["6e"]["Name"] = [[animation]];


-- StarterGui.new.baza.zadnica.info_f.knopka.TextLabel
G2L["6f"] = Instance.new("TextLabel", G2L["6b"]);
G2L["6f"]["BorderSizePixel"] = 0;
G2L["6f"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["6f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6f"]["TextSize"] = 14;
G2L["6f"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6f"]["BackgroundTransparency"] = 1;
G2L["6f"]["Size"] = UDim2.new(0, 287, 0, 45);
G2L["6f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6f"]["Text"] = [[My discord: pianino2]];
G2L["6f"]["Position"] = UDim2.new(0.03226, 0, 0.04255, 0);


-- StarterGui.new.baza.zadnica.info_f.knopka.TextButton
G2L["70"] = Instance.new("TextButton", G2L["6b"]);
G2L["70"]["BorderSizePixel"] = 0;
G2L["70"]["TextSize"] = 14;
G2L["70"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["70"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["70"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["70"]["Size"] = UDim2.new(0, 109, 0, 28);
G2L["70"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["70"]["Text"] = [[Click!]];
G2L["70"]["Position"] = UDim2.new(0.74839, 0, 0.21277, 0);


-- StarterGui.new.baza.zadnica.info_f.knopka.TextButton.UIStroke
G2L["71"] = Instance.new("UIStroke", G2L["70"]);
G2L["71"]["Transparency"] = 0.86;
G2L["71"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["71"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.info_f.knopka.TextButton.LocalScript
G2L["72"] = Instance.new("LocalScript", G2L["70"]);



-- StarterGui.new.baza.zadnica.info_f.knopka
G2L["73"] = Instance.new("Frame", G2L["6a"]);
G2L["73"]["BorderSizePixel"] = 0;
G2L["73"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["73"]["Size"] = UDim2.new(0, 465, 0, 47);
G2L["73"]["Position"] = UDim2.new(2.31481, 0, 1.92683, 0);
G2L["73"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["73"]["Name"] = [[knopka]];


-- StarterGui.new.baza.zadnica.info_f.knopka.UIStroke
G2L["74"] = Instance.new("UIStroke", G2L["73"]);
G2L["74"]["Transparency"] = 0.86;
G2L["74"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["74"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.info_f.knopka.ImageLabel
G2L["75"] = Instance.new("ImageLabel", G2L["73"]);
G2L["75"]["BorderSizePixel"] = 0;
G2L["75"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["75"]["Image"] = [[rbxassetid://95272865678017]];
G2L["75"]["Size"] = UDim2.new(0, 465, 0, 2);
G2L["75"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["75"]["BackgroundTransparency"] = 1;


-- StarterGui.new.baza.zadnica.info_f.knopka.ImageLabel.animation
G2L["76"] = Instance.new("LocalScript", G2L["75"]);
G2L["76"]["Name"] = [[animation]];


-- StarterGui.new.baza.zadnica.info_f.knopka.TextLabel
G2L["77"] = Instance.new("TextLabel", G2L["73"]);
G2L["77"]["BorderSizePixel"] = 0;
G2L["77"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["77"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["77"]["TextSize"] = 14;
G2L["77"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["77"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["77"]["BackgroundTransparency"] = 1;
G2L["77"]["Size"] = UDim2.new(0, 287, 0, 45);
G2L["77"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["77"]["Text"] = [[Discord server: https://discord.gg/gfevbcDyzm]];
G2L["77"]["Position"] = UDim2.new(0.03226, 0, 0.04255, 0);


-- StarterGui.new.baza.zadnica.info_f.knopka.TextButton
G2L["78"] = Instance.new("TextButton", G2L["73"]);
G2L["78"]["BorderSizePixel"] = 0;
G2L["78"]["TextSize"] = 14;
G2L["78"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["78"]["BackgroundColor3"] = Color3.fromRGB(13, 13, 13);
G2L["78"]["FontFace"] = Font.new([[rbxassetid://12187360881]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["78"]["Size"] = UDim2.new(0, 109, 0, 28);
G2L["78"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["78"]["Text"] = [[Click!]];
G2L["78"]["Position"] = UDim2.new(0.74839, 0, 0.21277, 0);


-- StarterGui.new.baza.zadnica.info_f.knopka.TextButton.UIStroke
G2L["79"] = Instance.new("UIStroke", G2L["78"]);
G2L["79"]["Transparency"] = 0.86;
G2L["79"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["79"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.new.baza.zadnica.info_f.knopka.TextButton.LocalScript
G2L["7a"] = Instance.new("LocalScript", G2L["78"]);



-- StarterGui.new.baza.UIStroke
G2L["7b"] = Instance.new("UIStroke", G2L["2"]);
G2L["7b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.new.baza.LocalScript
G2L["7c"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.new.baza.zadnica.ImageLabel.animation
local function C_6()
local script = G2L["6"];
	local notifications = script.Parent --почему нотификатионы? потому что я еблан!
	local TweenService = game:GetService("TweenService")
	
	
	
	local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, -1, true)
	
	local transparencyTween = TweenService:Create(notifications, tweenInfo, { ImageTransparency = 1 })
	
	transparencyTween:Play()
	
	
	
end;
task.spawn(C_6);
-- StarterGui.new.baza.zadnica.buttons.rage.LocalScript
local function C_d()
local script = G2L["d"];
	script.Parent.MouseButton1Click:Connect(function()
		
		script.Parent.Parent.rage.ImageLabel.ImageTransparency = 0
		script.Parent.Parent.visuals.ImageLabel.ImageTransparency = 0.5
		script.Parent.Parent.movement.ImageLabel.ImageTransparency = 0.5
		script.Parent.Parent.info.ImageLabel.ImageTransparency = 0.5
		
		
		
		script.Parent.Parent.Parent.combat_f.Visible = true
		script.Parent.Parent.Parent.info_f.Visible = false
		script.Parent.Parent.Parent.movement_f.Visible = false
		script.Parent.Parent.Parent.visuals_f.Visible = false
	end)
end;
task.spawn(C_d);
-- StarterGui.new.baza.zadnica.buttons.visuals.LocalScript
local function C_10()
local script = G2L["10"];
	script.Parent.MouseButton1Click:Connect(function()
	
		script.Parent.Parent.rage.ImageLabel.ImageTransparency = 0.5
		script.Parent.Parent.visuals.ImageLabel.ImageTransparency = 0
		script.Parent.Parent.movement.ImageLabel.ImageTransparency = 0.5
		script.Parent.Parent.info.ImageLabel.ImageTransparency = 0.5
	
	
	
		script.Parent.Parent.Parent.combat_f.Visible = false
		script.Parent.Parent.Parent.info_f.Visible = false
		script.Parent.Parent.Parent.movement_f.Visible = false
		script.Parent.Parent.Parent.visuals_f.Visible = true
	end)
end;
task.spawn(C_10);
-- StarterGui.new.baza.zadnica.buttons.movement.LocalScript
local function C_13()
local script = G2L["13"];
	script.Parent.MouseButton1Click:Connect(function()
	
		script.Parent.Parent.rage.ImageLabel.ImageTransparency = 0.5
		script.Parent.Parent.visuals.ImageLabel.ImageTransparency = 0.5
		script.Parent.Parent.movement.ImageLabel.ImageTransparency = 0
		script.Parent.Parent.info.ImageLabel.ImageTransparency = 0.5
	
	
	
		script.Parent.Parent.Parent.combat_f.Visible = false
		script.Parent.Parent.Parent.info_f.Visible = false
		script.Parent.Parent.Parent.movement_f.Visible = true
		script.Parent.Parent.Parent.visuals_f.Visible = false
	end)
end;
task.spawn(C_13);
-- StarterGui.new.baza.zadnica.buttons.info.LocalScript
local function C_15()
local script = G2L["15"];
	script.Parent.MouseButton1Click:Connect(function()
	
		script.Parent.Parent.rage.ImageLabel.ImageTransparency = 0.5
		script.Parent.Parent.visuals.ImageLabel.ImageTransparency = 0.5
		script.Parent.Parent.movement.ImageLabel.ImageTransparency = 0.5
		script.Parent.Parent.info.ImageLabel.ImageTransparency = 0
	
	
	
		script.Parent.Parent.Parent.combat_f.Visible = false
		script.Parent.Parent.Parent.info_f.Visible = true
		script.Parent.Parent.Parent.movement_f.Visible = false
		script.Parent.Parent.Parent.visuals_f.Visible = false
	end)
end;
task.spawn(C_15);
-- StarterGui.new.baza.zadnica.combat_f.knopka.ImageLabel.animation
local function C_1b()
local script = G2L["1b"];
	local notifications = script.Parent --почему нотификатионы? потому что я еблан!
	local TweenService = game:GetService("TweenService")
	
	
	
	local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, -1, true)
	
	local transparencyTween = TweenService:Create(notifications, tweenInfo, { ImageTransparency = 1 })
	
	transparencyTween:Play()
	
	
	
end;
task.spawn(C_1b);
-- StarterGui.new.baza.zadnica.combat_f.knopka.TextButton.LocalScript
local function C_1f()
local script = G2L["1f"];
	script.Parent.MouseButton1Click:Connect(function()
		while wait () do
			for i, e in pairs(game.Players:GetChildren()) do
				if e ~= game.Players.LocalPlayer then
					local meleeEvent = game:GetService("ReplicatedStorage").meleeEvent
					meleeEvent:FireServer(e)
				end end end
	end)
end;
task.spawn(C_1f);
-- StarterGui.new.baza.zadnica.combat_f.knopka.ImageLabel.animation
local function C_23()
local script = G2L["23"];
	local notifications = script.Parent --почему нотификатионы? потому что я еблан!
	local TweenService = game:GetService("TweenService")
	
	
	
	local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, -1, true)
	
	local transparencyTween = TweenService:Create(notifications, tweenInfo, { ImageTransparency = 1 })
	
	transparencyTween:Play()
	
	
	
end;
task.spawn(C_23);
-- StarterGui.new.baza.zadnica.combat_f.knopka.TextButton.LocalScript
local function C_27()
local script = G2L["27"];
	script.Parent.MouseButton1Click:Connect(function()
		spawn(function()
			while wait(0.1) do
				for i, v in next, game:GetService("Players"):GetChildren() do
					pcall(function()
						if v~= game:GetService("Players").LocalPlayer and not v.Character:FindFirstChildOfClass("ForceField") and v.Character.Humanoid.Health > 0 then
							while v.Character:WaitForChild("Humanoid").Health > 0 do
								wait();
								game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Character.HumanoidRootPart.CFrame;
								for x, c in next, game:GetService("Players"):GetChildren() do
									if c ~= game:GetService("Players").LocalPlayer then game.ReplicatedStorage.meleeEvent:FireServer(c) end
								end
							end
						end
					end)
					wait()
				end
			end
		end)
	end)
end;
task.spawn(C_27);
-- StarterGui.new.baza.zadnica.combat_f.knopka.ImageLabel.animation
local function C_2b()
local script = G2L["2b"];
	local notifications = script.Parent --почему нотификатионы? потому что я еблан!
	local TweenService = game:GetService("TweenService")
	
	
	
	local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, -1, true)
	
	local transparencyTween = TweenService:Create(notifications, tweenInfo, { ImageTransparency = 1 })
	
	transparencyTween:Play()
	
	
	
end;
task.spawn(C_2b);
-- StarterGui.new.baza.zadnica.combat_f.knopka.TextButton.LocalScript
local function C_2f()
local script = G2L["2f"];
	script.Parent.MouseButton1Click:Connect(function()
		-- Configuration
		local config = {
			TeamCheck = false,   -- Set to true to only target players on different teams
			FOV = 150,           -- Field of View
			Smoothing = 1,       -- Camera smoothing factor
			KeyToToggle = Enum.KeyCode.E, -- Key to toggle the aimbot
		}
	
		-- Services
		local RunService = game:GetService("RunService")
		local UserInputService = game:GetService("UserInputService")
	
		-- GUI
		local FOVring = Drawing.new("Circle")
		FOVring.Visible = true
		FOVring.Thickness = 1.5
		FOVring.Radius = config.FOV
		FOVring.Transparency = 1
		FOVring.Color = Color3.fromRGB(255, 128, 128)
		FOVring.Position = workspace.CurrentCamera.ViewportSize / 2
	
		-- Function to get the closest visible player
		local function getClosestVisiblePlayer(camera)
			local ray = Ray.new(camera.CFrame.Position, camera.CFrame.LookVector)
			local closestPlayer = nil
			local closestDistance = math.huge
	
			for _, player in pairs(game.Players:GetPlayers()) do
				if player ~= game.Players.LocalPlayer then
					local character = player.Character
					if character and character:FindFirstChild("Head") then
						local headPosition = character.Head.Position
						local targetPosition = ray:ClosestPoint(headPosition)
						local distance = (targetPosition - headPosition).Magnitude
	
						if distance < closestDistance then
							closestDistance = distance
							closestPlayer = player
						end
					end
				end
			end
	
			return closestPlayer
		end
	
		-- Function to toggle the aimbot
		local aimbotEnabled = false
	
		local function toggleAimbot()
			aimbotEnabled = not aimbotEnabled
			FOVring.Visible = aimbotEnabled
		end
	
		-- Function to update the aimbot
		local function updateAimbot()
			if aimbotEnabled then
				local currentCamera = workspace.CurrentCamera
				local crosshairPosition = currentCamera.ViewportSize / 2
				local closestPlayer = getClosestVisiblePlayer(currentCamera)
	
				if closestPlayer then
					local headPosition = closestPlayer.Character.Head.Position
					local headScreenPosition = currentCamera:WorldToScreenPoint(headPosition)
					local distanceToCrosshair = (Vector2.new(headScreenPosition.X, headScreenPosition.Y) - crosshairPosition).Magnitude
	
					if distanceToCrosshair < config.FOV then
						currentCamera.CFrame = currentCamera.CFrame:Lerp(CFrame.new(currentCamera.CFrame.Position, headPosition), config.Smoothing)
					end
				end
			end
		end
	
		-- Connect the toggleAimbot function to the toggle key
		UserInputService.InputBegan:Connect(function(input)
			if input.KeyCode == config.KeyToToggle then
				toggleAimbot()
			end
		end)
	
		-- Connect the updateAimbot function to the RenderStepped event
		local aimbotConnection
	
		UserInputService.InputBegan:Connect(function(input)
			if input.KeyCode == config.KeyToToggle then
				if aimbotEnabled then
					FOVring:Remove()
					aimbotConnection:Disconnect()
				else
					FOVring.Position = workspace.CurrentCamera.ViewportSize / 2
					FOVring.Radius = config.FOV
					aimbotConnection = RunService.RenderStepped:Connect(updateAimbot)
				end
			end
		end)
	end)
end;
task.spawn(C_2f);
-- StarterGui.new.baza.zadnica.visuals_f.knopka.ImageLabel.animation
local function C_34()
local script = G2L["34"];
	local notifications = script.Parent --почему нотификатионы? потому что я еблан!
	local TweenService = game:GetService("TweenService")
	
	
	
	local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, -1, true)
	
	local transparencyTween = TweenService:Create(notifications, tweenInfo, { ImageTransparency = 1 })
	
	transparencyTween:Play()
	
	
	
end;
task.spawn(C_34);
-- StarterGui.new.baza.zadnica.visuals_f.knopka.TextButton.LocalScript
local function C_38()
local script = G2L["38"];
	script.Parent.MouseButton1Click:Connect(function()
	
		while wait(0.1) do
			for i, childrik in ipairs(workspace:GetDescendants()) do
				if childrik:FindFirstChild("Humanoid") then
					if not childrik:FindFirstChild("EspBox") then
						if childrik ~= game.Players.LocalPlayer.Character then
							local esp = Instance.new("BoxHandleAdornment",childrik)
							esp.Adornee = childrik
							esp.ZIndex = 0
							esp.Size = Vector3.new(4, 5, 1)
							esp.Transparency = 0.65
							esp.Color3 = Color3.fromRGB(255,48,48)
							esp.AlwaysOnTop = true
							esp.Name = "EspBox"
						end
					end
				end
			end
		end
	
	end)
end;
task.spawn(C_38);
-- StarterGui.new.baza.zadnica.visuals_f.knopka.ImageLabel.animation
local function C_3c()
local script = G2L["3c"];
	local notifications = script.Parent --почему нотификатионы? потому что я еблан!
	local TweenService = game:GetService("TweenService")
	
	
	
	local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, -1, true)
	
	local transparencyTween = TweenService:Create(notifications, tweenInfo, { ImageTransparency = 1 })
	
	transparencyTween:Play()
	
	
	
end;
task.spawn(C_3c);
-- StarterGui.new.baza.zadnica.visuals_f.knopka.TextButton.LocalScript
local function C_40()
local script = G2L["40"];
	local state = false
	script.Parent.MouseButton1Click:Connect(function()
		state = not state
		if state then 
	
			script.Parent.BackgroundTransparency = 0
			script.Parent.Text = "on"
	
			workspace.Camera.FieldOfView = 120
		else
	
	
	
	
	
			script.Parent.BackgroundTransparency = 1
			script.Parent.Text = "off"
			workspace.Camera.FieldOfView = 70
	
	
		end
	end)
end;
task.spawn(C_40);
-- StarterGui.new.baza.zadnica.movement_f.knopka.ImageLabel.animation
local function C_45()
local script = G2L["45"];
	local notifications = script.Parent --почему нотификатионы? потому что я еблан!
	local TweenService = game:GetService("TweenService")
	
	
	
	local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, -1, true)
	
	local transparencyTween = TweenService:Create(notifications, tweenInfo, { ImageTransparency = 1 })
	
	transparencyTween:Play()
	
	
	
end;
task.spawn(C_45);
-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton.LocalScript
local function C_49()
local script = G2L["49"];
	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
	end)
end;
task.spawn(C_49);
-- StarterGui.new.baza.zadnica.movement_f.knopka.ImageLabel.animation
local function C_4d()
local script = G2L["4d"];
	local notifications = script.Parent --почему нотификатионы? потому что я еблан!
	local TweenService = game:GetService("TweenService")
	
	
	
	local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, -1, true)
	
	local transparencyTween = TweenService:Create(notifications, tweenInfo, { ImageTransparency = 1 })
	
	transparencyTween:Play()
	
	
	
end;
task.spawn(C_4d);
-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton.LocalScript
local function C_51()
local script = G2L["51"];
	script.Parent.MouseButton1Click:Connect(function()
	
		local Noclip = nil
		local Clip = nil
	
		function noclip()
			Clip = false
			local function Nocl()
				if Clip == false and game.Players.LocalPlayer.Character ~= nil then
					for _,v in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
						if v:IsA('BasePart') and v.CanCollide and v.Name ~= floatName then
							v.CanCollide = false
						end
					end
				end
				wait(0.21) -- basic optimization
			end
			Noclip = game:GetService('RunService').Stepped:Connect(Nocl)
		end
	
		function clip()
			if Noclip then Noclip:Disconnect() end
			Clip = true
		end
	
		noclip() -- to toggle noclip() and clip()
	
	end)
end;
task.spawn(C_51);
-- StarterGui.new.baza.zadnica.movement_f.knopka.ImageLabel.animation
local function C_55()
local script = G2L["55"];
	local notifications = script.Parent --почему нотификатионы? потому что я еблан!
	local TweenService = game:GetService("TweenService")
	
	
	
	local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, -1, true)
	
	local transparencyTween = TweenService:Create(notifications, tweenInfo, { ImageTransparency = 1 })
	
	transparencyTween:Play()
	
	
	
end;
task.spawn(C_55);
-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton.LocalScript
local function C_59()
local script = G2L["59"];
	script.Parent.MouseButton1Click:Connect(function()
	
	
		local FLYING = false
		function sFLY(flyspeed, QEfly, vfly)
			repeat wait() until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart") and game.Players.LocalPlayer.Character:FindFirstChildOfClass("Humanoid")
			repeat wait() until game.Players.LocalPlayer:GetMouse()
			if flyKeyDown or flyKeyUp then flyKeyDown:Disconnect() flyKeyUp:Disconnect() end
	
			local Character = game.Players.LocalPlayer.Character
			local hrp = Character:FindFirstChild("HumanoidRootPart")
			local hum = game.Players.LocalPlayer.Character:FindFirstChildOfClass("Humanoid")
			local mouse = game.Players.LocalPlayer:GetMouse()
			local moverParent = game.Workspace:FindFirstChildOfClass("Terrain")
			local moverAttachment = hrp.RootAttachment
	
			local T = hrp
			local CONTROL = {F = 0, B = 0, L = 0, R = 0, Q = 0, E = 0}
			local lCONTROL = {F = 0, B = 0, L = 0, R = 0, Q = 0, E = 0}
			local SPEED = 0
	
			local function FLY()
				FLYING = true
				local BG = Instance.new('AlignOrientation')
				BG.Mode = Enum.OrientationAlignmentMode.OneAttachment
				BG.RigidityEnabled = true
				BG.MaxTorque = Vector3.new(9e9, 9e9, 9e9)
				BG.CFrame = T.CFrame
				BG.Attachment0 = moverAttachment
				local BV = Instance.new('LinearVelocity')
				BV.VectorVelocity = Vector3.new(0, 0, 0)
				BV.MaxForce = 9e9
				BV.Attachment0 = moverAttachment
	
				BG.Parent = moverParent
				BV.Parent = moverParent
	
				task.spawn(function()
					repeat wait()
						if not vfly and hum then
							hum.PlatformStand = true
						end
						if CONTROL.L + CONTROL.R ~= 0 or CONTROL.F + CONTROL.B ~= 0 or CONTROL.Q + CONTROL.E ~= 0 then
							SPEED = 50
						elseif not (CONTROL.L + CONTROL.R ~= 0 or CONTROL.F + CONTROL.B ~= 0 or CONTROL.Q + CONTROL.E ~= 0) and SPEED ~= 0 then
							SPEED = 0
						end
						if (CONTROL.L + CONTROL.R) ~= 0 or (CONTROL.F + CONTROL.B) ~= 0 or (CONTROL.Q + CONTROL.E) ~= 0 then
							BV.VectorVelocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (CONTROL.F + CONTROL.B)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(CONTROL.L + CONTROL.R, (CONTROL.F + CONTROL.B + CONTROL.Q + CONTROL.E) * 0.2, 0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p)) * SPEED
							lCONTROL = {F = CONTROL.F, B = CONTROL.B, L = CONTROL.L, R = CONTROL.R}
						elseif (CONTROL.L + CONTROL.R) == 0 and (CONTROL.F + CONTROL.B) == 0 and (CONTROL.Q + CONTROL.E) == 0 and SPEED ~= 0 then
							BV.VectorVelocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lCONTROL.F + lCONTROL.B)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lCONTROL.L + lCONTROL.R, (lCONTROL.F + lCONTROL.B + CONTROL.Q + CONTROL.E) * 0.2, 0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p)) * SPEED
						else
							BV.VectorVelocity = Vector3.new(0, 0, 0)
						end
						BG.CFrame = game.Workspace.CurrentCamera.CoordinateFrame
					until not FLYING or Character.Parent == nil
					CONTROL = {F = 0, B = 0, L = 0, R = 0, Q = 0, E = 0}
					lCONTROL = {F = 0, B = 0, L = 0, R = 0, Q = 0, E = 0}
					SPEED = 0
					BG:Destroy()
					BV:Destroy()
					if hum then
						hum.PlatformStand = false
					end
				end)
			end
			flyKeyDown = mouse.KeyDown:Connect(function(KEY)
				if KEY:lower() == 'w' then
					CONTROL.F = flyspeed
				elseif KEY:lower() == 's' then
					CONTROL.B = - flyspeed
				elseif KEY:lower() == 'a' then
					CONTROL.L = - flyspeed
				elseif KEY:lower() == 'd' then 
					CONTROL.R = flyspeed
				elseif QEfly and KEY:lower() == 'e' then
					CONTROL.Q = flyspeed * 2
				elseif QEfly and KEY:lower() == 'q' then
					CONTROL.E = - flyspeed * 2
				end
				pcall(function() game.Workspace.CurrentCamera.CameraType = Enum.CameraType.Track end)
			end)
			flyKeyUp = mouse.KeyUp:Connect(function(KEY)
				if KEY:lower() == 'w' then
					CONTROL.F = 0
				elseif KEY:lower() == 's' then
					CONTROL.B = 0
				elseif KEY:lower() == 'a' then
					CONTROL.L = 0
				elseif KEY:lower() == 'd' then
					CONTROL.R = 0
				elseif KEY:lower() == 'e' then
					CONTROL.Q = 0
				elseif KEY:lower() == 'q' then
					CONTROL.E = 0
				end
			end)
			FLY()
		end
	
		sFLY(1, true, false)
	
	end)
end;
task.spawn(C_59);
-- StarterGui.new.baza.zadnica.movement_f.knopka.ImageLabel.animation
local function C_5d()
local script = G2L["5d"];
	local notifications = script.Parent --почему нотификатионы? потому что я еблан!
	local TweenService = game:GetService("TweenService")
	
	
	
	local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, -1, true)
	
	local transparencyTween = TweenService:Create(notifications, tweenInfo, { ImageTransparency = 1 })
	
	transparencyTween:Play()
	
	
	
end;
task.spawn(C_5d);
-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton.LocalScript
local function C_61()
local script = G2L["61"];
	script.Parent.MouseButton1Click:Connect(function()
	
		local Noclip = nil
		local Clip = nil
	
		function noclip()
			Clip = false
			local function Nocl()
				if Clip == false and game.Players.LocalPlayer.Character ~= nil then
					for _,v in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
						if v:IsA('BasePart') and v.CanCollide and v.Name ~= floatName then
							v.CanCollide = false
						end
					end
				end
				wait(0.21) -- basic optimization
			end
			Noclip = game:GetService('RunService').Stepped:Connect(Nocl)
		end
	
		function clip()
			if Noclip then Noclip:Disconnect() end
			Clip = true
		end
	
		noclip() -- to toggle noclip() and clip()
	
	end)
end;
task.spawn(C_61);
-- StarterGui.new.baza.zadnica.movement_f.knopka.ImageLabel.animation
local function C_65()
local script = G2L["65"];
	local notifications = script.Parent --почему нотификатионы? потому что я еблан!
	local TweenService = game:GetService("TweenService")
	
	
	
	local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, -1, true)
	
	local transparencyTween = TweenService:Create(notifications, tweenInfo, { ImageTransparency = 1 })
	
	transparencyTween:Play()
	
	
	
end;
task.spawn(C_65);
-- StarterGui.new.baza.zadnica.movement_f.knopka.TextButton.LocalScript
local function C_69()
local script = G2L["69"];
	script.Parent.MouseButton1Click:Connect(function()
	
		local InfiniteJumpEnabled = true
		game:GetService("UserInputService").JumpRequest:connect(function()
			if InfiniteJumpEnabled then
				game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
			end
		end)
	
	end)
end;
task.spawn(C_69);
-- StarterGui.new.baza.zadnica.info_f.knopka.ImageLabel.animation
local function C_6e()
local script = G2L["6e"];
	local notifications = script.Parent --почему нотификатионы? потому что я еблан!
	local TweenService = game:GetService("TweenService")
	
	
	
	local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, -1, true)
	
	local transparencyTween = TweenService:Create(notifications, tweenInfo, { ImageTransparency = 1 })
	
	transparencyTween:Play()
	
	
	
end;
task.spawn(C_6e);
-- StarterGui.new.baza.zadnica.info_f.knopka.TextButton.LocalScript
local function C_72()
local script = G2L["72"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Text = "Copied to clipboard!"
	 
		task.wait(2)
		script.Parent.Text = "Click!"
		setclipboard("pianino2")
	end)
end;
task.spawn(C_72);
-- StarterGui.new.baza.zadnica.info_f.knopka.ImageLabel.animation
local function C_76()
local script = G2L["76"];
	local notifications = script.Parent --почему нотификатионы? потому что я еблан!
	local TweenService = game:GetService("TweenService")
	
	
	
	local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, -1, true)
	
	local transparencyTween = TweenService:Create(notifications, tweenInfo, { ImageTransparency = 1 })
	
	transparencyTween:Play()
	
	
	
end;
task.spawn(C_76);
-- StarterGui.new.baza.zadnica.info_f.knopka.TextButton.LocalScript
local function C_7a()
local script = G2L["7a"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Text = "Copied to clipboard!"
		task.wait(2)
		script.Parent.Text = "Click!"
		setclipboard("https://discord.gg/gfevbcDyzm") 
	end)
end;
task.spawn(C_7a);
-- StarterGui.new.baza.LocalScript
local function C_7c()
local script = G2L["7c"];
	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.05
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
	
	
	
	
	
	
	local UIS = game:GetService('UserInputService')
	local Player = game.Players.LocalPlayer
	local Character = Player.Character
	local state = false
	
	
	
	
	UIS.InputBegan:connect(function(input)
		if input.KeyCode == Enum.KeyCode.Insert then
			state = not state
			if state then 
				script.Parent.Visible = false
			else
	
	
				script.Parent.Visible = true
	
	
			end
		end
	end)
	
end
task.spawn(C_7c);

return G2L["1"], require;


