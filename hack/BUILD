package(default_visibility = ["//visibility:public"])

licenses(["notice"])

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [
        ":package-srcs",
        "//hack/boilerplate:all-srcs",
        "//hack/e2e-internal:all-srcs",
        "//hack/lib:all-srcs",
    ],
    tags = ["automanaged"],
)
