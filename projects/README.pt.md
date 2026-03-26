# Projetos

Esta pasta contém projetos práticos de FPGA, desde o básico blink LED até implementações avançadas como processadores softcore RISC-V.

---

## Lista de Projetos

| Projeto | Dificuldade | Descrição |
|---------|-------------|-----------|
| [Toggle LED](./Toggle_led/) | Iniciante | Sistema de controle ON/OFF via botão com debounce e toggle |

---

## Toggle LED

**Sistema de controle ON/OFF via botão com debounce e toggle em FPGA**

![Demonstração Toggle LED](./Toggle_led/Assets/running.gif)

Um botão físico alterna o estado de 6 LEDs entre ligado e desligado. Demonstra conceitos fundamentais de design digital síncrono incluindo sincronização de sinais externos, debounce de chave mecânica e lógica de toggle em Verilog.

**Conceitos Chave:**
- Design de clock síncrono
- Debounce de chave mecânica (~5.4ms)
- Detecção de borda de descida
- Lógica de toggle bit a bit

**Hardware:** Tang Nano 9K (Gowin GW1NR-9C)

**Localização:** [./Toggle_led/](./Toggle_led/)

---

*Mais projetos em breve!*
