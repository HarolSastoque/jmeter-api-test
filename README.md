# Prueba de Carga con JMeter – API pública

Este proyecto realiza una prueba de carga básica utilizando Apache JMeter sobre la API pública de [ReqRes](https://reqres.in/).

## 🔗 API bajo prueba

```
GET https://reqres.in/api/users?page=2
```

## 🎯 Objetivo

Simular múltiples usuarios accediendo a la API para analizar su rendimiento y comportamiento bajo carga mínima.

## ⚙️ Configuración del plan de prueba

- Usuarios simultáneos: 20
- Ramp-up period: 5 segundos
- Loop Count: 1
- Peticiones: GET
- Parámetros: `page=2`

## 🧪 Herramientas utilizadas

- Apache JMeter 5.x
- Listener: Summary Report y View Results Tree

## 📸 Resultados (opcional)

Puedes incluir capturas de pantalla del "Summary Report".

## ▶️ Cómo ejecutar

1. Descarga Apache JMeter: https://jmeter.apache.org/download_jmeter.cgi  
2. Abre JMeter y carga el archivo `api-load-test.jmx`
3. Ejecuta la prueba con el botón de play ▶️
4. Observa los resultados en los listeners

## 📁 Estructura del proyecto

```
jmeter-api-test/
├── api-load-test.jmx
├── capturas/
│   └── resumen.png (opcional)
└── README.md
```

## 📌 Autor

Harol Sastoque – QA Manual y Automatizado  
[Portafolio](https://harolsastoque.github.io/HarolSastoque/)
