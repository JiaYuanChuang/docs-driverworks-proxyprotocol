## level closed

Integer indicating the closed level of the control surface. Default to 0. This capability is only needed if `has_level` is set and the value is other than 0. The value passed in this capability should be less than the value for `level_open`.


### Signature

`<level_closed></level_closed>`


### Example

\<capabilities\>
```
    <level_closed>true</level_closed>
</capabilities>
```