# Gripper

gripper connector/ gripper coupling 

gripper communication protocol

gripper options for xArm

gripper options that we have

## Parts in box



## Modbus
> Modbus is an industrial protocol that was developed in 1979 to make communication possible between automation devices. Originally implemented as an application-level protocol intended to transfer data over a serial layer, Modbus has expanded to include implementations over serial, TCP/IP, and the user datagram protocol (UDP)


> Modbus is a request-response protocol implemented using a master-slave relationship. In a master-slave relationship, communication always occurs in pairs—one device must initiate a request and then wait for a response—and the initiating device (the master) is responsible for initiating every interaction. Typically, the master is a human machine interface (HMI) or Supervisory Control and Data Acquisition (SCADA) system and the slave is a sensor, programmable logic controller (PLC), or programmable automation controller (PAC). The content of these requests and responses, and the network layers across which these messages are sent, are defined by the different layers of the protocol.

[Modbus Protocol Information](https://www.ni.com/en/shop/seamlessly-connect-to-third-party-devices-and-supervisory-system/the-modbus-protocol-in-depth.html)


## Modbus RS485
In order for the data exchange to happen, the host requires a medium that not only facilitates the exchange but also determines the pace.

Enter RS485.

It is basically an electrical or serial transmission standard that defines the physical level of electrical signals between the host and the slaves and also the wiring that enables the transfer of data. It is a popular standard used in data exchange as it allows the usage of several devices using the same standard on the same bus, which eliminates the need to multiply interfaces on the host while querying multiple devices.

Hence, when we say Modbus RS485, it denotes the protocol being used in process automation along with its ability to communicate effectively by the name of serial transmission standard.

## ModBus RTU
The RTU version uses a client/server technique to communicate between devices. Meaning, any application that utilizes the RTU protocol will have a client and at least one server. A client is typically a host supervisory computer running software that will communicate with one or more server devices.

Modbus enables client/server communication between devices connected through buses or networks. On the OSI Model, Modbus is positioned at Level 7. It is intended to be a request/reply protocol and delivers services specified by function codes. The function codes of the protocol are elements of its request/reply Protocol Data Unit.

## rs485


## rs485 to usb

## programming considerations


## Resources
1. https://wiki.ros.org/robotiq/Tutorials/Control%20of%20a%202-Finger%20Gripper%20using%20the%20Modbus%20RTU%20protocol%20%28ros%20kinetic%20and%20newer%20releases%29

2. https://blog.robotiq.com/controlling-the-robotiq-2f-gripper-with-modbus-commands-in-python

3. https://www.rtautomation.com/technologies/modbus-rtu/?srsltid=AfmBOopKtAbcT6BoNZfRAysM7znbaKk6KpyMX6PIy2KZvNf8QN1gJ_uZ

4. https://www.equustek.com/modbus-rs485-everything-need-know/

5. https://www.ni.com/en/shop/seamlessly-connect-to-third-party-devices-and-supervisory-system/the-modbus-protocol-in-depth.html#:~:text=Modbus%20is%20a%20request%2Dresponse,responsible%20for%20initiating%20every%20interaction.

6. https://www.sciencedirect.com/topics/engineering/end-effector