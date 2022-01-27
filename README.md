## Notas e consideracións

* Creación dun CRM con WordPress seguindo as seguintes guías: https://code.tutsplus.com/series/create-a-simple-crm-in-wordpress--cms-641
* Creación dende cero dun plugin de contacto con distintos campos. 
  * Engadido de campos dende o arquivo PHP e dende o propio WordPress usando un plugin de campos personalizados.

* Engadido de columnas para visualizar os datos dos contactos.
* Habilitar a busca por datos de contactos.
* Restrinxir certas accións para distintos roles.
* Creación de distintos roles con distintos permisos.
* Modificación de permisos.

 > * Debemos comentar a liña de código _add_action( 'plugins_loaded', array( &$this, 'acf_fields' ) );_ dentro do constructor, xa que da erro.
>* O filtrado por números de teléfono non funciona utilizando o código que se indica.
  > * *IMPORTANTE* débese desactivar a volver activar o plugin no último paso (https://code.tutsplus.com/tutorials/create-a-simple-crm-in-wordpress-using-custom-capabilities--cms-22985) para que apareza a sección de contactos accedendo cun rol de administrador, autor ou editor.