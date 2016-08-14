# dockerfile-analyzer
A static analyzer for Dockerfile which should help implement best practices given any Dockerfile as input

## Goals

1. Input:
  1. Accept a github repo as input and search its root for a `Dockerfile`
  1. Accept a Dockerfile as input via CLI
  1. Accept a Dockerfile as input via copy/paste into a textarea
1. Analyze:
  1. Use static analysis to understand what the user is attempting to do then use known best practices to provide improvements
    1. https://github.com/google/shipshape
      1. https://github.com/google/shipshape/blob/master/shipshape/androidlint_analyzer/README.md
      1. https://github.com/google/shipshape/blob/master/shipshape/docs/add-an-analyzer.md
    1. https://github.com/banyanops/collector
      1. https://groups.google.com/forum/#!topic/docker-user/uxYfPmsHVzo
    1. https://github.com/mre/awesome-static-analysis#containers
      1. Haskell Dockerfile Linter [OSS] - A smarter Dockerfile linter that helps you build best practice Docker images
        1. https://github.com/lukasmartinelli/hadolint
1. Best Practices to implement as suggestions:
  1. http://blog.getjaco.com/jaco-labs-nodejs-docker-missing-manual/
