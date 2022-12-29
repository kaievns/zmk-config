# Home row mods

Home row mods refer to using mod-tap behaviour on the home row buttons to
activate keyboard modifiers (CTRL, ALT, SHIFT, META), as opposed to the thumbs
row on a conventional keyboard.

This is a bit of a controversial topic, and for a good reason. They can be very
finicky to dial in; they can interfere with normal typing if implemented poorly;
and generally might feel weird to use to some people because they require to use
hands alteration a lot.

Given that I'm dealing with a 34 switches keyboard and i'm using the thumbs row
for layers switching, i have no option but to use home row mods in my setup.
Also, I actually kinda like it a lot.

## Mods arrangement

Since there are four modifier keys, as you can imagine, there are more than one
way to arrange them on the keyboard. The most common would be to put the `SHIFT`
mods under the pinkies because it feels the most natural because one uses
pinkies for shifts on a conventional keyboard.

Well, as you have probably guessed by now, I have rejected the dogma and use
another system. Well, actually I stole it from some guy on the internet who did
a lot of research and thinking on the subject; and I agree with their work. Here
is how they look

```
╭───────┬───────┬───────┬───────┬───────╮   ╭───────┬───────┬───────┬───────┬───────╮
│  Q    │  W    │  E    │  R    │  T    │   │  Y    │  U    │  I    │  O    │  P    │ 
├───────┼───────┼───────┼───────┼───────┤   ├───────┼───────┼───────┼───────┼───────┤
│GUI(A) │ALT(S) │SHFT(D)│CTL(F) │  G    │   │  H    │CTL(J) │SHFT(K)│ALT(L) │GUI(;) │
├───────┼───────┼───────┼───────┼───────┤   ├───────┼───────┼───────┼───────┼───────┤
│  Z    │  X    │  C    │  V    │  B    │   │  N    │  M    │ , <   │ . >   │ / ?   │
╰───────┴───────┴───────┼───────┼───────┤   ├───────┼───────┼───────┴───────┴───────╯
```

## Method to the madness

The way it's set up has to do with fingers strength and mods combinations.

A middle finger is the strongest on a palm, and `SHIFT` mod is by far the most
used one, so they go together. However sensible this sounds the reality is that
we all have the bad habit of holding shift with a pinky and then type like that
with both hands. So I need to make couple of comments on this.

Basically, you need to consider that there are two somewhat separate cases:
normal text shifts and typing in all caps. For regular text typing hands
alteration is the best, that's a known fact. For all caps (normally typing
constant names while programming) you'd be better of by making a sticky caps
lock button. So, shift goes under the middle finger.

The `CTRL` mod goes under the pinty fingers, because they normally trigger
actions, such as save, copy, paste, etc. And the brain feels very happy when
those associated with the pointy fingers for some reason. It's also the second
most used mod button and the second strongest finger on a palm. So, the two go
together like peanut butter and jelly.

The `ALT` mod is arguably the least used and goes under the most awkward finger
on the palm, the ring finger. And the `GUI` takes the last remaining finger, the
pinkie.

There is another reason why the `ALT` and `CTRL` mods sit next to `SHIFT` and
that is because the most common mod button combinations are `ALT+SHIFT` and
`CTRL+SHIFT`. And the way meat in our hands work, it's easier to press those
together with adjacent fingers.

So, when you put all those considerations together you have the `GASC` sequence.

Again, other combinations might work better for somebody else.

## NOTE on macOS

On macOS you'd want the GUI and CTRL swapped, to get the same benefits. Since
I'm a chronic system hopper, I prefer to change those mods in the macOS
preferences rather than flash them directly onto the board. So, if you're an
exclusively mac user, you might as well swap them in the firmware
