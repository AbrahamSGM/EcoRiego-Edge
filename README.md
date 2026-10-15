
# EcoRiego Edge

Sistema autónomo de riego inteligente con IA en el **nRF54LM20** para la optimización de recursos hídricos en la agroindustria.

## 📌 Descripción del Proyecto
EcoRiego Edge analiza la humedad del suelo y el clima local usando Inteligencia Artificial directamente en el microcontrolador para predecir la evaporación del agua y ajustar el riego automáticamente en tiempo real sin requerir conectividad Wi-Fi o internet en zonas rurales.

## 🚀 Características Clave
- **Edge AI:** Modelo predictivo local de evaporación en el nRF54LM20.
- **Autodiagnóstico Predictivo:** Detección de fallas en sensores (lecturas congeladas vs. comportamiento térmico) y cálculo de vida útil restante de batería.
- **Gestión Adaptativa de Energía:** Máquina de estados dependiente del Estado de Carga (SoC) de la batería.
- **Monitoreo BLE:** Lectura de alertas e historial mediante Bluetooth Low Energy desde una app móvil en campo.

## Lista de Materiales (BOM)
El detalle completo de componentes se encuentra en [`BOM.md`](BOM.md)[cite: 1].

## Hardware y Conexiones
Consulta los detalles y esquemáticos en la carpeta [`hardware/`](hardware/).
