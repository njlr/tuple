include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'boost-tuple',
  header_only = True,
  header_namespace = 'boost/tuple',
  exported_headers = subdir_glob([
    ('include/boost/tuple', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
