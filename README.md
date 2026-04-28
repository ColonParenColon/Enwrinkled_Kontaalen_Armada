# Enwrinkled_Kontaalen_Armada
Mod for Annihilate The Spance, adds a new faction reimagining the Kontaal if they "locked in" and "efficiencized" (sic)  
  
Main goal was to make the ships a wee bit (read: a lot) more powerful without just doing a number boost while also changing their general use-cases to encourage different playstyles.    
  
Changes made:  
  
***********************  
## DRONES  
  Jipper:  
	-Gave it a weapon to boost its own targeting priority to help clog PD and increase missile survivability.  
	-Boosted armor and reduced power of main weapon (No longer suitable for anti-drone duties)  
		  
  Hemnok:  
     -Increased standoff range to have it sit out of range of most secondary PD weapons (PL Defenders, Burst Cannons)  
     -Can now be a sort of back-line drone building up, so long as the enemy doesn't have long-range PD.  
		   
  Kikie:  
     -Made more accessible via the Katalosteer hangar.  
     -Now serves as the main interceptor drone.  
		   
***********************  
## LIGHTS  
   Tolly:  
     -Couldn't think of anything, so just made its death explosion push away friendly units (good for breaking up swarms so AOE weapons are less useful)  
			  
   Kana:  
     -Made it hang back and use the Alkanador PD laser (acts more like an Auxilia now)  
		   
   Dauwn:  
     -Was going to give it a cloak, but then that became official.  
     -Was also going to give it a small healing death explosion, but it didn't work.  
     -Point Shadow Ray has reduced shred but now has a small amount of vulnerability.  
		   
   Fauss:  
     -Gave it the Reyden flak gun. Now serves as an early game swarm clearer alongside the Hakurr.  
		   
   Hakurr:  
     -Cloaks  
     -Has a self-impulse weapon that causes it to launch toward enemies (and through them most of the time)  
     -Harasses fleets, but loses pure DPS as it can't consistently fire on the same target.  
		   
***********************  
## MEDIUMS  
  Otorell:  
    -Given the Lantra's light Dekker which also fires faster given it is no longer a backline ship  
    -Less effective against lights, more effective against heavies.  
		  
  Reyden:  
    -Tried to make it a back-line sniper by abusing the minimumDistance variable, but couldn't get it to feel right.  
    -Still a WIP. Goal is killing mediums / lightly armored heavies while being unable (or less likely) to target nearby enemies  
      -Basically a backline unit that only kills other backline units  
			  
  Alkanador:  
    -Gave it the Kana's AoE beam as god intended.  
    -Much better at frontline PD support (needed given the crap this faction does now)  
		  
  Partell:  
    -The Wick torpedos now cloak  
    -As a mercy they uncloak 2.5 units from an enemy.   
		  
  Lantra:  
    -Given a long range point light cannon.  
    -Low heat output limits its anti-armour capabilities.  
		  
  Matessa:  
    -Knit beam has lower healing output, but higher shred and heat depletion.  
    -It also provides Aegis to nearby allies.  
		  
***********************  
## HEAVIES  
  Abrundonell:  
	-Hightrack Autoguns were replaced with Point Shadow Beams  
	-Gets close to enemy armor and quickly shreds it.  
	-Very weak to missiles and drones from lack of PD.  
		  
  Barvek:  
    -Dekker. Close range heat gun.  
		  
  Katalosteer:  
    -Given the Barvek's now unused weapons.  
    -Backline anti-swarm artillery (like the Gytfalcon sequel you always wanted).  
    -Drone bay now outputs 4 Kikies and 2 Hemnoks.  
		  
  Grytes:  
    -Fires a modified mini Rocket Howler.  
      -Needs to be tweaked to pop closer to enemy's face so it can be PD'd more reliably.  
      -Also needs minor tracking on the bombs so it becomes more likely to hit anything other than the center target.  
			  
  Valantar:  
    -Weapon given minor shred. Not enough to matter though.  
		  
  Wernos:  
    -The math of turning 6 beams into one with only 1/3rd the damage bugged me. Now each beam array has three lasers.  
		  
  Noledar:  
    -No changes.  
    -Launches new Jippers and Hemnoks to distract PD and get a few missile shots in.  
		  
***********************  
## CAPITALS  
  Ekudon:  
    -Main gun turned into an Untresnavokadeer to hit capitals harder  
    -Swader array retuned to hurt mediums  
    -Given 10 Magshock Cannons to deal with lights.  
    -Goal is to be an all-in-one fortress to push the frontline in most any situation  
		  
  Tradnios:  
    -Front missile battery tuned to have shred and heat (but still nowhere near first release Solkata batteries)  
      -Kept as front missiles because I personally liked the big mouth of bombs.  
			  
  Solgasonder:  
    -Dinky PL Defenders replaced with knit beams  
      -Offers more healing, but less shred and cooling than the Mattessa  
      -2-3 of these makes a fleet very hard to kill. Oops  
			  
  Yobegregor:  
    -Given a bit more shred, enough to make it deadlier to heavies.  
    -Will still need an Abrundonell or Tradnios to tear down capital armor, but those are frontline so who cares.  
			  
  Untresnafol:  
    -Ate a Soul Warden and now launches nukes. :3  
		  
***********************  
  
## TO-DO
-Fix Ekudon Magshock Cannons visuals (bring back the cone!)  
-Give Tollys something real.  
-Either get the reyden to focus on backline (and do less overall damage) or find a different niche (maybe missiles)  
-Switch Hakurr gun with a close range ant-armour weapon (Fauss covers the AoE field, so now lights are missing an anti-armour)  
-Weaken Dauwns (Somehow they eat armour faster now despite reducing the rate. Probably some weird interaction with vulnerability)  
-Rework Jippers maybe. The PD clog is cool, but Kontaal just doesn't have the missiles or drone output for it to feel useful.  
    --Maybe a capture drone? Some sort of 0 range ECM beam type thing. Just need to figure out how that actually works.  
-Maybe add turrets?  
-Jeren update. If you mine the rocks to make ships, it stands to reason you can mine the ships too.  
-Do the same thing to the Vaalkorei, I'm thinking Harriers with plasma guns, Super-ECM Kingfishers, PD-able Magpie bombs, and an unchanged Corvus.  
-Add actual database entries.  
-Try to learn modeling to make them more visually distinct (or, maybe just to turn it into its own faction, but that sounds like a lot of work for a joke).  
