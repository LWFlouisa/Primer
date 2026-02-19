# Primer
This is not a roguelike, this is a cognitive architectural simulation that recreate post-conflict zones in my science fiction and fantasy novels. You type out full natural language prompts to instruct the cognitive agent, the MC, to interact with the simulation. Some concepts overlap with roguelike such as procedural dungeon creation.

Agents process your goals through NLP, selecting responces probabilistically derived from your previous input, learning which responces build trust between you and the agent using dynamic reward allocation. Currently command line, but the GUI should show the agents goal interpretation ( whether it understood what you asked ) and its chosen responce.

## Lore Context
This is an alternative history simulation of the evolution of new ethnic group over the centuries.

The cognitive architecture could be thought of as that world mold spawning agent to agent collaboration.

The inspiration came from imagining what a cognitive architecture would be like if border towns after an extensive ethno civil war needed an empathic machine to rebuild safety from the ashes.

The fantasy language this world speaks is a creole that blends Japanese, Francais, Alsatian German, and elements of other languages in the US.

This is reflected in the GUI that in graphical form reads top to bottom and right to left except when borrowing French and German words in groups in the US.

## Presentation
~~~
~~~~#~~~~~~~~~~~~~~~~~#~~~~
~~~#.#~~~~~~~#~~~~~~~#.#~~~
~~#...#~~~~~#.#~~~~~#...#~~
~~#...#~~~~#...#~~~~~~~~~~~
~~~#.#~~~~~#...#~~~~~~~~~~~
~~~~#~~~~~~~#.#~~~~~~~~~~~~
~~~~~~~~~~~~~#~~~~~~~~~~~~~
~~~~~~~~~~~~~#~~~~~~~~~~~~~
~~~~~~~~~~~~#.#~~~~~~~#~~~~ 
~~~~~~~~~~~#...#~~~~~#.#~~~
~~~~~~~~~~~#...#~~~~#...#~~
~~#...#~~~~~#.#~~~~~#...#~~
~~~#.#~~~~~~~#~~~~~~~#.#~~~
~~~~#~~~~~~~~~~~~~~~~~#~~~~
~~~~~~~~~~~~~#~~~~~~~~~~~~~
~~~~#~~~~~~~#.#~~~~~~~#~~~~ 
~~~#.#~~~~~#...#~~~~~#.#~~~
~~#...#~~~~#...#~~~~#...#~~
~~#...#~~~~~#.#~~~~~#...#~~
~~~#.#~~~~~~~#~~~~~~~#.#~~~
~~~~#~~~~~~~~~~~~~~~~~#~~~~
The present cold status: The room becomes silent, except for the low hum of gears.
Distance from Medusahoseki: 0 over this memory was from a prior 12 year period
The present heat status: Surface layer of sand is starting to turn to glass
Distance from Nemedusahoseki ( Salamander Riding Goat ): 33 over this memory was from a prior 9 year period
~~~

### Help Needed
* Render that ASCII map with actual graphics/colors (maybe the directional text overlaid)
* Display the environmental states in a panel
* Show agent memory/relationships in a sidebar
* Have a text input for "describe what happens next"
* Watch the map and states update
