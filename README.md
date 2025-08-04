# embedded-labs

Raccolta di progetti in Assembly per MSP430 sviluppati con Code Composer Studio.

---

## Progetti

### 1. Polling LED con pulsante (Asm_Dig_IO_Inputs_n_Polling_S1)
- Accende e spegne il LED P1.0 (LED1) tramite polling del pulsante P4.1 (S1).
- Utilizza delay software per rendere visibile il cambio di stato.
- File principali: `main.asm`

### 2. Gestione interrupt su P4.1 (IRQ_P4_S1)
- Toggle del LED P1.0 (LED1) usando interrupt generato dal pulsante P4.1 (S1).
- Configura pull-up e gestisce interrupt con ISR dedicata.
- File principali: `main.asm`
