project(
    'nanoflann', ['cpp'],
    default_options: ['cpp_std=c++17'],
    version: '1.7.0',
)

nanoflann_include = include_directories('include')

nanoflann_dep = declare_dependency(
    include_directories: nanoflann_include,
)

meson.override_dependency('nanoflann', nanoflann_dep)
