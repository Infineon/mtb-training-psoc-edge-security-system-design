# PSOC™ Edge Training - Designing a secure system

This training is part of the PSOC™ Edge security series and provides an overview of strategies
and best practices for designing secure embedded systems using PSOC™ Edge devices. 
It covers key security concepts, threat modeling, hardware and software protection mechanisms,
secure boot, encryption, and system-level design considerations.
The presentation aims to guide engineers in implementing robust security features to protect against vulnerabilities and ensure the integrity and confidentiality of embedded applications.

## Device family
- [PSOC™ Edge](https://www.infineon.com/products/microcontroller/32-bit-psoc-arm-cortex/32-bit-psoc-edge-arm)

## How to use this training?
1. Download the training [content](#content).
2. Watch the video or review the presentation at your own pace.

## Training level
- E2: Intermediate

## Pre-requisites 
### Recommended trainings
- This training doesn't cover basic concepts of ModusToolbox™ and PSOC™ Edge. 
  - For an introduction to PSOC™ MCUs, including getting started guides to ModusToolbox™, go to the [PSOC™ Developer Journey](https://www.infineon.com/psocdeveloper).
  - For PSOC™ Edge trainings, from beginner tutorials to advanced trainings, please visit the [PSOC™ Edge training collection at Infineon Academy](https://infineon-academy.csod.com/ui/lms-learner-playlist/PlaylistDetails?playlistId=8f04565f-88f4-4ca7-83b3-22e501656fbd).
- For an introduction to PSOC™ Edge Security, visit the [PSOC™ Edge Security Introduction training](https://github.com/Infineon/mtb-training-psoc-edge-security-intro).

### Tools (see [training manual](#content) for versions and installation instructions)
- [ModusToolbox™ with Eclipse IDE](https://softwaretools.infineon.com/tools/com.ifx.tb.tool.modustoolboxsetup)
- [Edge Protect Security Suite](https://softwaretools.infineon.com/tools/com.ifx.tb.tool.modustoolboxsetup)
- [ModusToolbox™ Programming tools](https://softwaretools.infineon.com/tools/com.ifx.tb.tool.modustoolboxsetup)

## Hardware
- [KIT_PSE84_EVAL](https://www.infineon.com/evaluation-board/KIT-PSE84-EVAL)

## Duration
- 1 hour

## Agenda
1. Secure design overview
2. Peripheral and memory protection controller (MPC and PPC)
3. ModusToolbox™ secure request framework (SRF)
4. Secure enclave runtime services (SERT) on EPC4 devices
5. Transition the device to production LCS
6. Re-provisioning
7. Debug ports configuration

## Expected outcome
- Understand common features and mechanisms to design secure systems using PSOC™ Edge

## Content
- [Training video at Infineon Academy](https://infineon-academy.csod.com/ui/lms-learning-details/app/video/b2ff54db-c8e4-4a97-be48-323fb88f2461)
- [Presentation](./Presentation/PSE_designing_secure_system.pdf)

## More PSOC™ Edge training
- [PSOC™ Edge E8x2/E8x3/E8x5/E8x6 training](https://github.com/Infineon/psoc-training-edge-e8x6) — Landing page with the full learning path and all PSOC™ Edge trainings, including security, graphics, voice and audio, and machine learning.
- [PSOC™ Edge training collection at Infineon Academy](https://infineon-academy.csod.com/samldefault.aspx?ouid=1&returnURL=%252fDeepLink%252fProcessRedirect.aspx%253fmodule%253dphnxdriver%2526routename%253dAdmin%252fPlayerPageRedirectHandler%2526Route%253d%25252flms-learner-playlist%25252fPlaylistDetails%2526Parameters%253dplaylistId%25253d8f04565f-88f4-4ca7-83b3-22e501656fbd) — Collection of videos for PSOC™ Edge trainings.

## References and resources
- [PSOC™ Edge MCUs](https://www.infineon.com/products/microcontroller/32-bit-psoc-arm-cortex/32-bit-psoc-edge-arm)
- [Infineon Edge Protect](https://www.infineon.com/promo/edge-protect)
- [Introduction to PSOC™ MCUs and ModusToolbox™](https://www.infineon.com/psocdeveloper)

## History 
| Date       | Version | Description             |
|------------|---------|-------------------------|
| 05/07/2026 | *A      | Update speaker notes. <br> Update formatting of some images.    |
| 02/27/2026 | **      | First public release    |