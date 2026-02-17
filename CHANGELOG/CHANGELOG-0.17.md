# Release notes for v0.17.0

[Documentation](https://kubernetes-csi.github.io/)

# Changelog since 0.16.0

## Changes by Kind

### Uncategorized

- Bump dependencies to kubernetes v1.35 ([#348](https://github.com/kubernetes-csi/external-health-monitor/pull/348), [@rhrmo](https://github.com/rhrmo))

## Dependencies

### Added
- github.com/Masterminds/semver/v3: [v3.4.0](https://github.com/Masterminds/semver/tree/v3.4.0)
- golang.org/x/tools/go/expect: v0.1.0-deprecated
- golang.org/x/tools/go/packages/packagestest: v0.1.1-deprecated

### Changed
- github.com/go-logr/logr: [v1.4.2 → v1.4.3](https://github.com/go-logr/logr/compare/v1.4.2...v1.4.3)
- github.com/google/pprof: [d1b30fe → 27863c8](https://github.com/google/pprof/compare/d1b30fe...27863c8)
- github.com/kubernetes-csi/csi-lib-utils: [v0.22.0 → v0.23.2](https://github.com/kubernetes-csi/csi-lib-utils/compare/v0.22.0...v0.23.2)
- github.com/mailru/easyjson: [v0.9.0 → v0.9.1](https://github.com/mailru/easyjson/compare/v0.9.0...v0.9.1)
- github.com/onsi/ginkgo/v2: [v2.21.0 → v2.27.2](https://github.com/onsi/ginkgo/compare/v2.21.0...v2.27.2)
- github.com/onsi/gomega: [v1.35.1 → v1.38.2](https://github.com/onsi/gomega/compare/v1.35.1...v1.38.2)
- github.com/prometheus/client_golang: [v1.22.0 → v1.23.2](https://github.com/prometheus/client_golang/compare/v1.22.0...v1.23.2)
- github.com/prometheus/client_model: [v0.6.1 → v0.6.2](https://github.com/prometheus/client_model/compare/v0.6.1...v0.6.2)
- github.com/prometheus/common: [v0.62.0 → v0.66.1](https://github.com/prometheus/common/compare/v0.62.0...v0.66.1)
- github.com/prometheus/procfs: [v0.15.1 → v0.16.1](https://github.com/prometheus/procfs/compare/v0.15.1...v0.16.1)
- github.com/rogpeppe/go-internal: [v1.13.1 → v1.14.1](https://github.com/rogpeppe/go-internal/compare/v1.13.1...v1.14.1)
- github.com/spf13/cobra: [v1.9.1 → v1.10.0](https://github.com/spf13/cobra/compare/v1.9.1...v1.10.0)
- github.com/spf13/pflag: [v1.0.6 → v1.0.9](https://github.com/spf13/pflag/compare/v1.0.6...v1.0.9)
- github.com/stoewer/go-strcase: [v1.3.0 → v1.3.1](https://github.com/stoewer/go-strcase/compare/v1.3.0...v1.3.1)
- github.com/stretchr/testify: [v1.10.0 → v1.11.1](https://github.com/stretchr/testify/compare/v1.10.0...v1.11.1)
- go.etcd.io/bbolt: v1.4.2 → v1.4.3
- go.etcd.io/etcd/api/v3: v3.6.4 → v3.6.5
- go.etcd.io/etcd/client/pkg/v3: v3.6.4 → v3.6.5
- go.etcd.io/etcd/client/v3: v3.6.4 → v3.6.5
- go.etcd.io/etcd/pkg/v3: v3.6.4 → v3.6.5
- go.etcd.io/etcd/server/v3: v3.6.4 → v3.6.5
- go.opentelemetry.io/auto/sdk: v1.1.0 → v1.2.1
- go.opentelemetry.io/contrib/instrumentation/net/http/otelhttp: v0.58.0 → v0.61.0
- go.opentelemetry.io/otel/metric: v1.35.0 → v1.38.0
- go.opentelemetry.io/otel/sdk/metric: v1.34.0 → v1.36.0
- go.opentelemetry.io/otel/sdk: v1.34.0 → v1.36.0
- go.opentelemetry.io/otel/trace: v1.35.0 → v1.38.0
- go.opentelemetry.io/otel: v1.35.0 → v1.38.0
- go.yaml.in/yaml/v2: v2.4.2 → v2.4.3
- golang.org/x/crypto: v0.36.0 → v0.45.0
- golang.org/x/mod: v0.20.0 → v0.29.0
- golang.org/x/net: v0.38.0 → v0.47.0
- golang.org/x/oauth2: v0.27.0 → v0.30.0
- golang.org/x/sync: v0.12.0 → v0.18.0
- golang.org/x/sys: v0.31.0 → v0.38.0
- golang.org/x/term: v0.30.0 → v0.37.0
- golang.org/x/text: v0.23.0 → v0.31.0
- golang.org/x/tools: v0.26.0 → v0.38.0
- google.golang.org/genproto/googleapis/rpc: a0af3ef → 200df99
- google.golang.org/grpc: v1.72.1 → v1.72.2
- google.golang.org/protobuf: v1.36.5 → v1.36.8
- gopkg.in/evanphx/json-patch.v4: v4.12.0 → v4.13.0
- k8s.io/api: v0.34.0 → v0.35.0
- k8s.io/apimachinery: v0.34.0 → v0.35.0
- k8s.io/apiserver: v0.34.0 → v0.35.0
- k8s.io/client-go: v0.34.0 → v0.35.0
- k8s.io/component-base: v0.34.0 → v0.35.0
- k8s.io/kms: v0.34.0 → v0.35.0
- k8s.io/kube-openapi: f3f2b99 → 589584f
- k8s.io/utils: 4c0f3b2 → bc988d5
- sigs.k8s.io/json: cfa47c3 → 2d32026

### Removed
- sigs.k8s.io/structured-merge-diff/v4: v4.6.0
