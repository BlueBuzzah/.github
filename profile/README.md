# BlueBuzzah Partners

**An open-source research project: vibrotactile stimulation gloves you build yourself**

## What we do

BlueBuzzah Partners is a group of volunteers. We publish open hardware designs, firmware, apps and documentation for a pair of wireless gloves that deliver patterned vibration to the fingertips, inspired by published research on vibrotactile coordinated reset (vCR) stimulation in Parkinson's disease. We do not make, sell or ship devices. Anyone who wants a pair buys the parts and builds it with the guide at [bluebuzzah.com](https://bluebuzzah.com).

## The research

Published studies have explored patterned fingertip vibration, around 250 Hz, delivered in coordinated reset sequences, with participants who have Parkinson's disease. Those studies used their own devices and protocols under medical supervision. BlueBuzzah is an independent open design and does not claim the same results.

- [Vibrotactile coordinated reset stimulation for the treatment of Parkinson's disease](https://pmc.ncbi.nlm.nih.gov/articles/PMC8771098/)
- [Coordinated reset vibrotactile stimulation induces sustained cumulative benefits in Parkinson's disease](https://pmc.ncbi.nlm.nih.gov/articles/PMC8055937/)
- [Stanford Medicine: Vibrating glove to reorganize neurons](https://stanmed.stanford.edu/vibrating-glove-reorganize-neurons-parkinsons/)

## Our projects

### [BlueBuzzah-Hardware](https://github.com/BlueBuzzah/BlueBuzzah-Hardware)

The glove itself: PCB, parts list, 3D-printed case and tactor parts, and the build guide's source material.

### [BlueBuzzah-Firmware](https://github.com/BlueBuzzah/BlueBuzzah-Firmware)

Runs on the gloves and controls the stimulation sessions.

- Bluetooth Low Energy (BLE) connectivity, no cables between the gloves
- Synchronized patterns across the primary and secondary glove
- Configurable session profiles and patterns
- Low power design for long battery life

### [BlueBuzzah-Updater](https://github.com/BlueBuzzah/BlueBuzzah-Updater)

A desktop app for installing firmware and setting up the gloves over USB, on macOS and Windows.

### [BuzzahBuddy](https://github.com/BlueBuzzah/BuzzahBuddy)

The companion app for iPhone, iPad and Android: start and stop sessions, adjust settings, and look back at your history, over Bluetooth.

Coming soon. Visit [buzzahbuddy.com](https://buzzahbuddy.com) for updates.

## Build your own

The gloves are designed to be built by people with basic electronics skills:

- Wireless BLE between the gloves, so there are no cables between your hands
- Spring-mounted LRA motors for precise, localized fingertip vibration
- Open-source hardware and software with a step-by-step build guide

## License

- Code (the firmware, the apps, scripts and website code): [MIT](https://opensource.org/licenses/MIT)
- Board designs: [CERN-OHL-S v2](https://ohwr.org/cern_ohl_s_v2.txt)
- 3D models, guides, docs and website content: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

Each repository carries its license files and says which parts each license covers.

The BlueBuzzah and BuzzahBuddy names and logos are not covered by these licenses. See [Licenses and the BlueBuzzah name](https://bluebuzzah.com/terms#licenses).

## Important notices

BlueBuzzah devices are not FDA cleared or approved medical devices and not intended to diagnose, treat, cure, mitigate, or prevent any disease. The information provided through BlueBuzzah is for general wellness purposes only and not a substitute for professional medical advice, diagnosis, or treatment.

**Important:** People with implanted electrodes from deep brain stimulation (DBS), heart pacemakers, or other internal electronic devices should take special precautions around all electronic devices, including BlueBuzzah. Consult your physician before use.

Read the [terms and safety](https://bluebuzzah.com/terms) page before you build or wear a pair, and the [privacy policy](https://bluebuzzah.com/privacy) for what the apps do with your data.
