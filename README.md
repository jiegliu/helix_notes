# helix_notes

```


████This is not a quick-start help doc

if u wanna that, go run command: 
hx --tutor

Also, read the finely doc ^_^
https://docs.helix-editor.com/

████This is some personal thingking of helix, learning notes, little usage combination
  When less is more, and when more is less?
less is more when u compare what u pay to what you take
  u don't need it too much, don't pay too much
  u need it for a long time, pay much to take much

more is less when
  1. u spend less time to learn it first time, and later, u need more time to learn more about it, correct more on existed error model of it in ur brain, which is a hell
  2. u spend more time to learn it first time, and need merely time to learn more

  Which one will u choose? it depends of ur need

████let's talk about helix, an editor who learned many good staff from other editors

things are different, if you mix them up into one word, u lost them ALL

a concept called file, is different in different time and different place

  a file stored in disk
  a file in RAM
  a file in human-brain model
  a file in computer abstract model
  a file showed in screen
  ...
i only list what iknow, take good staff if it suits u, and leave the trash left

in common case, we use hx( abbr. of helix) to open a name file or just this app

it auto find file from disk, load in RAM memory, well this is a simple model of its work, it did more and more work under the surface with these genius developers

so as a user, we won't care too much details, they helped us these parts, thanks them ❤❤❤

a unicode string is the whole file text, it is 1-Dimension(1 D), who has two direction: forward and backward.

this model is for computer, we human need see the text on a 2-Dimension(2 D) screen, who has four direction: left, down, up, right

now, this model is more friendly as we are not good at one-line 1D long text, both for reading or editing.

things are different and complex than one single concept, cuz we need them!

when we play games, qwer or wasd may not work for them literal value "qwer" or "wasd", that's it.

this pattern, or mechnism, or mode, is for "first thing first", in game, type info is secondary staff, while heros or cars skill is first-class staff.

while editing, particular in programming, "qwer", the literal function of physical keys on keyboard is not the first-class thing

it is important, but not that much important, we have more important thing to define for the human finger's stokes on keyboards

we pay same, but want more, we stroke one key, hit and released, so much info wasted on a "q"? nope!

so in default, every key has its first-class function, when we hit it, release it, combinate with other key, and sequence of these keys, should work on first-class usage

here, helix use hjkl to move around, while it is described in official doc that they work like arrows, well, let me talk details of their usage.

i'm going to talk facts and logical model which help my brain to think and use it, not what other's definition or official definition.

in facts

❤ h, l
e.g. h works like backward to 1D string text, 1 direction of 1 Dimension and its end is the start of file, not leftest of line
❤ j, k
e.g. j works like down to 2D string text, 1 direction of 1 dimension(vertical) of 2 Dimension screen.

why we don't define anohter 2 keys for horizontal dimension of 2D screen? cuz its usage mostly same to 1D stream of chars

there only exist pay and take, we wanna pay less and take more, not full every aspects of model, they work for us, not instead

but do we really need the details? well, it depends

i don't wanna memory non-organized info like hl will cross line, instead, 1D and 2D and pay-take model is consistent and reasonable for my brain

we know that 1 dimension has 2 direction, 2 ends, so h will stop work if at start end of file, l for end end...well

default design is showed before, but we have personal taste, so we can add a config file to define what III need!

like go up to a line, well, we human not good at memory and calculating by flexible to imagine!

so put config to letting screen show line number, so we can just go that line

what's the cons of this design, what if line 9999? let's rethink what really we need?

we wanna go up to a line, and the number of line relative to whole file is too much payed, and i get so less

since we can see the line, use this info, lets set the number of line showed on screen is relative to the screen not logic whole file!

is that good enough? nope, when? when a better one came up, the others are not good enough.

line number showed on screen relative to logical whole text or screen partial text is that too much info to operate

first thing goes first, so we need line numbers showed which is relative to the line we focused!

[editor]
line-number = "relative"

that's the our part to enable the function, and other work to make it happen are made by the developers

oh, may there are another better way, but since the concept is made in our brain, it's hard to change the tool

that's why qwerty layout is default, only reason is that we learned computer by it, and hard to change to colemak, or a nother physical key positions..

goon, after deleting the design of horizontal dimension of screen, what if we wanna a 2d screen left ends???

which is called start of line, line, is one dimention of 2d screen, also, there are many difference of a line end

including visible characters or not? will break line if out of screen width? 

so the design should care about everything we need, so it grow to more and more complex

we don't wanna handle the best solution of every target/task/goal/job.

we wanna learn a basci enough tools to work out of any new variable target/task/goal/job.

so there are many aspects of helix u can think of, for memory, i'm going to use what we have model, a for(key in helix) method

u see, many choices are made by myself due to my hard poor brain memory, any good suggestions are welcomed

also, hljk select current char, u can delete it using d,
so, movements goes also on semantics, like w for w





```
