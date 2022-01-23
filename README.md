# Update 2022-01-22

I had to shut down the Demo server because someone is using it to mine bitcoins. (by default, jupyter will allow anyone to create a terminal and there's no way to disable it easily.) If anyone is interested in setting it up locally, I'm glad to help.


# iSwift

[![Build Status](https://travis-ci.org/KelvinJin/iSwift.svg?branch=master)](https://travis-ci.org/KelvinJin/iSwift)

iSwift is the kernel IPython/Notebook implementation for Swift programming language.

It can:
  + Execute swift code on the Jupyter Notebook web editor, Jupyter console as well as Jupyter qtconsole.
  + Import Foundatation/Dispatch and other Buildin libraries.
  + Autocomplete swift code by pressing tab ↹.
  + Support encryption.
  + Support Linux/macOS

## Requirements

  + macOS/Linux
  + Swift 3.0
  + ZMQ
  + Jupyter 5.0

## Docker Installation

Simply clone this repo and run `docker build -t iswift .`. It will build the docker image.

## Docker Run
```
sudo docker run -t -i -p 8888:8888 --privileged iswift
```
## Author

[Jin Wang](https://twitter.com/jinw1990)

## Customization
[Cristian Cardoso] 

## Contribution

Contributions are welcome. Simply create an issue if you have ideas on how we
can improve iSwift.

## License
MIT
