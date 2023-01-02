# Editing layer

I call this an `editing` layer, but it is like everything else is multi-purposeful. The left side of this layer is part of the [punctuation](punctuation.md) setup. And the real reason I call it "editing" is because it has the cut/copy/paste and undo/redo buttons on the left side.

```
╭───────┬───────┬───────┬───────┬───────╮   ╭───────┬───────┬───────┬───────┬───────╮
│ ESC   │ ALTAB | ALTLD │       │       │   │       │  [    │  -    │  ]    │  `    │
├───────┼───────┼───────┼───────┼───────┤   ├───────┼───────┼───────┼───────┼───────┤
│ UNDO  │  CUT  │ COPY  │ PASTE │ REDO  │   │   ~   │  <    │  =    │  >    │ '     │
├───────┼───────┼───────┼───────┼───────┤   ├───────┼───────┼───────┼───────┼───────┤
│       │       │       │       │       │   │       │  /    │  |    │  \    │ "     │
╰───────┴───────┴───────┼───────┼───────┤   ├───────┼───────┼───────┴───────┴───────╯
                        │       │       │   │  &    │  DEL  │
                        ╰───────┴───────╯   ╰───────┴───────╯
```

Lets go through all the trickery that is going on in here. I already talked about the right hand side in the [punctuation](punctuation.md) document, now lets go through the left hand buttons.

## Home row edits

Do you get left hand craps from pressing copy-paste all day? I do. Well, i did, until i have moved those buttons into the home row. 

It's essentially the same mnemonic as the standard `Z/X/C/V` buttons, just moved into the home row. And activated via the primary thumb button press, rather than a `Ctrl` or `Meta` button. If you're a mac user, this will feel very natural and simply more comfortable.

The dedicated `Redo` button is actually pretty handy too. You will never go back to pressing `ctrl+shift+z` again.

## The ESC button

Through the years, i have successfully retrained my hands to do all sorts of weird things on a keyboard. Invariably though, the `ESC` was one of the more difficult to deal with. I guess after pressing it 50 times a day for 25 years, my brain really wants to have it in the top left corner.

And having it under a layer activation makes it very and natural to reach with a quick one hand motion.

## Fake ALT-TABs

The other thing that I found challenging to move away from is the `ALT-TAB` (or `CMD-TAB` on macOS) combination to switch between windows. Also, on macOS you also really want an `ALT-TILD` combo to switch between windows in a group.

So, I have fake one button combo buttons that mimic the ALT-TAB combo when pressed multiple times. It's a QMK thing called swapper, and quite common setup.

The beauty of this approach is that the `ALTAB` button sits in a layer under the primary left thumb button. So the process of activation of the left layer and pressing the fake `ALTAB` button feels almost exactly as a normal `CMD+TAB` combo on a conventional keyboard.

I say _almost exactly_ because, as you can see, I have the button shifted to the right under the ring finger rather than the pinkie. There are couple of reasons for this. Firstly, I _really_ want that ESC to be where it is. And secondly, the ring finger is stronger and much easier to use than the pinkie in the top row. This placement just makes it easier to access and use. 
