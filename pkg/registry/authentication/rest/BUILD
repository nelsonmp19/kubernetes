package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = ["storage_authentication.go"],
    tags = ["automanaged"],
    deps = [
        "//pkg/apis/authentication:go_default_library",
        "//pkg/apis/authentication/v1beta1:go_default_library",
        "//pkg/genericapiserver/registry/generic:go_default_library",
        "//pkg/genericapiserver/registry/rest:go_default_library",
        "//pkg/genericapiserver/server:go_default_library",
        "//pkg/registry/authentication/tokenreview:go_default_library",
        "//vendor:k8s.io/apiserver/pkg/authentication/authenticator",
    ],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [":package-srcs"],
    tags = ["automanaged"],
)
