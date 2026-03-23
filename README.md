# BGP_TE

Comparto un nuevo escenario de laboratorio centrado en el control de tráfico y la toma de decisiones en BGP, integrando múltiples protocolos IGP y un entorno multi-AS, multivendedor y completamente IPv6.

El objetivo principal era analizar y manipular la selección de rutas en BGP utilizando diferentes atributos, manteniendo la interoperabilidad con los protocolos IGP internos.


## Topología del laboratorio

🏗 Tecnologías implementadas

🌐 IPv6

🔁 IS-IS Nivel 1

🔁 OSPFv3

📡 BGP (eBGP + iBGP Full Mesh)

🧠 Ingeniería de tráfico BGP (Ponderación, Preferencia local, Precedencia de ruta AS)

🖧 DHCPv6 con estado

🔐 Políticas de firewall

🧩 Entorno multivendedor (Cisco, Juniper, Huawei, MikroTik, Fortinet, Palo Alto, VyOS, H3C)

![Topología BGP-TE](BGP_TE/BGP_iBGP_Full_Mesh_IPv6.png)

## Tabla de enrutamiento BGP(Atributos BGP no configurados)

![Tabla de enrutamiento Fortigate 13](BGP_TE/img1.png)

## Rutas al prefijo 2001:A:B:29::/64

![Rutas  al prefijo 2001:A:B:29::/64](BGP_TE/img2.png)

## Tabla de enrutamiento BGP(Atributos BGP configurados)

![Tabla de enrutamiento Fortigate 13](BGP_TE/img3.png)

## Modificacion Atributos MikroTik(Local-Preference)

![Modificacion Atributos Local Preference](BGP_TE/img4.png)

## Modificacion Atributos MikroTik(Weight)

![Modificacion Atributos MikroTik](BGP_TE/img6.png)

# Modificacion Atributos 2 MikroTik(Local-Preference)

![Modificacion Atributos Local Preference 2](BGP_TE/img5.png)

## PRUEBA DE CONECTIVIDAD 

![Prueba de Conectividad](BGP_TE/img7.png)
