load("//tools:defs.bzl", "go_library")

package(licenses = ["notice"])

go_library(
    name = "sighandling",
    srcs = [
        "sighandling.go",
        "sighandling_unsafe.go",
    ],
    visibility = ["//pkg/sentry:internal"],
    deps = ["//pkg/abi/linux"],
)
