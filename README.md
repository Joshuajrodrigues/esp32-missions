# esp32-missions

Just a place to keep my beginner hardware projects with esp32s and rust in one spot. named them after nasa missions.

## what is this

this is a "hub" repo. the actual code lives in separate repositories (submodules). i did it this way as they started out as separate projects but they are kinda linked and their names dont make sense indivually.

### mercury 
THis one is a morse code blinker


### gemini
this one is knight rider lights

## how to use this

if you just clone this, the folders will be empty. you gotta do:

```bash

git clone --recursive https://github.com/Joshuajrodrigues/esp32-missions
```
or if you already cloned it:

```Bash

git submodule update --init --recursive

```
## Components
- Esp32s
- rust
