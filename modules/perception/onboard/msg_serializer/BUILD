load("@rules_cc//cc:defs.bzl", "cc_library")
load("//tools:cpplint.bzl", "cpplint")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "msg_serializer",
    srcs = ["msg_serializer.cc"],
    hdrs = ["msg_serializer.h"],
    deps = [
        "//cyber",
        "//modules/common/time",
        "//modules/common/util:perf_util",
        "//modules/perception/base",
        "//modules/perception/onboard/common_flags",
        "//modules/perception/proto:perception_obstacle_cc_proto",
        "//modules/prediction/proto:feature_cc_proto",
        "@eigen",
    ],
)

cpplint()
