---
layout: default
title:  "Interesting Combat"
---

# Creating an interesting combat system.

There’s nothing worse than fake options. Gamers, myself included, have this tendency to not be happy until they turn any given system into a “solved game.” It doesn’t take long to find dozens of opinions on what’s overpowered, what’s useless, and what are optimal strategies, and these all have the same problem: they reduce the decision space. 

One of the greatest strengths of Dark Souls is that while some builds are stronger than others, a quick visit to any message board will see the question “what’s the best weapon” with “it depends.” 

This isn’t the same mindset as Advanced Dungeons & Dragons, where a first level fighter can fight all day, while a first level wizard had one spell and a long, sad walk home. By level 20, the fighter was a combat master who could still fight all day, but the Wizard was able to literally reshape reality with a wish. 

GDC had a wonderful talk about this and Pillars of Eternity. https://youtu.be/fvyrEhAMUPo I will not rehash their well-presented findings. But I will use the Harebrained Schemes Battltech game as an interesting point of reference. In their tweaking of tabletop values, they made a mid-range weapon a one shot kill on a head-hit. It went from dealing 83% of maximum damage to exactly 100%. As part of their backers, I did a risk assessment on the forums to see how it was versus how the tabletop rules were. It was fun but didn’t tell me anything new: people felt it was too frequent. HBS fixed the damage issue by adding a single point of extra structure in the head. But it still “felt” too often for some people, despite it being less often than the tabletop. 

People are bad at probability, and more visceral means it feels more frequent. XCom had a solution, fudging the numbers, but I’ve said “Thomas Theorem” (What is believed to be true is true in its consequence) more than I’ve said “Good Morning” in the last ten years and if I cover it again, it won’t be today.

And after all of that, I finally begin my point. I don’t know game system design. I know risk management and combat vehicle design. It’s shockingly applicable.

As a shorthand, I will be using “p” to represent probability. pHit is probability of hit, pKill is probability of kill, etc. They all contain multiple sub-factors, where a tank’s pHit requires accurate rangefinding, the ability to accurately lay in the gun, consistency of charge and projectile, etc. Much of this can be abstracted in a game, but the concepts are surprisingly helpful. AD&D used THAC0 to determine the probability to hit, and pKill was entirely based on hit dice vs damage done by the weapon. In Warhammer this is explicit in weapon skill and S/T ratios determining the probability of a wound.  

The importance to system design is not how these probabilities work, but how they synergize. Back to tanks. The M1 Abrams enjoys a tremendous pHit and pKill advantage over the Soviet tanks of the era. Similarly, pSurvive is also very high. It seems a superior tank, but would it win a war? The Soviet doctrine was to focus on pAvailibility. The goal was to have lighter and cheaper tanks and out-number the NATO tanks, and using an autoloader to both field more guns per person, but also increasing rounds per minute.

Regardless of the effectiveness of these tactics, the concept carries over into game balance. Two weapons, one pHit 1 and pKill 0.5 and another of pHit of 0.5 and a pKill of 1 are functionally identical, as pHit*pKill are both 0.5. It’s a simple example, but it demonstrates that each individual component adds to a single aggregate stat. Damage per Second (DPS) is a good example of this, but it is not a pure balancing mechanism. pAvailability also must be considered. Like a spell charge in AD&D or an MP cost in Final Fantasy, the availability is reduced not in a single round, but across an entire dungeon.  It goes back to the staying power of a fighter, but the burst damage of a magic user.

There’s also elemental weaknesses, buffs, debuffs, etc. but these all work into the concept of each component building upon the others. By enumerating the probabilities, we now have a way to balance our very, very boring game.

Why is it boring? Everything is the same. It’s balanced. Why pick rock over paper when neither beats the other? 

The player needs to find ways to create advantage. This is usually the role of elemental weaknesses, but other abilities can factor in. Take Final Fantasy IV (II US) for example. Cecil Harvey, in his paladin class, has a “cover” ability. This protects low HP team mates from physical attacks, increasing their survivability and their availability. 

Shin Megami Tensei is an exceptional example of many systems, but their elemental weakness system not only deals more damage, but depending on the game, allows for extra attacks or denies the enemy their turn. In addition, in some iterations knocking them all down will allow a special attack that bypasses special defenses. All of this costs SP, the limiting resource of a run. Ways of restoring SP, besides resting a day, are slim. Due to the Persona series’ story-driven gameplay, sometimes the day isn’t something that can be sacrificed. 

This encourages new strategies and improved efficiency. Characters are customized for certain specialties and built to interface best with their teammates. 

Conversely, FFVI (III US) has the Mage’s Tower, where only magic is available, along with a similar have in the FFIV where metal weapons and armor weren’t allowed. 

This has led to thoughts about Trenchmouth. It’s easy to find thematic weapons and systems; poison gas and gas masks are very widely known. There are knock-on effects than can be applied, such as reduced accuracy due to poor cheek weld and limited visibility, but what does that do to the game? Is it risk/reward or is it a simple optimization problem?

pHit, pKill, pAvailable, pSurvive. Those are my baselines. But how do I add something new, some agency? Some situational way to turn player skill and involvement into gameplay advantage. For that I don’t have an answer yet. 
