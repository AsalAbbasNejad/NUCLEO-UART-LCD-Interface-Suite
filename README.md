#  NUCLEO UART & LCD Interface Suite

This repository contains STM32 NUCLEO embedded projects focused on UART communication, LCD display handling, and analog-to-digital conversion (ADC). These projects demonstrate both DMA-based data handling and user interface feedback via an LCD.

## Project Contents

### 1. LCD Scroll Display with UART DMA
- **Function**: 
  - Displays group members’ names on an LCD, one per line.
  - Names scroll in 1-second intervals.
- **Implementation**:
  - Uses UART with DMA for efficient data transfer.
  - LCD output scrolls dynamically in an infinite loop.
- **Learning Outcome**:
  - UART with DMA
  - LCD initialization and text control
  - Time-controlled content updates

### 2. UART-to-LCD Message Transfer + ADC Projects
- **Function**:
  - Receives a variable-length string via UART (PC → NUCLEO), then displays it on the LCD.
  - Completes additional ADC-based tasks (Projects 2b and 2c).
- **Implementation**:
  - UART character-by-character input (optionally optimized)
  - Displays full message after input
  - Demonstrates basic ADC conversion and display logic
- **Learning Outcome**:
  - UART receive logic
  - Dynamic message display
  - Basic ADC reading and usage

---

##  Technologies Used

- **Hardware**: STM32 NUCLEO Development Board, Character LCD
- **Software**: STM32CubeIDE, STM32 HAL Drivers
- **Core Concepts**:
  - UART with and without DMA
  - LCD interfacing
  - ADC input reading
  - Timer-based display logic

---

## 🚀 How to Run

1. Clone/download this repository and open projects in **STM32CubeIDE**.
2. Connect your STM32 NUCLEO board and LCD screen.
3. Build and flash the firmware for each project.
4. Test functionality:
   - Names scroll every 1 second.
   - Type from PC → UART → LCD.
   - Observe ADC readings (if applicable to display or logic).

