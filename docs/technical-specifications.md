# Technical Specifications

## Imaging Specifications

### Sensor

| Parameter | Value |
|-----------|-------|
| Sensor Type | RGB-D (Red-Green-Blue + Depth) |
| Resolution (Color) | 2048 × 1536 pixels |
| Resolution (Depth) | 2048 × 1536 pixels |
| Pixel Size | 3.45 × 3.45 μm |
| Sensor Size | 1/2.3 inch |
| Dynamic Range | 60 dB |
| SNR (Signal-to-Noise Ratio) | >40 dB |

### Optical Performance

| Parameter | Value |
|-----------|-------|
| Focal Length | 25mm equivalent |
| Aperture | f/2.8 |
| Field of View (horizontal) | 70° |
| Field of View (vertical) | 53° |
| Depth of Field | 300mm - 1500mm |
| Autofocus Range | 200mm - ∞ |
| Focus Method | Contrast-based continuous |

### Color Performance

- **Color Space:** sRGB / AdobeRGB
- **White Balance:** Automatic / Manual
- **Color Accuracy:** ΔE < 2 under standard lighting
- **Saturation:** Adjustable (80-120%)

### Depth Accuracy

| Distance | Accuracy | Precision |
|----------|----------|----------|
| 300mm | ±0.5mm | ±0.1mm |
| 500mm | ±0.8mm | ±0.2mm |
| 1000mm | ±2.0mm | ±0.5mm |
| 1500mm | ±3.5mm | ±1.0mm |

## Performance Specifications

### Frame Rate

- **Maximum Frame Rate:** 30 fps (full resolution)
- **High-Speed Mode:** 60 fps (reduced resolution 1024 × 768)
- **Burst Capture:** 300 frames at 30 fps

### Processing Speed

- **Image Processing:** <50ms per frame
- **Depth Computation:** <100ms per frame
- **Full Pipeline:** <150ms per frame

### Storage

- **Raw Image Size:** ~12 MB per frame (uncompressed)
- **Compressed Size:** ~3 MB per frame (lossless TIFF)
- **Buffer Capacity:** 512 MB internal (17 frames)

## Physical Specifications

### Dimensions

| Measurement | Value |
|-------------|-------|
| Length | 95 mm |
| Width | 85 mm |
| Height | 65 mm |
| Weight | 250 g |

### Environmental

| Parameter | Value |
|-----------|-------|
| Operating Temperature | 0°C to 40°C |
| Storage Temperature | -10°C to 50°C |
| Operating Humidity | 10-85% RH (non-condensing) |
| Storage Humidity | 5-95% RH |
| Thermal Dissipation | <5W |

### Durability

- **IP Rating:** IP54 (dust and splash resistant)
- **Vibration Resistance:** 2G peak acceleration
- **Impact Resistance:** Drop tested from 1.5m
- **Shock Resistance:** IEC 60068-2-6

## Connectivity Specifications

### USB Interface

| Parameter | Value |
|-----------|-------|
| Standard | USB 3.0 (SuperSpeed) |
| Data Rate | 380 Mbps nominal |
| Max Throughput | 400 MB/s |
| Backward Compatibility | USB 2.0 (60 Mbps) |
| Connection Type | Micro USB 3.0 |

### Power Specifications

| Parameter | Value |
|-----------|-------|
| Input Voltage | 5V DC |
| Input Current | 2.0A nominal |
| Peak Current | 2.5A |
| Power Consumption | 7-10W typical |
| Power Over USB | Supported (USB 3.0 host) |
| External Power | 5V/2A USB connector |

## Mounting Specifications

- **Tripod Mount:** 1/4"-20 UNC
- **Quick Release Plate:** Arca-Swiss compatible
- **Mounting Thread Depth:** 8mm
- **Weight Capacity:** 2kg (with compatible mount)

## Output Formats

### Image Formats

- **Color:** JPEG, PNG, TIFF, BAYER RAW
- **Depth:** Depth Map (16-bit), Point Cloud (PLY, XYZ)
- **HDR:** OpenEXR, Radiance HDR

### Video Formats

- **Video Codec:** H.264, H.265 (HEVC)
- **Container:** MP4, MOV, AVI
- **Bit Depth:** 8-bit, 10-bit

## Regulatory Compliance

- **FCC:** Part 15 Class B
- **CE:** EN 61000 series (EMC)
- **RoHS:** Compliant 2011/65/EU
- **WEEE:** Compliant
- **Safety:** UL 62368-1, EN 62368-1

## See Also

- [Hardware Overview](./hardware-overview.md)
- [Connectors and Ports](./connectors-ports.md)
- [Performance Optimization](./performance-optimization.md)
