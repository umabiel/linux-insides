# Kernel boot process

Este capítulo describe el proceso de inicio del Kernel Linux. Veremos una seria de posts donde se describe el ciclo completo del proceso de inicio del Kernel:

* [From the bootloader to kernel](http://0xax.gitbooks.io/linux-insides/content/Booting/linux-bootstrap-1.html) - describe las etapas desde el encendido del Computador hasta la primera instruccion del Kernel.
* [First steps in the kernel setup code](http://0xax.gitbooks.io/linux-insides/content/Booting/linux-bootstrap-2.html) - describe los primeros pasos en el codigo de inicio del Kernel, Veremos la inicializacion del Heap, y la consulta con diferentes parametros como EDD, IST, etc... 
* [Video mode initialization and transition to protected mode](http://0xax.gitbooks.io/linux-insides/content/Booting/linux-bootstrap-3.html) - describe la inicializacion del modo de video en el codigo de incio del Kernel y su transicion al modo protegido.
* [Transition to 64-bit mode](http://0xax.gitbooks.io/linux-insides/content/Booting/linux-bootstrap-4.html) - describe la preparación para la transición al modo de 64 bits y la transición en ella.
* [Kernel Decompression](http://0xax.gitbooks.io/linux-insides/content/Booting/linux-bootstrap-5.html) -  describe la preparacion antes de la descomprecion del Kernel y su descompresion directa.