# Política de Privacidad - Kambio

**Última actualización:** 26 de septiembre de 2026

En **Kambio**, la privacidad de nuestros usuarios es una prioridad. Debido a la naturaleza técnica y simplificada de la aplicación, esta política es directa y transparente.

## 1. Recopilación de Información
**Kambio** es una herramienta de consulta que **no recopila, no almacena ni transmite** ningún tipo de información personal identificable (PII).
* No solicitamos registros, cuentas de usuario ni acceso a datos de redes sociales.
* No rastreamos el comportamiento del usuario ni utilizamos servicios de analítica.
* Las preferencias que configuras dentro de la app (moneda, tasa personal) se guardan **únicamente en tu dispositivo** y nunca se envían al desarrollador.

## 2. Permisos del Sistema
Para cumplir con su función principal, la aplicación requiere:
* **Internet:** para consultar las tasas de cambio desde la infraestructura en la nube del desarrollador.
* **Notificaciones (Android 13+):** opcionales, para recibir avisos cuando se publica una nueva tasa.

## 3. Origen de los Datos y Uso
Las tasas mostradas son datos públicos obtenidos por el desarrollador de fuentes oficiales y de mercado: el **Banco Central de Venezuela** (USD/VES) y el mercado **P2P de Binance** (USDT). La consulta a esas fuentes la realiza la infraestructura del desarrollador — nunca tu dispositivo — y publica los resultados en una base de datos en la nube de la que la aplicación los lee. La app muestra las tasas con fines informativos en su interfaz y su widget.

## 4. Servicios de Terceros
La aplicación utiliza servicios de infraestructura de **Google (Firebase)** para funcionar:
* **Cloud Firestore y Remote Config:** para leer las tasas y la configuración de la app. Estas consultas no incluyen datos personales.
* **Firebase Cloud Messaging:** para las notificaciones de tasas. Google gestiona un identificador anónimo de la instalación (token) necesario para entregarlas; no está asociado a datos personales y puedes revocarlas desde el sistema.

En su versión actual, **Kambio** no integra redes publicitarias (Ads), analítica ni reportes automáticos de errores.

## 5. Seguridad
Todas las conexiones se realizan mediante protocolos estándar (HTTPS/TLS) hacia los servicios de Google Cloud/Firebase, para garantizar que la información mostrada sea fidedigna y no sea interceptada durante la transmisión.

## 6. Menores de Edad
Al no recopilar ningún tipo de dato personal, la aplicación es segura para usuarios de todas las edades.

## 7. Cambios en esta Política
Nos reservamos el derecho de actualizar esta política si se añaden funcionalidades que requieran nuevos permisos o servicios de terceros (p. ej., reportes de errores o publicidad). Cualquier cambio será reflejado en este documento con una nueva fecha de actualización.

## 8. Contacto
Si tiene alguna duda sobre esta política, puede ponerse en contacto con el desarrollador a través de la tienda de aplicaciones o al correo de soporte proporcionado en la ficha de Google Play Store.
