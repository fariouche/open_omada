# OpenOmada
Open source Omada controller

The omada controller, used for managing tplink omada products, is a java server that enables administration of all omada products easily.
This controller exist also as a dedicated hardware (OC200 for example) with limitations.
However, this java server is about 500MB, and when you try to have something small that does not require all the features of the conroller, it's overkill.

Open Omada is a simple Python backend server, that support the minimum required to handle an Omada Access Point only (for the moment).
It supports automatic adoption of new APs, and basic statistics and configuration

It is possible to replace an existing omada controller. For that, the omada controller id, the user and password and the access point ssid and psk are needed.
With the abpve information, OpenOmada can replace an existing omada controller with no need to re-adopt all the acces point.

Possible usage of OpenOmada is in very small embedded devices with network access that support python and SSL TLS.
