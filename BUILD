cc_library(
  name = 'http-parser',
  export_incs = './',
  srcs = [
    'http_parser.c',
  ]
)

cc_test(
  name = 'test',
  warning = 'no',
  srcs = [
    'test.c',
  ],
  deps = ':http-parser',
)
