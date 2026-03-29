<style> 
  .card-container {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    justify-content: flex-start;
    align-content: flex-start;
    width: 190mm;
  }
  .card {
    border: 5px solid #58180D;
    background: #f0f0f0;
    padding: 10px;
    width: 63.5mm;
    height: 88.9mm;
    border-radius: 12px;
    box-sizing: border-box;
    #box-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    position: relative;
    overflow: hidden;
    font-family: 'BookSanity', sans-serif;
  }
  .card .title { color: #58180D; font-weight: bold; font-size: 23px; margin-bottom: 2px; border-bottom: 2px solid #58180D; font-family: 'MrEavesSmallCaps', sans-serif;}
  .card .type { font-style: italic; font-size: 12px; margin-top: 7px; margin-bottom: 16px; }
  .card .stat { font-weight: bold; font-size: 16px; margin: 2px 0; }
  .card .description { font-size: 16px; margin-top: 20px; line-height: 1.2; }
  .card .description b {font-weight: 800; }
  .card .footer { position: absolute; bottom: 8px; right: 8px; font-weight: bold; font-size: 14px; text-transform: uppercase; }
  .action { border-color: #228B22 !important; }
  .bonus { border-color: #DAA520 !important; }
  .reaction { border-color: #B22222 !important; }
  .familiar { border-color: #800080 !important; }
</style>

<div class="card-container">

<div class="card action">
<div class="title">Eldritch Blast</div>
<div class="type">Cantrip (Evocation)</div>
<div class="stat">Time: 1 Action</div>
<div class="stat">Range: 120 ft</div>
<div class="stat">Attack: 1d20 + 6</div>
<div class="stat">Damage: 1d10 + 4 Force</div>
<div class="description">A beam of crackling energy streaks toward a creature. If target is Hexed, add <b>1d6 Necrotic Damage</b>.</div>
<div class="footer">Action</div>
</div>

<div class="card action">
<div class="title">Burning Hands</div>
<div class="type">1st Level (Evocation) - Free</div>
<div class="stat">Time: 1 Action</div>
<div class="stat">Range: 15 ft Cone</div>
<div class="stat">Save: DC 14 Dex</div>
<div class="stat">Damage: 3d6 Fire</div>
<div class="description">Fire shoots from your fingertips. Half damage on successful save. Ignites flammable objects.</div>
<div class="footer">Action</div>
</div>

<div class="card action">
<div class="title">Command</div>
<div class="type">1st Level (Enchantment) - Free</div>
<div class="stat">Time: 1 Action</div>
<div class="stat">Range: 60 ft</div>
<div class="stat">Save: DC 14 Wis</div>
<div class="description">Speak a one-word command (e.g., "Halt," "Drop," "Flee"). Target must follow it on its next turn.</div>
<div class="footer">Action</div>
</div>

<div class="card action">
<div class="title">Armor of Agathys</div>
<div class="type">1st Level (Abjuration)</div>
<div class="stat">Time: 1 Action</div>
<div class="stat">Range: Self</div>
<div class="stat">Duration: 1 Hour</div>
<div class="description">Gain <b>5 Temporary HP</b>. While you have these HP, any creature that hits you with a melee attack takes <b>5 Cold Damage</b>.</div>
<div class="footer">Action</div>
</div>

</div>
\page

<div class="card-container">

<div class="card action">
<div class="title">Friends</div>
<div class="type">Cantrip (Enchantment)</div>
<div class="stat">Time: 1 Action</div>
<div class="stat">Range: 10 ft</div>
<div class="stat">Duration: 1 Minute</div>
<div class="description">Gain <b>Advantage</b> on all Charisma checks directed at one non-hostile creature. <i>(2024 Rule: No hostility when spell ends).</i></div>
<div class="footer">Action</div>
</div>

<div class="card bonus">
<div class="title">Hex</div>
<div class="type">1st Level (Enchantment)</div>
<div class="stat">Time: 1 Bonus Action</div>
<div class="stat">Range: 90 ft</div>
<div class="stat">Duration: 1 Hour (Conc)</div>
<div class="description">Target takes <b>1d6 Necrotic Damage</b> when you hit it and <b>Disadvantage</b> on checks for one stat. If target dies, move Hex on a later turn.</div>
<div class="footer">Bonus Action</div>
</div>

<div class="card bonus">
<div class="title">Misty Step</div>
<div class="type">2nd Level (Conjuration)</div>
<div class="stat">Time: 1 Bonus Action</div>
<div class="stat">Range: Self</div>
<div class="description">Briefly surrounded by silvery mist, you teleport up to 30 feet to an unoccupied space that you can see.</div>
<div class="footer">Bonus Action</div>
</div>

<div class="card bonus">
<div class="title">Command Imp</div>
<div class="type">Pact of the Chain (2024)</div>
<div class="stat">Time: 1 Bonus Action</div>
<div class="stat">Requirement: 100 ft</div>
<div class="description">You command Imp to take the <b>Attack</b> action on its turn.</div>
<div class="footer">Bonus Action</div>
</div>
</div>
\page

<div class="card-container">

<div class="card reaction">
<div class="title">Hellish Rebuke</div>
<div class="type">1st Level (Evocation)</div>
<div class="stat">Trigger: Taking Damage</div>
<div class="stat">Range: 60 ft</div>
<div class="stat">Save: DC 14 Dex</div>
<div class="stat">Damage: 2d10 Fire</div>
<div class="description">You blast the creature that hit you with hellfire. Half damage on successful save.</div>
<div class="footer">Reaction</div>
</div>

<div class="card familiar">
<div class="title">Imp: Sting (Attack)</div>
<div class="type">Imp Familiar (2024 Math)</div>
<div class="stat">Attack: 1d20 + 6</div>
<div class="stat">Damage: 1d4 + 4 Piercing</div>
<div class="description">Target makes a <b>DC 14 Con</b> save. On failure, it takes <b>3d6 Poison Damage</b> (half on success).</div>
<div class="footer">Familiar</div>
</div>

<div class="card familiar">
<div class="title">Imp: Invisibility</div>
<div class="type">Imp Familiar</div>
<div class="stat">Time: 1 Action (Imp)</div>
<div class="description">Imp magically turns Invisible until he attacks or until his concentration ends.</div>
<div class="footer">Familiar</div>
</div>

<div class="card familiar">
<div class="title">Imp: Help Action</div>
<div class="type">Imp Familiar</div>
<div class="stat">Time: 1 Action (Imp)</div>
<div class="description">Imp feints or distracts a target within 5 feet. Gives Warlock <b>Advantage</b> on their next attack against it. <i>(Does NOT break Invisibility).</i></div>
<div class="footer">Familiar</div>
</div>

</div>
\page

<div class="card-container">

<div class="card familiar">
<div class="title">Imp: Shapechange</div>
<div class="type">Imp Familiar</div>
<div class="stat">Time: 1 Action (Imp)</div>
<div class="description">Imp polymorphs into a <b>Raven</b> (50ft Fly), <b>Rat</b> (20ft Walk), or <b>Spider</b> (20ft Climb). He retains all stats but cannot attack.</div>
<div class="footer">Familiar</div>
</div>

</div>