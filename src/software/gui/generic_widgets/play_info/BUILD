load("@bazel_rules_qt//:qt.bzl", "qt_cc_library")

package(default_visibility = ["//software/gui:__subpackages__"])

qt_cc_library(
    name = "play_info_widget",
    src = "play_info_widget.cpp",
    hdr = "play_info_widget.h",
    deps = [
        "//software/ai/hl/stp:play_info",
        "@qt//:qt_widgets",
    ],
)
