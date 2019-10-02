# Simple Python Serial Communication Example

Serial communication using Python3.x on Canonical/Non-canonical mode.

## Requirement

* pyserial==3.4

```bash
sudo pip3 install pyserial==3.4
```

## Usage

### Serial Reader

```bash
python3 serial_reader.py --device /dev/ttyS1 --baud 38400
python3 serial_reader.py -d /dev/ttyS1 -b 38400
python3 serial_reader.py -d /dev/ttyS1 # default baud rate is set to 38400
```

### Serial Writer

```bash
python3 serial_writer.py --device /dev/ttyS1 --baud 38400 -c # canonical mode
python3 serial_writer.py -d /dev/ttyS1 -b 38400 # non-canonical mode
python3 serial_writer.py -d /dev/ttyS1 # default baud rate is set to 38400
```
