## MCS8051 - AT89S8253 BASIC-52 + I2C and SFR
![MCS8051_AT89S8253 (1)](https://github.com/user-attachments/assets/d93b633e-93c2-4956-ab7e-d691c641b0a3)

![1828](https://github.com/user-attachments/assets/980f8815-3f30-42e2-ba36-439f286fb07b)

![MCS8051_AT89S8253 (3)](https://github.com/user-attachments/assets/f0f6a956-b8c3-417f-b5e2-b7cb41a8c2a8)

![MCS8051_AT89S8253 (5)](https://github.com/user-attachments/assets/0477e0ff-5935-4969-bcd8-e7d0bdc41474)



## BASIC-52 Ver 1.31
rejuvenating a popular interpreter  
by Hans-Jürgen Böhling  
on Microcontrollers  
Published in Elektor 2/2001  

The MCS BASIC–52 interpreter, developed by Intel, is still very popular, but in its 15th year it needs a thoroughgoing facelift.The MCS BASIC–52 V1.0 interpreter was specially developed by Intel in 1985 for the 8052-AH microcontroller. With its code size of only 8 kB, it fitted into the internal ROM storage of this controller. Unfortunately, the 8052-AH has gone out of production. Nonetheless, the interpreter still enjoys considerable popularity in its final ‘official’ version (1.1), in spite of a few errors. Nowadays, the 8052 family, with its many derivative versions, has become the most widely used microcontroller family. Regrettably, MCS BASIC 1.1 will not run directly on the fastest members of this family. The authors have made numerous modifications to the source code to arrive at version 1.3, with the following results:– The interpreter no longer has any known errors.– BASIC–52 V1.3 can program EEPROMs, even if they are located in external memory.– The new command ‘ERASE’ erases an EEPROM.– The maximum value for ‘XTAL’ can now be set as high as 78 MHz, so the interpreter can even run on a Dallas 80C320 at 33 MHz!– A new reset routine recognises the baud rate and various types of controllers. This means that BASIC–52 V1.3 can run on many 8052-family members (80616, 517(A), 528, 535, 537, 575 etc.).– The new OPCODE 43h reads a value from the argument stack into a variable.– The size of the interpreter is still only 8 kB, which means that it will fit into an 87C52 with 8 kB of internal EPROM.

## I2C

Implementing the I2C Bus  
New instructions for MCS-51 BASIC  
by Hans-Jürgen Böhling  
on Microcontrollers  
Published in Elektor 7/2000  
The popular but already somewhat outdated programming language MCS-51 BASIC does not have any instructions for controlling an I2C bus. Fortunately, it’s easy to add home-made instructions to this version of BASIC.More than twelve years ago, when Intel’s development engineers made their BASIC interpreter (which was actually intended for internal, experimental use) available to the general public in the form of the mask-programmed 8052-AH-BASIC microcontroller, the development of I2C communications was still in its infancy. It’s thus no surprise that no thought was given to instructions for controlling an I2C bus. Of course, it is possible to program an I2C interface using the regular instructions, since there is no minimum clock frequency specified for I2C communications.  

