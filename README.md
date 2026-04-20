Schematicul meu este destul de bine organizat si se vede ca am gandit proiectul pe blocuri. Se distinge clar zona de microcontroller, partea de alimentare, zona de debug si fuel gauge-ul, ceea ce face schema mai usor de urmarit. Per total consider ca are o structura logica si se intelege destul de bine cum comunica componentele intre ele.
Proiectul meu este un dispozitiv bazat pe nRF52840. Acesta controleaza mai multe componente precum display-ul e-paper, IMU-ul, partea de haptic si fuel gauge-ul pentru baterie.
Componenta principala este nRF52840. Acesta comunica cu restul componentelor si controleaza functionarea intregului sistem.
Blocurile principale din proiect sunt:
- nRF52840
- display e-paper
- IMU
- haptic driver
- fuel gauge
- power management
- baterie Li-Po
- USB-C
Fisierele gerber bom si pick and place se gasesc in manufacturing
nRF52840 este conectat la componente prin interfete de tip I2C, SPI, GPIO si SWD.

