
# Memory Map

| Start | End | Description |
| ----------- | ----------- | ----------- |
| $0000 | $01FF | Internal RAM (256K bytes)  |
| $1000 | $105F | Internal peripherals mapped |
| $1800 | $1FFF | External peripherals I|
| $2000 | $7FFF | External user RAM |
| $8000 | $FFFF | External EPROM |

The proocessor has 16 address bits a15 - a0

0000 0000 0000 0000


## Address Decode Logic

Here is the High Level Address Decoder logic based on the original Buffalo Monitor ROM Specification.
