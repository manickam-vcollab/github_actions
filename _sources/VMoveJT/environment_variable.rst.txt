Environment Variables
=======================

VCollab Suite installer adds a system environment variable **VCOLLAB_DIR** during the installation process. The value of this variable is set to the installation directory of VCollab Suite. This variable is internally to VCollab software. The binary file directories also get added to the **PATH** variable during the installation. Since **VCOLLAB_DIR** is a system variable, the changes in its value will come into effect only after a system restart. Because of this reason, VCollab advises the administrators to restart the system after each installation. 

Some of the VCollab Suite applications also create temporary files during their execution. These temporary files are generally created in directory referred by environment variable **VCOLLAB_TEMP_PATH.** In case of non-existence of this variable, VMoveJT application uses the %TEMP% directory for storing the temporary files.