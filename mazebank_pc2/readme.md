    local success = exports['mazebank_pc2']:StartMazeBank2()
    if success then
        ESX.ShowNotification('Udane')
    elseif not success then
        ESX.ShowNotification('Nie Udane')
    end