## POOL HEATMODE LIST CHANGED

Sent to the proxy to indicate that the pool heat mode list has changed.


### Signature

`C4:POOL_HEATMODE_LIST_CHANGED ()`


| Parameter | Description |
| --- | --- |
| `XML` | `POOL_HEATMODE.` |


### Returns

`None`


### Example

```
<pool_heat_modes>
    <mode>
        <id>1</id>
        <text>Heater</text>
        <command>set_pool_heater</command>
    </mode>
    <mode>
        <id>2</id>
        <text>Solar Heater</text>
        <command>set_solar_heater</command>
    </mode>
</pool_heat_modes>
```