# The TDS-2

The TDS-2 is the next guitar pedal in the TDS series, with an improved design and use of a standard enclosure.

The main features of the TDS-2 are the use of clipping diodes and a buffering stage, before the op-amp that amplifies the base signal. I've also used a 3PDT footswitch and some audio jacks that hold the line low when no jack is inserted, just to make sure i don't get any unecessary noise.

![3D_isometric](https://github.com/user-attachments/assets/ef86e7f6-875a-43bb-ab0c-e3dd517bfd00)

# The Schematic

![image](https://github.com/TudorSupica/TDS-2/blob/main/schematic/TDS-2.jpg)

The principle behind the TDS-2 distortion pedal is a high amplification factor. The TL072 IC has two op-amps. The first one is used as a buffer so that the imput signal is high enough. The second op-amp actually amplifies the signal, since it's in a inverting configuration to counter the phase shift of the buffer stage. 
The amplification factor is given by the potentiometer that connects the oputput back to the inverting input. The capacitors are used to decouple and "delete" any DC voltage that might be present. I used two fast switching diodes to make a clipping stage, to ensure that the signal never goes above and below the +4,5v and -4,5v headroom.

# The PCB 

![image](https://github.com/TudorSupica/TDS-2/blob/main/PCB/2D/2D_front.jpg)

The PCB also has four M3 mounting holes that are connected directly to 0v, so that when I mount it in the enclosure, the aluminium enclosure gets grounded and acts like an EMF shield.
One thing I'd improve upon are the traces since they're quite narrow and may be prone to high levels of noise.

# The Hammond 1590B enclosure

The enclosure I picked for this pedal and subsequent versions of it is the Hammond 1590B, since it's made out of aluminium it's relatively cheap and effective. The enclosure offers more of a professional look to the pedal whilst also doubling as protection against EMF and other elements.

![image](https://github.com/user-attachments/assets/0b2e4468-79c0-4179-9b62-bffd1439946f)

I used this datasheet to get the dimensions needed for the PCB, and i found that 10cm x 5cm is more than enough. 

This project is not intended for beginners, but with a little guidance it can be a successful starting project.
