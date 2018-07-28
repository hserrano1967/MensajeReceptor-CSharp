# MensajeReceptor-CSharp
Mensaje receptor, MH Costa Rica, usando parte del codigo de royrojas

Hay una clase con el nombre N_Datos_Receptor , ahí pegan el certificado, el APIUser y el APIClave

    class N_Datos_Receptor
    {
        //Ojo: Aca se pone el thumbprint. Del Certificado.
        //Para esto irse a propiedades de internet y revisar en Contenido los certificados registrados.
        //Dar click en el certificado. Luego en Ver. Y en la Ficha Detalles. Buscar Huella Digital
        //Y este dato es el que se coloca aca.
        public static string certificado = "06x9xxx68xxx77e0f87b00b603837d0xxxxxxxxx";
        public static string APIUser = "cpf-99-9999-9999@stag.comprobanteselectronicos.go.cr";
        public static string APIClave = "XXXXXXXXXXXXXXXX";
    }

