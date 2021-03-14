# WORKSPACE
load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "io_bazel_rules_rust",
    sha256 = "c587d402e4502100b01e4ba7d9584809cf4f4eb2d2f6634097883637bfb512b1",
    strip_prefix = "rules_rust-67f0c5ec0397d24ccc14264a0eda86915ddf63e8",
    # HEAD commit as of 2020-12-05
    urls = ["https://github.com/bazelbuild/rules_rust/archive/67f0c5ec0397d24ccc14264a0eda86915ddf63e8.tar.gz"],
)

load("@io_bazel_rules_rust//rust:repositories.bzl", "rust_repositories", "rust_repository_set")

rust_repositories(
    edition = "2018",
    version = "1.48.0",
)
