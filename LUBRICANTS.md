# Lubricants

- [Lubricants](#lubricants)
  - [A quick reference](#a-quick-reference)
    - [Compatability](#compatability)
    - [Amounts recommended](#amounts-recommended)
  - [Housing And Stem For Switch And Stabilizer](#housing-and-stem-for-switch-and-stabilizer)
  - [Switch Spring](#switch-spring)
  - [Stabilizer Wire Lubricant](#stabilizer-wire-lubricant)

Lubricant recommendations are a soft science leaning towards parroting old wives’ tales than  hard reproducibility. Here, I parrot old wives tales, but try to provide some justification for them.

## A quick reference

### Compatability

|                 | Krytox 105-107 | 3203 | 3204 | 205g0         | XHT BDZ | Dielectric Grease | China Grease  | Superlube<sup>5</sup> |
| --------------- | -------------- | ---- | ---- | ------------- | ------- | ----------------- | ------------- | --------------------- |
| Spring          | ✓              | ✓    | ✓    | ✓             | X       | X                 | !<sup>4</sup> | 51004                 |
| Housing         | ✓<sup>1</sup>  | ✓    | ✓    | ✓             | X       | X                 | !<sup>4</sup> | 51004                 |
| Stem            | ✓<sup>1</sup>  | ✓    | ✓    | ✓<sup>2</sup> | X       | X                 | !<sup>4</sup> | 51004                 |
| Stabilizer Wire | X              | X    | X    | ✓<sup>3</sup> | ✓       | ✓                 | ✓<sup>4</sup> | NLGI G0-G2            |

<sup>1</sup>: PTFE oils do not provide the same smoothing to housings as greases do, but are still good for when users want to be more conservative/less drastic with their lubrication.  
<sup>2</sup>: Grease at this viscosity is known to dull/smoothen/reduce the intensity of the bump on tactile stems. Avoid unless you intend on reducing the bump.  
<sup>3</sup>: It can be argued that 205g0 is too thin for stabilizer wires, and will migrate soon with continuous usage. Still, this is a preference thing.  
<sup>4</sup>: Products marketed as "GPL 105/205g0" without being manufactured by Chemours/Dupont/Miller Stephenson are likely manufactured with less reputable grease formulations. These tend to separate (between grease and oil) faster than genuine Krytox/Tribosys products without good binders.  This is generally what you get if you've refused to buy lube off of anywhere but Amazon, and didn't end up buying 205g2. If you know what you're getting into, and can accept these products for what they are, more power to you.  
<sup>5</sup>: 51004 and 51030 are known good oils. For stabilizer wire, some silicone grease PTFE that's NLGI Grade 0 to Grade 2 (such as 92003) should be great.

### Amounts recommended

Folk knowledge suggests that 1-2 drops of GPL 105-107 (or equivalent PTFE lube) per 10 springs will be sufficient for bag lubing.

For grease, here are conservative estimates of how far some volume of lube will get you -

| Volume | Product mass (approx.) | Switch coverage |
| ------ | ---------------------- | --------------- |
| 3 mL   | ~5.7g                  | ~240            |
| 5 mL   | ~9.5g                  | ~400            |
| 10 mL  | ~19g                   | ~800            |
| 20 mL  | ~38g                   | ~1600           |
| 40 mL  | ~76g                   | ~3200           |

## Housing And Stem For Switch And Stabilizer

We recommend greases/oils that contain Teflon (PTFE/polytetrafluoroethylene) content for high-quality lubrication that is not not prone to separating quickly when left at rest.

- Recommended
  - Industrial greases developed by Miller Stephenson/Dupont/Chemours
    - Tribosys 3203 is a stand-in for 203g0, 3204 is a stand-in for 204g0, and Krytox GPL 205g0 are the commonly recommended greases to lightly paint your switch friction points with.
  - Oils from the same manufacturer
    - Prior to using grease to lube Ergo Clears to ensure that they didn’t have return issues, oils were a popular option to reduce friction in a switch. Krytox 105 (thinner) to 107 (a bit more viscous) will fill that need while minimizing the risk that you over-lube.
  - Superlube
    - Per xalmart, 51004's a good Superlube oil for these applications.
  - Not Recommended
    - AliExpress or Amazon mystery grease
      - If you’re buying lube off Taobao or AliExpress, the odds that its genuine Krytox from Miller Stephenson/Chemours/Dupont are infinitesimal. Notice how there’s no mention of Krytox, or if it is, it's pixelated out in the product image for some reason? You’re getting a product that is similar in consistency to what will work good as a switch grease, but lacks the proper chemical binders to prevent the oils from separating from the grease as quickly. There’s a reason we recommend vendors on MechMap: we trust them to sell products with the proper formulation that prevents their components from separating. We are not interested in scooping finders fees when you end up buying some Miller Stephenson product - we do this to ensure you don’t have to deal with a substandard product when you don’t know what substandard means yet.
    - Krytox GPL 205g2
      - If you’re here, maybe you were stubborn and refused to shop anywhere outside of Amazon if you’re asking about this. Maybe you have a gift card, maybe you’re using your parents credit card and they don’t trust it to be used on someone who named their shop after a bad pun on some keyboard thing. Grade 0 is thick enough for switches. Grade 1 is too thick most of the time, and Grade 2 is way too thick to be used without being thinned, and if anyone says that you do it because they’ve used it before, they’re just using you as a surface to stroke their own ego. Don’t get this, just get some Grade 0 lube.
    - Petroleum-based lubricants (WD40, vaseline, etc.)
      - Petroleum based lubricants melt plastics slowly. You would be better served leaving them stock than letting them melt over time.
    - Most spray lube (WD40, Superlube 31110)
      - Just run !spraylubing in MechKeys.
      - I say “most” due to the possibility of Tribosys KSL becoming available in the future, which has been formulated to not gunk up the connection of the contact leaves.
  - Hesitant Recommendation
    - Glorious G-Lube
      - Less than ideal, but it may be your only option. At least you know what you're getting into.
      - [SDS](https://cdn.discordapp.com/attachments/481804810497163264/768374046505041950/G-Lube_MSDS.pdf) for those interested
      - No PTFE content confirmed. A great description is provided by u/marks_ [here](https://www.reddit.com/r/MechanicalKeyboards/comments/jfbzqx/a_chemical_breakdown_of_glorious_lube_glube/)
    - Whatever grease you found on AliExpress or Amazon
      - The difference between SW92SA and Mystery Manufacturer “GPL 205g0” is that I already know that SW92SA is jank and going to separate, while if I buy GPL 205g0, I run the risk of deluding myself into believing that I have the hookup while everyone buying genuine Krytox from a traditional vendor is getting scammed. If you know you’re getting a grease that’s going to separate, then more power to you.
  
## Switch Spring

The purpose of lubing a switch spring is to provide goop that dampens the vibration a spring may experience during a strong upstroke movement that leads to what you may recognize as “spring ping”.

- Recommended
  - Traditional industrial greases like GPL 205g0, 3204/204g0, 3203/203g0 can be painted on the spring, or donut dipped.
  - Thinner oils like Krytox GPL 105, 106, 107 are fine for bag lubing.
  - Gazzew’s Blend #7 also works great for donut dipping. If you buy parts from him, he might throw this in if you spend enough. It’s real thick stuff, so its best for springs really.
  - Rainkeebs recommended gun oil. I trust rain.
  - Superlube oil like 51004
- Not Recommended
  - Dielectric grease
  - Petroleum-based lubricants
    - Your plastics will melt. I explained this earlier.

## Stabilizer Wire Lubricant

You no longer require PTFE content for applications to the wire to prevent wire ticking. Dielectric grease, silicone grease, lithium grease, all those will get the job done as well.

- Recommended
  - GPL 205g0 (Does not have to be Krytox)
    - Yeah, mystery grease will work here, just let the oil separate first so it doesn’t turn into a mess on your PCB later.
    - As thick as this is, you can (and probably should) go thicker on the stabilizer wire, which needs a more viscous material to prevent wire tick.
  - Gazzew Blend #7 (recommend for donut dipping springs and and stabilizer wires. Don’t ask if you should get this, it’s not a must-have, just use some other lube)
  - XHT-BDZ
    - A relatively new product, and prices will vary harder.. This is as thick as toothpaste, maybe thicker than Blend #7; the spec sheet says it's about Grade 1.5. Apply this conservatively, as applying a liberal amount may lead your stabilized keys to feel slightly sluggish on press. When used properly, this is pretty good.
  - Dielectric grease
    - You don’t need a specific brand. You do not need a specific brand. Permatex is pretty popular in North America, but your region may vary. It doesn’t need to be very specific because you just need some goop that’s thick enough to stop the wire from rattling all over the place.
  - Superlube
    - NLGI Grade 0 to Grade 2 will get the job done.
- Not recommended
  - Grease thinner than 205g0
    - This grease will migrate (read: be pushed around by the movement of the wire) around until there is little left to dampen the wire tick.
  - PTFE oils like GPL 105-107
    - I shouldn’t have to put this here, but if a history of help channel activity has taught me anything, some people need to be reminded that making a stabilizer wire oily will not stop it from slapping against the interior of a stabilizer stem.
  - Petroleum based lubricants
