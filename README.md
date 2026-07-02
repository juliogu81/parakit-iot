# Parakit IoT — Detección de Aves en Cultivos

Prototipo de un sistema de detección de aves en cultivos basado en una red de sensores acústicos.

**Autores:** Julio Gu, Bruno Lercari, Martín Núñez, Ernesto Rován  
**Tutores:** Facundo Benavides y Pablo Monzón  
**Facultad de Ingeniería, UdelaR**

---

## Repositorios

### Firmware — Nodos Sensores ESP32
Código del firmware para los nodos sensores: adquisición de audio, filtrado, inferencia del modelo de clasificación y comunicación LoRaWAN.

🔗 [github.com/jmartin166/esp-32](https://github.com/jmartin166/esp-32)

### Dataset de Audio — *Myiopsitta monachus*
Grabaciones de campo de cotorra (*Myiopsitta monachus*) y otras clases de audio utilizadas para el entrenamiento y evaluación del modelo de clasificación.

🔗 [huggingface.co/datasets/AvesIoT/myiopsitta-monachus-audios](https://huggingface.co/datasets/AvesIoT/myiopsitta-monachus-audios)
