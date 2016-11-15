ÚVOD...............................................................6

1 Iluzní zrcadlo.......................................................................7

2 VYUŽITÉ TECHNOLOGIE.....................................................................................8

2.1 Arduino..............................................................................................................8

2.2 Schema funkce iluze......................................................................................................9

2.3 POUŽITÝ SOFTWARE...............................................................................................9

3 ZPŮSOBY ŘEŠENÍ A POUŽITÉ POSTUPY.......................................................10

3.1 SEZNAM NUTNÝCH SOUČÁSTEK ...........................................................................11

3.2 SCHÉMATICKÉ ZAPOJENÍ ......................................................................................12

3.3 PRINCIPY Funkčnosti ........................................................................13

4 VÝSLEDKY ŘEŠENÍ..............................................................................................14

4.1 UKÁZKA KÓDU.....................................................................................................15

4.2 Sestavení zrcadla...........................................................................................16

4.3 Využití funkcí ovladače IR přepojení ..................................................17

ZÁVĚR................................................................................................................................18

SEZNAM POUŽITÝCH INFORMAČNÍCH ZDROJŮ ................................................19


1)An infinity mirror is a magical illusion mirror that gives a perception of great depth to a very thin mirror array. 
The perceived depth can be very many feet even though the mirror may not be actually deeper than a couple of inches.
The infinity mirror actually contains two mirrors with different  transmissivity and reflectivity. For all practical intents and purposes, mirrors that we deal with in everyday life are 100% reflective (technically a tiny amount of light will also be absorbed, but we can ignore that for now). That's the regular mirror at the "back" of the infinity mirror (on the left in the diagram above). The tinted window film, however (on the right in the diagram above), only reflects about half of the light that hits it*. This means that, when you sandwich an LED between the two mirrors, some of the light escapes through the front mirror and into your eye. The rest is bounced back off the rear mirror, then into the front mirror again, and this process continues off to infinity - thus the name. But, since a little bit of light escapes each time, each successive illusionary LED that you see will look a little bit dimmer, until they gradually disappear - you can't actually see infinitely many LEDs.

Note that this does not work because the window tint "only lets light through in one direction", which is a common misconception. In order for the illusion to work properly, the side of the front mirror the observer is on (the outside world) must be much darker than the side with the LEDs (inside the infinity mirror). This is the same effect that you see in crime dramas/movies where someone is held in an interrogation room that has a mirror on the wall, but there are people on the other side of that mirror observing as though it's just a window. That only works if the interrogation room is well-lit and the observation room is dark.

__Nazorny obrazek__
![alt tag](https://cdn.instructables.com/FQ0/TOIZ/HKVLJXM2/FQ0TOIZHKVLJXM2.MEDIUM.jpg?width=614)
![alt tag](https://cdn.instructables.com/FR4/L0IN/HKVL7G8A/FR4L0INHKVL7G8A.MEDIUM.jpg?width=614)


__SCHEMA zapojeni__

![alt tag](http://www.decoraport.ca/media/wysiwyg/Blog/p6.jpg)



__Schema pro prijimač_
![alt tag](https://cdn.sparkfun.com/assets/f/1/7/6/7/524b4959757b7f456d8b4568.png)
