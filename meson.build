project('droidcat', ['c'], version: '000a0')
root_src = files('Main_Thread_64.c')
compiler_args = [
    '-std=c++11', 
    '-fstack-protector', 
    '-O2', 
    '-ffast-math', 
    '-Wall', 
    '-Werror',
]
executable(meson.project_name(), sources: [root_src], cpp_args: compiler_args)
