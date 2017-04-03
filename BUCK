prebuilt_cxx_library(
  name = 'expr',
  header_only = True,
  header_namespace = '',
  licenses = [
    'LICENSE',
  ],
  exported_headers = [
    'expr.h',
    'expr_debug.h',
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = 'test',
  srcs = [
    'expr_test.c'
  ],
  deps = [
    ':expr',
  ],
)
