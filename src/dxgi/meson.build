# forked from dxvk @ ecd7b67069a6e2a4b78a8a929fd287030d283ccb (2021-12-17)

dxgi_res = [
  windows.compile_resources('version.rc'),
]

dxgi_src = [
  'dxgi.cc',
]


shared_library('dxgi', dxgi_src+ dxgi_res ,
  name_prefix    : '',
  install        : true,
  vs_module_defs : 'dxgi.def',
)

