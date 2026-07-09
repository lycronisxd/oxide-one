<h1>journaling for my laser cutter!</h1>
<hr>
<h2>defining the scope and needs for my project</h2>
<h3>entry 1 : june 8th (19:08 - 19:25)</h3>
i want begin my project by defining the scope of what i actually want my project to do, which is easier said than done! <br />
<br />

some of the things that i want out of my project are as follows ->
<br />

<ul>
<li>a working area the size of a small desk that i don't use in my room (will update the checklist with its measurements once i measure it)</li>
<li>an aluminium frame because it'll last a while and i can design an axis movement system around the frame (kind of like michael reeves' surgery robot)</li>
<li>a weak-ish diode laser (10-20w) because it'll mainly be used on thin enough plywood for projecting</li>
<li>stepper motors to control the axes precisely</li>
<li>custom esp32 driver board running grbl for cnc control</li>
<li>running off a 24v psu</li>
<li>low profile, but safe fume extraction</li>
</ul>
<br />
<b>journal time - 17 minutes</b>
<br />
<b>total time - 17 minutes</b>

<hr>
<h2>the frame!</h2>
<h3>entry 2 : june 9th (11:46 - 14:31)</h3>
after nearly 3 gruelling hours of modelling on onshape. ive come up with a design for an enclosure
<img width="785" height="778" alt="image" src="https://github.com/user-attachments/assets/4a55d868-6f30-403e-ac50-5f3413d07de7" />
<br />
i ended up measuring my desk to be around 480mm x 480mm of workspace, so the size of the enclosure reflects that perfectly. although i think i'll end up reducing the cutting bed to 400mm x 400mm cause its plenty for me and gives me enough space around the cutting bed.
<br />
<br />
the height is also huge, but it will end up being necessary because of the whole laser assembly, filtration (if i add it), fume extraction etc.
<br />
<br />
for the frame, im planning to use 2040 aluminium extrusion since it should be rigid enough for the laser cutter without being awfully heavy or delicate.
i also had to learn what a gusset was for this so it better be worth it! im planning to 3d print the gussets for structural stability, then thread m5x10mm screws through with t-nuts to hold the enclosure in place
<br />
<br />
i want to add maybe a softwood or plywood sides to engrave some decals on the sides then use t-nuts to hold them in place or use a laser-safe translucent acrylic and then paint or engrave some decals with a stencil, but that'll all come when i'm done with everything.
<br />
<br />
next, i think the right move is to design the x and y axis movement of the laser because i know that'll probably end up being the most tedious process in this entire project but it'll be fine :)
<br />
<br />
<b>journal time - 2 hours 45  minutes</b>
<br />
<b>total time - 3 hours 2 minutes</b>
<hr>
<h2>the movement mechanism</h2>
<h3>entry 3 : june 9th (15:00 - 17:46)</h3>
this might've been the worst 3 hours of my life as expected
<img width="759" height="786" alt="image" src="https://github.com/user-attachments/assets/d7448cca-8c85-48c1-90b4-7fbc92763d5c" />
<img width="1305" height="707" alt="image" src="https://github.com/user-attachments/assets/e5497fc3-9e5f-41db-a695-489d38ca3778" />
<br />
so i decided to use a new assembly for the movement mechanism because i thought it would be a good idea to seperate the mechanism from the main assembly then port it over (it was not.)
<br />
<br />
decided to use mgn12h linear rails for the movement mechanism and am planning to use 2 motors for the y axis movement and 1 motor for the x axis
<br />
<br />
also decided on a laser in the meantime to know height clearance, custom mounting bracket model etc. which is the 20W laser tree 4lds v2! i actually love that the 4lds v2 comes with the height adjustable bracket and all i needed to do was design an easily 3d printed part to attach it to the mgn12 carriage :)
<br />
<br />
figuring out how far up the rails would need to be was the next issue, because it always looked way too short, but alas i found a good looking spot with about 60mm of air clearance between the laser and cutting bed, but the gussets were in the way and would not let me mount another rail to the enclosure, so i had to model new gussets for the sides and FINALLY i could finish attaching this demon spawn of a mechanism!
<br /><br />

<b>journal time - 2 hours 46  minutes</b>
<br />
<b>total time - 5 hours 48 minutes</b>

<h3>entry 3.1 : june 9th (21:15 - 22:33)</h3>
so this is kinda an entry but kinda not but i spent a lot of time on this and im angry because my ASSEMBLY BROKE AND I HAD TO SPEND AN HOUR REBUILDING THE MOVEMENT MECHANISM
<br />
<br />
i hate onshape
<br />
<br />
<b>journal time - 1 hours 18  minutes</b>
<br />
<b>total time - 7 hours 6 minutes</b>
