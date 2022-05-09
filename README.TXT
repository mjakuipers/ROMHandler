//---------------------------------------------------------------------------//
//    Copyright (c) 2008  Meindert Kuipers, Netherlands                      //
//    meindert@kuiprs.nl                 www.kuiprs.nl                       //
//                                                                           //
// This program is free software; you can redistribute it and/or             //
// modify it under the terms of the GNU General Public License               //
// as published by the Free Software Foundation; either version 2            //
// of the License, or (at your option) any later version.                    //
//                                                                           //
// This program is distributed in the hope that it will be useful,           //
// but WITHOUT ANY WARRANTY; without even the implied warranty of            //
// MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the             //
// GNU General Public License for more details.                              //
//                                                                           //
// You should have received a copy of the GNU General Public License         //
// along with this program; if not, write to the Free Software               //
// Foundation, Inc., 59 Temple Place - Suite 330, Boston, MA  02111-1307, USA//
//---------------------------------------------------------------------------//
//
//---------------------------------------------------------------------------//
//  README.TXT                                                               //
//  File with installation and revision instructions                         //
//  Ver  Date     Description                                                //
//  0.20 May 2022 Fixed issue with saving INI file                           //
//                Fixed font size also in listing window                     //
//                Enable lower case and spaceless mnemonics                  //
//                Added MnemArg0 for JC/JNC jump distance                    // 
//			First public BETA
//---------------------------------------------------------------------------//

This is the first public BETA version. Please report any issues.

Initial version, based on MLDL2000 Version 1.91, without any hardware support.
Refer to the manual of M2kM for the basic operation of the ROMHandler.

The disassembler offers the following extra or undocumented functions compared 
to the most recent version of M2kM:
- disassembly of HEPAX RAM images, recognizes file types
- support for HP41CL commands
- support for HP41CL FLDB image listing
- alert for HP41CL image using upper bits
- lists HP41CL YCRC
- alert for HEPAX RAM file (xFF3 = 200)
- supports lower case mnemonics and mnemonics without spaces (CalypsiNut style)
- HEXdump of a ROM image
- listwindow and disassembly lister font can be selected (with Preferences)
- analysis of DM41X RAM file, and splits this file in seperate ROM files
- opens i41CX mailmod files

No warranty of any kind. Please backup your files before using this software!

The executable of the ROMHandler consists of the following files:

ROMHandler.exe     - the executable
ROMHandler.INI     - ini file with preferences for ROMHandler
SYSTEMLABELS.TXT   - textfile with labels of the HP41 System ROMS for the disassembler
XROM.TXT           - textfile with XROM numbers for the disassembler
README.TXT         - this file

All files should be installed in the same directory. ROMHandler  has no 
installer and does not use the Windows registry. Uninstalling is done by 
deleting the files mentioned above.
