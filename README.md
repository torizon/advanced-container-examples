This repo contains three examples of a "more advanced" container usage, together with a GitHub Workflow that can be easily copied into your project.

Mainly, we highlight multistaged, multiarch build together with different base distros: Debian (glibc), Alpine (musl) and Distroless (technically this one is still just Debian minus package manager and a bunch of other things. Should be called "package-manager-less" instead of "distroless" in my opinion).
