# Naviter Oudie(IGC) as a FLARM device - setting


## Many thanks to Lysupov ( https://github.com/lyusupov/SoftRF/wiki ) for working on SofRF project.

I have Naviter Oudie(IGC) connected to Prime Edition Mark II ( based on third-party's hardware - TTGO T-Beam (  http://s.click.aliexpress.com/e/clSbLKmc ) ) and working as a FLARM device. With this combination and correct setting is possible to view traffic around me on Oudie display.

Everything is documented on wiki page https://github.com/ivonovak/SoftRF-Naviter-Oudie/wiki


## Some recommendations :

1. For OGN tracker I recommend firmware version 1.0.-rc7 and higher (when it will be ...), with 1.0.-rc6 it didn't work
2. The baud rate on the Oudie COM port must be set to> = 19200. If it is lower, FLARM data is not transmitted !!
3. You must SAVE the settings in Oudie after making changes. Otherwise, it does not remember the setting and even forgets it after a while ...
4. When selecting the FLARM device, select "Other", otherwise the Oudie will "freeze" !
5. Oudie freezes even if the COM port is set incorrectly !
6. I still have not barographic sensor installed on OGN tracker. I recommend install it on OGN tracker to get correct data!




Ivo Novak
