load("@rules_java//java:defs.bzl", "java_library")

package(default_visibility = ["//kythe:default_visibility"])

java_library(
    name = "doc_unbracketer",
    srcs = ["DocUnbracketer.java"],
    deps = [
        "//kythe/proto:common_java_proto",
        "//kythe/proto:xref_java_proto",
        "//third_party/guava",
        "@com_google_common_html_types//jar",
        "@com_google_protobuf//:protobuf_java",
    ],
)

java_library(
    name = "marked_source_renderer",
    srcs = ["MarkedSourceRenderer.java"],
    deps = [
        "//kythe/proto:common_java_proto",
        "//third_party/guava",
        "@com_google_common_html_types//jar",
        "@com_google_protobuf//:protobuf_java",
    ],
)
