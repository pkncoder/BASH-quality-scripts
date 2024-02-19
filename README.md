# Pkncoder's Quality of Life (QoL) BASH Scripts

Hello, my name is Pkncoder. I have some personal scripts that I use to make things quicker

  *(or as an excuse to use the terminal)*

## Scripts
- show:
  - This takes any amount of positional arguments and opens the application givin
  - There are also shortcuts that are added for simplicity or because I can't remember the name
  - The current ones:
    - vsc / vscode: Visual Studio Code
    - fox: firefox
    - disc: discord
  - This impliments open -a to open the apps (*and uses open -a "firefox" --url* for spesific websites)

- create:
  - This creates a bash file with the name givin and preps it for use
  - This does multiple things in success:
    - Creates the file and adds the lines needed:
      - Adds the **SHEBANG** line
      - The date (from a variable declared before adding the line)
      - The creator (me <3)
    - Chmods (changes the permissions of the file) to add run-ibility to the file
    - Opens it with nano, which is better than vim (fight me)

- close:
  - This does as it's called. It closes applications givin (woah crazy)
  - This, like show, has shortcuts because FOR SOME REASON the app names are different than show with open
  - The current ones:
    - fox: closes firefox (the actual normal one)
    - disc / discord: closes discord
  - This impliments the pkill command
  - Note there is no VSCode close shortcut, as it panicked during testing when I pkilled it (and for saving reasons)
