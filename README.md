# External PIDs for Renault K9k engine parameters in Torque Pro and similar

Torque is a vehicle/car performance/diagnostics tool and scanner that uses an OBD II Bluetooth adapter to connect to your OBD2 engine management/ECU. Torque requires a file with external PIDs to support car/engine/ECU specific parameters.

PIDs itself is CSV file with the following format:

```
"Name", "ShortName", "ModeAndPID", "Equation", "Min Value", "Max Value", "Units", "OBD Header",
"Transmission Temperature(Method 3)", "Trans", "0105", "A-40", 0, 200, "C", ""
```

This repo contains PIDs for popular variants of the Renault K9k engine.

Please check your engine variant (K9k XXX) and chose suitable PIDs.

All PIDs files created with [PyRen](https://gitlab.com/py_ren/pyren) initially and then adopted manually. Authors and contributors do not take any responsibility for any possible damage to using these PIDs on your vehicle. 

## Linecnce

MIT

## Credits

[Megane Club Ukraine](https://megane-scenic.club)