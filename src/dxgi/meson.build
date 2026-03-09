# forked from dxvk @ ecd7b67069a6e2a4b78a8a929fd287030d283ccb (2021-12-17)

dxgi_res = [
  windows.compile_resources('version.rc'),
]

util_src = [
  'com_guid.cpp',
]

dxgi_src = [
  'dxgi_adapter.cpp',
  'dxgi_enums.cpp',
  'dxgi_factory.cpp',
  'dxgi_format.cpp',
  'dxgi_main.cpp',
  'dxgi_monitor.cpp',
  'dxgi_options.cpp',
  'dxgi_output.cpp',
  'dxgi_swapchain.cpp',
]


shared_library('dxgi',util_src + dxgi_src+ dxgi_res ,
  name_prefix    : '',
  install        : true,
  vs_module_defs : 'dxgi.def',
)

