# BlueBuzzah Partners

**Open-source vibrotactile therapy devices for Parkinson's disease symptom relief**

## Our Mission

BlueBuzzah Partners is building accessible, open-source technology to bring vibrotactile coordinated reset (vCR) therapy to patients with Parkinson's disease. Our goal is to empower individuals and caregivers to construct affordable, wireless therapy gloves based on publicly available research demonstrating the potential of this non-invasive approach.

## The Science Behind It

Research from institutions like Stanford University has shown promising results using patterned fingertip vibrations to address Parkinson's symptoms. The approach works by delivering gentle vibrations (around 250 Hz) to the fingertips, which stimulate sensory neurons connected to motor control regions of the brain. Studies have documented improvements in tremor, rigidity, balance, and movement—with some patients reporting unexpected benefits like mood stabilization and restored sense of smell.

The principle is elegant: fingertips contain dense concentrations of sensory neurons, allowing non-invasive stimulation of large brain regions without surgery or medication changes.

**Key Research References:**

- [Stanford Medicine: Vibrating Glove to Reorganize Neurons](https://stanmed.stanford.edu/vibrating-glove-reorganize-neurons-parkinsons/)
- [Vibrotactile coordinated reset stimulation for the treatment of Parkinson's disease](https://pmc.ncbi.nlm.nih.gov/articles/PMC8771098/)

## Our Projects

### [BlueBuzzah-Firmware](https://github.com/BlueBuzzah/BlueBuzzah-Firmware)

The heart of the BlueBuzzah glove system. This firmware runs on the BlueBuzzah devices and controls the vibrotactile therapy sessions.

**Features:**

- Bluetooth Low Energy (BLE) connectivity for wireless operation
- Synchronized left/right hand vibration patterns
- Configurable therapy sessions and patterns
- Low power design for extended battery life

### [BlueBuzzah-Updater](https://github.com/BlueBuzzah/BlueBuzzah-Updater)

A desktop application for managing and updating BlueBuzzah glove firmware. Simplifies the process of keeping your devices up to date without requiring technical expertise.

**Features:**

- Cross-platform desktop support
- Easy firmware updates over USB
- Device configuration and diagnostics

### [BuzzahBuddy](https://github.com/BlueBuzzah/BuzzahBuddy)

A mobile companion app for controlling and monitoring your BlueBuzzah therapy sessions from your smartphone.

**Features:**

- Bluetooth connection to BlueBuzzah gloves
- Session control and scheduling
- Progress tracking

**Coming Soon!** Visit [www.buzzahbuddy.com](https://www.buzzahbuddy.com) for updates.

## Build Your Own

The BlueBuzzah system is designed to be built by individuals with basic electronics skills. Our designs use:

- **Wireless BLE technology** to minimize bulk and eliminate cables between hands
- **Spring-based LRA buzzers** for precise, localized fingertip vibrations
- **Open-source hardware and software** with comprehensive documentation

## License

Most BlueBuzzah projects are released under the [MIT License](https://opensource.org/licenses/MIT), promoting open collaboration and accessibility.

## Medical Disclaimer

**BlueBuzzah devices have not been evaluated or approved by the FDA or any other regulatory body.**

This technology is provided for informational and experimental purposes only. It is **not** a medical device and should **not** be used as a substitute for professional medical advice, diagnosis, or treatment.

- Always consult with your physician before using vibrotactile therapy
- Never adjust medications without medical supervision
- Individual results vary significantly; what works for one person may not work for another
- This project is inspired by publicly available research but is not affiliated with or endorsed by Stanford University, Tass Lab, or any medical institution

**Use at your own risk.** The BlueBuzzah Partners community provides these designs in good faith but cannot guarantee safety, efficacy, or suitability for any individual's medical condition.
