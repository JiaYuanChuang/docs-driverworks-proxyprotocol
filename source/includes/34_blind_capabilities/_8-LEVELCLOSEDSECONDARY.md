## level closed secondary

Integer indicating how far past open `(level_open`) the blind can go to a second closed state.   No default value exists for this capability and drivers should not include `level_closed_secondary` if a secondary closed position does not exist.

An example case is a full range louver with 11 positions (0% to 100% with 10% resolution) that has `level_closed` of 0, `level_open` of 5, and a `level_close_secondary` of 5, giving the full close-open-close range of 0 to 10.  It should be noted that a generic "Close" UI or Composer Programming commands will send the `level_closed` value for "Close".  No default value exists for this capability and drivers should not include `level_closed_secondary` if a secondary closed position does not exist.


### Signature

`<level_closed_secondary></level_closed_secondary>`


### Example

```
<capabilities>
    <level_closed_secondary>11</level_closed_secondary>
</capabilities>
```