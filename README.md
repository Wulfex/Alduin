Alduin
------

###### Alduin
![Screenshot](https://cloud.githubusercontent.com/assets/11221489/19174337/e3f3aa68-8be2-11e6-8474-4908f44e7505.png)
![Screenshot](https://cloud.githubusercontent.com/assets/11221489/19262924/6eea0bd0-8f4e-11e6-9bba-73c268290a36.png)
![Screenshot](https://cloud.githubusercontent.com/assets/11221489/19262969/ae6acfb0-8f4e-11e6-81bb-43552a1b03a6.png)
![Screenshot](https://cloud.githubusercontent.com/assets/11221489/19263809/0a473360-8f53-11e6-850d-c8af33cd3e06.png)

```VimL
colorscheme alduin
```

Installation
---------------
There are a few ways to install alduin. The first option is by using your favorite vim package manager and the second is by manual download.

###### Package Manager Option
| Manager          | SetUp                                                                                      |
|------------------|--------------------------------------------------------------------------------------------|
| Vundle           | add to .vimrc:   `Plugin 'alessandroyorba/alduin'`                                         |
| NeoBundle        | add to .vimrc:   `NeoBundle 'alessandroyorba/alduin'`                                      |
| VimPlug          | add to .vimrc:   `Plug 'alessandroyorba/alduin'`                                           |
| Pathogen         | from terminal:   `cd ~/.vim/bundle && \ git clone git://github.com/alessandroyorba/alduin` |

###### Download Option
Download the .zip and copy `alduin.vim` to `~/.vim/colors` (on Windows `<your-vim-dir>\vimfiles\colors`). Or for global accessibility, `/usr/share/vim/vimfiles/colors`.

Alduin Settings
---------------
There are several options that you can enable for alduin. You can activate them by adding each of the following variables to your .vimrc. Remember to place the variables before you declare `colorscheme alduin`.

| Decription                            | Add variables to .vimrc                     | Screenshot                          |
|---------------------------------------|---------------------------------------------|-------------------------------------|
| meduim gray background                | `colorscheme alduin`                        | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/19174337/e3f3aa68-8be2-11e6-8474-4908f44e7505.png) |
| dark gray background                  | `let g:alduin_Shout_Dragon_Aspect = 1`      | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/19263012/f45e8ca0-8f4e-11e6-860d-7fdf24b75a0a.png) |
| black background                      | `let g:alduin_Shout_Become_Ethereal = 1`    | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/19263164/cb2628d8-8f4f-11e6-8202-fe0eda4d2335.png) |
| gray to black @ 5pm                   | `let g:alduin_Contract_Vampirism = 1`       | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/19263262/53ccd54c-8f50-11e6-8f49-a90efd127ae5.png) |
| underline matching parens             | `let g:alduin_Shout_Aura_Whisper = 1`       | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/19263436/36c3e99e-8f51-11e6-9c7a-3a957afab5ce.png) |
| adds dark red color                   | `let g:alduin_Shout_Fire_Breath = 1`        | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/19263338/adb7cf44-8f50-11e6-840b-b07180b03941.png) |
| removes background from Strings       | `let g:alduin_Shout_Animal_Allegiance = 1`  | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/19263701/69d87024-8f52-11e6-8086-ecaeca0b18b3.png) |
| removes cursorline                    | `let g:alduin_Shout_Clear_Skies = 1`        | [Screenshot](https://cloud.githubusercontent.com/assets/11221489/19264102/4230e2d4-8f54-11e6-9bf5-2fba384c6bae.png) |


Moar Screenshots
------------
The screenshots of Alduin were made and tested using a default Vi IMproved 8.0 in [iTerm 3](https://www.iterm2.com) and the Vi IMproved 8.0 in the GUI MacVim app. Extended syntax found in Javascript screenshots provided by Jose Elera Campana's Plug-in [vim-javascript-syntax](https://github.com/jelera/vim-javascript-syntax).

[Additional Screenshots](https://github.com/AlessandroYorba/Alduin/issues/5)

Skyrim belongs to the Nords!!
-------
If you like certain colorschemes like Twilight, Mustang, and Inkpot, I encourage you to give Alduin a try. The idea behind Alduin was to create a dark colorscheme that combined warm and soft colors for high readability with low distraction. Some of the features, and design cues pay homage to schemes like Jeet Sukumaran's [Sorcerer](http://jeetworks.org/sorcerer/), Ciaran McCreesh's [Inkpot](https://github.com/ciaranm/inkpot), as well as Romain Lafourcade's [Apprentice](https://github.com/romainl/Apprentice), and Steve Losh's [Badwolf](https://github.com/sjl/badwolf).

I'd love to hear from you guys if you have any feedback, suggestions or issues that you encounter. Just open an Issue ticket for any bugs or suggestions; and if you like alduin you might want to check out my other Vim theme [Sierra](https://github.com/AlessandroYorba/Sierra)
