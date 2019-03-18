# KiCad Board Template For Raspberry Pi Zero (W) uHAT

Easy starting point for Raspberry Pi Zero (W) uHAT extension board.
GPIO 40 Pin connector is of through hole type, board size is 65x30mm. Pi Zero or Zero W
boards do not have PoE header, other components can be placed in that region.  
ID EEPROM is not added as its footprint package and I2C pull-up resistors size could be different based on your project.  
Please refer to [HAT Design Guidelines](https://github.com/raspberrypi/hats/blob/master/designguide.md) for more details.

**KiCad version: 5.0.2**  

Project home page: <https://ravikiranb.com/projects/kicad-rpiz-uhat-template/>  

## Installing as template in KiCad on Ubuntu

* If KICAD_USER_TEMPLATE_DIR environment variable is not set:  
    Open KiCAD > **Preferences** Menu > **Configure Paths**  
    Set KICAD_USER_TEMPLATE_DIR environment variable to a directory where you would create/copy all user    templates.

* Get design files  
    $ git clone https://github.com/rkprojects/kicad-rpiz-uhat-template.git  
    $ cd kicad-rpiz-uhat-template   

    Copy to template directory  
    $ cp -r raspberrypi_zerow_uhat *<kicad_user_template_dir_path_set_above\>*  
    Or create symbolic link  
    $ ln -sr raspberrypi_zerow_uhat *<kicad_user_template_dir_path_set_above\>*


## Using Template

Create New project from template.  
Open KiCad > Press **CTRL-T** or from Menu **File** > **New** > **Project from Template**  
Click **User Templates** tab > Click Raspberry Pi icon > If there are many icons read template information to cross check > Click OK button.  
Refer to [KiCad docs](http://docs.kicad-pcb.org/) for more details.

## License

Copyright 2019 Ravikiran Bukkasagara, <contact@ravikiranb.com>

This project's Schematics, PCB design files, Footprint libraries and Documentation files are released under MIT Open Source License.  
Please refer to the file named **LICENSE** for complete license text.

