 local function CreateInstance(type, parent, data)
        local createdInstance = Instance.new(type)
            
        for index, value in next, data do
            createdInstance[index] = value
        end
            
        createdInstance.Parent = parent
        
        return createdInstance
    end

    local FarmUI = CreateInstance("ScreenGui", gethui(), {
        Name = "Kappa"
    })

    local holder = CreateInstance("ImageLabel", FarmUI, {
        Name = "holder",
        BackgroundTransparency = 1.000,
        Position = UDim2.new(0.0506075993, 0, 0.655761302, 0),
        Size = UDim2.new(0, 278, 0, 145),
        Image = "rbxassetid://4928857387",
        ImageColor3 = Color3.fromRGB(90, 168, 196)
    })

    local title = CreateInstance("TextLabel", holder, {
        Name = "title",
        AnchorPoint = Vector2.new(0.5, 0),
        BackgroundTransparency = 1.000,
        Position = UDim2.new(0.5, 0, 0.0500000007, 0),
        Size = UDim2.new(0, 200, 0, 26),
        Font = Enum.Font.SourceSansBold,
        Text = "FarmHub Drop Farm",
        TextColor3 = Color3.fromRGB(255, 255, 255),
        TextScaled = true,
        TextSize = 14.000,
        TextWrapped = true
    })

    local stats = CreateInstance("TextLabel", holder, {
        Name = "stats",
        AnchorPoint = Vector2.new(0.5, 0),
        BackgroundTransparency = 1.000,
        Position = UDim2.new(0.5, 0, 0.229310349, 0),
        Size = UDim2.new(0, 260, 0, 34),
        Font = Enum.Font.SourceSansBold,
        Text = "Loading, Please wait..",
        TextColor3 = Color3.fromRGB(255, 255, 255),
        TextSize = 15.500,
        TextWrapped = true
    })

    local status = CreateInstance("TextLabel", holder, {
        Name = "status",
        AnchorPoint = Vector2.new(0.5, 0),
        BackgroundColor3 = Color3.fromRGB(17, 32, 37),
        Position = UDim2.new(0.5, 0, 0.5, 0),
        Size = UDim2.new(0, 239, 0, 34),
        Font = Enum.Font.SourceSansBold,
        Text = "   Loading..",
        TextColor3 = Color3.fromRGB(255, 255, 255),
        TextSize = 20.000,
        TextXAlignment = Enum.TextXAlignment.Left
    })

    local uicorner = CreateInstance("UICorner", status, {
        CornerRadius = UDim.new(0, 10)
    })

    local uistroke = CreateInstance("UIStroke", status, {
        ApplyStrokeMode = "Border",
        Color = Color3.fromRGB(67, 125, 146),
        Thickness = 3,
    })

    local invite = CreateInstance("TextLabel", holder, {
        Name = "invite",
        AnchorPoint = Vector2.new(0.5, 0),
        BackgroundTransparency = 1.000,
        Position = UDim2.new(0.5, 0, 0.75, 0),
        Size = UDim2.new(0, 248, 0, 34),
        Font = Enum.Font.SourceSansBold,
        Text = "",
        TextColor3 = Color3.fromRGB(255, 255, 255),
        TextSize = 15.000,
        TextWrapped = true
    })