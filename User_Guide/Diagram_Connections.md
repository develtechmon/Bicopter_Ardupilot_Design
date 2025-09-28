
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
