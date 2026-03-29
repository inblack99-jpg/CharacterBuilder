<style>
  .phb { background : white; }
  .card {
    border: 5px solid #58180D;
    background: #EEE5CE;
    padding: 8px;
    width: 220px;
    height: 310px;
    display: inline-block;
    vertical-align: top;
    margin: 3px;
    border-radius: 12px;
    box-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    position: relative;
    overflow: hidden;
  }
  .card h4 { color: #58180D; margin-top: 0; margin-bottom: 5px; border-bottom: 2px solid #58180D; font-size: 1.1em; }
  .card .type { font-style: italic; font-size: 0.7em; margin-bottom: 5px; }
  .card .stat { font-weight: bold; font-size: 0.8em; margin: 1px 0; }
  .card .description { font-size: 0.8em; margin-top: 8px; line-height: 1.1em; }
  .card .footer { position: absolute; bottom: 8px; right: 8px; font-weight: bold; font-size: 0.6em; text-transform: uppercase; }
  .action { border-color: #228B22 !important; } /* Green */
  .bonus { border-color: #DAA520 !important; }  /* Gold */
  .reaction { border-color: #B22222 !important; } /* Red */
  .familiar { border-color: #800080 !important; } /* Purple */
</style>

<div class='card action'>
#### Eldritch Blast
<div class='type'>Cantrip (Evocation)</div>
<div class='stat'>Time: 1 Action</div>
<div class='stat'>Range: 120 ft</div>
<div class='stat'>Attack: 1d20 + 6</div>
<div class='stat'>Damage: 1d10 + 4 Force</div>
<div class='description'>A beam of crackling energy streaks toward a creature. If target is Hexed, add **1d6 Necrotic**.</div>
<div class='footer'>Action</div>
</div>

<div class='card action'>
#### Burning Hands
<div class='type'>1st Level (Evocation)</div>
<div class='stat'>Time: 1 Action</div>
<div class='stat'>Range: 15ft Cone</div>
<div class='stat'>Save: DC 14 Dex</div>
<div class='stat'>Damage: 3d6 Fire</div>
<div class='description'>Fire shoots from your fingertips. Half damage on successful save. Ignites flammable objects.</div>
<div class='footer'>Action</div>
</div>

<div class='card action'>
#### Command
<div class='type'>1st Level (Enchantment)</div>
<div class='stat'>Time: 1 Action</div>
<div class='stat'>Range: 60 ft</div>
<div class='stat'>Save: DC 14 Wis</div>
<div class='description'>Speak a one-word command (e.g., "Halt," "Drop," "Flee"). Target must follow it on its next turn.</div>
<div class='footer'>Action</div>
</div>

<div class='card action'>
#### Armor of Agathys
<div class='type'>1st Level (Abjuration)</div>
<div class='stat'>Time: 1 Action</div>
<div class='stat'>Range: Self</div>
<div class='stat'>Duration: 1 Hour</div>
<div class='description'>Gain **5 Temporary HP**. While you have these HP, any creature that hits you with a melee attack takes **5 Cold Damage**.</div>
<div class='footer'>Action</div>
</div>

<div class='card action'>
#### Friends
<div class='type'>Cantrip (Enchantment)</div>
<div class='stat'>Time: 1 Action</div>
<div class='stat'>Range: 10 ft</div>
<div class='stat'>Duration: 1 Minute</div>
<div class='description'>Gain **Advantage** on all Charisma checks directed at one non-hostile creature. *(2024 Rule: No hostility when spell ends).*</div>
<div class='footer'>Action</div>
</div>

<div class='card bonus'>
#### Hex
<div class='type'>1st Level (Enchantment)</div>
<div class='stat'>Time: 1 Bonus Action</div>
<div class='stat'>Range: 90 ft</div>
<div class='stat'>Duration: 1 Hour (Conc)</div>
<div class='description'>Target takes **+1d6 Necrotic** when you hit it. Disadvantage on checks for one stat. If target dies, move Hex on a later turn.</div>
<div class='footer'>Bonus Action</div>
</div>


<div class='card bonus'>
#### Misty Step
<div class='type'>2nd Level (Conjuration)</div>
<div class='stat'>Time: 1 Bonus Action</div>
<div class='stat'>Range: Self</div>
<div class='description'>Briefly surrounded by silvery mist, you teleport up to 30 feet to an unoccupied space that you can see.</div>
<div class='footer'>Bonus Action</div>
</div>

<div class='card bonus'>
#### Command Xil
<div class='type'>Pact of the Chain</div>
<div class='stat'>Time: 1 Bonus Action</div>
<div class='stat'>Requirement: 100 ft</div>
<div class='description'>You command Xil to take the **Attack** action on its turn. Xil stings with its tail for 1d8+4 damage.</div>
<div class='footer'>Bonus Action</div>
</div>

<div class='card reaction'>
#### Hellish Rebuke
<div class='type'>1st Level (Evocation)</div>
<div class='stat'>Trigger: Taking Damage</div>
<div class='stat'>Range: 60 ft</div>
<div class='stat'>Save: DC 14 Dex</div>
<div class='stat'>Damage: 2d10 Fire</div>
<div class='description'>You blast the creature that hit you with hellfire. Half damage on successful save.</div>
<div class='footer'>Reaction</div>
</div>

<div class='card familiar'>
#### Xil: Invisibility
<div class='type'>Imp Familiar</div>
<div class='stat'>Time: 1 Action (Xil)</div>
<div class='description'>Xil magically turns Invisible until he attacks or until his concentration ends.</div>
<div class='footer'>Familiar</div>
</div>

<div class='card familiar'>
#### Xil: The Help Action
<div class='type'>Imp Familiar</div>
<div class='stat'>Time: 1 Action (Xil)</div>
<div class='description'>Xil feints or distracts a target within 5 feet. Gives Brenya **Advantage** on her next attack against it. *(Does NOT break Invisibility).*</div>
<div class='footer'>Familiar</div>
</div>

<div class='card familiar'>
#### Xil: Shapechanger
<div class='type'>Imp Familiar</div>
<div class='stat'>Time: 1 Action (Xil)</div>
<div class='description'>Xil polymorphs into a **Raven** (50ft Fly), **Rat** (20ft Walk), or **Spider** (20ft Climb). He retains all stats but cannot attack.</div>
<div class='footer'>Familiar</div>
</div>

<div class='card familiar'>
#### Xil: Sting (Attack)
<div class='type'>Imp Familiar</div>
<div class='stat'>Attack: 1d20 + 6</div>
<div class='stat'>Damage: 1d4 + 4 Piercing</div>
<div class='description'>Target makes a **DC 14 Con Save**. On failure, it takes **3d6 Poison** damage (half on success).</div>
<div class='footer'>Familiar</div>
</div>