# System Requirements

## Minimum Requirements

### Computer Specifications

**Operating System:**
- Windows 10 or later (64-bit)
- macOS 10.14 or later
- Ubuntu 18.04 LTS or later (64-bit)

**Processor:**
- Intel Core i5 (6th Generation) or equivalent AMD processor
- Minimum 2.0 GHz clock speed
- 2 cores minimum

**Memory:**
- 8 GB RAM minimum
- 16 GB RAM recommended for optimal performance

**Storage:**
- 500 MB available disk space for software installation
- 10 GB additional space recommended for image storage
- SSD strongly recommended for faster processing

**Display:**
- 1920 × 1080 resolution minimum
- 1920 × 1200 or higher recommended
- 24-bit color display

### USB Requirements

**USB 3.0 Host Controller:**
- USB 3.0 or USB 3.1 port recommended
- Dedicated USB 3.0 controller (not shared hub)
- High-speed external hub with dedicated power supply supported

**Power Requirements:**
- 5V/2A external power supply
- Or USB bus power (limited functionality)

## Recommended Configuration

### Professional Setup

**Processor:**
- Intel Core i7 (8th Generation or newer)
- Or AMD Ryzen 5 (2000 series or newer)

**Memory:**
- 32 GB RAM for multi-camera systems
- DDR4 or faster

**Storage:**
- NVMe SSD (1TB or larger)
- Secondary storage for backup
- RAID configuration for critical applications

**Display:**
- Multi-monitor setup (2-4 monitors)
- 4K resolution (3840 × 2160) for detailed inspection
- Color-calibrated professional monitor

### Network Requirements

- Gigabit Ethernet for network features
- WiFi 5 (802.11ac) or better for wireless connectivity
- Network bandwidth: 100 Mbps minimum

## Software Dependencies

### Required

- .NET Framework 4.8 or later (Windows)
- Visual C++ Runtime 2019 or later
- OpenGL 4.5 compatible graphics driver

### Optional but Recommended

- Python 3.7+ (for scripting)
- MATLAB R2019a or later (for advanced processing)
- OpenCV 4.0+ (for custom applications)

## GPU Acceleration

The software supports GPU acceleration for improved performance:

**NVIDIA GPUs:**
- CUDA Compute Capability 6.1 or higher
- NVIDIA Driver 450 or later
- Examples: GeForce GTX 1060, RTX 2080, etc.

**AMD GPUs:**
- RDNA architecture or newer
- AMD Radeon Pro drivers

**Intel GPUs:**
- Intel UHD Graphics 630 or newer
- Intel Graphics drivers up to date

## Compatibility

### Verified Operating Systems

- Windows 10 Build 1909+
- Windows 11
- macOS 10.14 (Mojave) through 13.x (Ventura)
- Ubuntu 20.04 LTS
- CentOS 8.x

### Virtual Machine Support

- VMware ESXi 7.0+
- Hyper-V (Windows 10/11)
- KVM (Linux)
- VirtualBox 6.1+ (with USB 3.0 support enabled)

**Note:** Virtual machine performance may be limited compared to native installation.

## Connectivity Verification

Before installation, verify your system:

1. Check USB 3.0 controller in Device Manager
2. Verify sufficient disk space
3. Test USB port with another USB 3.0 device
4. Confirm network connectivity if required

## See Also

- [Installation Guide](./installation.md)
- [Getting Started](./getting-started.md)
- [Troubleshooting](./troubleshooting.md)
