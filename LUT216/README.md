# LUT216 by [Z.A.N.](https://sblive.narod.ru/index.htm)
My attempt at some English translation for Z.A.N.'s BMC-based Sinclair ZX Spectrum clone.<br>

WORK IN PROGRESS!<br>

The name "LUT216" comes from (I believe):
- "ЛУТ" (LUT) = Laser-UV Technology (Лазерно-Ультрафиолетовая Технология), the Russian term for the Toner Transfer + UV exposure/photoresist method of DIY PCB production
- "216" = the КА1515ХМ1-216 [Базового Матричного Кристалла (Basic Matrix Crystal)](https://ru.wikipedia.org/wiki/1515ХМ1) that is the heart of this computer

[Original Page (RU)](https://sblive.narod.ru/ZX-Spectrum/LUT216/LUT216.htm)

## [Original Information](/LUT216/Originals)
A copy of the original files from Z.A.N.'s page for reference:
- LUT216.rar: Gerbers
- LUT216SCH.GIF: schematic
- LUT216MontMono.png: board layout

## Western Parts List (Work In Progress)
See also: https://elcomps.com/en/a72<br>

All mistakes are mine - I couldn't find a BOM so have generated this from the schematic.<br>

|Part ID|Soviet Part    |Western Part|Part Type                   |
|-------|---------------|------------|----------------------------|
| D1    | К555ЛН1       | 74LS04     | Hex inverter               |
| D2    | К555АП3       | 74LS240    | Octal inverter line driver |
| D3    | КА1515ХМ1-216 |            | Basic matrix crystal (ULA) |
| D4    | К561ЛН2       | CD4049     | CMOS hex inverter          |
| D5    | КР1858ВМ1     | Z80        | CPU                        |
| D6    | КР565РУ5      | 4164       | 64Kbit DRAM                |
| D7    | КР565РУ5      | 4164       | 64Kbit DRAM                |
| D8    | КР565РУ5      | 4164       | 64Kbit DRAM                |
| D9    | КР565РУ5      | 4164       | 64Kbit DRAM                |
| D10   | КР565РУ5      | 4164       | 64Kbit DRAM                |
| D11   | КР565РУ5      | 4164       | 64Kbit DRAM                |
| D12   | КР565РУ5      | 4164       | 64Kbit DRAM                |
| D13   | КР565РУ5      | 4164       | 64Kbit DRAM                |
| D14   |               | 27128      | 16KByte EPROM*             |
| X1    |               | MAB5SH     | 5-pin DIN for joystick     |
| X2    |               | MAB5SH     | 5-pin DIN for RGB video    |
| X3    |               | MAB5SH     | 5-pin DIN for tape         |
| T1    | КТ315         | BC547      | PNP transistor (C-B-E)     |
| T2    | КТ315         | BC547      | PNP transistor (C-B-E)     |
| T3    | КТ315         | BC547      | PNP transistor (C-B-E)     |
| T4    | КТ315         | BC547      | PNP transistor (C-B-E)     |
| T5    | КТ315         | BC547      | PNP transistor (C-B-E)     |

*Note: D14 has space for a 28 or 32 pin EPROM.  Address lines above A13 are not used.

