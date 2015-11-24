# SerialComm Monitor v1 Source Code

**SerialComm Monitor** is a serial communication application based on `SerialPort` class, built in C# WPF with MVVM design pattern to send (write) or receive (read) data string from a serial communication physical interface.

![Screenshot](http://i.imgur.com/FSliKIX.png)

## Prerequisites

- [Visual Studio IDE](https://www.visualstudio.com/en-us/downloads/download-visual-studio-vs.aspx) (2013 and above)
- [Microsoft .NET Framework 4.5 (x86 and x64)](https://www.microsoft.com/en-us/download/details.aspx?id=30653)

## Dependencies

- [NLog](http://nlog-project.org/)

## Features

- Available serial port settings
  - Selectable COM* ports
  - Selectable baud rates
  - Selectable parities
  - Selectable data bits
  - Selectable stop bits
  - Enable/disable Data Termina Ready (DTR)
  - Enable/disable Request To Send (RTS)
- Send (write) data string to serial port
- Receive or monitor (read) data sent from serial port
- Line ending options
- Autoscroll output box
- Metro-like application skin

## TODO

- [ ] Auto populate COM* ports on refresh button
- [ ] Ability to save output data into a text file
- [ ] Add more settings; Handshake, CTS and DSR
- [ ] Ability to send data within interval time set

## License

Released under [MIT license](LICENSE.md)




