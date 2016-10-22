http_archive(
  name = "libssl",
  url = "http://github.com/google/boringssl/archive/bbcaa15b0647816b9a1a9b9e0d209cd6712f0105.tar.gz",  # 2016-07-11
  sha256 = "025264d6e9a7ad371f2f66d17a28b6627de0c9592dc2eb54afd062f68f1f9aa3",
  strip_prefix = "boringssl-bbcaa15b0647816b9a1a9b9e0d209cd6712f0105",
)

bind(
  name = "protobuf_compiler",
  actual = "@protobuf//:protoc_lib",
)

bind(
  name = "protobuf_clib",
  actual = "@protobuf//:protoc_lib",
)


http_archive(
  name = "protobuf",
  url = "http://github.com/google/protobuf/archive/008b5a228b37c054f46ba478ccafa5e855cb16db.tar.gz",
  sha256 = "2737ad055eb8a9bc63ed068e32c4ea280b62d8236578cb4d4120eb5543f759ab",
  strip_prefix = "protobuf-008b5a228b37c054f46ba478ccafa5e855cb16db",
)

bind(
  name = "nanopb",
  actual = "@nanopb_git//:nanopb",
)

new_http_archive(
  name = "nanopb_git",
  url = "http://github.com/nanopb/nanopb/archive/1251fa1065afc0d62f635e0f63fec8276e14e13c.tar.gz",
  sha256 = "ab1455c8edff855f4f55b68480991559e51c11e7dab060bbab7cffb12dd3af33",
  strip_prefix = "nanopb-1251fa1065afc0d62f635e0f63fec8276e14e13c",
  build_file = "//:nanopb.BUILD",
)

new_http_archive(
  name = "zlib_archive",
  url = "http://zlib.net/zlib-1.2.8.tar.gz",
  sha256 = "36658cb768a54c1d4dec43c3116c27ed893e88b02ecfcb44f2166f9c0b7f2a0d",
  strip_prefix = "zlib-1.2.8",
  build_file = "//:zlib.BUILD",
)

bind(
  name = "zlib",
  actual = "@zlib_archive//:zlib",
)
