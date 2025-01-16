# Molecular-communication-dataset
This is a dataset collected by a molecular communication experimental platform.
![图片](https://github.com/user-attachments/assets/cefe894d-9214-43ff-8aa8-59a07aad925c)
This platform is composed of the transmitter, the communication channel, and the receiver. 

At the transmitter side, two chemical solutions (acids and bases), representing bit-0 and bit-1 respectively, are injected repeatedly into the “communication channel” using two peristaltic pumps (Pump-1 for acids and Pump-2 for bases).

The communication channel is made up of multiple silicon tubes, which are filled with fresh water continuously injected by another peristaltic pump (Pump-3). Thus, acids, bases, and the freshwater are mixed together to simulate a binary digital communication system subject to severe ISI and noise.

At the receiver, a pH electrode is placed in a flow-through cell to sample the pH values of the liquid, which are then sent to a computer and stored as the received signal sequence. To create the dataset, 1000 sequences with each having 100 bits are transmitted. Thus, the total amount of collected data is 100000 bits.
