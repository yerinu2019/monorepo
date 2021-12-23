load("@com_github_bazelbuild_buildtools//buildifier:def.bzl", "buildifier")
load("@bazel_gazelle//:def.bzl", "gazelle")

buildifier(
    name = "buildifier",
)

# gazelle:prefix github.com/yerinu2019/monorepo
# gazelle:build_file_name BUILD,BUILD.bazel
gazelle(name = "gazelle")
