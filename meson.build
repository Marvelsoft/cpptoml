project('cpptoml',
        'cpp',
        version: run_command('cat', files('version.txt')).stdout().strip()
      )
cpptoml_inc = include_directories('include')
cpptoml_dep = declare_dependency(include_directories: cpptoml_inc)
