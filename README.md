                                  # AsistenciasApp 
Una solución digital para modernizar el registro de asistencia en instituciones educativas.  
AsistenciasApp transforma el proceso manual de pase de lista en una tarea eficiente, rápida y confiable. 
Utilizando tecnología móvil accesible, elimina el desperdicio de tiempo en las aulas (que suele costar entre 15 y 20 minutos por clase) y reduce drásticamente los errores humanos y la pérdida de información en registros físicos. 
Desarrollada con un stack moderno y eficiente basado en Flutter y Dart , la aplicación ofrece un sistema híbrido único:
  | Funciona de manera local e independiente de internet mediante SQLite 
  | Se sincroniza en la nube en tiempo real mediante Firebase para garantizar la seguridad de los datos 
  | La autenticación de usuarios y el respaldo institucional.  
                    🚀 Características Principales
  | Múltiples métodos de registro: Escaneo directo con la cámara 
  | Carga de capturas/imágenes de códigos QR desde la galería, y un sistema de respaldo para registro manual en casos excepcionales. 
  | Gestión de datos avanzada (Novedad 2025): Apartado con historial diario e histórico diferenciado por fecha y hora , listado ordenado alfabéticamente y barra de búsqueda integrada.  
  | Base de datos diferenciada: Arquitectura limpia que separa el contenido del usuario institucional; permite borrar registros de asistencia sin eliminar la cuenta del usuario de la institución. 
  | Seguridad robusta: Autenticación obligatoria mediante correo y contraseña vinculada a Firebase.  
  | Alto rendimiento: Interfaz fluida optimizada a 60fps con bajo consumo de memoria RAM y batería.  
  | Innovación en desarrollo: Integración activa en pruebas de Reconocimiento Facial mediante Google ML Kit como alternativa de registro sin contacto. 
                        📱 Guía de Instalación   
  (Paso a Paso en Android)Para instalar AsistenciasApp en tu dispositivo móvil utilizando el archivo ejecutable compilado (APK), sigue estos sencillos pasos:   
  Paso 1: Preparar el dispositivo (Permitir Fuentes Desconocidas)Debido a que el archivo se instala por fuera de la tienda oficial de Google Play Store, Android requiere una autorización de seguridad.
  Abre los Ajustes o Configuración de tu teléfono.Dirígete a Seguridad (o Privacidad / Protección de aplicaciones según tu marca de dispositivo).
  Busca la opción Instalar aplicaciones desconocidas (o Fuentes desconocidas).Selecciona la aplicación que usarás para abrir el archivo (por ejemplo, tu navegador Google Chrome o el Administrador de Archivos) y activa el interruptor de Permitir desde esta fuente.
  Paso 2: Descargar y transferir el APKDescarga el archivo AsistenciasApp.apk provisto por el equipo de desarrollo directamente en tu teléfono, o transfiérelo desde una computadora mediante cable USB.  
  Paso 3: Ejecutar la instalaciónAbre el Administrador de Archivos o la carpeta de Descargas de tu dispositivo.Presiona sobre el archivo AsistenciasApp.apk.Aparecerá una ventana flotante preguntando si deseas instalar la aplicación. 
  Presiona Instalar. Espera unos segundos a que finalice la barra de progreso. Si el sistema de protección integrado de Android (Play Protect) te muestra una advertencia, selecciona Instalar de todas formas.Una vez concluido, presiona Abrir o busca el ícono de la app en tu menú principal.
                      🛠️ Guía de Funcionamiento
  Dentro de la AppUna vez abierta la aplicación, el flujo de trabajo está diseñado para ser intuitivo y no requiere capacitación extensiva:    
  | 1. Autenticación de UsuarioAl ingresar por primera vez, te encontrarás con la pantalla de inicio de sesión segura provista por Firebase.  Digita tu usuario (correo electrónico) y contraseña institucionales asignados para validar tu identidad y habilitar la sincronización en la nube.  
  | 2. Panel de Control y Selección de Método de Registro: 
      En la pantalla principal tendrás acceso directo a las herramientas de toma de asistencia:Registro por Cámara:  
      Presiona esta opción para activar la cámara de tu celular. Apunta directamente al código QR del carné digital o físico del estudiante.
      El escáner integrado (Mobile Scanner) extraerá automáticamente los datos (Nombre, ID y curso) en menos de un segundo.  
      Registro por Imagen: Si un estudiante te envía una captura de pantalla de su carné por no portarlo físicamente, utiliza esta opción para cargar la foto directamente desde la galería de imágenes de tu dispositivo.  Registro Manual: Si el código QR del alumno está dañado, selecciona esta opción de respaldo para digitar manualmente su nombre o número de identificación.  3. Almacenamiento Autónomo e HistorialGuardado automático: Cada vez que escaneas o registras a un alumno, el sistema genera una marca con la fecha y hora exacta. Esta información se guarda inmediatamente en la base de datos SQLite local, lo que significa que el docente puede seguir tomando lista perfectamente aunque se caiga el internet o no haya señal en el aula.  Revisión del Historial: Explora el apartado de registros para auditar las asistencias. Puedes usar la barra de búsqueda superior para filtrar rápidamente por el apellido del estudiante o verificar el listado en orden alfabético. Al recuperar la conectividad, Firebase sincronizará los datos en segundo plano automáticamente con los servidores escolares.  💻 Stack Tecnológico UtilizadoFramework: Flutter (Estructura multiplataforma de alto rendimiento nativo).  Lenguaje de Programación: Dart.  Base de Datos Local: SQLite (Persistencia offline confiable).  
      Servicios Cloud & Auth: Firebase Cloud Services.  
      Paquete de Escaneo: Mobile Scanner.  
      Inteligencia Artificial (En progreso): Google ML Kit para reconocimiento facial.
