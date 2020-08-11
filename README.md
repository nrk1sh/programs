Fastzoom script:
alias f "weapon_crossbow;wait;wait;+attack2;wait;wait;+attack;wait;wait;-attack2;wait;wait;-attack;wait;wait;weapon_crowbar;wait;wait;wait;wait;wait;weapon_crossbow"
bind "key" "f"
Rpg script:
alias rpg "+attack;wait;-attack;+attack2;wait;-attack2;+reload;wait;-reload"
bind "key" "rpg"
Models OFF/ON script:
alias md "md1"
alias md1 "r_drawviewmodels 1;alias md md2"
alias md2 "r_drawviewmodels 0;alias md md1"
bind "key" "md"
