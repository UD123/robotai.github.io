# Operating Guide

## Startup Procedure

### Initial Power-On

1. **Connect Power Supply**
   - Connect 5V/2A power adapter to camera
   - LED indicator should turn on (typically red initially)
   - Wait 5-10 seconds for initialization

2. **Connect USB Cable**
   - Connect USB 3.0 cable to computer
   - Camera will begin enumeration process
   - LED indicator will change to green when ready
   - This may take 10-15 seconds on first connection

3. **Verify Connection**
   - Open RobotAI Camera software
   - Navigate to Settings > Device Manager
   - Confirm camera appears in device list
   - Status should show "Connected"

### Warm-Up Period

- Allow 2-3 minutes for sensor warm-up
- Image quality improves during warm-up
- Optimal performance after 5 minutes
- Recommended: Pre-capture warm-up before critical images

## Basic Image Capture

### Live View Mode

1. Open the **Live View** tab
2. Camera feed appears in real-time
3. Adjust position and focus
4. Monitor exposure and white balance
5. Frame your subject

### Capture Process

**Single Frame Capture:**

1. Position subject in frame
2. Verify focus (green highlight)
3. Check lighting conditions
4. Click **Capture** button or press spacebar
5. Image saves to default location
6. Preview appears in Gallery

**Continuous Capture:**

1. Set desired frame rate (1-30 fps)
2. Set capture duration
3. Click **Start Recording**
4. Camera captures frames continuously
5. Click **Stop Recording** when done
6. Video saves to file

**Burst Capture:**

1. Set burst count (1-300 frames)
2. Set frame rate
3. Click **Burst Capture**
4. Camera captures all frames
5. Frames saved as sequence

## Focus Control

### Autofocus Operation

**Continuous Autofocus:**
- Default mode
- Camera continuously adjusts focus
- Best for moving subjects
- Slightly higher power consumption

**Single Autofocus:**
- Focus locks on selected point
- Press spacebar or click AF button
- Focus remains locked until reactivated
- Lower power usage

### Manual Focus Adjustment

1. Open **Settings > Focus**
2. Disable **Autofocus**
3. Use **Focus Distance** slider
4. Adjust range: 0.3m - ∞
5. Live view updates in real-time

### Focus Lock

1. Frame subject in autofocus mode
2. Click **Lock Focus** or press L key
3. Green lock icon appears
4. Focus remains fixed until unlocked
5. Click **Unlock Focus** to resume autofocus

## Exposure and White Balance

### Exposure Control

**Automatic Exposure (AE):**
- Default mode for optimal exposure
- Adjusts shutter speed and ISO automatically
- Press A key to toggle

**Manual Exposure:**
1. Disable Auto Exposure
2. Set Shutter Speed (1/4000 - 1 sec)
3. Set ISO Sensitivity (100 - 3200)
4. Observe histogram for optimization

**Exposure Compensation:**
- Range: -2.0 to +2.0 EV
- Adjust in 1/3 EV increments
- Useful for challenging lighting

### White Balance

**Automatic White Balance (AWB):**
- Default setting
- Analyzes scene and adjusts color
- Best for mixed lighting

**Preset White Balance:**
- Daylight (5500K)
- Cloudy (6500K)
- Tungsten (3200K)
- Fluorescent (4500K)

**Manual White Balance:**
1. Place white reference card in scene
2. Click **White Balance Picker**
3. Click on white card in frame
4. Color is neutralized

## Image Quality Settings

### Resolution

**Available Options:**
- 2048 × 1536 (Full resolution, default)
- 1024 × 768 (High speed mode)
- 640 × 480 (Preview quality)

### Image Format

**Compression Options:**
- JPEG (lossy, smaller files)
- PNG (lossless, medium size)
- TIFF (lossless, large files)
- BAYER RAW (unprocessed sensor data)

### Quality Level

**JPEG Quality:**
- Range: 60-100%
- 90% recommended for quality/size balance
- 100% for maximum quality

## Recording and Playback

### Video Recording

1. Open **Video** tab
2. Select resolution and codec
3. Set frame rate (1-30 fps)
4. Click **Record** to start
5. LED indicator pulses green
6. Click **Stop** to end recording
7. Video file saves automatically

### File Management

**Default Locations:**
- Windows: `C:\Users\[Username]\Pictures\RobotAI`
- macOS: `~/Pictures/RobotAI`
- Linux: `~/Pictures/RobotAI`

**Custom Location:**
1. Settings > File Management
2. Click "Browse" to choose folder
3. Confirm selection
4. New captures save to location

### Playback

1. Open **Gallery** tab
2. Select image or video from list
3. Double-click to open
4. Navigate using arrow keys
5. Delete with Delete key

## Advanced Settings

### Sensor Settings

**Gain Control:**
- Digital gain: 0-40dB
- Analog gain: 0-20dB
- Higher gain = noisier images

**Binning Mode:**
- Off (default, full resolution)
- 2×2 (4× speed, 1/4 resolution)

### Depth Processing

1. Open **Settings > Depth**
2. Select processing quality:
   - Fast (real-time, lower accuracy)
   - Balanced (standard)
   - High Quality (slower, best accuracy)

### Profile Management

**Save Current Settings:**
1. Configure all settings
2. Click **Save Profile As...**
3. Enter profile name
4. Click **Save**

**Load Profile:**
1. Click **Profile** dropdown
2. Select saved profile
3. Settings apply instantly

## System Monitoring

### Status Display

Top status bar shows:
- Camera connection status
- Current temperature
- USB bandwidth usage
- Memory usage
- Frame rate

### Performance Metrics

**View Performance:**
1. Click **View > Performance**
2. Real-time graphs display:
   - CPU usage
   - Memory usage
   - Network bandwidth
   - Temperature

### Error Handling

**Common Issues and Messages:**
- "Camera Not Found" - Check USB connection
- "Overheating" - Reduce usage, allow cooling
- "Insufficient Memory" - Free up disk space
- "Low Power" - Connect external power supply

## Safe Shutdown

### Proper Power-Down Sequence

1. Stop any active recording
2. Close RobotAI Camera software
3. Wait for LED to stabilize
4. Disconnect USB cable
5. Disconnect power adapter
6. Store camera safely

### Emergency Shutdown

If camera becomes unresponsive:
1. Disconnect USB cable immediately
2. Disconnect power adapter
3. Wait 10 seconds
4. Reconnect power only
5. Wait for LED to turn green
6. Reconnect USB and restart software

## See Also

- [Image Capture Settings](./image-capture-settings.md)
- [Calibration Procedures](./calibration.md)
- [Troubleshooting Guide](./troubleshooting.md)
