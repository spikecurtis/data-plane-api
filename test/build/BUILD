load("//bazel:api_build_system.bzl", "api_cc_test")

licenses(["notice"])  # Apache 2

api_cc_test(
    name = "build_test",
    srcs = ["build_test.cc"],
    proto_deps = [
        "//api/filter:accesslog",
        "//api:cds",
        "//api:discovery",
        "//api:eds",
        "//api:hds",
        "//api:lds",
        "//api:rds",
        "//api:rls",
    ],
)
