### Q\_ActiveMask

![image](https://user-images.githubusercontent.com/69573151/212328886-4d5587f1-b2cd-4e8a-9cbe-0aa55ca1abcf.png)

ISO 11783-6

Command change active mask( Part 6 - F.34 )

This command is used to change the active mask of a working set to either a data or an alarm mask object.

Return values

iso\_s16

*   E\_NO\_ERR ( 0 ) - OK
*   E\_OVERFLOW (-6 ) - buffer overflow
*   E\_NOACT (-8 ) - Command not possible in current state
*   E\_NO\_INSTANCE (-21) - No VT client available
