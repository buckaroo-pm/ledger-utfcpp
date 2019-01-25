load('//:subdir_glob.bzl', 'subdir_glob')

cxx_library(
  name = 'utfcpp',
  exported_headers = subdir_glob([
    ('source', '**/*.h')
  ]),
  visibility = ['PUBLIC']
)
