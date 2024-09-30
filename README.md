```lua
-- Criar um ScreenGui
local screenGui = Instance.new("ScreenGui")
screenGui.Name = "FloatingIconGui"
screenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

-- Criar um Frame para o ícone flutuante
local iconFrame = Instance.new("Frame")
iconFrame.Size = UDim2.new(0, 100, 0, 100) -- Tamanho do ícone
iconFrame.Position = UDim2.new(0.5, -50, 0.5, -50) -- Posição no centro da tela
iconFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255) -- Cor de fundo branca
iconFrame.BackgroundTransparency = 0.5 -- Transparência do fundo
iconFrame.BorderSizePixel = 0 -- Sem borda
iconFrame.Parent = screenGui

-- Criar um ImageLabel para exibir a imagem do ícone
local imageLabel = Instance.new("ImageLabel")
imageLabel.Size = UDim2.new(1, 0, 1, 0) -- Preencher o Frame
imageLabel.Image = "rbxassetid://SEU_ID_DE_IMAGEM_AQUI" -- Substitua pelo ID da sua imagem
imageLabel.BackgroundTransparency = 1 -- Fundo transparente
imageLabel.Parent = iconFrame

-- Função para fazer o ícone flutuar
local function floatIcon()
    while true do
        iconFrame.Position = iconFrame.Position + UDim2.new(0, 0, 0.01, 0) -- Movimento para cima
        wait(0.1)
        iconFrame.Position = iconFrame.Position - UDim2.new(0, 0, 0.01, 0) -- Movimento para baixo
        wait(0.1)
    end
end

-- Iniciar a flutuação do ícone
floatIcon()
```

### Vitor Hub - Script Completo

```lua
-- Vitor Hub - Script Completo

-- Configurações
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local workspace = game:GetService("Workspace")
local teleportService = game:GetService("TeleportService")

-- Funções de Farm
local function farmLevel()
    print("Iniciando farm de nível...")
    -- Adicione aqui a lógica para farmar nível.
end

local function farmKatakuri()
    print("Fazendo farm de Katakuri...")
    -- Adicione aqui a lógica para farmar Katakuri.
end

local function farmOssos()
    print("Fazendo farm de ossos...")
    -- Adicione aqui a lógica para farmar ossos.
end

local function farmBau()
    print("Fazendo farm de baú...")
    -- Adicione aqui a lógica para farmar baús.
end

-- Funções de Auto Ativação
local function autoAtivarV4()
    print("Ativando V4...")
    -- Lógica para ativar V4.
end

local function autoAtivarV3()
    print("Ativando V3...")
    -- Lógica para ativar V3.
end

local function autoAtivarHakiObs()
    print("Ativando Haki Observação...")
    -- Lógica para ativar Haki Observação.
end

-- Funções de Teleporte
local function teleporteFruta()
    print("Teleportando para fruta...")
    -- Lógica para teletransportar para a fruta mais próxima.
end

local function guardarFruta()
    print("Guardando fruta...")
    -- Lógica para guardar a fruta atual no inventário.
end

local function girarFruta()
    print("Girando fruta...")
    -- Lógica para girar a fruta.
end

-- Funções de ESP
local function espPlayers()
    print("Ativando ESP nos jogadores...")
    -- Lógica para ativar ESP em jogadores.
end

local function espFruta()
    print("Ativando ESP nas frutas...")
    -- Lógica para ativar ESP nas frutas.
end

local function espIsland()
    print("Ativando ESP nas ilhas...")
    -- Lógica para ativar ESP nas ilhas.
end

-- Iniciar as funções conforme necessário (exemplo)
farmLevel()       -- Inicia o farm de nível
farmKatakuri()    -- Inicia o farm de Katakuri
farmOssos()       -- Inicia o farm de ossos
farmBau()         -- Inicia o farm de baú
autoAtivarV4()    -- Ativa V4
autoAtivarV3()   -- Ativa V3
autoAtivarHakiObs()  -- Ativa Haki Observação
teleporteFruta()  -- Teleporta para a fruta
guardarFruta()   -- Guarda a fruta atual
girarFruta()     -- Gira a fruta
espPlayers()     -- Ativa ESP em jogadores
espFruta()       -- Ativa ESP em frutas
espIsland()      -- Ativa ESP em ilhas

```
