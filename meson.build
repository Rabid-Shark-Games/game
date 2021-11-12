project('game', 'cpp',
	default_options: 'default_library=static')

deps = [dependency('sdl2'),
	dependency('glew')]

sources = ['main.cpp']

executable('game', 'main.cpp',
	   win_subsystem: 'windows',
	   dependencies: deps)
