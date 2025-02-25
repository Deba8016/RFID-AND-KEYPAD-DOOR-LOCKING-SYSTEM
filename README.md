# RFID and Keypad Door Locking System

## Brief Description
This project implements an RFID and Keypad-based door locking system using Arduino. The system grants access if a recognized RFID card is scanned or if a correct password is entered on the keypad. The door lock is controlled using a relay.

## Components Used
- Arduino Board
- RFID Module (MFRC522)
- Keypad (4x4 Matrix)
- Relay Module
- Servo Motor (for Locking Mechanism)
- LEDs (for status indication)
- Buzzer (optional for sound alerts)
- Power Supply

## Features
- Dual authentication (RFID Card and Keypad Password)
- Secure access control system
- Status indicators (LEDs for authorized/denied access)
- Reset functionality for security enforcement
- Serial output for debugging and monitoring

## Use Cases
1. **Home Security**: Ensures only authorized individuals can unlock the door.
2. **Office Access Control**: Restricts access to specific personnel.
3. **Storage Room Security**: Protects valuable inventory and sensitive documents.
4. **Smart Home Integration**: Can be connected to a home automation system for enhanced security.

## How It Works
1. The system continuously checks for an RFID card scan.
2. If a recognized card is detected, the lock opens temporarily.
3. If an RFID card is not present, the system waits for a keypad password entry.
4. If the correct password is entered, the lock opens.
5. Unauthorized attempts trigger access denial with LED indicators.
6. After a successful unlock, the system resets for the next authentication cycle.

