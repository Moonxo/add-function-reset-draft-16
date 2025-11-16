# add-function-reset-draft-16
function resetMyGarage() external override {
        delete garages[msg.sender];
    }
