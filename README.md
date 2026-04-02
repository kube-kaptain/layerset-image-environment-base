# Layerset Image Environment Base

Kaptain layerset composing the full build configuration for image-environment-base images.

Composes these layers in order:

1. **layer-github-flow-strict** — strict GitHub flow quality enforcement (slash blocking, conventional commit blocking)
2. **layer-image-environment-base** — multi-arch docker builds, file-pattern-match versioning, Dockerfile in src/docker for both archs
