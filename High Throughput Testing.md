# 96 Well Protein Expressions and Prep

### Day 1: OVERNIGHTS

1. Pick a single colony from plate and inoculate 0.5ml of room temp LB/Kan (NOT TB) in STERILE deep well plate (Round bottom 2 mL Deep well plate; e.g. Cat No # 278743)
    * Generally we have been picking and growing up 4 individual colonies/mutation, so we have quadruplicate data on each mutation. Plate assays have a lot of variability and each colony is not guaranteed to have the mutation, so quadruplicate assaying helps significantly.
2. Cover with breathable seal
3. Shake at 37deg 16-24hrs in warm room plate shaker (Heidolph Brinkmann Titramax 1000 @ 1200rpm) to ensure they are all fully grown

### Day 2: EXPRESSION

1. Vortex the overnights at 1500rpm for 30sec to ensure to mix any cells that have settled to the bottom into the media.
    * Make glycerol stocks if first time doing this set: 110uL cells + 110uL 20% glycerol. Store in -80.
2. Inoculate a fresh STERILE plate of 1.0ml of TB/Kan in a deep well plate with 20uL of overnight cultures
3. Cover with breathable seal
4. Grow at 37deg as above for 3 hours (target OD approx 0.3-0.8)
5. Add IPTG to 0.5mM (50uL of 10mM IPTG) using the repeater
6. Transfer plate to 18deg shaker (Heidolph Brinkmann Titramax+Incubator 1000 @ 1200rpm in cold room, preheat to 18) and shake at 1200rpm for 24-30hrs.

### Day 3: STORE

1. Spin down cells at 4000rpm for 20min
2. Pour off supernatant
3. Store cells in -20 until ready for purification

### Day 3/4: PURIFICATION (~3hrs minimum)

1. Lyse cells via BugBuster (~30min) or Freeze/Thaw Cycles (~3hours)
#### FREEZE/THAW
1. With repeater add 250uL of appropriate lysis buffer and re-suspend with mixmate (5min at 1500rpm) OR with Pipettman
2. Place plates in -80 for 15 minutes to freeze
3. Pull plates out and let thaw for 35 minutes. Shake plate at 1500rpm while thawing.
4. If doing multiple plates, then rotate plates letting each plate shake for 10minutes.
5. Make sure cells have thawed, then place back in -80 and repeat so cells are frozen a total of 3 times! If cells have not thawed let mix at room temp for longer!
#### BUGBUSTER
1. With repeater add 250uL of appropriate lysis buffer and re-suspend with mixmate (2min at 1000rpm) OR with Pipettman
2. Continue to incubate at room temp for 20min, mixing with plate mixer (1000rpm).
    * If you are worried about protein stability then incubate in the cold room for one hour using plate shaker to continuously mix (1200rpm).
#### After Lysis
2. Pellet Insoluble Matter &amp; Clarify Supernatant (~1 hour)
3. Spin the lysis for 60min at 4000rpm (spin longer if supernatant is not clear enough. But one hour should really be sufficient!)
4. If the supernatant still looks cloudy you need to clarify first, but if clear this step can be skipped.
5. To clarify: Carefully transfer 200uL of supernatant to a Millipore Multiscreen-HTS DV 0.65um hydrophil low protein binding filter plate (Part #: MSDVN6550) with a Costar V-bottom plate (fisher part #: 07-200- 695) taped below as a collection plate.
    * Try to avoid picking up pellet, but a small amount is normal to pick up in this step.
6. Spin 2000g for 20minutes (or until most of the supernatant has gone through)

### Purification (~1 hrs)
1. Bind Clarified Supernatant (~40min)
2. Tape a Costar V-bottom plate underneath a of a Millipore Multiscreen-HTS DV 1.2um hydrophil low protein binding filter plate (Part #: MSBVN1250).
3. Aliquot 100uL of 50% NiNTA slurry to each well
    * BE FAST, YOU WANT TO MAKE SURE THE BEADS DON’T SETTLE TOO MUCH WHILE YOU ARE ALIQUOUTING. If using a pipette use a P1000 since the resin tends to clog the smaller 200uL tips!
4. Add 200uL of wash buffer
5. Spin 1500rpm for 1min
6. Use 200uL multichannel to add clarified lysate to each well (~200uL/well)
    * Be careful to NOT TOUCH the cell pellet. I find one of the best ways to do this is to use a small piece of cardboard and tape it to the pipette such that it can’t go low enough to touch the cell pellet.
7. Mix in plate mixer for 30min (700rpm or just fast enough so liquid is not coming out of the well! Start slow and work your way up!)
8. Spin 1500rpm for 5min
9. Discard flow through
10. Wash off unbound protein (~20min)
11. With repeater apply 200uL of wash buffer to each well.
12. Incubate for 1min while mixing in plate mixer (same speed as determined before)
13. Spin 1500rpm for 5min
14. Discard flow through and repeat 2 more times (wash with ~12 c.v. or 600uL of wash buffer in total)
15. Elute Protein (~5min)
16. Switch out collection plate to a new V-bottom plate. Tape on so the collection plate does not slip!
17. With repeater add 100uL of elution buffer (500mM Imidizole) to each well.
18. Mix in plate mixer (same speed as determined before) for 10min.
19. Spin 5min 1500rpm.
    * You should now have your protein!
20. We have generally been getting approx. 0.1-10.0mg/ml of protein off the column for the NiNTA prep (depending on the protein) and about 5-fold less in the straight cell lysis prep.

### Clean NiNTA for Re-Use
    * The NiNTA Resin is the most expensive part of this assay, so if you are doing MANY PLATES it is worth trying to save!
22. Pipette 200uL of water into each well and transfer to a multichannel tray
23. Use 1mL Multichannel, no need to change tips between wells.
24. Pour tray in 50mL falcon tube
25. The Following wash procedure is adapted from the QIAExpressionist for regenerating NiNTA
26. Spin for 5min at 800rpm and then carefully decant supernatant
27. Fill with Water, spin 5min 800rpm and decant
28. Fill with 2%-SDS, spin 5min 800rpm and decant
29. Fill with Water, spin 5min 800rpm and decant
30. Fill with 100mM EDTA pH 8, spin 5min 800rpm and decant
31. Fill with Water, spin 5min 800rpm and decant
32. Fill with 100mM NiSO4, spin 5min 800rpm and decant
33. Fill with Water, spin 5min 800rpm and decant
34. Add 25% Ethanol until beads are in ~50% slurry, STORE AT 4degC

-- -- -- -- -- -- -- -- -- -- -- -- -- -- -- -Buffer Examples; alter to fit your protein’s ideal buffer -- -- -- -- -- -- -- -- -- -
Wash Buffer:
1x PBS
30mM Imidizole
BUGBUSTER Lysis Buffer:
1x PBS
1mM PMSF
1.5x Bug Buster
2mg/ml lysozyme (small scoop)
0.2mg/ml DNAse (small scoop)
FREEZE/THAW Lysis Buffer:
1x PBS
1mM PMSF
2mg/ml lysozyme (small scoop)
0.2mg/ml DNAse (small scoop)
Elution Buffer:
1x PBS
250mM Imidizole
