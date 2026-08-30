<!-- ==================== DYNAMIC HEADER ==================== -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20,24,30&height=220&section=header&text=LE%20DUC%20TUNG&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Embedded%20Systems%20%E2%80%A2%20Firmware%20Architecture%20%E2%80%A2%20Hardware%20Design&descAlignY=58&descAlign=50" width="100%"/>

  <a href="https://github.com/Dtung24">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&duration=2400&pause=1000&color=00F5D4&center=true&vCenter=true&width=700&lines=Bare-Metal+Firmware+%26+HAL%2FLL+Driver+Development;FreeRTOS+%26+Zephyr+Multithreaded+Systems;Custom+PCB+Design+(Altium+Designer)+%26+Hardware+Integration;Signal+Processing+(Kalman+Filter)+%26+Sensor+Fusion;Edge+AI%2C+Adaptive+Beamforming+%26+Wireless+Telemetry" alt="Typing SVG" />
  </a>

  <br/>

  <p align="center">
    <img src="https://komarev.com/ghpvc/?username=Dtung24&label=PROFILE+VIEWS&style=for-the-badge&color=7928CA" alt="Profile Views"/>
    <img src="https://img.shields.io/badge/STATUS-DESIGNING%20%26%20BUILDING-00F5D4?style=for-the-badge&logoColor=black" alt="Status"/>
    <img src="https://img.shields.io/badge/EXPERTISE-HARDWARE%20%2B%20FIRMWARE-FF007F?style=for-the-badge" alt="Expertise"/>
  </p>
</div>

---

## ⚡ System Telemetry & Quick Snapshot

```c
/**
 * @file    engineer_profile.c
 * @author  Le Duc Tung (@Dtung24)
 * @brief   System core configuration and technical parameters
 */
typedef struct {
    const char* role           = "Embedded Systems & Hardware Engineer";
    const char* core_stack[]   = { "C/C++", "FreeRTOS", "STM32 HAL/LL", "Altium Designer" };
    const char* architectures[]= { "ARM Cortex-M (M3/M4/M7)", "Espressif (ESP32/ESP32-S3)", "RISC-V" };
    const char* protocols[]    = { "UART", "SPI", "I2C", "CAN Bus", "Cellular LTE", "BLE/Wi-Fi" };
    bool        dma_zero_copy  = true;
    bool        hard_realtime  = true;
    uint32_t    current_focus  = ADAPTIVE_BEAMFORMING | EDGE_TINYML | HIGH_SPEED_PCB;
} SystemProfile_t;
