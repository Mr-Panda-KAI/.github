# Mr Panda KAI 🐼

**Tu Asistente Financiero con IA para Web3**

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](package.json)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/tu-organizacion/mr-panda-kai)

## 🌟 Descripción

**Mr Panda KAI** es un chatbot inteligente que revoluciona la experiencia financiera en Web3. Combina la simplicidad de una conversación natural con la seguridad y el poder de la tecnología blockchain, eliminando las barreras técnicas que tradicionalmente han dificultado la adopción masiva de las finanzas descentralizadas.

## ✨ Características Principales

### 🗣️ Transacciones Conversacionales
- Envía y recibe activos digitales usando lenguaje natural
- Elimina la necesidad de copiar direcciones de wallet complejas
- Comandos simples como "Envía 50 USDC a María"

### 👥 Gestión Inteligente de Contactos
- Registra contactos con nombres fáciles de recordar
- Asocia automáticamente nombres con direcciones de wallet
- Pagos tan simples como enviar un mensaje

### 📊 Historial y Monitoreo
- Consulta tu historial de transacciones on-chain
- Visualiza balances en tiempo real
- Seguimiento completo de todas las operaciones

### 🔗 Integración Web3 Nativa
- Conexión directa con MetaMask
- Soporte para múltiples redes blockchain
- Interacción segura con smart contracts

## 🛠️ Stack Tecnológico

- **Smart Contracts:** Solidity
- **Frontend:** React, JavaScript
- **Inteligencia Artificial:** Deepseek
- **Web3:** MetaMask, Web3.js/Ethers.js
- **Blockchain:** Ethereum, Polygon (y otras redes compatibles)

## 🚀 Inicio Rápido

### Prerrequisitos

```bash
# Node.js (v16 o superior)
node --version

# npm o yarn
npm --version
```

### Instalación

```bash
# Clonar el repositorio
git clone https://github.com/tu-organizacion/mr-panda-kai.git

# Navegar al directorio
cd mr-panda-kai

# Instalar dependencias
npm install

# Configurar variables de entorno
cp .env.example .env
```

### Configuración

1. Configura las variables de entorno en `.env`:
```env
REACT_APP_DEEPSEEK_API_KEY=tu_clave_deepseek
REACT_APP_INFURA_PROJECT_ID=tu_proyecto_infura
REACT_APP_CONTRACT_ADDRESS=direccion_del_contrato
```

2. Inicia el servidor de desarrollo:
```bash
npm start
```

3. Abre [http://localhost:3000](http://localhost:3000) en tu navegador

## 📖 Uso

### Comandos Básicos

```
💬 "Hola Mr Panda, ¿cuál es mi balance?"
💬 "Envía 100 USDC a Juan"
💬 "Agrega el contacto María con dirección 0x..."
💬 "Muéstrame mis últimas 5 transacciones"
💬 "¿Cuánto ETH tengo?"
```

### Gestión de Contactos

```
💬 "Registra a Pedro: 0x1234...abcd"
💬 "Envía 50 DAI a Pedro"
💬 "¿Cuál es la dirección de María?"
```

## 🏗️ Arquitectura

```
mr-panda-kai/
├── src/
│   ├── components/          # Componentes React
│   ├── contracts/          # ABIs y configuraciones de contratos
│   ├── hooks/              # Custom hooks para Web3
│   ├── services/           # Servicios de API y blockchain
│   ├── utils/              # Utilidades y helpers
│   └── ai/                 # Integración con Deepseek
├── contracts/              # Smart contracts en Solidity
├── public/                 # Archivos públicos
└── docs/                   # Documentación adicional
```

## 🔐 Seguridad

- **Nunca almacenamos claves privadas**
- **Todas las transacciones requieren confirmación del usuario**
- **Conexión segura a través de MetaMask**
- **Smart contracts auditados**

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/nueva-caracteristica`)
3. Commit tus cambios (`git commit -m 'Agrega nueva característica'`)
4. Push a la rama (`git push origin feature/nueva-caracteristica`)
5. Abre un Pull Request

## 📝 Roadmap

- [ ] **Q1 2024**
  - [x] MVP con funcionalidades básicas
  - [ ] Soporte para múltiples tokens
  - [ ] Integración con más wallets
  
- [ ] **Q2 2024**
  - [ ] Análisis predictivo con IA
  - [ ] Notificaciones inteligentes
  - [ ] App móvil

- [ ] **Q3 2024**
  - [ ] Integración con DEXs
  - [ ] Funciones DeFi avanzadas
  - [ ] Staking automático

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 🆘 Soporte

- **Documentación:** [docs/](./docs/)
- **Issues:** [GitHub Issues](https://github.com/tu-organizacion/mr-panda-kai/issues)
- **Discord:** [Únete a nuestra comunidad](https://discord.gg/tu-server)
- **Email:** soporte@mrpandakai.com

## 🙏 Agradecimientos

- Al equipo de Deepseek por su excelente API de IA
- A la comunidad de desarrolladores Web3
- A todos nuestros early adopters y testers

---

**Hecho con ❤️ por el equipo de Mr Panda KAI**

*"Simplificando Web3, una conversación a la vez"* 🐼✨
