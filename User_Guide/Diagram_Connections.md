
## MTF-02 Optical Flow
| MTF-02 | Flight Controller | Ardupilot Port |
|--------|-------------------|----------------|
| GND    | GND               |                |
| 5V     | 4V5               |                |
| RX     | TX3               | SERIAL2        |
| TX     | RX3               | SERIAL2        |

## Right Servo
| RIGHT SERVO | Flight Controller | Ardupilot Port                                                             |
|-------------|-------------------|----------------------------------------------------------------------------|
| GND         | GND               |                                                                            |
| 5V          | 4V5               |                                                                            |
| Signal      | S5                | SERVO5_FUNCTION = 75 (TiltMotorFrontRight - for both pitch and yaw control) |

## Left Servo
| LEFT SERVO | Flight Controller | Ardupilot Port                                                              |
|------------|-------------------|-----------------------------------------------------------------------------|
| GND        | GND               |                                                                             |
| 5V         | 4V5               |                                                                             |
| Signal     | S6                | SERVO6_FUNCTION = 76 (TiltMotorsFrontLeft - for both pitch and yaw control) |

## Right Motor
| RIGHT MOTOR to ESC 4 in 1  | Flight Controller | Ardupilot Port                                |
|----------------------------|-------------------|-----------------------------------------------|
| VDD                        | VDD               |                                               |
| M1                         | S1                | SERVO1_FUNCTION = 74 (Throttle right)  ESC M1 |
| GND                        | GND               |                                               |

## Left Motor
| RIGHT MOTOR to ESC 4 in 1  | Flight Controller | Ardupilot Port                                |
|----------------------------|-------------------|-----------------------------------------------|
| VDD                        | VDD               |                                               |
| M3                         | S3                | SERVO3_FUNCTION = 73 (Throttle left)  ESC M1  |
| GND                        | GND               |                                               |

## ELRS Happy Model EP1
| ELRS | Flight Controller | Ardupilot Port |
|------|-------------------|----------------|
| GND  | VDD               |                |
| VCC  | 4V5               |                |
| RX   | TX2               | SERIAL6        |
| TX   | RX2               | SERIAL6        |

## Compass
| M10 GPS | Flight Controller | Ardupilot Port |
|---------|-------------------|----------------|
| GND     | GND               |                |
| 5V      | 4V5               |                |
| RX      | TX5               | SERIAL3        |
| TX      | RX5               | SERIAL3        |
| SCL     | SCL               | SERIAL3        |
| SDA     | SDA               | SERIAL3        |

