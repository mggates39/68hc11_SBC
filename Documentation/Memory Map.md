
# Memory Map

| Start | End | Description |
| ----------- | ----------- | ----------- |
| $0000 | $01FF | Internal RAM (256K bytes) |
| $0100 | $0FFF | External User RAM (part of 32K RAM) |
| $1000 | $103F | Internal peripherals mapped (64 bytes) |
| $1040 | $7FFF | External User RAM (rest of 32K RAM) |
| $8000 | $9FFF | External EPROM 8K Extra ROM |
| $A000 | $AFFF | External I/O |
| $B000 | $BFFF | Reserved |
| $C000 | $DFFF | External EPROM 8K Spare ROM |
| $E900 | $FFFF | External EPROM 8K Boot ROM |

The proocessor has 16 address bits a15 - a0

0000 0000 0000 0000


## Address Decode Logic

Here is the High Level Address Decoder logic based on the original Buffalo Monitor ROM Specification.
