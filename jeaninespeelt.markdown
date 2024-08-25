---
title: Jeanine probeert wat
description: Want da s leuk
layout: default
---
## Allergie-informatie

<div class="w-full mt-6 text-center">Bekijk de allergie-informatie voor:</div>

<div class="w-full my-2 flex justify-center">
  <button class="py-2 px-4 border-t-2 border-b-2 border-l-2 rounded-l hover:bg-secondary hover:text-white hover:border-secondary border-secondary bg-secondary text-white" onclick="changeProgram('dinsdagdiner')">Diner dinsdag</button>
  <button class="py-2 px-4 border-t-2 border-b-2 hover:bg-secondary hover:text-white hover:border-secondary border-primary" onclick="changeProgram('lunch')">Lunch woensdag</button>
  <button class="py-2 px-4 border-t-2 border-b-2 border-r-2 rounded-r hover:bg-secondary hover:text-white hover:border-secondary border-primary" onclick="changeProgram('woensdagdiner')">Diner woensdag</button>
</div>

<div id="program-content" class="mt-4">
  Selecteer een eetmoment om de allergie-informatie te bekijken.
</div>

<script>
  function changeProgram(type) {
    const contentDiv = document.getElementById('program-content');

    switch(type) {
      case 'dinsdagdiner':
        contentDiv.innerHTML = 'Dit is het menu van Diner dinsdag.';
        break;
      case 'lunch':
        contentDiv.innerHTML = 'Dit is het menu van Lunch woensdag.';
        break;
      case 'woensdagdiner':
        contentDiv.innerHTML = 'Dit is het menu van Diner woensdag.';
        break;
      default:
        contentDiv.innerHTML = 'Selecteer een eetmoment om de allergie-informatie te bekijken.';
    }
  }
</script>
