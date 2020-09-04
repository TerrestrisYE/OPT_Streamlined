# OPT Engine Roles
The Hitchhiker's guide to use cases for OPT engines.
These engines primarily provide for four major principles of SSTO (spaceplane or not, but primarily spaceplane) propulsion systems:
* :one: The **SABRE-derived** approach where you accelerate on air-breathing with turbojet and ramjet engines up to Mach 5 and carry lots of Oxidizer for the rocket mode. Oxidizer mass is very significant and is a sizeable fraction of the limiting factor of rocketry. This is the only principle available in the stock game so the majority of players simply go this way or attempt crazy, barely passing alternatives like turboramjet + vacuum NTR.
* :two: **Use of scramjet** to vastly extend the air-breathing operation range (from Mach 5 up to 14) and reduce the amount of Oxidizer that needs to be carried for the rocket mode. Unfortunately, instead of dealing with Oxidizer mass, you have to deal with exponentially high levels of shock-heating due to staying at low altitudes, and the craft melting before it reaches Mach 9.
* :three: The **rocket-only** principle which is only practical with the involvement of aerospikes or ram-rockets, and is best demonstrated by X-33/Venture Star (and so, are targeted for vertical launch, horizontal landing craft).
* :four: Any breed of **air-breathing plasma engine**. Here, the atmosphere alone is the propellant and the medium for ignition is whatever applicable means to supply an enormous electrical current to energize the air being maniplulated within the engine. Unfortunately, no means exists yet to hold or move such a current on a practical sized craft, but a number of early prototypes or tech demos have been seen. Inspired by this, OPT introduces the "Warpjet" family of engines.

These engines also fall into some groups (by demand or by a characteristic) as denoted by these icons:
* :cancer: Air-breathing mode can change between LiquidFuel + IntakeAir and LFO + IntakeAtm. Can operate without loss in any atmosphere.
* :zap: Demands ElectricCharge.
* :muscle: Heavy lifter.
* :radioactive: Atomic engine.
* :alien: Late-game, hyper-efficient engine.

---

:small_blue_diamond: **HAE-02 Turboramjet**. Do with this what you will with the stock Whiplash. But this is much more advanced and fits Mk2 bodies. It works very well for efficient hypersonic airliners and small stratolaunchers. Its Isp remains at 4000s but it allows cruise speeds up to Mach 6.4, with its operating limit at Mach 7.5.

:small_blue_diamond: **J-60 Screamjet, J-61 Turboramjet**. :two: :muscle: These Mk2 engines are all-range, operating between Mach 0 and 14, endorsing the second principle. As is the norm for scramjets (passing Mach 6) their Isp falls sharply and they become gas guzzlers, but still remain notably efficient over typical rockets.

:small_blue_diamond: **J-60D Hybrid Screamjet**. :one: :muscle: :zap: This engine follows the SABRE principle and is both a jet engine and a hybrid plasma rocket. It's a great heavy-lift engine on its own but is best kept on spaceplanes and not used for vertical ships.

:small_blue_diamond: **J & Stail Linear Aerospike**. :three: :muscle: :muscle: :muscle: These endorse the third principle and have great efficiency and are super-heavy lift engines (3200kN thrust). 

:small_blue_diamond: **ARI-75**. :three: :zap: This 1.25m engine is of the type air-augmented rocket / "ram-rocket" + hybrid plasma. In vacuum, its hybrid plasma nature grants it higher Isp than any typical LFO engine. This engine can also exploit the atmosphere to gain thrust and efficiency so that it's far better to use it in atmospheres with or without Oxygen than to use most other LFO engines.

:small_blue_diamond: **ARI-73**. :three: :radioactive: This 1.25m engine is of the type air-augmented nuclear rocket / nuclear "ram-rocket". In vacuum its Isp is marginally better than typical nuclear rockets but it offers 3x the thrust of the NERVA without 3x the mass. This engine has no speed limit in atmosphere so it can continue to accelerate the craft without losing efficiency or thrust as long as it remains low enough in an atmosphere to exploit it well, meanwhile, combinations involving standard nuclear turbojets leave a lot to be desired when such jets weaken at Mach 2 in thick atmosphere or at any speed in thin atmosphere.

:small_blue_diamond: **J-92 Nebula Shcramjet**. :two: :muscle: :zap: The 2.5m jet engine that everyone knows. Before OPT Reconfig, it was just an alternative shape but same performance to the HAE-02. But since Reconfig, it's a super-advanced all-range jet engine. As a "hybrid plasma scramjet" it remains super-efficient unlike any other scramjet but at the cost of a large amount of EC/s. Change over from its normal turbojet mode at Mach 5. The shcramjet mode fails under Mach 4. With its super efficiency and no speed limit, the Nebula uniquely allows for SSTO spaceplanes to skip carrying Oxidizer entirely, and rely on nuke engines alone for orbital insertion.

