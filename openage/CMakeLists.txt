# python module configurations

# python config file is created in libopenage
# in order to get options from libopenage

add_py_modules(
	__init__.py
	__main__.py
	assets.py
	config.py
	default_dirs.py
	NOINSTALL devmode.py
)

add_subdirectory(cabextract)
add_subdirectory(codegen)
add_subdirectory(convert)
add_subdirectory(cppinterface)
add_subdirectory(cvar)
add_subdirectory(event)
add_subdirectory(game)
add_subdirectory(log)
add_subdirectory(util)
add_subdirectory(renderer)
add_subdirectory(testing)
