package(default_visibility = ["//visibility:public"])

cc_proto_library(
    name = "canbus_proto",
    deps = [
        ":canbus_proto_lib",
    ],
)

proto_library(
    name = "canbus_proto_lib",
    srcs = glob([
        "**/*.proto",
    ]),
    deps = [
        "//modules/common/proto:common_proto_lib",
        "//modules/common/proto:header_proto_lib",
        "//modules/common/proto:vehicle_signal_proto_lib",
    ],
)
