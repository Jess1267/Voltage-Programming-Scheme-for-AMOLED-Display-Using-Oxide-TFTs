# Voltage-Programming-Scheme-for-AMOLED-Display-Using-Oxide-TFTs

## Abstract
This repository proposes a novel pixel architecture for Active Matrix Organic Light Emitting Diode (AMOLED) displays, aimed at reducing settling and programming times to meet the demands of Ultra-High Definition (UHD) displays. By utilizing a voltage programming scheme and reducing the number of Thin Film Transistors (TFTs) used, the proposed design overcomes the limitations of traditional circuits, such as low aperture ratio, threshold voltage variation, and mobility degradation in oxide TFTs. Simulations of the proposed circuit demonstrate improved performance in aperture ratio and luminance uniformity.

## Introduction
AMOLED displays rely on pixel driver circuits that address brightness uniformity, threshold voltage variation, and mobility degradation. Traditional designs, such as the 2T1C circuit, suffer from limitations in aperture ratio and resolution due to threshold voltage and current-resistance effects. Recent advancements, including hybrid current-biased voltage-programmed methods, attempt to mitigate these issues but increase circuit complexity. This study aims to design a simplified pixel driver circuit with fewer transistors, improving efficiency, refresh rates, and power utilization.

### Research Gap
Existing pixel circuits face the following challenges:

-**2T1C Pixel Circuit:** Brightness uniformity deteriorates due to threshold voltage variations and IR voltage drops.
-**5T2C Pixel Circuit:** While effective in compensating for non-idealities, the complexity reduces the aperture ratio and increases design overhead.
-**Hybrid Designs:** Current-biased voltage programming methods improve uniformity but require long programming times and complex configurations.

This study focuses on reducing transistor count while maintaining performance, addressing the limitations of existing designs.

## Proposed Architecture
### Design Overview
The proposed 4T2C pixel circuit reduces one transistor compared to the 5T2C circuit, which simplifies the design and enhances the aperture ratio. The circuit transitions through three operational phases:

-Threshold Voltage Detection Phase: Detects and compensates for Vth variations.
-Data Input Phase: Programs the data voltage.
-Emission Phase: Ensures steady luminance output during display operation.

### Key Changes
-Replacement of constant Vref with a pulse signal for dynamic compensation.
-Simplification of transistor count to improve aperture ratio and reduce complexity.
