### Vitor Hub - Script Completo

```lua
-- Vitor Hub - Script Completo
-- Este script é projetado para farmar níveis, Katakuri, ossos e baús, além de incluir funções de auto ativação e ESP.

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
