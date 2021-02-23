# Super Capslock
Make Capslock Great Again!

## Requirements
- Windows with [AutoHotkey](https://www.autohotkey.com/)
- Linux with `X.Org` (`xmodmap` and `xcape`)
- macOS with [Karabiner-Elements](https://karabiner-elements.pqrs.org/)

## Features
- Post ESCAPE if CAPSLOCK is pressed. 
- Post CAPSLOCK if ESCAPE is pressed. 

## Usage
### Windows 
> Running the script with administrator privileges is  recommended, which means you can use the feature in all programs.
> 
Run `SuperCaps.ahk` with [AutoHotkey](https://www.autohotkey.com/). You can also compile the script and use `SuperCaps.exe`.


### Linux
- Download the script `xmodmap` and run it using `xmodmap .xmodmap`
- Run `xcape -e 'Mode_switch=Escape'`

Check [this](https://unix.stackexchange.com/questions/414926/bind-capshjkl-to-arrow-keys-caps-to-esc) for more details.

### macOS
- Install [Karabiner-Elements](https://karabiner-elements.pqrs.org/)
- Add `Vimode with smart caps` and enable all three rules.

Check [Karabiner-Elements Documentation](https://karabiner-elements.pqrs.org/docs/manual/configuration/configure-complex-modifications/) for more details.
