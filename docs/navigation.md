# Navigation

Since there are no arrow keys or anything like that on a 40% keyboard, i have a dedicated navigation layer. The great thing about that is that you can actually make neat things with it and make navigation even more comfortable than on a conventional full-size keyboard.

```
╭───────┬───────┬───────┬───────┬───────╮   ╭───────┬───────┬───────┬───────┬───────╮
│  ^    │  {    │  *    │  }    │       │   │       │ Home  │  Up   │  End  │ PgUp  │
├───────┼───────┼───────┼───────┼───────┤   ├───────┼───────┼───────┼───────┼───────┤
│ GUI ! │ ALT ( │ SFT # │ CTL ) │       │   │       │ Left  │ Down  │ Right │ PgDwn │
├───────┼───────┼───────┼───────┼───────┤   ├───────┼───────┼───────┼───────┼───────┤
│  ?    │  @    │  %    │  $    │       │   │       │       │       │       │       │
╰───────┴───────┴───────┼───────┼───────┤   ├───────┼───────┼───────┴───────┴───────╯
                        │       │  _    │   │       │       │
                        ╰───────┴───────╯   ╰───────┴───────╯
```

A few things to explain here.

Firstly, as you have noticed, i'm a no vim user. I like normal arrow keys, and I want them under the strong three fingers so they'd be natural to use. Additionally, I really like to have the `home` and `end` buttons handy. Which don't work on macOS by default, but you _can_ make them work like windows/linux with a simple patch.

```sh
mkdir -p $HOME/Library/KeyBindings
echo '{
/* Remap Home / End keys to work same as in windows/linux */
"\UF729" = "moveToBeginningOfLine:"; /* Home */
"\UF72B" = "moveToEndOfLine:"; /* End */
"$\UF729" = "moveToBeginningOfLineAndModifySelection:"; /* Shift + Home */
"$\UF72B" = "moveToEndOfLineAndModifySelection:"; /* Shift + End */
"^\UF729" = "moveToBeginningOfDocument:"; /* Ctrl + Home */
"^\UF72B" = "moveToEndOfDocument:"; /* Ctrl + End */
"$^\UF729" = "moveToBeginningOfDocumentAndModifySelection:"; /* Shift + Ctrl + Home */
"$^\UF72B" = "moveToEndOfDocumentAndModifySelection:"; /* Shift + Ctrl + End */
}' > $HOME/Library/KeyBindings/DefaultKeyBinding.dict
```

And I also have the page up/down buttons handy, because they're used in editors to move between tabs. I tried to use mouse scroll instead for those two, but I don't know if like that.

Secondly, the navigation layout is activated with a right hand thumb press see the [layer switching](./layer-switching.md) which allows for one handed operation of the navigation buttons. Also, because it is activated with the primary right hand thumb button, it shares the left side with the [punctuation setup](./punctuation.md)

And lastly, notice the `GUI` , `ALT` , `SHIFT` , and `CTRL` symbols on the right. Those are part of the [home row mods](./home-row-mods.md) setup and provide for very handy quick mods for the navigation buttons on the right. Using those, one can quickly jump and select text as naturally as possible.
