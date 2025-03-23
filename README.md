/ Note: Text that comes after "//" is ignored, which allows
// you to write notes - like the one you're reading now!

title
  Your Generator's Title

output
  {This|That} [animal] is so [adjective]!
  I wish I could [verb] that [animal].
  Aren't [animal.pluralForm] just so [adjective]?
  There must be at least {1-10} [animal]{s} [location]!
  THE [animal.upperCase]! It's eating the {import:common-noun}!
  {A} [animal] is a bit like {a} {import:common-noun}. // {A} and {a} will automatically choose "a" and "an" as appropriate

animal
  pig
  cow
  chicken
  zebra
  crayfish
  jellyfish^0.5  // this item is HALF as likely as the others
  worm^2         // this item is TWICE as likely as the others
	
adjective
  small
  big
  cute
  sneaky
  unusual
  helpful
  mean
	
verb
  pat
  befriend
  help
	
location
  on {the|this|that} island
  in {the|this|that} valley
  {around|in} here
  over there
  under this {thing^2|thingie}
	

// Tips:
//  - Highlight multiple lines and press Tab or Shift+Tab to indent and un-indent them all an once
//  - You can change the URL of your generator by clicking the "settings" button in the top-right
//  - You can use the sparkle button in the lower-right of the screen to ask the AI to adjust the visual design of your generator.
//  - Add background images, fonts, and other stuff with plugins:  perchance.org/plugins
//  - Here are some generators you might like to import:  perchance.org/useful-generators
//  - Read this page after reading the tutorial:  perchance.org/examples
//  - There's a gear button in the top-left which you can use to make the lines wrap around when they reach the edge of the screen, and to change the font size. Also, if you add   $output=[this.joinItems("<br>")]   as the first or last item in your list, then writing [yourListName] will magically output all of the items joined together with <br> (which means "line break" in HTML - i.e. a line separator), rather than outputting a random item from the "yourListName" list.
//  - Ask our friendly community members if you need help:  lemmy.world/c/perchance