:small_blue_diamond: **J-81 Nacelle**. :three: :zap: :zap: :alien: The oddly shaped super-advanced engine. It's borderline hyper-efficient but at the costs of: Its air-breathing mode works well near Kerbin sea level, only in Oxygen, and under Mach 3. If you can develop a flight profile within this precise condition, you can use a massive early boost to air-breathing ascent and then you can coast to Apoapsis on its super-high rocket mode Isp with less worry of its low thrust.

:small_blue_diamond: **Dark Drive**. :three: :muscle: :muscle: :muscle: :alien: The 3.75m black hole engine. Everyone knows it. Many fear and/or rage at it. It's OPT's ultimate engine, borderline interstellar class. Use it for motherships and megaships that want to be able to land anywhere. Build your ship right and you can SSTO on Eve and Tylo, and you can casually dive through gas giants. But be sure to have an OPT science lab and an Ore supply. The Dark Goo inside slowly boils away to keep your probe cores alive.

## VTOL engines suite

:small_blue_diamond: **Bubble**. :one: :cancer: :zap: :alien: The 2.5m spherical engine is also borderline interstellar. Hyper efficient and more appealing than the J-81. It is entirely a companion to the Dark Drive. Use it for SSTO shuttles that accompany your megaship. Its air-breathing mode can further split between using IntakeAir (Oxygen) and Oxidizer (when no Oxygen) so it's usable in any atmosphere.

:small_blue_diamond: **Helicarrier**. :one: :muscle: :cancer: :zap: The 3.75m heavy-lift disc engine. It is not hyper-efficient but is extremely versatile and is purposed for use by heavy and super-efficient craft that are both horizontal and vertical.

:small_blue_diamond: **LP-J 01 "Downswell"**. :cancer: :zap: Low-profile, highly versatile air-breathing engine. It is more of a vent than a true engine so it uniquely allows for its throttle response to be changed to match other air-breathing engines.

:small_blue_diamond: **LP-R 01 "Prominence"**. :three: Low-profile version of the ARI-75. It lacks the air-augmented mode.

:small_blue_diamond: **LP-R 02 "Irradiance"**. :three: :radioactive: Low-profile version of the ARI-73. It lacks the air-augmented mode.

:small_blue_diamond: **Sky Light**. :zap: A 3.1m ducted fan engine, tilt-engine, and is even stackable (but be sure to lock its gimbal then). Its top speed is Mach 1 but it is ultra-efficient, has great heat tolerance for an exposed fan, and allows for small OPT airplanes/spaceplanes to make the best of a small fuel supply while in atmosphere. It works well for boat and blimp main engines too.

:small_blue_diamond: **Slipstream**. :zap: Not an engine in the true sense. This is as the tail rotor for helicopters but in-game is a lift surface and powerful, omni-directional air-breathing RCS thruster. While engaged it will always sip on EC to maintain its internal pressurized air supply for thrust.

:small_blue_diamond: **Valkyrie**. :one: :muscle: :zap: The heavy lift cuboid tilt-engine. It is nearly what many players would ask for. It's powerful, efficient, tilt capable, and it can change between air-breathing and rocket mode. And its air-breathing mode can change between using IntakeAir and Oxidizer. But its air-breathing speed limit is roughly Mach 2.5.
* :small_blue_diamond: **Warpjet MARGE**. :muscle: :zap: :zap: This is like the Valkyrie but (as all Warpjets) feeds on EC and IntakeAtm and has no operating speed limit.

:small_blue_diamond: **Warpjet SAGE**. :four: :zap: :zap: This is like the J-61 Turboramjet but is optimized for use in thin atmosphere. It has a closed cycle but depends on your ship having an abundant supply of IntakeAtm. Some OPT parts allow you to tank IntakeAtm (the Mk2 nose and the drop tanks). Use it well and you can SSTO on literally just air (and lots of EC). This is the purpose of all Warpjets.

:small_blue_diamond: **Warpjet SURGE**. :four: :muscle: :muscle: :zap: :zap: :zap: This is like the J-60 Screamjet. It works exceptionally well in thin atmosphere and in extra thicc atmosphere. However, it has no closed cycle mode so it's useless in vacuum. It's heavy lift, unlike the SAGE, so use it as the main engines on a heavy spaceplane.

:small_blue_diamond: **Egg Dog**. :three: :muscle: :muscle: :muscle: :zap: This is a heavy lifter hybrid plasma LFO engine. Its power compares to the stock Vector/SSME but is still super-efficient (costing EC/s). It is available as both a radial tilt VTOL engine and a stack engine.

:small_blue_diamond: **Wrapper J, K, L (VTOL)**. :muscle: :zap: These engines clip onto and through the sides of the J, K and Humpback bodies for adjustable, form-fitting "inline" vertical engines.
* :small_blue_diamond: **Warpjet Wrapper J, K, L (VTOL)**. :muscle: :zap: :zap: These engines clip onto and through the sides of the J, K and Humpback bodies for adjustable, form-fitting "inline" vertical engines.
