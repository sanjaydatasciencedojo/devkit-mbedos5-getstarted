# Get started
This is the get started example of build a MXChip IoT DevKit App by using mbed cli.

1. Install [mbed CLI](https://github.com/ARMmbed/mbed-cli#installing-mbed-cli) if you didn't have it on your machine.

2. Clone the code:

   ```
   mbed import https://github.com/VSChina/devkit-mbedos5-getstarted
   cd devkit-mbedos5-getstarted
   ```

   Or

   ```
   git clone https://github.com/VSChina/devkit-mbedos5-getstarted
   cd devkit-mbedos5-getstarted
   mbed update
   ```

3. Compile:

   ```mbed compile -m AZ3166 -t GCC_ARM```

4. Upload to [MXChip IoT DevKit](aka.ms/iot-devkit):

   - Connect your [MXChip IoT DevKit](aka.ms/iot-devkit) with your machine via USB.
   - You can find a removable USB Mass Storage disk named **AZ3166**.
   - Copy the ```.\BUILD\AZ3166\GCC_ARM\devkit-mbedos5-getstarted.bin``` into this disk.
   - The [MXChip IoT DevKit](aka.ms/iot-devkit) will reboot after finished the copy and run the new application.



