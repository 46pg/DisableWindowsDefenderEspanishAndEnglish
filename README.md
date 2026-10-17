# DisableWindowsDefenderEspanishAndEnglish

DEFENDERCONTROL - INSTRUCTIONS (ENGLISH)
===========================================

WHAT IT DOES
------------
A menu-based script that lets you:

1. Disable Defender completely - turns off the whole antivirus (engine,
   real-time scanning, manual scanning).
2. Enable Defender completely - turns everything back on.
3. Disable ONLY Real-Time Protection - turns off just real-time
   scanning, leaving the rest of Defender running (scheduled scans,
   definition updates, etc.).
4. Enable ONLY Real-Time Protection - turns it back on.

Every time you open the script, it shows you the current status of both
before asking for an option.


REQUIRED STEP BEFORE USING IT (ONE-TIME ONLY)
-----------------------------------------------
For these changes to stick instead of being reverted automatically, you
need to turn off "Tamper Protection":

1. Open Windows Security.
2. Go to Virus & threat protection > Manage settings.
3. Turn off the "Tamper Protection" toggle.

WARNING: While this protection is off, third-party programs (including
this script) can modify Defender's settings without going through
Windows' official interface. This is a real security layer you'll be
giving up.


HOW TO USE THE SCRIPT
----------------------
1. Double-click DefenderControl_EN.bat.
2. Accept the administrator prompt (UAC window).
3. Choose an option from 1 to 5 by typing the number and pressing Enter.
4. For the change to fully take effect, restart your computer after
   using options 1 or 2 (full Defender). Options 3 and 4 (real-time
   only) usually apply without restarting, but restarting never hurts.
5. The script returns to the menu after each action, so you can make
   several changes in a row. Option 5 to exit.


IMPORTANT NOTES
----------------
- While Defender is disabled (partially or fully), your computer has no
  active antivirus protection for that part. Avoid opening files from
  unknown sources or browsing suspicious sites during that time.
- If a Windows update re-enables Defender on its own, just run the
  script again.
- If you want to restore full protection without relying on the script,
  use option 2 or 4, restart, and turn "Tamper Protection" back on in
  Windows Security.
- You can open the .bat file with Notepad at any time to check exactly
  what it does line by line; there's nothing hidden in it.

(Add to exclusions)
  
----------------

DEFENDERCONTROL - INSTRUCCIONES (ESPAÑOL)
===========================================

QUE HACE
--------
Un script con menu que te permite:

1. Desactivar Defender completo - apaga todo el antivirus (motor, analisis
   en tiempo real, analisis manual).
2. Activar Defender completo - lo vuelve a encender todo.
3. Desactivar SOLO la Proteccion en tiempo real - apaga unicamente el
   escaneo en tiempo real, dejando el resto de Defender funcionando
   (analisis programados, actualizacion de definiciones, etc.).
4. Activar SOLO la Proteccion en tiempo real - la vuelve a encender.

Cada vez que abres el script, te muestra el estado actual de ambas cosas
antes de pedirte una opcion.


PASO OBLIGATORIO ANTES DE USARLO (SOLO UNA VEZ)
------------------------------------------------
Para que estos cambios se mantengan y no se reviertan solos, necesitas
desactivar "Proteccion contra alteraciones":

1. Abre Seguridad de Windows.
2. Ve a Proteccion contra virus y amenazas > Administrar configuracion.
3. Apaga el interruptor de "Proteccion contra alteraciones".

ADVERTENCIA: Mientras esta proteccion este apagada, programas de terceros
(incluido este script) pueden modificar la configuracion de Defender sin
pasar por la interfaz de Windows. Es una capa de seguridad real que
estaras renunciando a usar.


COMO USAR EL SCRIPT
--------------------
1. Doble clic en DefenderControl.bat.
2. Acepta el permiso de administrador (ventana de UAC).
3. Elige una opcion del 1 al 5 escribiendo el numero y presionando Enter.
4. Para que el cambio surta efecto por completo, reinicia el equipo
   despues de usar las opciones 1 o 2 (Defender completo). Las opciones
   3 y 4 (solo tiempo real) suelen aplicarse sin reiniciar, pero
   reiniciar nunca esta de mas.
5. El script regresa al menu despues de cada accion, asi puedes hacer
   varios cambios seguidos. Opcion 5 para salir.


NOTAS IMPORTANTES
------------------
- Mientras Defender este desactivado (parcial o totalmente), tu equipo
  no tiene proteccion antivirus activa en esa parte. Evita abrir
  archivos de origen desconocido o navegar en sitios sospechosos durante
  ese tiempo.
- Si alguna actualizacion de Windows reactiva Defender por su cuenta,
  vuelve a correr el script.
- Si quieres recuperar la proteccion por completo y sin depender del
  script, usa la opcion 2 o 4, reinicia, y vuelve a activar "Proteccion
  contra alteraciones" en Seguridad de Windows.
- Puedes abrir el .bat con el Bloc de notas en cualquier momento para
  revisar exactamente que hace linea por linea; no contiene nada oculto.


  (Añadir a exclusiones)

  
