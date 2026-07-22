# Connectors and Ports

## USB Port

### USB 3.0 Micro-B Connector

The primary interface for data transfer and optional power.

**Specifications:**
- **Type:** Micro-B USB 3.0 (SuperSpeed)
- **Location:** Right side of camera body
- **Pin Configuration:** 10-pin micro-B
- **Cable Length:** 3m standard (5m available)

**Pin Assignments:**

| Pin | Function | Wire Color |
|-----|----------|------------|
| 1 | VBUS | Red |
| 2 | D- | White |
| 3 | D+ | Green |
| 4 | GND | Black |
| 5 | SSRX- | Blue |
| 6 | SSRX+ | Purple |
| 7 | GND_DRAIN | - |
| 8 | SSTX- | Orange |
| 9 | SSTX+ | Yellow |
| 10 | GND | Black |

### Data Transfer Protocol

**USB 3.0 Communication:**
- High-speed bulk transfer for image data
- Interrupt transfer for control commands
- Isochronous transfer for video streaming
- Theoretical maximum: 380 Mbps
- Practical throughput: 350-380 Mbps

**Handshake Process:**
1. Device detection and enumeration
2. Descriptor reading and validation
3. Driver loading and initialization
4. Device status verification
5. Ready for operation

## Power Input

### Micro USB Power Connector

**Specifications:**
- **Type:** Micro USB 2.0 (5.5mm × 2.1mm)
- **Voltage:** 5V DC
- **Current:** 2.0A nominal, 2.5A peak
- **Power Consumption:** 7-10W typical
- **Location:** Left side of camera body

### Power Supply Requirements

**Recommended Power Supply:**
- Input: 100-240V AC, 50-60Hz
- Output: 5V/2.5A minimum
- Efficiency: >85%
- Protections: Overcurrent, overvoltage, thermal

**USB Bus Power (Alternative):**
- 5V/500mA per USB 2.0 specification
- 5V/900mA per USB 3.0 specification
- Limited functionality with bus power only
- Recommended for testing only

### Power Connector Pinout

| Pin | Function |
|-----|----------|
| 1 | GND (Ground) |
| 2 | +5V (Positive) |
| 3 | ID (No connection) |

## Status Indicator LED

### Location and Function

**Position:** Top-front of camera body

**LED Status Codes:**

| Color | Pattern | Status | Action |
|-------|---------|--------|--------|
| Green | Solid | Connected & Ready | Normal operation |
| Green | Pulsing (1Hz) | Recording/Processing | Processing data |
| Green | Pulsing (2Hz) | Standby Mode | Camera idle |
| Blue | Blinking (0.5Hz) | Firmware Update | Do not disconnect |
| Red | Solid | Error | Check error log |
| Red | Blinking | Critical Error | Power cycle required |
| Yellow | Blinking | Thermal Warning | Reduce usage/cool down |
| Yellow | Solid | Low Power | Connect power supply |
| Purple | Pulsing | Calibration Mode | Calibration in progress |

## Audio Jack (Optional)

**Specifications:**
- **Type:** 3.5mm stereo jack
- **Function:** Auxiliary audio input (optional feature)
- **Impedance:** 32Ω - 10kΩ
- **Max Input Level:** 2V RMS

## Serial Communication (Advanced)

### RS-232 Debug Port

**Specifications (if available):**
- **Type:** 3.5mm serial connector
- **Baud Rate:** 115200 bps
- **Data Bits:** 8
- **Stop Bits:** 1
- **Parity:** None
- **Flow Control:** Hardware RTS/CTS

### Debug Commands

Common diagnostic commands via serial connection:

```
# Get device info
GET_DEVICE_INFO

# Check temperature
GET_TEMP

# Reset to factory defaults
RESET_FACTORY

# Get firmware version
GET_FIRMWARE_VERSION
```

## Network Connectivity (Optional)

### Ethernet Over USB

**When Available:**
- Gigabit Ethernet over USB 3.0
- Supports network streaming
- Remote access to camera
- Configuration via web interface

## Mechanical Mounting

### Tripod Mount

**Specifications:**
- **Thread:** 1/4"-20 UNC
- **Location:** Bottom center of camera
- **Depth:** 8mm
- **Material:** Stainless steel

### Quick Release Compatibility

- **Standard:** Arca-Swiss
- **Capacity:** Up to 2kg
- **Attachment:** Via 1/4"-20 plate

## Cable Management

### Built-in Cable Clips

- Adhesive-backed clips on camera body
- Secure USB and power cables
- Prevents cable strain
- Removable design

### Cable Organization Tips

1. Route cables along the back of the camera
2. Use cable clips to secure at 30cm intervals
3. Avoid sharp bends (minimum 25mm radius)
4. Separate power and data cables
5. Label cables with identification tags

## Connector Maintenance

### Cleaning

1. Power off camera and disconnect cables
2. Use compressed air to remove dust
3. Gently clean pins with soft brush
4. Use isopropyl alcohol for stubborn debris
5. Allow 5 minutes for drying

### Troubleshooting Connection Issues

**Poor USB Connection:**
- Inspect connector for bent pins
- Clean connector with isopropyl alcohol
- Try different USB port
- Update USB driver
- Replace USB cable

**Power Issues:**
- Verify power supply specifications
- Check cable for damage
- Test with different power adapter
- Check LED indicator for status

## See Also

- [Hardware Overview](./hardware-overview.md)
- [Technical Specifications](./technical-specifications.md)
- [Troubleshooting](./troubleshooting.md)
