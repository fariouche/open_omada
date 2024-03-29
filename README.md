# open_omada
Opensource Omada controller

The omada controller, for managing tplink omada products, is a java server that enables administration of all omada products easily.
This controller exist also as an dedicated hardware (OC200 for example) with limitations.
However, this java server is about 500MB, and when you try to have something small that does not require all the features of the conroller, it's overkill.

Open Omada is a simple Python backend server, that support the minimum required to handle an Omada AccessPoint only (for the moment).
It supports automatic adoption of new APs, and basic statistics and configuration
