git_repository(
    name = "io_bazel_rules_go",
    remote = "https://github.com/bazelbuild/rules_go.git",
    tag = "0.5.3"
)
load("@io_bazel_rules_go//go:def.bzl", "go_repositories","go_repository")


go_repositories()

go_repository(
    name = "logrus",
    importpath = "github.com/sirupsen/logrus",
    commit = "f006c2ac4710855cf0f916dd6b77acf6b048dc6e"
)