# WebAR Sensor Lab

Demo técnica de las **tres APIs web** que hacen posible la realidad aumentada en navegador sin SDK propietario ni marcadores — las mismas que usan experiencias como la web AR de Kinder.

## Las tres APIs

| API | Rol | Estándar |
|-----|-----|----------|
| `MediaDevices.getUserMedia()` | Captación de vídeo de cámara | W3C Media Capture |
| `DeviceOrientationEvent` | Giroscopio / IMU (alpha, beta, gamma) | W3C DeviceOrientation |
| WebGL / Three.js | Render 3D en tiempo real | Khronos WebGL |

## Modos

- **Ficha 3D** — tarjeta técnica flotante que orbitas moviendo el móvil (mapeo IMU → rotación de escena).
- **Selfie voxel** — nube de cubos con estética de cubización, análoga al efecto Kinder.
- **Retícula** — grid técnico con telemetría del giroscopio en pantalla.

## Requisitos

- **HTTPS obligatorio**: `getUserMedia` y el permiso de sensores en iOS ≥13 exigen contexto seguro. GitHub Pages lo cumple.
- Permiso de cámara + sensores (se solicita tras pulsar *Iniciar sensores*).

## Uso educativo

Material de apoyo para los módulos **MTA** (sensores IMU, captación de señal de vídeo) y **DIG** (AR como tecnología habilitadora, estándares web) del ciclo superior de Realización de Proyectos Audiovisuales y Espectáculos.

---
CIFP Tartanga · Imagen y Sonido

