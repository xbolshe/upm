include_directories(..)
set (libname "si7005")
set (libdescription "upm SI7005")
set (module_src ${libname}.cxx mraa-utils.cxx)
set (module_h ${libname}.h)
upm_module_init()
