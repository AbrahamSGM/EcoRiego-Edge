
# EcoRiego Edge

Sistema autónomo de riego inteligente con IA en el **nRF54LM20** para la optimización de recursos hídricos en la agroindustria.

Con la implementación de este proyecto se busca dar una alternativa de solución al desperdicio de agua en la agricultura. Problema ocasionado por el uso de riegos genéricos que ignoran la evaporación real originada por la temperatura y la retención hídrica del suelo. A diferencia de otras soluciones existentes, que hacen uso de conexión a wifi, se presenta una propuesta que analice los datos recabados por los sensores localmente mediante la implementación de la inteligencia artificial en el borde garantizando autonomía en zonas rurales donde no existen conexiones inalámbricas como Wi-Fi maximizando el rendimiento hídrico, evita el estrés o la saturación de los cultivos y reducir costos energéticos con la implementación de una placa de desarrollo de bajo consumo como lo es la nRF54LM20 de Nordic Semiconductor.

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
