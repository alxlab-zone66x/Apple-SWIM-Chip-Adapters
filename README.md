<img src="docs/macintosh_portable_battery_adapter_v1.0_pcb_front.png" alt="Macintosh Portable Battery Adapter v1.0 PCB front" style="display: inline-block; width: 50%;" /><img src="docs/macintosh_portable_battery_adapter_v1.0_pcb_back.png" alt="Macintosh Portable Battery Adapter v1.0 PCB back" style="display: inline-block; width: 50%;" />

# Apple SWIM Chip Adapters

This project is for a couple of chip adapters to convert the PLCC-28 and PLCC-44 Apple SWIM chips to DIP-28.

The intention of the project was to allow me to use the PLCC-44 SWIM chip from my battery bombed Macintosh Classic into a Macintosh SE to give it 1.44MB floppy drive support.

The PLCC-28 and DIP-28 SWIM chips have the exact same pin layout (i.e., pin 1 goes to pin 1, pin 2 to pin 2, etc). This means that PLCC-28 to DIP-28 adapter can be used with universal programmers as well.

 The pinouts of the SWIM chips was found in the [SWIM_Chip_User's_Reference](docs/info/SWIM_Chip_Users_Ref_198801.pdf). That 

## Bill of Materials

### PLCC-28 to DIP-28 SWIM Chip Adapter

| Quantity | Description                                               | Designators | Product Number | Datasheet                                |
| :------- | --------------------------------------------------------- | ----------- | -------------- | ---------------------------------------- |
| 1        | Supercapacitor balancing IC.                              | U2          | PLCC-28-AT     | [pdf](docs/datasheets/ALD810025.pdf)     |
| 28       | DIP pin                                                   |             | SHP-001        | [pdf](docs/datasheets/ALD810025.pdf)     |
| 3        | 10F, 2.7V supercapacitor, 5mm lead spacing, 10mm diameter | C1,C2,C3    | TPL-10/10X30F  | [pdf](docs/datasheets/TPL-10_10X30F.pdf) |



### PLCC-44 to DIP-28 SWIM Chip Adapter

All the same parts as v1.0 and v1.1 with the addition of the supercapacitor stuff. Use either the IC or the resistors but not both. You can use a supercapacitor with a different capacity, but if you use resistors for balancing, you'll probably need to recalculate the resistance value. Refer to this [PDF](docs/info/o671684v410%20ANP090a_EN.pdf) by Würth Elecktronik to do the calculation.

| Quantity | Description                                               | Designators | Product Number | Datasheet                                |
| :------- | --------------------------------------------------------- | ----------- | -------------- | ---------------------------------------- |
| 1        | Supercapacitor balancing IC.                              | U1          | ALD810025SCL   | [pdf](docs/datasheets/ALD810025.pdf)     |
| 3        | 1/4W 9kOhm resistor (though-hole or 0805)                 | R1,R2,R3    |                |                                          |
| 3        | 10F, 2.7V supercapacitor, 5mm lead spacing, 10mm diameter | C1,C2,C3    | TPL-10/10X30F  | [pdf](docs/datasheets/TPL-10_10X30F.pdf) |



## Manufacturing

The release includes the manufacturing files for JLCPCB specifically. If you need to the gerber files, BOM or component pick & place in a different format then you would have to generate them yourself.

The PCB thickness chosen should be 1.6mm.



## Pictures

<img src="docs/macintosh_portable_battery_adapter_v1.0_stack_of_pcbs.jpg" style="display: inline-block; width: 33%;" alt="Macintosh Portable Battery Adapter v1.0 PCB stack" /><img src="docs/macintosh_portable_battery_adapter_v1.0_soldered_wires.jpg" style="display: inline-block; width: 33%;" alt="Macintosh Portable Battery Adapter v1.0 soldered wires" /><img src="docs/macintosh_portable_battery_adapter_v1.0_with_no_case.jpg" style="display: inline-block; width: 33%;" alt="Macintosh Portable Battery Adapter v1.0 without a case" /><img src="docs/macintosh_portable_battery_adapter_v1.0_case_top.jpg" style="display: inline-block; width: 33%; margin-right: auto;" alt="Macintosh Portable Battery Adapter v1.0 case top" /><img src="docs/macintosh_portable_battery_adapter_v1.0_case_angled.jpg" style="display: inline-block; width: 33%; margin-right: auto;" alt="Macintosh Portable Battery Adapter v1.0 case angled" /><img src="docs/macintosh_portable_battery_adapter_v1.2_pcb.jpg" style="display: inline-block; width: 33%; margin-right: auto;" alt="Macintosh Portable Battery Adapter v1.2 pcb" />







## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>

Macintosh Portable Battery Adapter by [Alexandre Marcoux](https://github.com/alxlab-zone66x/Macintosh_Portable_Battery_Adapter) licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.



## Community

For more great retro hardware projects and a great community check out:

[<img src="docs/tinker_different_sat_rev_600.png" alt="Tinker Different" style="float: left;" />](https://tinkerdifferent.com/)









Join us in #skunkworks on [Discord](https://discord.gg/GKcvtgU7P9) to help make retro solutions available to all.

[<img src="docs/discordbanner.png" alt="Discord Open Retro SCSI skunkworks" style="float: left;" />](https://discord.gg/GKcvtgU7P9)







## Attribution

Macintosh Portable Battery Enclosure (M5137) by [StephenLulz](https://www.thingiverse.com/StephenLulz) is licensed under the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
