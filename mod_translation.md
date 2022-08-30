# Description how to translate my mods
-----

`Requirements:`
- let me know beforehand
- only translate in your native language
- make sure the language is not yet available

-----

`Rewards:`
- you are now part of a mod! yey!
- they are mentioned as a translator in the language file
- you earn a special rank on my discord

-----

`How it works:`
1. your get the file
2. rename the file name to your language
3. it's best to open the file with the program Notepad++ (https://notepad-plus-plus.org/downloads/)
4. add this line on the top of the file:
```json
// translated by [your username]
```
5. translate all names on the right side (if you are not sure what is meant by something, please contact me)



```json
{
  "replace": false,
  "values": [
    "#minecraft:is_forest",
    {
      "id": "#forge:is_forest",
      "required": false
    },
    {
      "id": "#c:forest",
      "required": false
    }
  ]
}
```
