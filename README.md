# ParkED Custom Messages

This package will most likely be required by all other packages in the system.

## Supported Message types:

### Servo_Array
    uint16[] data

## Supported Actions:

### Move_Forward
    #goal         
    int64 time_in_secs
    ---
    #result
    bool successful
    ---
    #feedback
    float64 time_left